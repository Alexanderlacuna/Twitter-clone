/* eslint-disable no-trailing-spaces */
<template>
<div id="app" class="h-screen bg-white" >
    <router-view/>

<!-- sectiios -->
<div class="grid grid-cols-12 h-full ">

  <!-- section 1 -->

  <div class=" col-span-3 py-4 px-2 md:px-8 lg:px-16 ">

    <!-- section-a -->
    <div class="font-medium lg:font-semibold text-xs md:text-lg lg:text-lg capitalize  ">

     <div class="lg:mb-6  px-1">
        <a href="#"><i class="fab fa-twitter text-blue-500 fa-lg "></i></a>
     </div>
      <div class="flex  space-x-5 lg:mb-6 text-blue-500  hover:bg-blue-100 lg:w-3/4 rounded-full py-2 px-1">
       <div>
          <i class="fas  fa-lg fa-home "></i>

       </div>
        <h3 class="">Home</h3>
        

      </div>

      <div  class="flex  space-x-6 lg:mb-6 hover:bg-blue-100 lg:w-3/4 rounded-full py-2 px-1 ">
        
     <div >
        <i class="far fa-bell fa-lg"></i>
     </div>

      <h3 class="">Notification</h3>
      </div>

      <div  class="flex  space-x-5 lg:mb-6 hover:bg-blue-100 lg:w-3/4 rounded-full py-1 px-1">
       <div>
          <i class="far fa-envelope fa-lg"></i>
       </div>
        <h3 class="">message</h3>
      </div>
      <div  class="flex  space-x-6 lg:mb-6 hover:bg-blue-100 lg:w-3/4 rounded-full py-1 px-1 ">
        <div>
          <i class="far fa-bookmark fa-lg"></i>
        </div>
        <h3 >bookmark</h3>
      </div>
      <div  class="flex  space-x-5 lg:mb-6 hover:bg-blue-100 lg:w-3/4 rounded-full py-1 px-1">
       <div>
          <i class="far fa-list-alt fa-lg"></i>
       </div>
        <h3>lists</h3>
      </div>
      <div class="flex space-x-5 lg:mb-6 hover:bg-blue-100 lg:w-3/4 rounded-full py-1 px-1">
      <div>
         <i class="far fa-user fa-lg"></i>
      </div>
        <h3>Profile</h3>
      </div>
      <div class="lg:mb-4 text-center flex space-x-5 hover:bg-blue-100 lg:w-3/4 rounded-full py-1 px-1 ">

         <div>
           <i class=" fas fa-ellipsis-h fa-lg" ></i>
         </div>
         <h3 >More</h3>
       
      </div>
    </div>

    <div class="my-6 bg-blue-500 text-center lg:px-4 lg:py-3 rounded-full text-white capitalize hover:bg-blue-600 transition ease-in-out duration-500">
      <button>Tweet</button>
    </div>
