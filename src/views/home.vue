<template>
 <div class="h-screen bg-white m-0 p-0">
     
     <div class=" flex justify-center align-middle w-100 bg-white top-0">
         <img class="scale-50"  src="src\assets\new_logo.png"/>
        
     </div>
     <div class="text-black font-bold font-sans">Capturing Excess ROI in Technology sector</div>
     <h1 class="text-black font-sans my-10">Holdings</h1>

     <div class="grid grid-cols-3 mx-20 my-10">
         <div @click="$router.push('/greenlines')" class="hover:bg-zinc-100 h-32 text-4xl font-bold font-sans cursor-pointer	text-gray-300 text-center py-12 hover:text-green-500 hover:shadow-2xl">Greenlines</div>
         <div class="hover:bg-zinc-100 h-32 text-4xl font-bold font-sans cursor-pointer	 text-gray-300 text-center py-12 hover:text-blue-500 hover:shadow-2xl">By Culture</div>
         <div class="hover:bg-zinc-100 h-32 text-4xl font-bold font-sans cursor-pointer	text-gray-300 text-center py-12 hover:text-purple-500 hover:shadow-2xl">Krish.Capital</div>
         <div class="hover:bg-zinc-100 h-32 text-4xl font-bold font-sans cursor-pointer	text-gray-300 text-center py-12 hover:text-teal-500 hover:shadow-2xl">Lynn health</div>
     </div>



     </div>
     

</template>

<script>
export default {

}
</script>

<style>

</style>