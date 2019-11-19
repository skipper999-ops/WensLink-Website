<template>
    <div>
        <div class="container">
            <div class="page-pad bg-white">
                <div class="order-border">
                    <div class="page-header">
                        <nuxt-link to="sidenav"><p style="padding: 0 0 0 5px;">My Account</p></nuxt-link>
                        <p style="margin:0 4px 0 6px">></p>
                        <p>My Orders</p>
                    </div>
                    <div class="item-header justify-content-between border-top border-bttm">
                        <div class="custom-btn">
                            <nuxt-link to="cart"><p>OD1234567890</p></nuxt-link>
                        </div>
                        <div class="btn track-btn">
                            <span></span>
                            <span><p>Track</p></span>
                        </div>
                    </div>
                    <div class="row mb-2 pad">
                        <div class="col-md-2">
                            <div class="d-flex justify-content-center">
                                <nuxt-link to="cart"><img src="~static/images/honor.png"></nuxt-link>
                            </div>
                        </div>
                        <div class="col-md-3">
                            <div>
                                <p>Honor 8X</p>
                            </div>
                            <div>
                                <p class="pt-1 text-seller">Color:Black</p>
                            </div>
                            <div>
                                <p class="pt-1 text-seller">Seller:RetailNet</p>
                            </div>
                        </div>
                        <div class="col-md-1">
                            <p>₹1,305</p>
                        </div>
                        <div class="col-md-3">
                            <div>
                                <div>
                                    <p>Delivered on Wed, Oct 16</p>
                                </div>
                                <div>
                                    <p>Return policy valid till Nov 15</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-3">
                            <div class="d-block">
                                <div class="d-flex">
                                    <span></span>
                                    <span><p class="blue">RETURN</p></span>
                                </div>
                                <div class="d-flex">
                                    <span></span>
                                    <span><p class="blue">REVIEWS</p></span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="d-flex justify-content-between border-top pad3">
                        <div class="d-flex">
                            <span>
                                <p>Ordered On</p>
                            </span>
                            <span>
                                <p class="text-seller">Fri, Oct 11th '19</p>
                            </span>
                        </div>
                        <div class="d-flex">
                            <span>
                                <p>Order Total</p>
                            </span>
                            <span>
                                <p class="text-seller">₹1,305</p>
                            </span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style scoped>
.page-pad{
    padding: 2px 20px 10px;
    
}
.bg-white{
    background-color: #ffffff;
}
.page-header{
    display: flex;
    margin: 20px 0;
}
.item-header{
    display: flex;
    padding: 15px 15px;
    background-color: #e6e6e6;
}
.custom-btn{
    color: rgb(255, 255, 255);
    box-shadow: none;
    text-transform: uppercase;
    cursor: pointer;
    text-align: center;
    width: 196px;
    background: #006600;
    border-width: 1px;
    border-style: solid;
    border-color: #006600;
    border-image: initial;
    padding: 8px 12px;
    border-radius: 2px;
}
.track-btn{
        cursor: pointer;
    text-align: center;
    display: inline-block;
    border-radius: 2px;
    background: #f9f9f9;
    border: 1px solid #d7d7d7;
    margin-left: 10px;
}
.order-border{
    border: 1px solid #e6caca91;
    box-shadow:1px 1px 4px 2px #b0a5a51a;
}
.border-top{
    border-top: 1px solid #e6caca91;
}
.border-bttm{
    border-bottom: 1px solid #e6caca91;
}
.border-right{
    border-right: 1px solid #e6caca91;
}
.border-left{
    border-left:1px solid #e6caca91;
}
.pad{
    padding: 10px 10px 0 10px;
}
.pad2{
    padding: 15px 10px 15px 10px;
}
.blue{
    color:blue;
    font-size: 14px;
    font-weight: 700;
}
.pad3{
    padding: 5px;
}
.page-header p{
    font-size: 18px;
    font-weight: 600;
}
.text-seller{
    color:#918b8b;
}
</style>