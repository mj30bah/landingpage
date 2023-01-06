<template>
  <div class="cpe px-1 py-4  md:px-5">
     <div class="container mx-auto">
       
               <div class=" text-gray-800 w-full  md:h-24 px-10 py-10 block md:flex justify-between items-center">
          <div class="text-4xl  font-semibold text-center font-sans">Getting Started</div>
          <div class="text-center"> <button class="w-56 h-12 mx-auto mt-3 md:mt-0  flex justify-center items-center text-xl font-bold rounded hover:bg-gray-300">Read More 
              <svg class="ml-2 mt-1" stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 448 512" aria-hidden="true" focusable="false" height="1em" width="0.7em" xmlns="http://www.w3.org/2000/svg"><path d="M190.5 66.9l22.2-22.2c9.4-9.4 24.6-9.4 33.9 0L441 239c9.4 9.4 9.4 24.6 0 33.9L246.6 467.3c-9.4 9.4-24.6 9.4-33.9 0l-22.2-22.2c-9.5-9.5-9.3-25 .4-34.3L311.4 296H24c-13.3 0-24-10.7-24-24v-32c0-13.3 10.7-24 24-24h287.4L190.9 101.2c-9.8-9.3-10-24.8-.4-34.3z"></path></svg>
              </button>
          </div>
      </div>
      <div class=" w-full h-auto  lg:h-screen grid grid-cols-1 px-2 md:grid-cols-3  ">
         <div class="md:col-span-1 h-auto mb-4 bg-gray-50 py-3 md:bg-transparent	 rounded-lg  flex md:block px-2 md:pr-10 divide-gray-200 divide-x md:divide-x-0 md:divide-y">

             <div  class=" w-1/3 md:w-full px-1 py-1  md:py-2 h-28 md:h-28  cursor-pointer  " style="hover:background-color:#94ecc4;">
                 <div  class="block md:flex w-full h-full  items-center rounded-lg px-4 " id="tab-one" tabindex="1" @click="changecontent('one')">
                    <div class="flex justify-center">
                        <div class="w-12 h-12 flex justify-center items-center rounded-full mt-2 md:mt-0 " style="background-color:#94ecc4;">
                            <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 496 512" class="css-1rm4t68 text-green-600" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3.3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5.3-6.2 2.3zm44.2-1.7c-2.9.7-4.9 2.6-4.6 4.9.3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8zM97.2 352.9c-1.3 1-1 3.3.7 5.2 1.6 1.6 3.9 2.3 5.2 1 1.3-1 1-3.3-.7-5.2-1.6-1.6-3.9-2.3-5.2-1zm-10.8-8.1c-.7 1.3.3 2.9 2.3 3.9 1.6 1 3.6.7 4.3-.7.7-1.3-.3-2.9-2.3-3.9-2-.6-3.6-.3-4.3.7zm32.4 35.6c-1.6 1.3-1 4.3 1.3 6.2 2.3 2.3 5.2 2.6 6.5 1 1.3-1.3.7-4.3-1.3-6.2-2.2-2.3-5.2-2.6-6.5-1zm-11.4-14.7c-1.6 1-1.6 3.6 0 5.9 1.6 2.3 4.3 3.3 5.6 2.3 1.6-1.3 1.6-3.9 0-6.2-1.4-2.3-4-3.3-5.6-2z"></path></svg>
                        </div>
                    </div>
                    <div class=" items-center px-1 md:px-4  py-4 ">
                        <p class="text-center md:text-left text-sm md:text-xl font-extrabold text-gray-700 mx-atuo">Community</p>
                        <p class="text-base text-center md:text-left text-gray-600 hidemobile">Open Source</p>
                    </div>
                 </div>
             </div>

             <div  class="w-1/3 md:w-full  px-1 py-1  md:py-2 h-28 md:h-28  cursor-pointer">
                
                <div class="block md:flex items-center w-full h-full rounded-lg px-4" id="tab-two" tabindex="2" @click="changecontent('two')">
                     <div class="flex justify-center">
                     <div class="w-12 h-12 flex justify-center items-center  rounded-full mt-2 md:mt-0" style="background-color:#d6befb;">
                         <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 448 512" class="css-w852yk text-purple-600" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M224 256c70.7 0 128-57.3 128-128S294.7 0 224 0 96 57.3 96 128s57.3 128 128 128zm95.8 32.6L272 480l-32-136 32-56h-96l32 56-32 136-47.8-191.4C56.9 292 0 350.3 0 422.4V464c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48v-41.6c0-72.1-56.9-130.4-128.2-133.8z"></path></svg>
                     </div>
                 </div>
                 <div class=" items-center px-1 md:px-4 py-4 ">
                     <p class="text-center md:text-left text-sm md:text-xl font-extrabold text-gray-700">Pro</p>
                     <p class="text-base text-center md:text-left text-gray-600 hidemobile">Go next level, unlock all features</p>
                 </div>
             </div>
                </div>


             <div  class="w-1/3   md:w-full px-1 py-1  md:py-2 h-28 md:h-28  cursor-pointer">
                 
                 <div class="block md:flex items-center w-full h-full rounded-lg px-4" tabindex="3" id="tab-three" @click="changecontent('three')" >
                    <div class="flex justify-center">
                     <div class="w-12 h-12 flex justify-center items-center  rounded-full mt-2 md:mt-0 " style="background-color:#90cdf4;">
                         <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 448 512" class="css-3zzjdv text-blue-600" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M64 224h13.5c24.7 56.5 80.9 96 146.5 96s121.8-39.5 146.5-96H384c8.8 0 16-7.2 16-16v-96c0-8.8-7.2-16-16-16h-13.5C345.8 39.5 289.6 0 224 0S102.2 39.5 77.5 96H64c-8.8 0-16 7.2-16 16v96c0 8.8 7.2 16 16 16zm40-88c0-22.1 21.5-40 48-40h144c26.5 0 48 17.9 48 40v24c0 53-43 96-96 96h-48c-53 0-96-43-96-96v-24zm72 72l12-36 36-12-36-12-12-36-12 36-36 12 36 12 12 36zm151.6 113.4C297.7 340.7 262.2 352 224 352s-73.7-11.3-103.6-30.6C52.9 328.5 0 385 0 454.4v9.6c0 26.5 21.5 48 48 48h80v-64c0-17.7 14.3-32 32-32h128c17.7 0 32 14.3 32 32v64h80c26.5 0 48-21.5 48-48v-9.6c0-69.4-52.9-125.9-120.4-133zM272 448c-8.8 0-16 7.2-16 16s7.2 16 16 16 16-7.2 16-16-7.2-16-16-16zm-96 0c-8.8 0-16 7.2-16 16v48h32v-48c0-8.8-7.2-16-16-16z"></path></svg>
                     </div>
                 </div>
                 <div class=" items-center px-1 md:px-4  py-4 ">
                     <p class="text-center md:text-left text-sm md:text-xl font-extrabold text-gray-700 ">Extendend</p>
                     <p class="text-base text-center md:text-left text-gray-600 hidemobile">Use for end products that are "sold"</p>
                 </div>
                 </div>

             </div>


         </div>


         <!-- content -->
         <div class="md:col-span-2 0 px-20 py-20 bg-white rounded-2xl">
           <div v-if="content=='one'"> 1111111 Lorem ipsum dolor sit amet consectetur adipisicing elit. 
               Iure deserunt fugit quia sapiente itaque a omnis, laudantium dolorum dolore in id consectetur dicta quae sed nam, optio facilis voluptas sint.
               </div>  
           <div v-if="content=='two'">22222 Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero magnam, sed totam veritatis aliquam consectetur expedita possimus 
               accusamus modi beatae perferendis error quaerat, ipsum, quod voluptatem! Consequuntur maiores ut ad.</div>  
           <div v-if="content=='three'">333333 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ab debitis minima beatae possimus veritatis dolores ipsa. Voluptates adipisci
                perferendis, quas itaque laboriosam ut, nulla sequi consequuntur nam, eum rerum voluptate.</div>   
         </div>


      </div>

     </div>
  </div>
</template>

<script>
export default {
data(){
 return{
     content:"one",
 }
},
mounted(){
this.changecontent('one');
  const elem = document.getElementById('tab-one');
 elem.style.backgroundColor="#dcfbe7";
},
methods:{
changecontent(contentnum){
    const elem = document.getElementById('tab-one');
  elem.style.backgroundColor="transparent";
 this.content=contentnum;
},
}

}
</script>

<style scoped>
@media only screen and (max-width:768px) {
    .hidemobile{
        display: none;
    }
    
}
.cpe{
     background-color: #F7FAFC;
    background-image: linear-gradient(90deg, #EDF2F7 0%, #ffffff 100%);
}

#tab-one:focus{
    background-color: #dcfbe7 !important;
    border: 3px solid #c9c7c7;
    border-radius: 15px;
       outline: none !important;
}
#tab-two:focus{
    background-color: #f3d4ff !important;
    border: 3px solid #c9c7c7;
    border-radius: 15px;
       outline: none !important;
}
#tab-three:focus{
    background-color: #bee3f8 !important;
    border: 3px solid #c9c7c7;
    border-radius: 15px;
       outline: none !important;
}

</style>