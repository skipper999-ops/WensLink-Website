<template>
    <div>
        <div class="row">
            <div class="col-12" id="showFilter">
                <button 
                    style="display:block; margin-left:auto; margin-right:auto; width: 150px; margin-top: 5px;" 
                    id="showFilter">
                    <i class="fa fa-bars mr-2"></i>Filters
                </button>
            </div>
            
            <div class="col-sm-4 offset-lg-1 col-lg-2 hideXS" id='filters' style="padding-left: 0px; padding-right: 0px;">
                <div style="background-color: white; height: auto; margin: 5px; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);">
                    <div data-role="main" class="ui-content" style="border-bottom: 1px solid #ddd;">
                        <form method="post" action="">
                          <div data-role="rangeslider">
                            <label for="price-min">Price</label>
                            <input type="range" name="price-min" id="price-min" value="0" min="0" max="2000">
                            <label for="price-max">Price:</label>
                            <input type="range" name="price-max" id="price-max" value="2000" min="0" max="2000">
                          </div>
                        </form>
                    </div>
                    
                    <div class="set">
                        <a href="#" class="activeOnLoad">Brand<i class="fa fa-plus"></i></a>
                        <div class="content">
                            <form method="post" action="">
                                <input placeholder="Search Brand &#xf002;" class="fonticon" id="search_box">
                            </form>    
                            <form method="post">
                                <div class="form-check">
                                    <label class="form-check-label">
                                        <input type="checkbox" class="form-check-input" value="">iPhone
                                    </label>
                                    <label class="form-check-label">
                                        <input type="checkbox" class="form-check-input" value="">Mi
                                    </label>
                                    <label class="form-check-label">
                                        <input type="checkbox" class="form-check-input" value="">Asus
                                    </label>
                                    <label class="form-check-label">
                                        <input type="checkbox" class="form-check-input" value="">Samsung
                                    </label>
                                </div>
                            </form>
                        </div>
                    </div>
                    <div class="set">
                        <a href="#">Internal Storage<i class="fa fa-plus"></i></a>
                        <div class="content">
                            <form method="post">
                                <div class="form-check">
                                    <label class="form-check-label">
                                        <input type="checkbox" class="form-check-input" value="">256 GB
                                    </label>
                                    <label class="form-check-label">
                                        <input type="checkbox" class="form-check-input" value="">128 GB
                                    </label>
                                    <label class="form-check-label">
                                        <input type="checkbox" class="form-check-input" value="">64 GB
                                    </label>
                                </div>
                            </form>
                        </div>
                    </div>
                    <div class="set">
                        <a href="#">RAM<i class="fa fa-plus"></i></a>
                        <div class="content">
                            <form method="post">
                                <div class="form-check">
                                    <label class="form-check-label">
                                        <input type="checkbox" class="form-check-input" value="">3 GB
                                    </label>
                                    <label class="form-check-label">
                                        <input type="checkbox" class="form-check-input" value="">4 GB
                                    </label>
                                    <label class="form-check-label">
                                        <input type="checkbox" class="form-check-input" value="">8 GB
                                    </label>
                                </div>
                            </form>
                        </div>
                    </div>
                    <div class="set">
                        <a href="#">Customer Ratings<i class="fa fa-plus"></i></a>
                        <div class="content">
                            <form method="post">
                                <div class="form-check">
                                    <label class="form-check-label">
                                        <input type="checkbox" class="form-check-input" value="">4 <i class="fa fa-star" aria-hidden="true"></i> & above
                                    </label>
                                    <label class="form-check-label">
                                        <input type="checkbox" class="form-check-input" value="">3 <i class="fa fa-star" aria-hidden="true"></i> & above
                                    </label>
                                    <label class="form-check-label">
                                        <input type="checkbox" class="form-check-input" value="">2 <i class="fa fa-star" aria-hidden="true"></i> & above
                                    </label>
                                    <label class="form-check-label">
                                        <input type="checkbox" class="form-check-input" value="">1 <i class="fa fa-star" aria-hidden="true"></i> & above
                                    </label>
                                </div>
                            </form>
                        </div>
                    </div>
                    <div class="set">
                        <a href="#">Operating System<i class="fa fa-plus"></i> </a>
                        <div class="content">
                            <form method="post">
                                <div class="form-check">
                                    <label class="form-check-label">
                                        <input type="checkbox" class="form-check-input" value="">Android
                                    </label>
                                    <label class="form-check-label">
                                        <input type="checkbox" class="form-check-input" value="">iOS
                                    </label>
                                    <label class="form-check-label">
                                        <input type="checkbox" class="form-check-input" value="">Symbian
                                    </label>
                                    <label class="form-check-label">
                                        <input type="checkbox" class="form-check-input" value="">Windows
                                    </label>
                                </div>
                            </form>
                        </div>
                    </div>
                          
                </div>
            </div>
            <div class="col-sm-8 col-lg-8" style="padding-left: 0px; padding-right: 0px;">
                <div style="background-color: white; min-height: 83vh; 
                    margin: 5px; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2); padding: 10px;">
                    
                    <div class="row d-flex mc5">
                        <div class="col-12 col-lg-6 d-flex justify-content-center">
                            <div style="padding-top: 13px;">
                                <div>We've got 1000+ results for 'iPhone 11'</div>
                            </div>
                        </div>
                        <div class="col-12 col-lg-6">
                            <div class="d-flex justify-content-center">
                                <div style="padding-top: 13px; color: #C0C0C0;">Sort By:</div>
                                <div style="width: 170px;">
                                    <select style="font-size: 0.9em;">
                                        <option selected>Price Low to High</option>
                                        <option value="">Price High to Low</option>
                                        <option>Relevance</option>
                                        <option value="">Popularity</option>
                                        <option value="">Discount</option>
                                        <option value="">Fresh Arrivals</option>
                                    </select>
                                </div>
                            </div>
                        </div>

                    </div>
                    <hr style="margin-left: -10px; margin-right: -10px;">
                    <div class="row" style="padding: 15px;">
                        <div class="col-12 col-sm-4 col-lg-3 myCard">
                            <a href="#" style="text-decoration: none; color: black;">
                            <img src="https://assets.croma.com/medias/sys_master/images/images/h71/ha7/8868307664926/221104_pjpeg.jpg"
                                style="width: 100%; height: 75%;" class="mt-2">
                            <h6 class="mt-2" style="text-align: center; font-size: 0.8rem;">Apple iPhone 11 (Red, 64 GB)</h6>
                            <br>
                            <h6 style="margin-top: -20px; text-align: center; font-size: 0.8rem;">Rs.64,900</h6>
                            </a>
                        </div>
                        <div class="col-12 col-sm-4 col-lg-3 myCard">
                            <a href="#" style="text-decoration: none; color: black;">
                            <img src="https://assets.croma.com/medias/sys_master/images/images/h39/h41/8868309008414/221103_pjpeg.jpg"
                            style="width: 100%; height: 75%;" class="mt-2">
                            <h6 class="mt-2" style="text-align: center; font-size: 0.8rem;">Apple iPhone 11 (Yellow, 64 GB)</h6>
                            <br>
                            <h6 style="margin-top: -20px; text-align: center; font-size: 0.8rem;">Rs.64,900</h6>
                            </a>
                        </div>
                        <div class="col-12 col-sm-4 col-lg-3 myCard">
                            <a href="#" style="text-decoration: none; color: black;">
                            <img src="https://assets.croma.com/medias/sys_master/images/images/hb6/hd3/8868308058142/221105_pjpeg.jpg"
                            style="width: 100%; height: 75%;" class="mt-2">
                            <h6 class="mt-2" style="text-align: center; font-size: 0.8rem;">Apple iPhone 11 (Black, 64 GB)</h6>
                            <br>
                            <h6 style="margin-top: -20px; text-align: center; font-size: 0.8rem;">Rs.64,900</h6>
                            </a>
                        </div>
                        <div class="col-12 col-sm-4 col-lg-3 myCard">
                            <a href="#" style="text-decoration: none; color: black;">
                            <img src="https://images-na.ssl-images-amazon.com/images/I/61NQsEQhPdL._SL1500_.jpg"
                            style="width: 100%; height: 75%;" class="mt-2">
                            <h6 class="mt-2" style="text-align: center; font-size: 0.8rem;">Apple iPhone 11 (White, 64 GB)</h6>
                            <br>
                            <h6 style="margin-top: -20px; text-align: center; font-size: 0.8rem;">Rs.64,900</h6>
                            </a>
                        </div>    
                        <div class="col-12 col-sm-4 col-lg-3 myCard">
                            <a href="#" style="text-decoration: none; color: black;">
                            <img src="https://store.storeimages.cdn-apple.com/4982/as-images.apple.com/is/MWVG2_AV2?wid=1144&hei=1144&fmt=jpeg&qlt=80&op_usm=0.5,0.5&.v=1566852605702"
                            style="width: 100%; height: 75%;" class="mt-2">
                            <h6 class="mt-2" style="text-align: center; font-size: 0.8rem;">Apple iPhone 11 (Teal, 64 GB)</h6>
                            <br>
                            <h6 style="margin-top: -20px; text-align: center; font-size: 0.8rem;">Rs.64,900</h6>
                            </a>
                        </div>
                        <div class="col-12 col-sm-4 col-lg-3 myCard">
                            <a href="#" style="text-decoration: none; color: black;">
                            <img src="https://assets.croma.com/medias/sys_master/images/images/h71/ha7/8868307664926/221104_pjpeg.jpg"
                            style="width: 100%; height: 75%;" class="mt-2">
                            <h6 class="mt-2" style="text-align: center; font-size: 0.8rem;">Apple iPhone 11 (Red, 128 GB)</h6>
                            <br>
                            <h6 style="margin-top: -20px; text-align: center; font-size: 0.8rem;">Rs.69,900</h6>
                            </a>
                        </div>
                        <div class="col-12 col-sm-4 col-lg-3 myCard">
                            <a href="#" style="text-decoration: none; color: black;">
                            <img src="https://assets.croma.com/medias/sys_master/images/images/h39/h41/8868309008414/221103_pjpeg.jpg"
                            style="width: 100%; height: 75%;" class="mt-2">
                            <h6 class="mt-2" style="text-align: center; font-size: 0.8rem;">Apple iPhone 11 (Yellow, 128 GB)</h6>
                            <br>
                            <h6 style="margin-top: -20px; text-align: center; font-size: 0.8rem;">Rs.64,900</h6>
                            </a>
                        </div>
                        <div class="col-12 col-sm-4 col-lg-3 myCard">
                            <a href="#" style="text-decoration: none; color: black;">
                            <img src="https://assets.croma.com/medias/sys_master/images/images/hb6/hd3/8868308058142/221105_pjpeg.jpg"
                            style="width: 100%; height: 75%;" class="mt-2">
                            <h6 class="mt-2" style="text-align: center; font-size: 0.8rem;">Apple iPhone 11 (Black, 128 GB)</h6>
                            <br>
                            <h6 style="margin-top: -20px; text-align: center; font-size: 0.8rem;">Rs.64,900</h6>
                            </a>
                        </div>
                        
                        <div class="wrapper" style="display: block; margin-left: auto; margin-right: auto;">
                            <div class="container">
                                <div class="row">
                                    <div class="col-sm-12">
                                      <ul id="pagination-demo" class="pagination-sm"></ul>
                                    </div>
                                </div>
                            </div>
                        </div>

                      </div>
                    </div>
                </div>
            </div>
    </div>    
