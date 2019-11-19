<template>
    <div>
        <div class="container">
            <div class="row mt-4">
                <div class="col-md-8">
                    <div class="shadow bg-white">
                        <div class="d-flex w-100 justify-content-between border-bottom">
                            <div class="cart-header">
                                <p>My Cart</p>
                            </div>
                            <div class="d-flex pad-2">
                                <span><img src="~static/icons/maps-and-flags.svg"></span>
                                <span><p style="padding:5px">Deliver to</p></span>
                                <span>
                                    <div class="d-flex form-group m-0">
                                        <label for="sel1"></label>
                                            <select class="form-control" id="sel1">
                                                 <option>1</option>
                                                 <option>2</option>
                                                 <option>3</option>
                                                 <option>4</option>
                                                </select>
                                         </div>
                                     </span>
                                  </div>
                            </div>
                        <div class="pad24">
                        <div class="row">
                            <div class="col-md-2">
                                <div class="d-flex justify-content-center">
                                    <img src="~static/images/honor.png">
                                </div>
                                
                            </div>
                            <div class="col-md-7">
                               <div>
                                <div>
                                    <p class="pad-9" style="font-size:16px">Realme XT (Pearl Blue, 64 GB)</p>
                                </div>
                                <div>
                                    <p class="pad-11 font-12">4GB Ram</p>
                                </div>
                                <div>
                                    <p class="pad-11 font-12">Seller:Vision Star</p>
                                </div>
                                <div>
                                    <p class="pad-11">Rs 15000</p>
                                </div>
                               </div>
                            </div>
                            <div class="col-md-3">
                                <div>
                                    <p class="pad-9 font-12">Delivery by Tue Oct 22 | Free₹40</p>
                                </div>
                                <div>
                                    <p class="font-12">10 Days Replacement Policy</p>
                                </div>
                            </div>
                        </div>
                        <div class="d-flex mt-2 align-items-center">
                            <div class="mt-3">
                                    <div class="quantity buttons_added">
                                    <input type="button" value="-" class="minus" :disabled="data <= 0" @click="minus">
                                    <input type="number" step="1" min="1" max="" v-model="data" name="quantity" value="1" title="Qty" 
                                            class="input-text qty text" size="4" pattern="" inputmode="">
                                    <input type="button" value="+" class="plus" @click="plus">
                                </div>
                            </div>
                            <div class="d-flex">
                                    <span style="padding:0 0 0 36px"><nuxt-link class="none" to="">SAVE FOR LATER</nuxt-link></span>
                                    <span style="padding:0 0 0 12px"><nuxt-link class="none" to="">REMOVE</nuxt-link></span>
                            </div>
                        </div>
                      </div>
                    </div>
                        <div class="d-flex justify-content-end pad12">
                            <button type="button" class="btn btn-order">PLACE ORDER</button>
                        </div>
                </div>
                <div class="col-md-4">
                    <div class="bg-white shadow border-rad">
                        <div class="border-bottom f600" style="padding:13px 24px">
                            <p style="color:#878787">PRICE DETAILS</p>
                        </div>
                        <div style="padding:0 24px">
                            <div class="d-flex justify-content-between" style="margin:20px 0">
                                <span><p>Price (2 items)</p></span>
                                <span><p>₹24,998</p></span>
                            </div>
                            <div class="d-flex justify-content-between" style="margin:20px 0">
                                <span><p>Delivery</p></span>
                                <span><p>FREE</p></span>
                            </div>
                            <div class="d-flex justify-content-between border-top-dotted f600" style="margin:20px 0">
                                <span><p>Total Payable</p></span>
                                <span><p>₹24,998</p></span>
                            </div>
                        </div>
                        <div class="border-top" style="padding:20px 24px">
                            <p>You will save ₹4,000 on this order</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    data(){
        return{

                data: 1

        }

    },
    mounted(){

    },
    methods:{

            minus: function(){
                    this.data -= 1
            },

            plus: function(){
                    this.data += 1
            }

    }
}
</script>
<style scoped>
.pad24{
    padding: 24px;
}
.btn-order{
    background: #fb641b;
    box-shadow: 0 1px 2px 0 rgba(0,0,0,.2);
    border: none;
    color: #fff;
    width: 248px;
    height: 47px;
    font-size: 20px;
    font-weight: 600;
    border-radius: 2px;
    position: relative;
}
.shadow{    
    box-shadow: 1px 5px 8px 7px rgba(128, 128, 128, 0.25882352941176473);
}
.bg-white{
    background-color: #ffffff;
}
.pad12{
    padding: 12px 0;
}
.pad-2{
        padding: 14px 9px 0 0;
}
.cart-header{
    font-size: 23px;
    font-weight: 600;
    padding:15px 0 15px 15px
}
.border-rad{
    border-radius:2px;
}
.border-bottom{
    border-bottom: 1px solid #b3adad3b;
}
.border-top{
    border-top: 1px solid #b3adad3b;
}
.border-top-dotted{
    border-top: 1px dotted #b3adad3b;
}
.f600{
    font-weight: 600;
}
.none{
    text-decoration: none;
}
.none:hover{
    color:black;
    text-decoration: none;
}
.pad-9{
    padding: 0 0 9px 0;
}
.pad-11{
    padding: 0 0 11px 0;
}
.font-12{
    font-size: 12px;
}
.form-group option{
    color:#b3adad3b;
    font-size: 13px;
}
.quantity {
  display: inline-block;
}
 
 .quantity .input-text.qty {
  width: 35px;
  height: 39px;
  padding: 0 5px;
  text-align: center;
  background-color: transparent;
  border: 1px solid #efefef;
}
 
 .quantity.buttons_added {
  text-align: left;
  position: relative;
  white-space: nowrap;
  vertical-align: top; }
 
 .quantity.buttons_added input {
  display: inline-block;
  margin: 0;
  vertical-align: top;
  box-shadow: none;
}
 
 .quantity.buttons_added .minus,
 .quantity.buttons_added .plus {
  /* padding: 7px 10px 8px; */
  height: 40px;
  background-color: #ffffff;
  border: 2px solid #efefef;
  cursor:pointer;
  border-radius: 100%;
  width: 40px;
}
 
 .quantity.buttons_added .minus {
  border-right: 0;
}
 
 .quantity.buttons_added .plus {
  border-left: 0;
}
 
 .quantity.buttons_added .minus:hover,
 .quantity.buttons_added .plus:hover {
  background: #eeeeee; }
 
 .quantity input::-webkit-outer-spin-button,
 .quantity input::-webkit-inner-spin-button {
  -webkit-appearance: none;
  -moz-appearance: none;
  margin: 0; }
  
  .quantity.buttons_added .minus:focus,
 .quantity.buttons_added .plus:focus {
  outline: none;
}
</style>