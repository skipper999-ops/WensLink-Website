<template>
  <div>
    <client-only>
    <Header v-if="$nuxt.$route.name != 'legal-about' && $nuxt.$route.name != 'legal-buyeragreement' && $nuxt.$route.name != 'legal-privacy' && $nuxt.$route.name != 'legal-returnpolicy' &&$nuxt.$route.name != 'legal-selleragreement' && $nuxt.$route.name != 'legal-disclaimer'"/>
    <nuxt />
    <Footer/>
    </client-only>
  </div>
</template>
<script>
import Header from '@/components/header.vue'
import Footer from '@/components/footer.vue'
export default {
  components:{ Header,
              Footer
}, mounted(){

  console.log($nuxt.$route.name)
}
}
</script>

<style>

@import url('https://fonts.googleapis.com/css?family=Open+Sans&display=swap');


.owl-carousel .owl-dots.disabled, .owl-carousel .owl-nav.disabled{
  display: block!important
}

.owl-carousel{
  position: relative;
}
 .owl-prev{
 position: absolute;
 font-size:20px;
top:25%;
left:-15px
      }
.owl-next{
position: absolute;
top:25%;
right: -15px
}

.owl-nav p{
margin-bottom: 0;
font-size: 20px;
}

.no-select, .owl-prev, .owl-next, .owl-nav {
    -webkit-user-select: none; /* Safari */
     -khtml-user-select: none; /* Konqueror HTML */
       -moz-user-select: none; /* Firefox */
        -ms-user-select: none; /* Internet Explorer/Edge */
            user-select: none; /* Non-prefixed version, currently
                                  supported by Chrome and Opera */
}


.owlnavigation{
border: 0;
    box-shadow: 0px 0px 6px 0px rgba(0,0,0,0.18824);
    width: 35px;
    height: 75px;
    background-color: white;
    line-height: 75px;
    font-weight: bold;
    border-radius: 5px
}

html {
  font-family: 'Open Sans', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
body{
  background-color: #f2f2f2;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

p{
  margin-bottom: 0
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}

.owl-carousel .owl-item img{
  object-fit: contain
}

input[type="text"],
input[type="email"],input[type="number"] {
  outline: 0;
  border: 0;
  padding: 10px;
  border-radius: 2px;
  transition: all 0.2s ease-in-out
}
input[type="text"]:focus,
input[type="email"]:focus,input[type="number"]:focus{
  outline: 0;
  /* border: 0;
  box-shadow: #0000003d 0px 9px 12px 0px; */
  
  transition: all 0.2s ease-in-out
}
input[type=number]::-webkit-inner-spin-button, 
input[type=number]::-webkit-outer-spin-button { 
  -webkit-appearance: none; 
  margin: 0; 
}
a:hover{
  text-decoration: none;
}

</style>
