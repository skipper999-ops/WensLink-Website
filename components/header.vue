<template>
  <div>
    <div class="bg-primary" style="height:130px">
    <div class="container">
      <div class="row">
        <div class="col-lg-2 justify-content-center align-items-center">
          <div style="font-size:20px;font-weight:strong;color:#fff">
            <a><nuxt-link to="/">
              <img
                style="height: 100px;object-fit: contain;width:100%;padding:10px"
                src="~static/images/logo.png"
              /></nuxt-link>
            </a>
          </div>
        </div>
        <div class="col-lg-7 bg-custom1 d-flex justify-content-center align-items-center">
          <input type="text" class="w-100" align="left" name="search" placeholder="Search" style="font-size:12px"/>
        </div>
        <div class="col-lg-3 d-flex align-items-center justify-content-around p-0">
          <span class="text">
            <img style="margin-right:5px" src="~/static/icons/favorite-heart-button.png" />
            <nuxt-link to="wishlist">Wishlist</nuxt-link>
          </span>
          <span class="text">
            <img style="margin-right:5px" src="~/static/icons/user.png" />
            <nuxt-link to="sidenav">My Acoount</nuxt-link>
          </span>
          <span class="text">
            <img style="margin-right:5px" src="~/static/icons/shopping-cart-black-shape.png" />
            <nuxt-link to="cart">Cart</nuxt-link>
          </span>
        </div>
      </div>

     <div class="container">
        <div class="row" style="position: relative;">
            <div class="col-12 p-0 m-0 d-flex justify-content-center align-items-center">
                <div>
                    <nav class="navbar navbar-expand-lg navbar-light p-0 m-0 justify-content-center">
                        <a class="navbar-style dropdown" href="#">Electronics</a>
                        <a class="navbar-style" href="#">TV & Applicances</a>
                        <a class="navbar-style" href="#">Men</a>
                        <a class="navbar-style" href="#">Women</a>
                        <a class="navbar-style" href="#">Baby & Kids</a>
                        <a class="navbar-style" href="#">Home & Furniture</a>
                        <a class="navbar-style" href="#">Sports, Books & More</a>
                        <a class="navbar-style" href="#">Offer Zone</a>
                    </nav>
                </div>
            </div>
            <div class="col-12 dropdown-body d-flex hide" style="padding: 0px; z-index: 9; position: absolute; top: 39px;">
                <div class="col-sm-3 dropdown-section d-flex flex-column" style="background-color: white;">
                    <p><a>Mobiles<i class="fa fa-caret-right pl-3"></i></a></p>
                    <a>Mi</a>
                    <a>Realme</a>
                    <a>Samsung</a>
                    <a>Infinix</a>
                    <a>OPPO</a>
                    <a>Apple</a>
                    <a>Vivo</a>
                    <a>Honor</a>
                    <a>Asus</a>
                    <a>Pixel 3a | 3a XL</a>
                    <a>Redmi K20 | K20 Pro</a>
                    <a>Realme X</a>
                    <a>Redmi 7A</a>
                    <a>Vivo Z1Pro</a>
                    <a>Realme 5 Pro</a>
                    <a>Oppo Reno 2z</a>
                    <a>Realme 5</a>
                </div>
                <div class="col-sm-3 dropdown-section d-flex flex-column" style="background-color: white;">
                    <p><a>Mobile Accessories<i class="fa fa-caret-right pl-3"></i></a></p>
                    <a>Mobile Cases</a>
                    <a>Headphones & Headsets</a>
                    <a>Power Banks</a>
                    <a>Screenguards</a>
                    <a>Memory Cards</a>
                    <a>Smart Headphones</a>
                    <a>Mobile Cables</a>
                    <a>Mobile Chargers</a>
                    <a>Mobile Holders</a>
                    <p><a>Laptops<i class="fa fa-caret-right pl-3"></i></a></p>
                    <a>Gaming Laptops</a>
                    <p><a>Desktop PCs<i class="fa fa-caret-right pl-3"></i></a></p>
                    <p><a>Gaming & Accessories<i class="fa fa-caret-right pl-3"></i></a></p>
                    <p><a>Computer Accessories<i class="fa fa-caret-right pl-3"></i></a></p>
                </div>
                <div class="col-sm-3 dropdown-section d-flex flex-column" style="background-color: white;">
                    <p><a>Computer Accessories<i class="fa fa-caret-right pl-3"></i></a></p>
                    <a>External Hard Disks</a>
                    <a>Pendrives</a>
                    <a>Laptop Skins & Decals</a>
                    <a>Laptop Bags</a>
                    <a>Mouse</a>
                    <p><a>Computer Peripherals<i class="fa fa-caret-right pl-3"></i></a></p>
                    <a>Computer</a>
                    <a>Printers & Ink Cartridges</a>
                    <a>Monitors</a>
                    <p><a>Tablets<i class="fa fa-caret-right pl-3"></i></a></p>
                    <p><a>Camera<i class="fa fa-caret-right pl-3"></i></a></p>                    
                    <a>DSLR & Mirrorless</a>
                    <a>Compact & Bridge Cameras</a>
                    <a>Sports & Action</a>
                </div>
                <div class="col-sm-3 dropdown-section d-flex flex-column" style="background-color: white;">
                    <p><a>Speakers<i class="fa fa-caret-right pl-3"></i></a></p>
                    <a>Home Audio Speakers</a>
                    <a>Home Theatres</a>
                    <a>Soundbars</a>
                    <a>Bluetooth Speakers</a>
                    <p><a>Smart Wearable Tech<i class="fa fa-caret-right pl-3"></i></a></p>
                    <a>Smart Watches</a>
                    <a>Smart Glasses (VR)</a>
                    <a>Smart Bands</a>
                    <p><a>Health Care Appliances<i class="fa fa-caret-right pl-3"></i></a></p>
                    <a>Bp Monitors</a>
                    <a>Weighing Scale</a>
                </div>
            </div>
        </div>
    </div>



    </div>
    </div>
  </div>
  <!-- navbar ends here -->
