<template>
  <div class=" py-3 px-4  border-b border-gray-300 cursor-pointer hover:bg-gray-300
  transition ease-in-out duration-200">
       <div class="flex justify-between"> 
         <p class=" text-gray-600 text-sm ">Trends in {{tweet.country}}</p>
         <div> 
          <i class="fas fa-angle-down text-gray-500"></i>
         </div>
       </div>
       
       <div class="font-semibold ">
         <h3 class="tracking-wide">#{{tweet.name}}</h3>
       </div>
       <div class="text-sm  text-gray-600 pt-1">
         {{tweet.tweet_numbers}} Tweets
       </div>
     </div>

</template>

<script>
export default {

    props:["tweet"]

}
</script>

<style>

</style>