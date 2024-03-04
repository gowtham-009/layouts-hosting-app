<template>
    <div class="main-module">
       <div class="sub-contain w-100 d-flex gap-5 p-5">
         <div class="personal-box pb-1  w-25 p-3">
            <div class="personal-link d-flex gap-3 w-100 p-2">
                <div class="pen d-flex justify-content-center align-items-center p-3">
                  <i class="fa-solid fa-pencil text-white  fs-4"></i>
                </div>
            <p class="fs-4">Personal</p>
            </div>
         </div>
         <div class="personal-box p-3  w-100">
            <div class="d-flex p-3 line w-100">
            <div class="title-content-box w-100  p-2 d-flex align-items-center gap-3">
               <p class="fs-5">Welcome</p><h3 class="d-flex bol">VENKATACHALAM,</h3><p class="fs-5 mt-2">Share a bit about yourself</p>
            </div>
            <div class="title-content-box w-25  p-2 d-flex justify-content-end align-items-center gap-3">
               <div class="question"><i class="fa-solid fa-question text-white"></i></div><i class="fa-solid fa-ellipsis-vertical fs-3"></i>
            </div>
         </div>
         <div class="container trade-cont">
            <div class="row p-3">
               <div class="col-12 p-3 tb">
                  <p class="text-dark fs-5 fw-bold">Your trading experience</p>
                  <div class="trade-btn mt-3 d-flex flex-wrap gap-2">
                     <!-- btn-1 -->
                     <input class="trad-exp-input" type="radio" id="radioButton1" name="radioGroup">
                     <label class="trad-exp-label" for="radioButton1">Less than 1 year</label>
                     <!-- btn-2 -->
                     <input class="trad-exp-input" type="radio" id="radioButton2" name="radioGroup">
                     <label class="trad-exp-label" for="radioButton2">1-2 Years</label>
                      <!-- btn-3 -->
                      <input class="trad-exp-input" type="radio" id="radioButton3" name="radioGroup">
                     <label class="trad-exp-label" for="radioButton3">2-5 Years</label>
                      <!-- btn-4 -->
                      <input class="trad-exp-input" type="radio" id="radioButton4" name="radioGroup">
                     <label class="trad-exp-label" for="radioButton4">5-10 Years</label>
                      <!-- btn-5 -->
                      <input class="trad-exp-input" type="radio" id="radioButton5" name="radioGroup">
                     <label class="trad-exp-label" for="radioButton5">10-20 Years</label>
                      <!-- btn-6 -->
                      <input class="trad-exp-input" type="radio" id="radioButton6" name="radioGroup">
                     <label class="trad-exp-label" for="radioButton6">20-25 Years</label>
                      <!-- btn-7 -->
                      <input class="trad-exp-input" type="radio" id="radioButton7" name="radioGroup">
                     <label class="trad-exp-label" for="radioButton7">More than 25</label>
                     
                  </div>
               </div>
               <div class="col-12 tb p-3">
                  <p class="text-dark fs-5 fw-bold">Your annual income</p>
                  <div class="trade-btn mt-3 d-flex flex-wrap gap-2">
                     <!-- btn-1 -->
                     <input class="annual-income-input" type="radio" id="a-radioButton1" name="radioGroup-a">
                     <label class="annual-income-label" for="a-radioButton1">Below 1 Lakhs</label>
                     <!-- btn-2 -->
                     <input class="annual-income-input" type="radio" id="a-radioButton2" name="radioGroup-a">
                     <label class="annual-income-label" for="a-radioButton2">1L-5L</label>
                      <!-- btn-3 -->
                      <input class="annual-income-input" type="radio" id="a-radioButton3" name="radioGroup-a">
                     <label class="annual-income-label" for="a-radioButton3">5L-10L</label>
                      <!-- btn-4 -->
                      <input class="annual-income-input" type="radio" id="a-radioButton4" name="radioGroup-a">
                     <label class="annual-income-label" for="a-radioButton4">Above 25L</label>
                  </div>
               </div>
               <div class="col-12  tb p-3">
                  <p class="text-dark fs-5 fw-bold">Your occupation</p>
                  <div class="trade-btn mt-3 d-flex flex-wrap gap-2">
                      <!-- btn-1 -->
                      <input class="your-occupation-input" type="radio" id="o-radioButton1" name="radioGroup-o">
                     <label class="your-occupation-label" for="o-radioButton1">Private sector</label>
                     <!-- btn-2 -->
                     <input class="your-occupation-input" type="radio" id="o-radioButton2" name="radioGroup-o">
                     <label class="your-occupation-label" for="o-radioButton2">Government services</label>
                      <!-- btn-3 -->
                      <input class="your-occupation-input" type="radio" id="o-radioButton3" name="radioGroup-o">
                     <label class="your-occupation-label" for="o-radioButton3">Public sector</label>
                      <!-- btn-4 -->
                      <input class="your-occupation-input" type="radio" id="o-radioButton4" name="radioGroup-o">
                     <label class="your-occupation-label" for="o-radioButton4">Agriculturist</label>
                       <!-- btn-5-->
                       <input class="your-occupation-input" type="radio" id="o-radioButton1" name="radioGroup-o">
                     <label class="your-occupation-label" for="o-radioButton1">Professional</label>
                     <!-- btn-6-->
                     <input class="your-occupation-input" type="radio" id="o-radioButton2" name="radioGroup-o">
                     <label class="your-occupation-label" for="o-radioButton2">Business</label>
                      <!-- btn-7-->
                      <input class="your-occupation-input" type="radio" id="o-radioButton3" name="radioGroup-o">
                     <label class="your-occupation-label" for="o-radioButton3">Housewife</label>
                      <!-- btn-8-->
                      <input class="your-occupation-input" type="radio" id="o-radioButton4" name="radioGroup-o">
                     <label class="your-occupation-label" for="o-radioButton4">Retired</label>
                       <!-- btn-9-->
                       <input class="your-occupation-input" type="radio" id="o-radioButton1" name="radioGroup-o">
                     <label class="your-occupation-label" for="o-radioButton1">Student</label>
                     <!-- btn-10-->
                     <input class="your-occupation-input" type="radio" id="o-radioButton2" name="radioGroup-o">
                     <label class="your-occupation-label" for="o-radioButton2">Other</label>
                  </div>
               </div>
               <div class="col-12 cont-btn d-flex justify-content-center align-item-center p-3">
                  <NuxtLink class="btn otp-btn w-50" to="/page6">Continue</NuxtLink>
               </div>
            </div>
         </div>
         </div>
        
       </div>
       
    </div>
