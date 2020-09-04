<template>

 <div class=" py-4 px-4 flex justify-between border-b border-gray-300 hover:bg-gray-400 transition ease-in-out duration-150">
       <div class="flex space-x-1">
         <div>
           <img :src="require(`../assets/css/img/${item.imageUrl}`)" class="w-12 h-12 rounded-full object-cover" alt="">
         </div>
         <div>
          <h3 class="font-semibold"> @{{item.accountName}}</h3>
         <h3 class="text-gray-600">  @{{item.handle}}</h3>
         </div>
       </div>
       <div class="self-center">
         <button class="px-5 py-1 border border-blue-500 text-blue-700 bg-white rounded-full font-semibold hover:bg-blue-100">follow</button>
       </div>
       
     </div>

  
</template>

<script>
export default {
     props:["item"],

     data(){

         return {
             test:"woman-1.jpg"
         }

     },

     created(){
         console.log(this.item.imageUrl);
     }

}
</script>

<style>

</style>