</template>
<script>
export default {
  mounted(){
    $(document).on('mouseover', '.dropdown', function () {
        $(".dropdown-body").removeClass('hide');
    }).on('mouseout', '.dropdown', function() {
        $(".dropdown-body").addClass('hide')
    })
    $(document).on('mouseover', '.dropdown-body', function () {
        $(".dropdown-body").removeClass('hide');
    }).on('mouseout', '.dropdown-body', function() {
        $(".dropdown-body").addClass('hide');
    })
  }
}
</script>
<style scoped>
input[type="text"] {
  /* width: 130px; */
  -webkit-transition: width 0.4s ease-in-out;
  transition: width 0.4s ease-in-out;
}

.bg-primary {
  background-color: #89d0e2 !important;
}

span a {
  color: #fff;
  font-size: 12px;
  text-decoration: none;
}
input[type="text"]:focus {
  width: 100%;
}

.my-text {
  font-size: 12px;
}

.flex-container {
  display: flex;
  flex-direction: column;
}

.category{
  color: white
}

.my-text-custom {
  font-size: 10px;
}

/* ul {
        list-style-image: url("auction/Group 51.svg");
      } */

/* .bg-custom1 {
        background-color: #e6e6e6;
      } */

.my-text-custom2 {
  font-size: 18px;
  font-weight: bold;
}

.my-text-custom3 {
  font-size: 15px;
}

.login-section {
  padding: 20px 20px 20px;
}

.padding-10 {
  padding: 10px;
}

.padding-top-10 {
  padding-top: 10px;
}

.padding-bottom-10 {
  padding-bottom: 10px;
}

.padding-right-10 {
  padding-right: 10px;
}

.padding-left-10 {
  padding-left: 10px;
}

.no-mar {
  margin: 0 !important;
}

.no-padd {
  padding: 0 !important;
}

.myHeader p {
  margin: 0;
  font-size: 10px;
  margin-left: 10px;
}

.myborder-right .null {
  margin: 0;
  margin: 0 10px !important;
  font-size: 12px !important;
  font-weight: bold;
}

.myborder-right div {
  border-right: 1px solid #b0b0b0;
}
.my-header-2 {
  box-shadow: 0px 6px 5px 0px #a9a9a9d6;
}
.flex-container1 {
  display: flex;
}
.box-style {
  height: 300px;
  width: 300px;
}
.box-style-fixed {
  height: 126px;
}

.owl-carousel {
  position: relative;
}
.owl-prev {
  position: absolute;
  font-size: 20px;
  top: 25%;
  left: -10px;
}
.owl-next {
  position: absolute;
  top: 25%;
  right: -10px;
}

.owl-nav p {
  margin-bottom: 0;
  font-size: 20px;
}

.no-select,
.owl-prev,
.owl-next,
.owl-nav {
  -webkit-user-select: none; /* Safari */
  -khtml-user-select: none; /* Konqueror HTML */
  -moz-user-select: none; /* Firefox */
  -ms-user-select: none; /* Internet Explorer/Edge */
  user-select: none; /* Non-prefixed version, currently
                                  supported by Chrome and Opera */
}

button {
  outline: none !important;
  font-size: 20px;
}
.ellipse {
  width: 45px;
  height: 45px;
  background-color: #f65656;
  border-radius: 50%;
  /* text-align: center; */
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
}

