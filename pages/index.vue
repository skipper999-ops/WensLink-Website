<template>
  <div>
    <div style="background-image: linear-gradient(to left, #92d2dc, #bbe3be);">
      <div class="container pt-5 mt-1 pb-5">
        <div class="row">
          <div class="col-sm-8 col-md-8" style="padding-left: 0">
            <div style="height: 281px;">
              <img
                style="object-fit: cover; object-position:center;box-shadow: #0000003d 0px 9px 12px 0px;border-radius: 5px;"
                class="w-100 h-100"
                src="~static/images/1.png"
                alt
              />
            </div>
          </div>
          <div class="col-sm-4 col-md-4" style="height: 200px">
            <div class="row h-50">
              <div class="col-sm-12 p-0">
                <div class="bg-success" style="height: 132px">
                  <img
                    style="object-fit: cover; object-position: center;box-shadow: #0000003d 0px 9px 12px 0px;border-radius: 5px;"
                    src="~static/images/NoPath - Copy (3).png"
                    alt
                    class="w-100 h-100"
                  />
                </div>
              </div>
              <div class="col-sm-12 mt-4 p-0">
                <div style="height: 125px">
                  <img
                    style="object-fit: cover; object-position: center;box-shadow: #0000003d 0px 9px 12px 0px;border-radius: 5px;"
                    src="~static/images/NoPath - Copy (8).png"
                    alt
                    class="w-100 h-100"
                  />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div
      class="container bg-white p-0 mt-5"
      style="box-shadow: rgba(212, 212, 212, 0.24) 0px 9px 12px 0px;border: 1px solid #e2e2e2b5;"
    >
      <div
        class="container pb-3 pt-3 align-items-center w-100 d-flex justify-content-between"
        style="box-shadow: 0px 1px 0px 0px #f1f0f0;"
      >
        <div class="d-flex align-items-center">
          <p class="font-weight-bold">Deal of the Day</p>
          <p style="padding-left: 10px">
           <img
              src="~static/images/timer.png"
              style="    height: 100%;
    width: 15px;
    object-fit: contain;margin-right: 10px"
            />
            <span id="demo"></span>
          </p>
        </div>

        <button type="button" class="btn btn-primary btn-sm">View All</button>
      </div>
      <div class="container-fluid h-100 mt-5 mb-5">
        <div class="owl-carousel owl-carousel3">
          <div>
            <div class="box-size">
              <nuxt-link to="proddesc"><img src="~static/images/u-rockerz-255f-boat-original-imafg96fqggknft6.png" /></nuxt-link>
            </div>
            <div class="w-100 text-center">
              <p class="font-weight-bold">Boat Rockers 225</p>
              <p class="m-0 text-medium">Upto 50% off</p>
              <p class="m-0 text-small">Hurry Up!</p>
            </div>
          </div>
          <div>
            <div class="box-size">
              <nuxt-link to="proddesc"><img class="w-100 h-100" src="~static/images/hp-v152w-original-imaek4gdpcpdvcw8.png" /></nuxt-link>
            </div>
            <div class="w-100 text-center">
              <p class="font-weight-bold">Pendrive</p>
              <p class="text-medium">Upto 50% off</p>
              <p class="text-small">Hurry Up!</p>
            </div>
          </div>
          <div>
            <div class="box-size">
              <nuxt-link to="proddesc"><img class="w-100 h-100" src="~static/images/41wFnqU3sfL.__AC_SY200_.png" /></nuxt-link>
            </div>
            <div class="w-100 text-center">
              <p class="font-weight-bold">T-shirt</p>
              <p class="text-medium">Upto 50% off</p>
              <p class="text-small">Hurry Up!</p>
            </div>
          </div>
          <div>
            <div class="box-size">
              <nuxt-link to="proddesc"><img class="w-100 h-100" src="~static/images/41f8GVcsWEL._SCLZZZZZZZ___AC_SY200_.png" /></nuxt-link>
            </div>
            <div class="w-100 text-center">
              <p class="font-weight-bold">Pillows</p>
              <p class="text-medium">Upto 50% off</p>
              <p class="text-small">Hurry Up!</p>
            </div>
          </div>
          <div>
            <div class="box-size">
              <nuxt-link to="proddesc"><img
                class="w-100 h-100"
                src="~static/images/sa6048-8-kreuzer-brown-original-imafg95bgaqwzga5.png"
              /></nuxt-link>
            </div>
            <div class="w-100 text-center">
              <p class="font-weight-bold">Shoes</p>
              <p class="text-medium">Upto 50% off</p>
              <p class="text-small">Hurry Up!</p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container mt-5 bg-white mb-4">
      <div>
        <p class="font-weight-bold text-center">Shop by Top Categories</p>
      </div>
      <div>
        <div class="container-fluid h-100 mt-3">
          <div class="owl-carousel owl-carousel3 no_nav">
            <div>
              <div class="box-size">
                <nuxt-link to="proddesc"><img
                  class="w-100 h-100"
                  src="~static/images/LED-Television-PNG-Transparent-Picture.png"
                /></nuxt-link>
              </div>
              <div class="w-100 align-self-center">
                <p>Television</p>
                <p>Sale upto 30% off</p>
              </div>
            </div>
            <div class="box-size">
               <nuxt-link to="proddesc"><img class="w-100 h-100" src="~static/images/hp-v152w-original-imaek4gdpcpdvcw8.png" /></nuxt-link>
            </div>
            <div class="box-size">
               <nuxt-link to="proddesc"><img class="w-100 h-100" src="~static/images/41wFnqU3sfL.__AC_SY200_.png" /></nuxt-link>
            </div>
            <div class="box-size">
               <nuxt-link to="proddesc"><img class="w-100 h-100" src="~static/images/41f8GVcsWEL._SCLZZZZZZZ___AC_SY200_.png" /></nuxt-link>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container" style="height:140px">
      <img class="h-100 w-100" src="~static/images/NoPath - Copy (73).png" />
    </div>

    <div
      class="container p-0 mt-5 bg-white"
      style="box-shadow: rgba(212, 212, 212, 0.24) 0px 9px 12px 0px;border: 1px solid #e2e2e2b5;"
    >
      <div
        class="container pb-3 pt-3 align-items-center w-100 d-flex justify-content-between"
        style="box-shadow: 0px 1px 0px 0px #f1f0f0;"
      >
        <div class="d-flex align-items-center">
          <p class="font-weight-bold">Fashion For Travel Lovers</p>
          <!-- <p style="padding-left: 10px">
            <img
              src="~static/images/timer.png"
              style="    height: 100%;
    width: 15px;
    object-fit: contain;margin-right: 10px"
            />
            <span id="demo"></span>
          </p> -->
        </div>

        <button type="button" class="btn btn-primary btn-sm">View All</button>
      </div>
      <div class="container-fluid h-100 mt-5 mb-5">
        <div class="owl-carousel owl-carousel3">
          <div>
            <div class="box-size">
              <img class="w-100 h-100" src="~static/images/airplane_pilliow.png" />
            </div>
            <div class="d-flex flex-column">
              <p class="text-center productPrice mb-1 mt-2">Pillows</p>
              <p class="text-center text-small productPrice mb-2">Price: $ 150.00</p>
              <nuxt-link class="text-center" to="proddesc"><button
                class="btn btn-sm"
                style="margin: auto;background-color: #ffc300;color: #ffffff"
              >Add to Cart</button></nuxt-link>
            </div>
          </div>
          <div>
            <div class="box-size">
              <img class="w-100 h-100" src="~static/images/travelbag.png" />
            </div>
            <div class="d-flex flex-column">
              <p class="text-center productPrice mb-1 mt-2">Travel Bag</p>
              <p class="text-center text-small productPrice mb-2">Price: $ 150.00</p>
              <nuxt-link class="text-center" to="proddesc"><button
                class="btn btn-sm"
                style="margin: auto;background-color: #ffc300;color: #ffffff"
              >Add to Cart</button></nuxt-link>
            </div>
          </div>
          <div>
            <div class="box-size">
              <img class="w-100 h-100" src="~static/images/laptopbag.png" />
            </div>
            <div class="d-flex flex-column">
              <p class="text-center productPrice mb-1 mt-2">Laptop Bag</p>
              <p class="text-center text-small productPrice mb-2">Price: $ 150.00</p>
              <nuxt-link class="text-center" to="proddesc"><button
                class="btn btn-sm"
                style="margin: auto;background-color: #ffc300;color: #ffffff"
              >Add to Cart</button></nuxt-link>
            </div>
          </div>
          <div>
            <div class="box-size">
              <img class="w-100 h-100" src="~static/images/travelbag (2).png" />
            </div>
            <div class="d-flex flex-column">
              <p class="text-center productPrice mb-1 mt-2">Baggage</p>
              <p class="text-center text-small productPrice mb-2">Price: $ 150.00</p>
              <nuxt-link class="text-center" to="proddesc"><button
                class="btn btn-sm"
                style="margin: auto;background-color: #ffc300;color: #ffffff"
              >Add to Cart</button></nuxt-link>
            </div>
          </div>
          <div>
            <div class="box-size">
              <img class="w-100 h-100" src="~static/images/casado.png" />
            </div>
            <div class="d-flex flex-column">
              <p class="text-center productPrice mb-1 mt-2">Casado</p>
              <p class="text-center text-small productPrice mb-2">Price: $ 150.00</p>
              <nuxt-link class="text-center" to="proddesc"><button
                class="btn btn-sm"
                style="margin: auto;background-color: #ffc300;color: #ffffff"
              >Add to Cart</button></nuxt-link>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div
      class="container p-0 mt-5 bg-white"
      style="box-shadow: rgba(212, 212, 212, 0.24) 0px 9px 12px 0px;border: 1px solid #e2e2e2b5;"
    >
      <div
        class="container pb-3 pt-3 align-items-center w-100 d-flex justify-content-between"
        style="box-shadow: 0px 1px 0px 0px #f1f0f0;"
      >
        <div class="d-flex align-items-center">
          <p class="font-weight-bold">Best Camera Smartphone</p>
          <!-- <p style="padding-left: 10px">
            <img
              src="~static/images/timer.png"
              style="    height: 100%;
    width: 15px;
    object-fit: contain;margin-right: 10px"
            />
            <span id="demo"></span>
          </p> -->
        </div>

        <button type="button" class="btn btn-primary btn-sm">View All</button>
      </div>
      <div class="container-fluid h-100 mt-5 mb-5">
        <div class="owl-carousel owl-carousel3">
          <div>
            <div class="box-size">
              <nuxt-link class="text-center" to="proddesc"><img class="w-100 h-100" src="~static/images/oppo.png" /></nuxt-link>
            </div>
            <div class="d-flex flex-column">
              <p class="text-center productPrice mb-1 mt-2">Oppo F9 Pro</p>
              <p class="text-center text-small productPrice mb-2">Price: $ 150.00</p>
              <nuxt-link class="text-center" to="proddesc"><button
                class="btn btn-sm"
                style="margin: auto;background-color: #ffc300;color: #ffffff"
              >Add to Cart</button></nuxt-link>
            </div>
          </div>
          <div>
            <div class="box-size">
              <nuxt-link class="text-center" to="proddesc"><img class="w-100 h-100" src="~static/images/nokia.png" /></nuxt-link>
            </div>
            <div class="d-flex flex-column">
              <p class="text-center productPrice mb-1 mt-2">Nokia 5,1 Plus</p>
              <p class="text-center text-small productPrice mb-2">Price: $ 150.00</p>
              <nuxt-link class="text-center" to="proddesc"><button
                class="btn btn-sm"
                style="margin: auto;background-color: #ffc300;color: #ffffff"
              >Add to Cart</button></nuxt-link>
            </div>
          </div>
          <div>
            <div class="box-size">
              <nuxt-link class="text-center" to="proddesc"><img class="w-100 h-100" src="~static/images/realme.png" /></nuxt-link>
            </div>
            <div class="d-flex flex-column">
              <p class="text-center productPrice mb-1 mt-2">Realme 2 Pro</p>
              <p class="text-center text-small productPrice mb-2">Price: $ 150.00</p>
              <nuxt-link class="text-center" to="proddesc"><button
                class="btn btn-sm"
                style="margin: auto;background-color: #ffc300;color: #ffffff"
              >Add to Cart</button></nuxt-link>
            </div>
          </div>
          <div>
            <div class="box-size">
              <nuxt-link class="text-center" to="proddesc"><img class="w-100 h-100" src="~static/images/samsung.png" /></nuxt-link>
            </div>
            <div class="d-flex flex-column">
              <p class="text-center productPrice mb-1 mt-2">Samsung</p>
              <p class="text-center text-small productPrice mb-2">Price: $ 150.00</p>
              <nuxt-link class="text-center" to="proddesc"><button
                class="btn btn-sm"
                style="margin: auto;background-color: #ffc300;color: #ffffff"
              >Add to Cart</button></nuxt-link>
            </div>
          </div>
          <div>
            <div class="box-size">
              <nuxt-link class="text-center" to="proddesc"><img class="w-100 h-100" src="~static/images/honor.png" /></nuxt-link>
            </div>
            <div class="d-flex flex-column">
              <p class="text-center productPrice mb-1 mt-2">Honor</p>
              <p class="text-center text-small productPrice mb-2">Price: $ 150.00</p>
              <nuxt-link class="text-center" to="proddesc"><button
                class="btn btn-sm"
                style="margin: auto;background-color: #ffc300;color: #ffffff"
              >Add to Cart</button></nuxt-link>
            </div>
          </div>
          <!-- <div>
            <div class="box-size">
              <img class="w-100 h-100" src="~static/images/71uyAFj1bkL._AC_UL320_.png" />
            </div>
            <div class="d-flex flex-column">
              <p class="text-center productPrice mb-1 mt-2">Fashion 7 Leather Bag</p>
              <p class="text-center text-small productPrice mb-2">Price: $ 150.00</p>
              <button
                class="btn btn-sm"
                style="margin: auto;background-color: #ffc300;color: #ffffff"
              >Add to Cart</button>
            </div>
          </div> -->
        </div>
      </div>
    </div>

    <div class="container p-0 mt-5">
      <div class="h-100 mt-5 mb-5">
        <div class="owl-carousel owl-carousel2">
          <div style="height: 150px">
            <nuxt-link class="text-center" to="proddesc"><img
              style="object-fit: cover; object-position: center;border-radius: 5px;"
              src="~static/images/NoPath - Copy (8).png"
              alt
              class="w-100 h-100"
            /></nuxt-link>
          </div>

          <div style="height: 150px">
            <nuxt-link class="text-center" to="proddesc"><img
              style="object-fit: cover; object-position: center;border-radius: 5px;"
              src="~static/images/NoPath - Copy (8).png"
              alt
              class="w-100 h-100"
            /></nuxt-link>
          </div>
          <div style="height: 150px">
            <nuxt-link class="text-center" to="proddesc"><img
              style="object-fit: cover; object-position: center;border-radius: 5px;"
              src="~static/images/NoPath - Copy (8).png"
              alt
              class="w-100 h-100"
            /></nuxt-link>
          </div>
        </div>
      </div>
    </div>

  <div
      class="container p-0 mt-5"
      style="box-shadow: rgba(212, 212, 212, 0.24) 0px 9px 12px 0px;border: 1px solid #e2e2e2b5;"
    >
      <div
        class="container pb-3 pt-3 align-items-center w-100 d-flex justify-content-between"
        style="box-shadow: 0px 1px 0px 0px #f1f0f0;background-color:#f6f7f9">
        <div class="d-flex align-items-center">
          <p class="font-weight-bold">Camera & Camcorder</p>
        </div>

      
         <div class="row" style="display:flex;align-items:center;width:70%">
           <p class="col-sm-3 bold">New Products</p>
           <p class="col-sm-3">Best Selling</p>
           <p class="col-sm-3">Featured Products</p>
           <p class="col-sm-3">Most Popular Views</p>
         </div>
      
      </div>
      <div class="container-fluid h-100 mt-5 mb-5">
        <div class="row">
          <div class="col-sm-3">
            <img
              class="h-100 w-100"
              style="object-fit:cover;border-radius: 5px;"
              src="~static/images/NoPath - Copy (78).png"
            />
          </div>
          <div class="col-sm-9">
            <div class="owl-carousel owl-carousel4">
              <div>
                <div class="box-size">
                  <nuxt-link class="text-center" to="proddesc"><img class="w-100 h-100" src="~static/images/samsung-camera.png" /></nuxt-link>
                </div>
                <div class="d-flex flex-column">
                  <p class="text-center productPrice mb-1 mt-2">Samsung Camera</p>
                  <p class="text-center text-small productPrice mb-2">Price: $ 150.00</p>
                  <nuxt-link class="text-center" to="proddesc"><button
                    class="btn btn-sm"
                    style="margin: auto;background-color: #ffc300;color: #ffffff"
                  >Add to Cart</button></nuxt-link>
                </div>
              </div>
                 <div>
                <div class="box-size">
                  <nuxt-link class="text-center" to="proddesc"><img class="w-100 h-100" src="~static/images/canon.png" /></nuxt-link>
                </div>
                <div class="d-flex flex-column">
                  <p class="text-center productPrice mb-1 mt-2">Canon</p>
                  <p class="text-center text-small productPrice mb-2">Price: $ 150.00</p>
                  <nuxt-link class="text-center" to="proddesc"><button
                    class="btn btn-sm"
                    style="margin: auto;background-color: #ffc300;color: #ffffff"
                  >Add to Cart</button></nuxt-link>
                </div>
              </div>
               <div>
                <div class="box-size">
                  <nuxt-link class="text-center" to="proddesc"><img class="w-100 h-100" src="~static/images/polo.png" /></nuxt-link>
                </div>
                <div class="d-flex flex-column">
                  <p class="text-center productPrice mb-1 mt-2">Polo</p>
                  <p class="text-center text-small productPrice mb-2">Price: $ 150.00</p>
                  <nuxt-link class="text-center" to="proddesc"><button
                    class="btn btn-sm"
                    style="margin: auto;background-color: #ffc300;color: #ffffff"
                  >Add to Cart</button></nuxt-link>
                </div>
              </div>
              <div>
                <div class="box-size">
                  <nuxt-link class="text-center" to="proddesc"><img class="w-100 h-100" src="~static/images/sonydslr.png" /></nuxt-link>
                </div>
                <div class="d-flex flex-column">
                  <p class="text-center productPrice mb-1 mt-2">Sony Dslr</p>
                  <p class="text-center text-small productPrice mb-2">Price: $ 150.00</p>
                  <nuxt-link class="text-center" to="proddesc"><button
                    class="btn btn-sm"
                    style="margin: auto;background-color: #ffc300;color: #ffffff"
                  >Add to Cart</button></nuxt-link>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container mt-5" style="height:140px">
      <img
        class="h-100 w-100"
        style="object-fit:cover;border-radius: 5px;"
        src="~static/images/Untitled-2.png"
      />
    </div>
  </div>