<!-- twtter -->
    <div>

      <div class="  flex  flex-col  md:flex-row  mt-3     md:justify-between">
        <div class="flex flex-col  md:flex-row space-x-2 ">

          <div >
            
        <i class="fas fa-user-circle fa-2x text-gray-600  rounded-full px-3 py-3"></i>
        </div>

        <div class="md:flex flex-col justify-center">

          
          <p class="    lg:font-semibold  text-xs md:text-sm ">alexanderkabua</p>
         
          <p class="text-xs md:text-sm text-gray-700    ">@alexanderkabua</p>
        </div>


        </div>

        <div class="self-center ">
         <i class="fas fa-angle-down "></i>
        </div>

      </div>
      
    </div>
  </div>

  <!-- section 2 -->

  <div class="px-5 py-6 col-span-5 border-l border-r border-gray-300  ">
    <div class="border-b border-gray-400 pb-4 ">
      <div class="flex  justify-between">
        <div>
        <h3 class="font-semibold text-lg">Home</h3>
      </div>

      <div class="self-center">
        <i class="far fa-star text-blue-500"></i>
      </div>
      </div>
    </div>
   <!-- second section -->
    <div class=" py-2 border-b-8 border-gray-300 ">
         <div class="flex">
           <div >
            
        <i class="fas fa-user-circle fa-3x text-gray-500  rounded-full px-3 py-3 "></i>
        </div>

        <div class="self-center text-lg text-gray-600  tracking-wide"> 
          <h3>What's happening</h3>
        </div>

         </div>

         <div class=" lg:pl-16 flex justify-between">
            <div class="inline-flex   ">

                        <a href=""><span><i class="fas  fa-chart-area text-blue-500  px-2 py-2 hover:bg-blue-200 rounded-full"></i></span></a>
                        <a href=""><span> <i class="fab fa-git-square text-blue-500  px-2 py-2 hover:bg-blue-200 rounded-full"></i></span></a>
                        <a href=""><span><i class="far fa-chart-bar text-blue-500  px-2 py-2 hover:bg-blue-200 rounded-full"></i></span></a>
                        
                        <a href=""><span>  <i class="fad fa-frown text-blue-500  px-2 py-2 hover:bg-blue-200 rounded-full"></i>
                        </span></a>

                        <a href=""><span><i class="far fa-clock text-blue-500  px-2 py-2 hover:bg-blue-200 rounded-full "></i></span></a>
                      

                    </div>

           <button class="bg-blue-400 px-5 py-2 text-white rounded-full ">Tweet</button>
         </div>


     
      
      

     
      
    </div>
 <!-- article section -->
       <div class=" transition   ease-in-out duration-150 hover:bg-gray-100">
          <div class="py-3 grid   md:grid-cols-12 border-b   border-gray-400   ">
              
             <div class="col-span-6 md:col-span-2  w-full  relative ">
                 <img src="./assets/css/img/rust.png"  class="block  " alt="profile photo">
                 <div   v-if="opened" class=" absolute z-10 bg-white border border-gray-300 shadow-md   control-follow space-y-3">
                  <div  class="flex justify-between items-center">
                    <div>
                     <img src="./assets/css/img/rust.png" class="w-12 h-12 object-cover" alt="">
                    </div>
                    <div>

                      <div>
                        <button class="  px-3 py-2 text-blue-600 font-semibold  border border-blue-300 rounded-full hover:bg-blue-100 ">follows</button>
                      </div>
                      
                    </div>
                  </div>
                  <div>
                    <h3 class="font-semibold">Mathias</h3>
                    <h3 class="text-gray-700">@mathi</h3>
                  </div>

                  <div>
                    <h3>Occassional blogger.programmer .Reverse Engineering enthusist</h3>
                  </div>

                  <div class="flex justify-between">
                    <h3><span class="font-semibold">123</span> <span class="text-gray-700">followers</span></h3>
                    <h3 ><span class="font-semibold">12</span>   <span class="text-gray-700">followers</span></h3>
                  </div>

                  <div>
                    <p class="text-gray-700 text-sm">not followed by anyone you are following</p>
                  </div>

                 </div>

             </div>








          <div class=" col-span-10 flex flex-col ">

             <div class="flex  space-x-1">
             
            <div @click="opened=!opened" class="cursor-pointer">
               <h3  class="font-semibold hover:underline transition ease-in-out duration-150  "  >Rust Trending</h3>

            </div>
           
    
             <h3 class="text-gray-600">@RustTrending</h3>
             <h3 class="text-gray-600">. 24ms</h3>
           </div>

           <div class="">
             <p class="font-medium tracking-normal leading-tight font-serif  text-gray-800">srust unofficial/awesome-rust:A curated list of 
               Rust code and resources
             </p>


            <div class="border border-gray-400 rounded-lg h-3/4 pb-4">

              <img class="block" src="./assets/css/img/rust.png" alt="">

              

              
            </div>

            <div class="flex justify-evenly my-2">
              <div>
               <a href="" class="px-2 py-2 text-gray-700  rounded-full hover:text-blue-500 hover:bg-blue-200 transition ease-in-out duration-100"><i class="far fa-comment-alt "></i></a>
              </div>
              <div>
              <a href="" class="px-2 py-2 rounded-full text-gray-700 hover:bg-green-200 hover:text-green-500
              
              transition ease-in-out duration-100"><i class="fas fa-retweet "></i></a>
              </div>

              <div>
                <a href="" class="px-2 py-2 rounded-full text-gray-700 hover:bg-pink-200 hover:text-pink-600
              
              transition ease-in-out duration-100"><i class="far fa-heart "></i></a>
              </div>

              <div>
               <a href="" class="px-2 py-2 rounded-full text-gray-700 hover:bg-blue-200 hover:text-blue-500
              
              transition ease-in-out duration-100"><i class="fas fa-upload "></i></a>
              </div>
            </div>

           </div>
          </div>
         </div>

       </div>

       <!-- ends here -->
                <div class="py-3 grid   md:grid-cols-12 border-b border-gray-400">
             
             <div class="col-span-6 md:col-span-2  w-full  ">
                 <img src="./assets/css/img/rust.png"  class="block  " alt="profile photo">

             </div>








          <div class=" col-span-10 flex flex-col ">

             <div class="flex  space-x-1">
             <h3  class="font-semibold">Rust Trending</h3>
             <h3 class="text-gray-600">@RustTrending</h3>
             <h3 class="text-gray-600">. 24m</h3>
           </div>

           <div class="">
             <p class="font-medium tracking-normal">rust unofficial/awesome-rust:A curated list of 
               Rust code and resources
             </p>


            <div class="border border-gray-600 rounded-lg h-3/4 pb-4">

              <img class="block" src="./assets/css/img/rust.png" alt="">

              

              
            </div>

            <div class="flex justify-evenly my-2">
              <div>
               <a href=""><i class="fas fa-upload"></i></a>
              </div>
              <div>
              <a href=""><i class="fas fa-upload"></i></a>
              </div>

              <div>
                <a href=""><i class="far fa-heart"></i></a>
              </div>

              <div>
               <a href=""><i class="far fa-heart"></i></a>
              </div>
            </div>

           </div>
          </div>
         </div>
                <div class="py-3 grid   md:grid-cols-12 border-b border-gray-400">
             
             <div class="col-span-6 md:col-span-2  w-full  ">
                 <img src="./assets/css/img/rust.png"  class="block  " alt="profile photo">

             </div>








          <div class=" col-span-10 flex flex-col ">

             <div class="flex  space-x-1">
             <h3  class="font-semibold">Rust Trending</h3>
             <h3 class="text-gray-600">@RustTrending</h3>
             <h3 class="text-gray-600">. 24m</h3>
           </div>

           <div class="">
             <p class="font-medium tracking-normal">rust unofficial/awesome-rust:A curated list of 
               Rust code and resources
             </p>


            <div class="border border-gray-600 rounded-lg h-3/4 pb-4">

              <img class="block" src="./assets/css/img/rust.png" alt="">

              

              
            </div>

            <div class="flex justify-evenly my-2">
              <div>
               <a href=""><i class="fas fa-upload"></i></a>
              </div>
              <div>
              <a href=""><i class="fas fa-upload"></i></a>
              </div>

              <div>
                <a href=""><i class="far fa-heart"></i></a>
              </div>

              <div>
               <a href=""><i class="far fa-heart"></i></a>
              </div>
            </div>

           </div>
          </div>
         </div>
  
  </div>
