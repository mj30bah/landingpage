<template>
  <div class=" min-h-80 h-auto px-4">
          <div class=" container mx-auto">
             <div class="w-6/12  mx-auto  text-center  py-8">
              <p class="text-4xl font-semibold text-gray-700">our customer brands</p>
             </div>
             <div class="grid grid-cols-2 sm:grid-cols-4  md:grid-cols-5  w-8/12 mx-auto  gap-1   py-8">
      
             <div v-for="logo in 10" :key="logo" class="px-1 py-2 flex justify-center items-center h-16">
             <img src="../assets/image/google.svg" alt="">
             </div>
          </div>
        </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>