</template>

<script setup>

</script>

<style scoped>
 *{
    margin:0%;
    padding: 0%;
    list-style-type: none;
    box-sizing: border-box;
    
 }
 /* trade-btn-groups */
 .trad-exp-input[type="radio"] {
      display: none;
    }
    .trad-exp-label {
      display: inline-block;
      padding: 10px 20px;
    
       
      color: black; 
        border: 1px solid rgb(167, 167, 167); 
      cursor: pointer;
      border-radius: 20px;
    }

  
    .trad-exp-input[type="radio"]:checked + .trad-exp-label {
      color: aliceblue;
      background-color:blueviolet; /* Set your desired background color for the selected state */
    }
    /* /annual-income-btn-groups */
    .annual-income-input[type="radio"] {
      display: none;
    }
    .annual-income-label {
      display: inline-block;
      padding: 10px 20px;
    
       
      color: black; 
        border: 1px solid rgb(167, 167, 167); 
      cursor: pointer;
      border-radius: 20px;
    }

  
    .annual-income-input[type="radio"]:checked + .annual-income-label {
      color: aliceblue;
      background-color: blueviolet; /* Set your desired background color for the selected state */
    }
    /* your-occupation-btn-groups */
    .your-occupation-input[type="radio"] {
      display: none;
    }
    .your-occupation-label {
      display: inline-block;
      padding: 10px 20px;
    
       
      color: black; 
        border: 1px solid rgb(167, 167, 167); 
      cursor: pointer;
      border-radius: 20px;
    }

  
    .your-occupation-input[type="radio"]:checked + .your-occupation-label {
      color: aliceblue;
      background-color: blueviolet; /* Set your desired background color for the selected state */
    }
 .bol{
   font-weight: 600;
}
 .main-module{
    width: 100%;
    height: 720px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: white;
 }
 .sub-contain{
    height: auto;
    background-color:rgb(253, 253, 240);
 }
 .personal-box{
    background-color: white;
    border-radius: 10px;
 }
 .pen{
    width: 40px;
    height: 40px;
    border-radius: 100%;
    background-color: rgb(81, 0, 157);
 }
 .personal-link{
    background-color: rgb(239, 234, 244);
    border-radius: 10px;
 }
 .personal-link p{
    color: rgb(81, 0, 157);
 }
.title-content-box {
   height: 60px;
}
.question{
    width: 30px;
    height: 30px;
    border-radius: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: gray;

   
}
.line{
   border-bottom: 3px solid rgb(239, 234, 244);;
}
.trade-cont{
   width:60%;
}

.two-trade{
background-color: blueviolet;
}
.tb{
   border-bottom: 2px solid rgb(185, 184, 184);
}
.otp-btn{
   border: none;
   padding: 2%;
   color: white;
   font-size: 20px;
   background-color: blueviolet;
   border-radius: 30px;
}
@media(max-width:992px){
   .main-module{
      align-items: start;
   }
   .pb-1{
      width: 100% !important;
   }
   .sub-contain{
      flex-wrap: wrap;
   }
   .trade-cont{
      width: 100%;
   }
   .title-content-box{
      flex-wrap: wrap;
      overflow: hidden;
   }
}
</style>