<!-- section 3 -->
  <div class=" col-span-4 py-2 md:px-8 ">
    <div class="pb-4 relative" >
      <i class="fas fa-search absolute control-search text-blue-500 "></i>
      <input v-model="selectedSearch"  type="text "  @focus="displayed=true" @blur="displayed=false"   placeholder="Search Twitter" class="placeholder-gray-900 border border-gray-100  bg-gray-300      py-1 px-2 md:px-20 md:py-2 rounded-full outline-none  focus:bg-white \ focus:border-blue-400 focus:placeholder-black" >
  
      <div  v-if="displayed"  class="absolute bg-white  w-full control-item border border-gray-300 shadow-xl   z-20 " 
     
      >
           <div class=" py-3 px-4 flex justify-between border-b border-gray-300">
       <h3 class="font-semibold  text-xl">Recent</h3>

       <button class="text-blue-600 text-sm font-bold px-2  ">Clear all</button>
       
     </div>
     <div class=" py-2 px-4 flex justify-between border-b border-gray-300 hover:bg-gray-400 transition ease-in-out duration-150">
       <div class="flex space-x-1">
         <div>
           <img src="./assets/css/img/woman-1.jpg" class="w-12 h-12 rounded-full object-cover" alt="">
         </div>
         <div>
          <h3 class="font-semibold"> Yaah</h3>
         <h3 class="text-gray-600">  @yaahc_</h3>
         </div>
       </div>
       <div class="self-center">
       <div class="px-4">
          <i class="fas fa-times text-blue-500"></i>
       </div>
       </div>
       
     </div>

        <div class=" py-2 px-4 flex justify-between border-b border-gray-300 hover:bg-gray-400 transition ease-in-out duration-150">
       <div class="flex space-x-1">
         <div>
           <img src="./assets/css/img/rust.png" class="w-12 h-12 rounded-full object-cover" alt="test">
         </div>
         <div>
          <h3 class="font-semibold">Read Rust</h3>
         <h3 class="text-gray-600">  @read_rust</h3>
         </div>
       </div>
       <div class="self-center">
      <div class=" px-4">
         <i class="fas fa-times text-blue-500"></i>
      </div>
       </div>
       
     </div>
      <div class=" py-3 px-4 flex justify-between border-b border-gray-300">
       <h3 class="font-normal text-blue-500"><a href="">show more</a></h3>
       
     </div>
 

       
      </div>
    </div>


    <div class="bg-gray-100 rounded-lg  " >
     <div class=" py-3 px-4 flex justify-between border-b border-gray-300">
       <h3 class="font-semibold text-lg">Trends for you</h3>
       <div>
         <i class="fas fa-cog fa-lg text-blue-600"></i>
       </div>
     </div>
     <!-- starts here -->
    
      <div v-for="tweet in tweets" :key="tweet.id">
        <trend :tweet="tweet"/>

     </div>

     <!-- ends here -->

    
    
     <!-- finishes here -->
    
     <div class=" py-3 px-4 flex justify-between border-b border-gray-300">
       <h3 class="text-blue-500">show more</h3>
     </div>
    </div>
  <!-- part section -->
    <div class="bg-gray-100 mt-3">
     <div class=" py-3 px-4 flex justify-between border-b border-gray-300">
       <h3 class="font-semibold  text-xl">Who to  follow</h3>
       
     </div>
    
       
     <!-- starts -->
     <div v-for="data in items" :key="data.id">
         

         <recommend :item="data"/>

     </div>
     <!-- end -->
      <div class=" py-3 px-4 flex justify-between border-b border-gray-300">
       <h3 class="font-normal text-blue-500"><a href="">show more</a></h3>
       
     </div>
 



    </div>

    <!-- part end -->

    <div class="py-4">
      <div class="flex  space-x-3 text-sm  text-gray-600 transition ease-in-out duration-1000">

        <a href="" class="border-b border-white hover:border-gray-600  transition ease-in-out duration-150">Terms</a>
        <a href=""  class="border-b border-white hover:border-gray-600
          transition ease-in-out duration-150">Privacy policy</a>
        <a href=""  class="border-b border-white hover:border-gray-600
          transition ease-in-out duration-150">Cookies</a>
        <a href=""  class="border-b border-white hover:border-gray-600
          transition ease-in-out duration-150">Ads info</a>
        <a href=""  class="border-b border-white hover:border-gray-600
          transition ease-in-out duration-150">More <i class="fas fa-angle-down"></i></a>
      

      </div>
      <div class="text-sm text-gray-600 py-1">
      &copy; 2020 Twitter,Inc.
      </div>
    </div>
    <div>

    </div>

    

  
  </div>

  

