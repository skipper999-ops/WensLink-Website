<template>
    <div>
        <div class="container">
            <div class="pad2030 bg-white mt-3 border shadow">
                <div>
                    <p style="font-size:19px;font-weight:600;">My Whislist</p>
                </div>
            </div>
            <div class="item-pad bg-white">
                <div>
                    <img src="~static/images/samsung-camera.png">
                </div>
                <div class="row pad-left bg-white w-100">
                    <div class="col-md-10">
                        <div>
                            <p style="margin:0 0 5px 0">Woodland Casual Shoes</p>
                            <div>
                                <span>4.1</span>
                                <span>(3206)</span>
                            </div>
                            <div class="price">
                                <p>Rs3995</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-2">
                        <div class="d-flex justify-content-center">
                           <nuxt-link to=""><img style="height:12px;width:16px;position:top right" src="~static/icons/delete.svg"></nuxt-link>
                        </div>
                    </div>
                </div>
    
            </div>
        </div>
    </div>    
</template>
<style scoped>
.pad2030{
    padding: 20px 30px;
}
.bg-white{
    background-color: #ffffff;
}
.item-pad{
    line-height: 1;
    padding: 24px 0 30px 24px;
    display: flex;
    overflow: hidden;
    box-shadow: 0px 5px 9px 2px #a69d9d24;
}
.pad-left{
    padding: 0 0 0 25px;
}
/* .shadow{    
    box-shadow: 1px 5px 8px 7px rgba(128, 128, 128, 0.25882352941176473);
} */
.border{
    border: 1px solid #b5989863;
}
shadow{
    box-shadow: 0px -1px 9px 2px #a69d9d24;
}
.border-bttm{
    border-bottom: 1px solid  #b5989863;
}
.price{
    display: block;
    margin-top: 8px;
    padding-right: 10px;
}
</style>