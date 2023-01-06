<template>
<div >

 <div class="main-hero  w-full min-h-screen font-sans" >
  <div class="background-color-layer"></div>
  <div class="background-color-layer-smooth"></div>
   <div class="container mx-auto">

<nav class=" border-gray-200 px-2 sm:px-4 py-2.5 rounded dark:bg-gray-800">
<div style="z-index: 1;" class="container flex flex-wrap justify-between items-center mx-auto">
<a href="#" class="flex items-center">
<img style="z-index: 1;" src="../assets/image/lorem.png" class="mr-3 h-9 sm:h-20" alt="Flowbite Logo">
<span style="z-index: 1;" class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white">Lorem</span>
</a>
<button data-collapse-toggle="mobile-menu" type="button" class="inline-flex items-center p-2 ml-3 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600" aria-controls="mobile-menu" aria-expanded="false">
<span class="sr-only">Open main menu</span>
<svg class="w-6 h-6" @click="opennav" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd"></path></svg>
<svg class="hidden w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
</button>
<div class="hidden w-full md:block md:w-auto" id="mobile-menu">
    
<ul class="flex flex-col mt-4 md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium">
<li >
<a style="z-index: 1;"  @click="goto('GettingStarted')" class="block cursor-pointer py-2 pr-4 pl-3 text-xl  text-white bg-blue-700 rounded md:bg-transparent md:text-blue-700 md:p-0 dark:text-white font-sans" >Getting Started</a>
</li>
<li>
<a style="z-index: 1;" @click="goto('Brands')" href="#Brands" class="block py-2 cursor-pointer pr-4 pl-3 text-xl cursor-pointer text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700 font-sans ">Brands</a>
</li>
<li>
<a style="z-index: 1;" @click="goto('TextImage')" href="#newskill" class="block py-2 cursor-pointer pr-4 pl-3 text-xl cursor-pointer text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700 font-sans">new skill</a>
</li>
<li>
<a style="z-index: 1;" @click="goto('Arsenal')"  href="#arsenal" class="block py-2 cursor-pointer  pr-4 pl-3 text-xl cursor-pointer text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700 font-sans">arsenal</a>
</li>
<li>
<a style="z-index: 1;" @click="goto('Prices')"  href="#Prices" class="block py-2 cursor-pointer pr-4 pl-3 text-xl cursor-pointer text-gray-700 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent font-sans">Prices</a>
 </li>
 <li>
<a style="z-index: 1;" @click="goto('Testi')"  href="#Testi" class="block py-2 cursor-pointer pr-4 pl-3 text-xl cursor-pointer text-gray-700 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent font-sans">Testimonial</a>
 </li>
  <li>
<a style="z-index: 1;" @click="goto('Faq')"  href="#Faq" class="block py-2 cursor-pointer pr-4 pl-3 text-xl cursor-pointer text-gray-700 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent font-sans">Faq</a>
 </li>
</ul>
</div>
</div>
</nav>
<div class="hidden md:hidden mobile-menu px-4 bg-gray-200 ">
	<ul class="">
		<li class="active"><a href="#" @click="goto('GettingStarted')" class="block text-sm px-2 py-4 text-white bg-gray-300 font-semibold">Getting Started</a></li>
		<li><a href="#Brands" @click="goto('Brands')" class="block text-sm px-2 py-4 hover:bg-gray-300 transition duration-300">Brands</a></li>
		<li><a href="#newskill" @click="goto('TextImage')" class="block text-sm px-2 py-4 hover:bg-gray-300 transition duration-300">new skill</a></li>
		<li><a href="#arsenal" @click="goto('Arsenal')"  class="block text-sm px-2 py-4 hover:bg-gray-300 transition duration-300">arsenal</a></li>
    <li><a href="#Prices" @click="goto('Prices')"  class="block text-sm px-2 py-4 hover:bg-gray-300 transition duration-300">Prices</a></li>
    <li><a href="#Testi" @click="goto('Testi')" class="block text-sm px-2 py-4 hover:bg-gray-300 transition duration-300">Testimonial</a></li>
        <li><a href="#Faq" @click="goto('Faq')"  class="block text-sm px-2 py-4 hover:bg-gray-300 transition duration-300">Faq</a></li>

	</ul>
</div> 

<div class="hero-content grid grid-cols-1 md:grid-cols-12 w-full h-full md:h-screen ">
  <div class="md:col-span-6 flex md:py-10 ">

     <div class="px-4 md:px-20 py-20 font-semibold">
       <div class="block md:flex text-center" >
      <div class="text-3xl text-gray-600  font-sans">1-on-1  </div>
      <div class="text font-semibold text-3xl h-12 font-sans" > </div>
      <div class="text-3xl text-gray-600 font-sans">Mentorshi  </div>
       </div>
       <h1 style="z-index: 1;" class="text-gray-800 py-5 font-sans text-6xl font-semibold">
        Powerful theme editor for your next:
       </h1>
       <p class="text-gray-500 font-sans text-xl">
        The Theme Editor you always wanted


        </p>
              <button class=" w-36 h-16 mt-4  bg-purple-500 rounded text-white hover:bg-purple-600 cursor-pointer text-xl font-semibold " >Get started</button>

     </div>

     

    </div>
  <div class="img md:col-span-6">
    <img src="../assets/image/hero.webp" alt="">
  </div>
</div>