</div>
</div>




</template>


<script>
import recommend from "./components/recommend.vue";

import trend from "./components/trend.vue";

export default {

  components:{
    recommend,
    trend

  },

 

  data(){
    


    return {
      displayed:false,

      opened:false,

      selectedSearch:"",
      tweets:[
        {
          id:1,
          country:"Kenya",
          name:"KameneAndJalas",
          tweet_numbers:3079
        },
          {
          id:2,
          country:"Kenya",
          name:"SportPesa",
          tweet_numbers:1649
        },
          {
          id:3,
          country:"Kenya",
          name:"Ruto",
          tweet_numbers:3102
        }

      ],
      menu:[
         {
           id:1,
           icon:"fa home",
           name:"name is"
         }

      ],
      items:[
        {
          id:1,
          accountName:"Jenna",
          handle:"Jen",
          imageUrl:"woman-1.jpg"
        },
        {
          id:2,
          accountName:"Sands",
          handle:"Sans",
          imageUrl:"rust.png"

        },
        {
          id:3,
          accountName:"Rust",
          handle:"rustnomicon",
          imageUrl:"woman-1.jpg"
        },
        
      ]
    }
  
  },

watch:{

  selectedSearch:(val)=>{
    console.log(val);
  },

  opened:(val)=>{
    console.log("Value has changed");
  }

},

  methods:{

    handleHover:()=>{
      console.log("hello");
    },

    handleClick:()=>{
      console.log("hello world");
    }
  },

  computed:{
  

  

  }

}
</script>


<style>

.control-search{
  
  top:14px;
  /* text-align: center; */
  left:20px;
}

.control-item{
  right:4px;
  /* margin-top:1px; */
  @apply rounded-lg;

}

.control-follow{
  background: red;
  width:22rem;
  left:-5rem;
  @apply px-5 ;
  @apply py-3;
  @apply rounded-lg; 
}
</style>
