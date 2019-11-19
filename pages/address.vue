<template>
    <div>
        <div class="container">
            <div class="pad1 mb-3">
                <p class="addr-head">Manage Address</p>
                    <div class="main">
                        <div class="sub-main">
                            <form>
                                <div><p>ADD A NEW ADDRESS</p></div>
                                <div class="location">
                                    <div class="mb-2">
                                        <button type="button" class="lbutton">USE MY CURRENT LOCATION</button>
                                    </div>
                                    <div class="d-flex">
                                        <div class="custom-input mr-2">
                                            <label for="name" class="custom-label">Name</label>
                                            <input type="text" name="name" class="iclass">
                                        </div>
                                        <div class="custom-input">
                                            <label for="phone" class="custom-label">10-digit phone number</label>
                                            <input type="text" maxlength="10" required name="Phone" class="iclass">
                                        </div>
                                    </div>
                                    <div class="d-flex">
                                        <div class="custom-input mr-2">
                                            <label for="pcode" class="custom-label">Pin-Code</label>
                                            <input type="number" name="pcode" required maxlength="6" class="iclass">
                                        </div>
                                        <div class="custom-input">
                                            <label for="locality" class="custom-label">Locality</label>
                                            <input type="text" name="locality" class="iclass">                                    
                                        </div>
                                    </div>
                                    <div>
                                        <label for="addr" class="custom-label">Address(Area And street)</label>
                                        <textarea class="iclass" rows="5" id="comment"></textarea>
                                    </div>
                                    <div class="d-flex">
                                        <div class="custom-input mr-2">
                                            <label for="city" class="custom-label">City</label>
                                            <input type="text" name="city" class="iclass">
                                        </div>
                                        <div class="custom-input">
                                            <label for="town" class="custom-label">State</label>
                                            <select class="iclass" id="town">
                                                <option>1</option>
                                                <option>2</option>
                                                <option>3</option>
                                                <option>4</option>
                                            </select>
                                        </div>
                                    </div>
                                    <div class="d-flex">
                                        <div class="custom-input mr-2">
                                            <label for="lmark" class="custom-label">Land Mark</label>
                                            <input type="number" name="pcode" required maxlength="6" class="iclass">
                                        </div>
                                        <div class="custom-input">
                                            <label for="locality" class="custom-label">Alternate Phone Number</label>
                                            <input type="number" name="aPhone" maxlength="10" class="iclass">                                    
                                        </div>
                                    </div>
                                    <div class="d-flex">
                                        <div>
                                            <button class="save-bttn" type="button">SAVE</button>
                                        </div>
                                        <div>
                                            <button class="cancel-bttn" type="button">CANCEL</button>
                                        </div>
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
.main{
    border: 1px solid #e0e0e0;
    background: #fff;
    border-radius: 2px;
    margin-bottom: 30px;
    /* padding: 10px 13px 0 13px; */
}
.sub-main{
    background-color: #f5faff;
    padding: 20px;
    position: relative;
}
.location{
    margin-top: 16px;
    width: 570px;
}
.lbutton{
    background: #006600;
    color: #fff;
    box-shadow: 0 2px 4px 0 rgba(0,0,0,.2);
    border: none;
    padding: 14px 24px;
    font-size: 14px;
}
.text-box{
    width: 280px;
}
.custom-input{
    position: relative;
    margin-bottom: 10px;
    width: 280px;
}
.iclass{
    width: 100%;
    font-size: 14px;
    border: 1px solid #e0e0e0;
    outline: none;
    border-radius: 2px;
    padding:10px 16px 11px 13px;
    box-shadow: none;
}
.custom-label{
    width: 100%;
    font-size: 14px;
    outline: none;
    border-radius: 2px;
    padding: 20px 16px 0 13px;
    box-shadow: none;
    color:#918b8b;
}
.pad1{
     background-color: #fff;
    padding: 24px 32px;
    position: relative;
}
.addr-head{
    color:#918b8b;
    font-size: 21px;
    font-weight: 600;
}
.iclass option{
    font-size:13px;
}
.save-bttn{
    box-shadow: 0 1px 2px 0 rgba(0,0,0,.2);
    border: none;
    color: #fff;
    background-color: #006600;
    height: 48px;
    width: 230px;
    cursor: pointer;
    font-weight: 600;
}
.cancel-bttn{
    font-weight: 500;
    color: #2874f0;
    background-color: transparent;
    border: none;
    margin-left: 20px;
    padding: 10px 0 1px 38px;
    cursor: pointer;
}
</style>