</template>
<style scoped>
 input[type=number] {
        -moz-appearance:textfield;
    }

    .fonticon {
        font-family: fontawesome;
    }

    .myCard {
        margin-bottom: 30px;
    }

    .myCard:hover {
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
        transform: scale(1.01);
    }

    #pagination-demo{
        display: inline-block;
        margin-bottom: 1.75em;
    }

    #pagination-demo li{
        display: inline-block;
    }

    .page-content{
        background: #eee;
        display: inline-block;
        padding: 10px;
        width: 100%;
        max-width: 660px;
    }

    @media (max-width: 37.5em) {
        .hideXS {
            display: none;
        }
    }

    .showItem {
        display: none;
    }

    .hideItem {
        display: block;
    }

    @media (min-width: 37.5em) {
        #showFilter {
            display: none;
        }
    }

    #st1 {
        position: absolute; 
        right: 20px; 
        padding-left: 25px;
        padding-right: 5px;
    }

    @media (max-width: 37.5em) {
        #st1 {
            position: relative;
        }
    }
</style>
<script>
export default {
    
    mounted(){
        $(document).ready(
        $("input").removeClass("label")
    )

    $('#pagination-demo').twbsPagination({
        totalPages: 15,
        visiblePages: 5,
        next: 'Next',
        prev: 'Prev',
        onPageClick: function (event, page) {
            //fetch content and render here
            $('#page-content').text('Page ' + page) + ' content here';
        }
    });
    
    $('#showFilter').click(function(){
        $('#filters').toggleClass('showItem hideItem')
    });
    $(document).ready(function() {
  $(".set > a").on("click", function() {
    if ($(this).hasClass("active")) {
      $(this).removeClass("active");
      $(this)
        .siblings(".content")
        .slideUp(200);
      $(".set > a i")
        .removeClass("fa-minus")
        .addClass("fa-plus");
    } else {
      $(".set > a i")
        .removeClass("fa-minus")
        .addClass("fa-plus");
      $(this)
        .find("i")
        .removeClass("fa-plus")
        .addClass("fa-minus");
      $(".set > a").removeClass("active");
      $(this).addClass("active");
      $(".content").slideUp(200);
      $(this)
        .siblings(".content")
        .slideDown(200);
    }
  });
});
    $(document).ready(function(){
        $(".activeOnLoad").click()
    })
    }
}
</script>