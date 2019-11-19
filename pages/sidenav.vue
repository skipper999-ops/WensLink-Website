<template>
    <div class="container">
        <div class="row mt-2">
            <div class="col-md-3">
                <div class="pad bg-white">
                    <div class="d-flex align-items-center">
                        <span class="mr-2">
                            <img style="height:50px;width50px" src="~static/icons/profilepic.svg">
                        </span>
                        <span>
                            <div>
                                <p>Hello</p>
                            </div>
                            <div>
                                <p class="accnt">Chiranjib Paul</p>
                            </div>
                        </span>
                    </div>
                </div>
                <div class="bg-white">
                <div class="pad mt-5 border-bottom bg-white">
                    <div class="d-flex justify-content-between align-items-center">
                        <span>
                            <img src="~static/icons/download.svg">
                        </span>
                        <span>
                            <nuxt-link to="orders"><p class="accnt">MY ORDERS</p></nuxt-link>
                        </span>
                        <span>
                            <p>></p>
                        </span>
                    </div>
                </div>
                <div class=" border-bottom">
                    <div class="text-center pad2"> 
                        <nuxt-link class="none" to=""><p class="accnt2">Account Settings</p></nuxt-link>
                    </div>
                    <div class="text-center pad2">
                        <nuxt-link class="none" to=""><p>Profile Information</p></nuxt-link>
                    </div>
                    <div class="text-center pad2">
                        <nuxt-link class="none" to=""><p>Manage Addresses</p></nuxt-link>
                    </div>
                    <div class="text-center pad2">
                        <nuxt-link class="none" to=""><p>PAN Card Information</p></nuxt-link>
                    </div>
                </div>
                <div class="">
                    <div class="d-flex justify-content-center">
                        <nuxt-link class="accnt pad2 none" to=""><p>My Wishlist</p></nuxt-link>
                    </div>
                </div>
            </div>
            </div>
            <div class="col-md-9 bg-white">
                <div class="info">
                    <div class="d-flex mb-2">
                        <span class="pr-2 font-weight"><p>Personal Information</p></span>
                        <span><p>Edit</p></span>
                    </div>
                    <div>
                        <form action="">
                            <div class="mb-2 d-flex">
                                <div class="mr-3">
                                    <label for="fname" class="custom-label">First Name</label>
                                    <input type="text" name="fname" class="form-control iclass">
                                </div>
                                <div class="">
                                    <label for="lname" class="custom-label">Last Name</label>
                                    <input type="text" class="form-control iclass" name="lname" required autocomplete="name">
                                </div>                              
                            </div>
                            <div class="pb-5">
                                <label for="gender" class="custom-label">Your Gender</label><br>
                                <input type="radio" class="mr-3" name="gender" value="Male"><span class="mr-2">Male</span>
                                <input type="radio" class="mr-3" name="gender" value="Female"><span>Female</span>
                            </div>
                            <div class=" mb-3">
                                    <div class="d-flex pb-4">
                                        <span class="pr-4 font-weight"><p>E-mail Address</p></span>
                                        <span class="mr-2"><p>Edit</p></span>
                                        <span><p>Change Password</p></span>
                                    </div>
                                    <div>
                                        <input type="email" required name="email" class="w-50 form-control iclass">
                                    </div>
                             </div>
                             <div class="mb-4">
                                 <div class="d-flex pb-4">
                                        <span class="pr-4 font-weight"><p>Phone Number</p></span>
                                        <span class="mr-2"><p>Edit</p></span>
                                </div>
                                <div>
                                        <input type="number" required maxlength="10" name="number" class="w-50 form-control iclass">
                                </div>
                             </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style scoped>
.pad{
    padding: 0 12px;
    /* margin: 0 0 16px 0; */
}
.bd-white{
    background-color: #ffffff;
}
/* .{
   box-:0 2px 4px 0 rgba(0,0,0,.08);
} */
.border-bottom{
    border-bottom: 1px solid #b3adad3b;
}
.accnt{
    font-size: 20px;
    font-weight: 600;
    padding: 10px 0;
    color: #878787;
}
.pad2{
    padding: 7px 0;
}
.none:hover{
    padding: 7px 0;
    font-weight: 500;
    color: #2874f0;
    background-color: #f5faff;
    
}
.none{
    text-decoration: none;
    color: black;
}
.accnt2{
    font-size: 20px;
    font-weight: 600;
}
.info{
    padding: 32px 24px 0;
}
.iclass{
    width: 100%;
    font-size: 14px;
    border: 1px solid #e0e0e0;
    outline: none;
    border-radius: 3px;
    padding:10px 16px 11px 13px;
    box-shadow: none;
}
.custom-label{
    font-size: 14px;
}
.font-weight{
    font-weight:600;
    font-size: 16px;
}
</style>