</template> 
<script>
export default {
  mounted() {
    var countDownDate = new Date("Jan 5, 2021 15:37:25").getTime();

    // Update the count down every 1 second
    var x = setInterval(function() {
      // Get today's date and time
      var now = new Date().getTime();

      // Find the distance between now and the count down date
      var distance = countDownDate - now;

      // Time calculations for days, hours, minutes and seconds
      var days = Math.floor(distance / (1000 * 60 * 60 * 24));
      var hours = Math.floor(
        (distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60)
      );
      var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
      var seconds = Math.floor((distance % (1000 * 60)) / 1000);

      // Display the result in the element with id="demo"
      document.getElementById("demo").innerHTML =
        days + "d " + hours + "h " + minutes + "m " + seconds + "s ";

      // If the count down is finished, write some text
      if (distance < 0) {
        clearInterval(x);
        document.getElementById("demo").innerHTML = "EXPIRED";
      }
    }, 1000);

    $(".owl-carousel1").owlCarousel({
      loop: true,
      margin: 30,
      nav: true,
      navText: [
        "<p class='border round-0 no-select'>&lt</p>",
        "<p class='border round-0 no-select'>&gt;</p>"
      ],
      center: true,
      dotsEach: true,
      responsive: {
        1: {
          items: 1
        },
        600: {
          items: 3
        },
        1000: {
          items: 5
        }
      }
    });
    $(".owl-carousel2").owlCarousel({
      loop: true,
      margin: 30,
      nav: true,
      navText: [
        "<p class='owlnavigation no-select'>&lt</p>",
        "<p class='owlnavigation no-select'>&gt;</p>"
      ],
      center: true,
      dotsEach: true,
      responsive: {
        1: {
          items: 1
        },
        600: {
          items: 3
        },
        1000: {
          items: 3
        }
      }
    });
    $(".owl-carousel3").owlCarousel({
      loop: true,
      margin: 30,
      nav: true,
      navText: [
        "<p class='owlnavigation no-select'>&lt</p>",
        "<p class='owlnavigation no-select'>&gt;</p>"
      ],
      center: true,
      dotsEach: true,
      responsive: {
        1: {
          items: 1
        },
        600: {
          items: 3
        },
        1000: {
          items: 5
        }
      }
    });
     $(".owl-carousel4").owlCarousel({
      loop: true,
      margin: 30,
      nav: true,
      navText: [
        "<p class='owlnavigation no-select'>&lt</p>",
        "<p class='owlnavigation no-select'>&gt;</p>"
      ],
      center: true,
      dotsEach: true,
      responsive: {
        1: {
          items: 1
        },
        600: {
          items: 2
        },
        1000: {
          items: 4
        }
      }
    });
  }
};
</script>
<style scoped>
.box-size {
  height: 150px;
  width: 100%;
  object-fit: contain;
}
.text-small {
  font-size: 12px;
}
.text-medium {
  font-size: 14px;
}
.owl-carousel .owl-item img {
  width: 100%;
  height: 100%;
  padding-bottom: 20px;
}
.owl-carousel2 .owl-item img {
  width: 100%;
  height: 100%;
  padding-bottom: 0;
}
</style>