.ellipse span {
  width: 12px;
  height: 12px;
  background-color: #fff;
  border: 1px solid #f65656;
  border-radius: 50%;
  /* text-align: center; */
  display: flex;
  align-items: center;
  justify-content: center;
  position: absolute;
  top: 0;
  right: 0;
  font-size: 10px;
}
.ellipse2 {
  width: 45px;
  height: 45px;
  background-color: #00a9e0;
  border-radius: 50%;
  /* text-align: center; */
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
}
.ellipse2 span {
  width: 12px;
  height: 12px;
  background-color: #fff;
  border: 1px solid #00a9e0;
  border-radius: 50%;
  /* text-align: center; */
  display: flex;
  align-items: center;
  justify-content: center;
  position: absolute;
  top: 0;
  right: 0;
  font-size: 10px;
}
.topbids-actions button {
  height: 35px;
  justify-content: center;
  align-items: center;
}
.small-font {
  font-size: 12px;
}
.w3-navbar a:hover {
  color: #039be59e !important;
  background-color: #ccc;
  border: 1px solid #039be5;
  border-radius: 4px;
}
.w3-navbar a {
  border: 1px solid transparent;
}
.navbar-border {
  border-top: 1px solid #9e9e9e;
  border-bottom: 1px solid #9e9e9e;
}
li {
  list-style-type: none;
}

.dropdown-ul {
  border-radius: 0 0 3px 3px;
  height: 150px;
  min-height: 320px;
  /* box-shadow: 0 7px 17px 0 rgba(23,84,116,0.18) */
}

.dropdown-ul li {
  padding: 10px 20px;
  font-size: 14px;
  cursor: default;
}

.dropdown-ul li .category-head {
  font-size: 12px;
}

.dropdown-ul li .subcategory {
  position: absolute;
  left: 150px;
  top: 0;
  height: 100%;
  background-color: white;
  width: 450px;
  z-index: 9;
  font-size: 11px;
  padding: 10px;
  /* box-shadow: 0 7px 17px 0 rgba(23,84,116,0.18) */
}

.dropdown-ul li .subcategory p {
  margin-bottom: 4px;
  color: #666;
}

.dropdown-ul li .subcategory a {
  color: #666;
}

/* li {
  float: left;
}

li a, .dropbtn {
  display: inline-block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover, .dropdown:hover .dropbtn {
  background-color: blue;
}

li.dropdown {
  display: inline-block;
  } */

.hide {
  display: none;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  z-index: 1;
}

.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.category-li {
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  border-left: 2px solid transparent;
}

.category-li:hover {
  border-left: 2px solid red;
  background-color: #f5f5f5;
  border-top: 1px solid #dedede;
  border-bottom: 1px solid #dedede;
}

.dropdown-content a:hover {
  background-color: #f1f1f1;
}

.dropdown:hover .dropdown-content {
  display: block;
}

.category-header {
  font-family: MaisonNeueBook;
  color: #333;
  text-transform: uppercase;
}

.subcategory .subsection:not(:last-child) {
  border-right: 1px solid #e4e4e4;
}

.subsection > div:not(:first-child) {
  padding-top: 15px;
  border-top: 1px solid #f7f7f7;
}

.subsection a:last-child p {
  padding-bottom: 10px;
}
.jssorl-009-spin img {
  animation-name: jssorl-009-spin;
  animation-duration: 1.6s;
  animation-iteration-count: infinite;
  animation-timing-function: linear;
}
body {
    width: 100%!important;
    background-color: #f1f3f6!important;
}

.mc1 {
    background-color: #89d0e2!important; 
    height: auto;
}

@media (max-width: 37.5em) {
    .padSmall {
        padding-top: 15px;
    }
}

a {
    cursor: pointer;
}

li {
    list-style: none;
    padding: 10px;
    padding-top: 0px;
    padding-bottom: 0px;
    font-size: 1.1em;
}

.navbar-style {
    display: inline-block;
    padding-top: .3125rem;
    margin-right: 1.2rem;
    font-size: 1rem;
    line-height: inherit;
    white-space: nowrap;
    text-decoration: none!important;
    cursor: pointer;
    color: #333;
}

.navbar-style:hover {
    color: #ffffff;
    transform: scale(1.05);
}

.dropdown-body {
    z-index: 9;
}

.hide {
    display: none!important;
    visibility: hidden;
}

.dropdown-section a {
    font-size: 0.9em;
    padding-bottom: 3px;
}

.dropdown-section a:hover {
    transform: scale(1.02);
}

.dropdown-section p {
    font-size: 1.05em;
    margin-bottom: 5px;
    margin-top: 10px
}

@keyframes jssorl-009-spin {
  from {
    transform: rotate(0deg);
  }

  to {
    transform: rotate(360deg);
  }
}
</style>