</div>

  </div>

   <Cpe id="GettingStarted" />
   <Logos id="Brands" />
  <TextImage id="TextImage" />
  <Arsenal id="Arsenal" />
  <Prices id="Prices" />
  <Testimonial id="Testi" />
  <Faq id="Faq" />
  <Footer id="Footer" />

<button class="scroll-top">
  <div class="arrow up"></div>
</button>


  </div>
</template>
	
<script>
export default {

mounted(){

	var typing=new Typed(".text", {
			strings: [ "Web Designer", "Freelancer", "Web Developer"],
			typeSpeed: 100,
			backSpeed: 40,
			loop: true,
		});

    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});


const colorMax = 192;

// gets the breakpoint at which the scroll-to-top button should appear
const scrollBreakpoint = window.innerHeight * 0.9;

document.addEventListener('DOMContentLoaded', () => {
  randomizeBackgrounds();
  setupScrollListener();
  setupScrollEvent();  
});

// scrolls window to top
function setupScrollEvent() {
  const scrollButton = document.querySelector('.scroll-top');
  
  scrollButton.addEventListener('click', (e) => {
    // not the best solution until Safari/Edge support scroll behavior
    // window.scrollTo({ top: 0, behavior: 'smooth' });
    
    // Thanks to Geroge Daniel https://stackoverflow.com/questions/51229742/javascript-window-scroll-behavior-smooth-not-working-in-safari
    smoothVerticalScrolling(scrollButton.parentElement, 250, "top");
  });
}

// prepares the window for a scroll event to show the scroll button
function setupScrollListener() {  
   window.addEventListener('scroll', (e) => {
     const scrollButton = document.querySelector('.scroll-top');
     
     // const scrollOffset = document.scrollingElement.scrollTop;
     const scrollOffset = window.scrollY;
    
     if (scrollOffset >= scrollBreakpoint) {
       scrollButton.classList.add('visible');
     } else if (scrollOffset <= 0) {
       scrollButton.classList.remove('visible');
     }    
  });
}

function randomizeBackgrounds() {
  // get all the content containers
  const contentContainers = document.querySelectorAll('.asli');
  
  [].forEach.call(contentContainers, container => {
    // assign random background
    container.style.background = `rgb(${randVal(colorMax)},${randVal(colorMax)},${randVal(colorMax)})`;
  });
}

// random between 0 to max
function randVal(max) {
  return Math.floor(Math.random() * Math.floor(max));
}

// uses a timeout to scroll to top
function smoothVerticalScrolling(e, time, where) {
  // gets the element's top position relative to the viewport
  const eTop = e.getBoundingClientRect().top;
  
  // divides the top offset into 100 steps to be ellapsed
  const eAmt = eTop / 100;
  
  // starting time
  let curTime = 0;
  
  // not to exceed the desired duration
  while (curTime <= time) {
    // call a function to execute at one hundreth of the desired scroll time
    window.setTimeout(SVS_B, curTime, eAmt, where);
    // increase by one hundreth of the desired time to execute exactly 100 times
    curTime += time / 100;
  }
}

function SVS_B(eAmt, where) {
  // scroll by half the hundredth of the top offset if destination is not top (since to center only involves scrolling either in the top or bottom half of the window)
  if(where == "center" || where == "") {
    window.scrollBy(0, eAmt / 2); 
  }
  // otherwise scroll the full amount
  if (where == "top") {
    window.scrollBy(0, eAmt);
  }    
}

},
methods:{
  opennav(){
   const mobilemenu= document.querySelector('.mobile-menu');
   mobilemenu.classList.toggle('hidden');
  },
  goto(id){
    
    let ele = document.getElementById(id);   
    
       window.scrollTo({
  top:ele.offsetTop,
  left: ele.offsetLeft,
  behavior: 'smooth'
});
     
  }
}
}
</script>

<style scoped>
body {
  font-family: Tahoma, sans-serif;
}
.main-hero{
 position: relative;

}
.background-color-layer{

    z-index: -1;
    content: '';
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height:100%;
   background-image: linear-gradient(60deg,#ffffff 0%, #7f58de 30%, #4ac1a2 80%, rgb(0 0 0 / 5%) 100%);
  opacity: 0.25;

}
.background-color-layer-smooth{

    z-index: -1;
    content: '';
    position: absolute;
    left: 0px;
    top: 0px;
    width: 100%;
    height:100%;
    background-image: linear-gradient(20deg, #ffffff 60%, rgba(255, 255, 255, 0) 100%);  opacity: 0.55;

}
.container{
  opacity: 1!important;
  z-index: 1;
  margin: 0 auto;
}
.cursorpointer {
  cursor: pointer !important;
}
.img{
  z-index: 1;
  display: flex;
  justify-content: center;
  align-items: center;
}

.scroll-top {
  background: #333333;
  border: 0;
  border-radius: 50%;
  bottom: 0;
  cursor: pointer;
  height: 50px;
  margin: 15px;
  opacity: 0.75;
  position: fixed;
  right: -70px;
  transition: right 0.2s ease-in-out;
  width: 50px;
  z-index: 99;
}
.scroll-top.visible {
  right: 0;
}

.arrow {
  border: solid #fcfafa;
  border-width: 0 3px 3px 0;
  display: inline-block;
  margin-top: 5px;
  padding: 4px;
}
.arrow.up {  
  transform: rotate(-135deg);
}
</style>