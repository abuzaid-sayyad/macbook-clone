<template>
  <div class="w-full dark h-screen overflow-hidden bg-center bg-cover" style="background-image: url(https://res.allmacwallpaper.com/get/Retina-MacBook-Air-13-inch-wallpapers/waves-light-8k-2560x1600/23837-11.jpg)">
    <div class="nightwind-prevent w-full h-6 px-4 fixed top-0 flex flex-row justify-between items-center text-sm text-white bg-gray-500 bg-opacity-10 blur shadow transition">
      <div class="flex flex-row items-center space-x-4">
        <div class="inline-flex cursor-default flex-row space-x-1 hover:bg-white hover:bg-opacity-30 rounded p-1">
          <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 1024 1024" height="18" width="18" xmlns="http://www.w3.org/2000/svg"><path d="M747.4 535.7c-.4-68.2 30.5-119.6 92.9-157.5-34.9-50-87.7-77.5-157.3-82.8-65.9-5.2-138 38.4-164.4 38.4-27.9 0-91.7-36.6-141.9-36.6C273.1 298.8 163 379.8 163 544.6c0 48.7 8.9 99 26.7 150.8 23.8 68.2 109.6 235.3 199.1 232.6 46.8-1.1 79.9-33.2 140.8-33.2 59.1 0 89.7 33.2 141.9 33.2 90.3-1.3 167.9-153.2 190.5-221.6-121.1-57.1-114.6-167.2-114.6-170.7zm-105.1-305c50.7-60.2 46.1-115 44.6-134.7-44.8 2.6-96.6 30.5-126.1 64.8-32.5 36.8-51.6 82.3-47.5 133.6 48.4 3.7 92.6-21.2 129-63.7z"></path></svg>
        </div>
        <span class="cursor-default font-semibold">Beer</span>
      </div>
      <div class="flex flex-row justify-end items-center space-x-2">
        <div class="hidden sm:inline-flex cursor-default flex-row space-x-1 hover:bg-white hover:bg-opacity-30 rounded p-1">
          <span class="text-xs mt-0.5 mr-1">100%</span>
          <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 16 16" height="20" width="20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M12 5H2a1 1 0 00-1 1v4a1 1 0 001 1h10a1 1 0 001-1V6a1 1 0 00-1-1zM2 4a2 2 0 00-2 2v4a2 2 0 002 2h10a2 2 0 002-2V6a2 2 0 00-2-2H2z" clip-rule="evenodd"></path><path d="M2 6h10v4H2V6zm12.5 3.5a1.5 1.5 0 000-3v3z"></path></svg>
        </div>
        <div class="hidden sm:inline-flex cursor-default flex-row space-x-1 hover:bg-white hover:bg-opacity-30 rounded p-1">
          <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 640 512" height="17" width="17" xmlns="http://www.w3.org/2000/svg"><path d="M634.91 154.88C457.74-8.99 182.19-8.93 5.09 154.88c-6.66 6.16-6.79 16.59-.35 22.98l34.24 33.97c6.14 6.1 16.02 6.23 22.4.38 145.92-133.68 371.3-133.71 517.25 0 6.38 5.85 16.26 5.71 22.4-.38l34.24-33.97c6.43-6.39 6.3-16.82-.36-22.98zM320 352c-35.35 0-64 28.65-64 64s28.65 64 64 64 64-28.65 64-64-28.65-64-64-64zm202.67-83.59c-115.26-101.93-290.21-101.82-405.34 0-6.9 6.1-7.12 16.69-.57 23.15l34.44 33.99c6 5.92 15.66 6.32 22.05.8 83.95-72.57 209.74-72.41 293.49 0 6.39 5.52 16.05 5.13 22.05-.8l34.44-33.99c6.56-6.46 6.33-17.06-.56-23.15z"></path></svg>
        </div>
        <div class="inline-flex cursor-default flex-row space-x-1 hover:bg-white hover:bg-opacity-30 rounded p-1"><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 24 24" height="17" width="17" xmlns="http://www.w3.org/2000/svg"><path d="M10,18c1.846,0,3.543-0.635,4.897-1.688l4.396,4.396l1.414-1.414l-4.396-4.396C17.365,13.543,18,11.846,18,10 c0-4.411-3.589-8-8-8s-8,3.589-8,8S5.589,18,10,18z M10,4c3.309,0,6,2.691,6,6s-2.691,6-6,6s-6-2.691-6-6S6.691,4,10,4z"></path></svg></div>
        <div  @click="openBox = !openBox" class="inline-flex h-6 cursor-default flex-row space-x-1 hover:bg-white hover:bg-opacity-30 rounded p-1"><svg viewBox="0 0 29 29" width="16" height="16" xmlns="http://www.w3.org/2000/svg" fill="currentColor"><path d="M7.5,13h14a5.5,5.5,0,0,0,0-11H7.5a5.5,5.5,0,0,0,0,11Zm0-9h14a3.5,3.5,0,0,1,0,7H7.5a3.5,3.5,0,0,1,0-7Zm0,6A2.5,2.5,0,1,0,5,7.5,2.5,2.5,0,0,0,7.5,10Zm14,6H7.5a5.5,5.5,0,0,0,0,11h14a5.5,5.5,0,0,0,0-11Zm1.43439,8a2.5,2.5,0,1,1,2.5-2.5A2.5,2.5,0,0,1,22.93439,24Z"></path></svg></div>
        <span>Wed May 26</span>
        <span>Wed May 26</span>
      </div>
    </div>
    <div class="dock w-full sm:w-max fixed left-0 right-0 mx-auto bottom-0 overflow-x-scroll sm:overflow-x-visible" style="z-index: 99999;">
      <ul class="mx-auto w-max p-2 space-x-2 flex flex-row justify-center bg-white bg-opacity-20 blur rounded-none sm:rounded-t-lg shadow-2xl">
        <li v-for="(item, index) in bottomBar" id="dock-launchpad" class="flex flex-col items-center justify-end mb-1 transition duration-150 ease-in origin-bottom">
          <a :href="item.path">
            <p class="tooltip text-black text-sm absolute -mt-9 -top-full px-3 py-1 bg-gray-300 bg-opacity-80 blur-sm rounded-md ml-4">{{item.name}}</p>
            <img class="w-12" :src="require(`~/assets/images/${item.image}`)" :alt="item.alt" :title="item.title" draggable="false" style="will-change: width; width: 3.125rem;">
            <div class="h-1 w-1 m-0 rounded-full bg-gray-800 invisible"></div>
          </a>
        </li>
      </ul>
    </div>

    <div v-if="openBox" class="fixed w-96 max-w-full top-8 right-0 sm:right-2 z-50 p-2 grid grid-cols-4 grid-rows-5 gap-2 dark:bg-gray-800 bg-white bg-opacity-40 blur-28 rounded-2xl text-black shadow-2xl">
      <div class="row-span-2 col-span-2 bg-gray-200 bg-opacity-70 rounded-xl p-2 flex flex-col justify-around">
        <div class="flex flex-row items-center space-x-2 pr-6">
          <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 640 512" class="bg-blue-500 text-white rounded-full p-2" height="36" width="36" xmlns="http://www.w3.org/2000/svg"><path d="M634.91 154.88C457.74-8.99 182.19-8.93 5.09 154.88c-6.66 6.16-6.79 16.59-.35 22.98l34.24 33.97c6.14 6.1 16.02 6.23 22.4.38 145.92-133.68 371.3-133.71 517.25 0 6.38 5.85 16.26 5.71 22.4-.38l34.24-33.97c6.43-6.39 6.3-16.82-.36-22.98zM320 352c-35.35 0-64 28.65-64 64s28.65 64 64 64 64-28.65 64-64-28.65-64-64-64zm202.67-83.59c-115.26-101.93-290.21-101.82-405.34 0-6.9 6.1-7.12 16.69-.57 23.15l34.44 33.99c6 5.92 15.66 6.32 22.05.8 83.95-72.57 209.74-72.41 293.49 0 6.39 5.52 16.05 5.13 22.05-.8l34.44-33.99c6.56-6.46 6.33-17.06-.56-23.15z"></path></svg>
          <div class="flex flex-col">
            <span class="font-medium">Wifi</span>
            <span class="font-thin text-xs">Home</span>
          </div>
        </div>
        <div class="flex flex-row items-center space-x-2 pr-6">
          <svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="bg-blue-500 text-white rounded-full p-2" height="36" width="36" xmlns="http://www.w3.org/2000/svg"><polyline points="6.5 6.5 17.5 17.5 12 23 12 1 17.5 6.5 6.5 17.5"></polyline></svg>
          <div class="flex flex-col">
            <span class="font-medium">Bluetooth</span>
            <span class="font-thin text-xs">On</span>
          </div>
        </div>
        <div class="flex flex-row items-center space-x-2 pr-6">
          <svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="bg-blue-500 text-white rounded-full p-2" height="36" width="36" xmlns="http://www.w3.org/2000/svg"><path d="M4 11a9 9 0 0 1 9 9"></path><path d="M4 4a16 16 0 0 1 16 16"></path><circle cx="5" cy="19" r="1"></circle></svg>
          <div class="flex flex-col">
            <span class="font-medium">AirDrop</span>
            <span class="font-thin text-xs">Contacts Only</span>
          </div>
        </div>
      </div>
      <div class="col-span-2 bg-gray-200 hover:bg-gray-300 cursor-pointer bg-opacity-60 blur rounded-xl p-2 flex flex-row items-center space-x-2">
        <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 512 512" class="text-gray-700 bg-gray-300 bg-opacity-50 rounded-full p-2" height="34" width="34" xmlns="http://www.w3.org/2000/svg"><path d="M256 118a22 22 0 01-22-22V48a22 22 0 0144 0v48a22 22 0 01-22 22zm0 368a22 22 0 01-22-22v-48a22 22 0 0144 0v48a22 22 0 01-22 22zm113.14-321.14a22 22 0 01-15.56-37.55l33.94-33.94a22 22 0 0131.11 31.11l-33.94 33.94a21.93 21.93 0 01-15.55 6.44zM108.92 425.08a22 22 0 01-15.55-37.56l33.94-33.94a22 22 0 1131.11 31.11l-33.94 33.94a21.94 21.94 0 01-15.56 6.45zM464 278h-48a22 22 0 010-44h48a22 22 0 010 44zm-368 0H48a22 22 0 010-44h48a22 22 0 010 44zm307.08 147.08a21.94 21.94 0 01-15.56-6.45l-33.94-33.94a22 22 0 0131.11-31.11l33.94 33.94a22 22 0 01-15.55 37.56zM142.86 164.86a21.89 21.89 0 01-15.55-6.44l-33.94-33.94a22 22 0 0131.11-31.11l33.94 33.94a22 22 0 01-15.56 37.55zM256 358a102 102 0 11102-102 102.12 102.12 0 01-102 102z"></path></svg>
        <div class="flex flex-col">
          <span class="font-medium ml-1">Light Mode</span>
        </div>
      </div>
      <div class="bg-gray-200 bg-opacity-60 blur rounded-xl p-2 flex flex-col justify-center items-center text-center">
        <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 16 16" height="20" width="20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M5.041 10.5h5.918a3 3 0 00-5.918 0zM4 11a4 4 0 118 0 .5.5 0 01-.5.5h-7A.5.5 0 014 11zm4-8a.5.5 0 01.5.5v2a.5.5 0 01-1 0v-2A.5.5 0 018 3zm8 8a.5.5 0 01-.5.5h-2a.5.5 0 010-1h2a.5.5 0 01.5.5zM3 11a.5.5 0 01-.5.5h-2a.5.5 0 010-1h2a.5.5 0 01.5.5zm10.657-5.657a.5.5 0 010 .707l-1.414 1.414a.5.5 0 11-.707-.707l1.414-1.414a.5.5 0 01.707 0zM4.464 7.464a.5.5 0 01-.707 0L2.343 6.05a.5.5 0 01.707-.707l1.414 1.414a.5.5 0 010 .707z" clip-rule="evenodd"></path></svg>
        <span class="text-xs">Keyboard Brightness</span>
      </div>
      <div  @click="fullScreenMode = !fullScreenMode" class="bg-gray-200 hover:bg-gray-200 cursor-pointer bg-opacity-60 blur rounded-xl p-2 flex flex-col justify-center items-center text-center">
        <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 16 16" height="16" width="16" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M1.5 1a.5.5 0 00-.5.5v4a.5.5 0 01-1 0v-4A1.5 1.5 0 011.5 0h4a.5.5 0 010 1h-4zM10 .5a.5.5 0 01.5-.5h4A1.5 1.5 0 0116 1.5v4a.5.5 0 01-1 0v-4a.5.5 0 00-.5-.5h-4a.5.5 0 01-.5-.5zM.5 10a.5.5 0 01.5.5v4a.5.5 0 00.5.5h4a.5.5 0 010 1h-4A1.5 1.5 0 010 14.5v-4a.5.5 0 01.5-.5zm15 0a.5.5 0 01.5.5v4a1.5 1.5 0 01-1.5 1.5h-4a.5.5 0 010-1h4a.5.5 0 00.5-.5v-4a.5.5 0 01.5-.5z" clip-rule="evenodd"></path></svg>
        <span class="text-xs mt-1.5">Enter Fullscreen</span>
      </div>
      <div class="col-span-4 bg-gray-200 bg-opacity-60 blur rounded-xl p-2 space-y-2 flex flex-col justify-around">
        <span class="font-medium">Display</span>
        <div class="slider flex flex-row w-full">
          <div class="h-8 p-2 bg-gray-100 rounded-l-full border-t border-l border-b border-gray-400 border-opacity-60">
            <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 512 512" class="text-gray-500" height="16" width="16" xmlns="http://www.w3.org/2000/svg"><path d="M256 118a22 22 0 01-22-22V48a22 22 0 0144 0v48a22 22 0 01-22 22zm0 368a22 22 0 01-22-22v-48a22 22 0 0144 0v48a22 22 0 01-22 22zm113.14-321.14a22 22 0 01-15.56-37.55l33.94-33.94a22 22 0 0131.11 31.11l-33.94 33.94a21.93 21.93 0 01-15.55 6.44zM108.92 425.08a22 22 0 01-15.55-37.56l33.94-33.94a22 22 0 1131.11 31.11l-33.94 33.94a21.94 21.94 0 01-15.56 6.45zM464 278h-48a22 22 0 010-44h48a22 22 0 010 44zm-368 0H48a22 22 0 010-44h48a22 22 0 010 44zm307.08 147.08a21.94 21.94 0 01-15.56-6.45l-33.94-33.94a22 22 0 0131.11-31.11l33.94 33.94a22 22 0 01-15.55 37.56zM142.86 164.86a21.89 21.89 0 01-15.55-6.44l-33.94-33.94a22 22 0 0131.11-31.11l33.94 33.94a22 22 0 01-15.56 37.55zM256 358a102 102 0 11102-102 102.12 102.12 0 01-102 102z"></path></svg>
          </div>
          <div class="rangeslider rangeslider-horizontal" aria-valuemin="1" aria-valuemax="100" aria-valuenow="71" aria-orientation="horizontal">
            <div class="rangeslider__fill" style="width: 219px;"></div>
            <div class="rangeslider__handle" tabindex="0" style="left: 219px;">
              <div class="rangeslider__handle-label"></div>
            </div>
            <ul class="rangeslider__labels"></ul>
          </div>
        </div>
      </div>
      <div class="col-span-4 bg-gray-200 bg-opacity-60 blur rounded-xl p-2 space-y-2 flex flex-col justify-around">
        <span class="font-medium">Sound</span>
        <div class="slider flex flex-row w-full">
          <div class="h-8 p-2 bg-gray-100 rounded-l-full border-t border-l border-b border-gray-400 border-opacity-60">
            <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 512 512" class="text-gray-500" height="16" width="16" xmlns="http://www.w3.org/2000/svg"><path d="M232 416a23.88 23.88 0 01-14.2-4.68 8.27 8.27 0 01-.66-.51L125.76 336H56a24 24 0 01-24-24V200a24 24 0 0124-24h69.75l91.37-74.81a8.27 8.27 0 01.66-.51A24 24 0 01256 120v272a24 24 0 01-24 24zm-106.18-80zm-.27-159.86zM320 336a16 16 0 01-14.29-23.19c9.49-18.87 14.3-38 14.3-56.81 0-19.38-4.66-37.94-14.25-56.73a16 16 0 0128.5-14.54C346.19 208.12 352 231.44 352 256c0 23.86-6 47.81-17.7 71.19A16 16 0 01320 336z"></path><path d="M368 384a16 16 0 01-13.86-24C373.05 327.09 384 299.51 384 256c0-44.17-10.93-71.56-29.82-103.94a16 16 0 0127.64-16.12C402.92 172.11 416 204.81 416 256c0 50.43-13.06 83.29-34.13 120a16 16 0 01-13.87 8z"></path><path d="M416 432a16 16 0 01-13.39-24.74C429.85 365.47 448 323.76 448 256c0-66.5-18.18-108.62-45.49-151.39a16 16 0 1127-17.22C459.81 134.89 480 181.74 480 256c0 64.75-14.66 113.63-50.6 168.74A16 16 0 01416 432z"></path></svg>
          </div>
          <div class="rangeslider rangeslider-horizontal" aria-valuemin="1" aria-valuemax="100" aria-valuenow="100" aria-orientation="horizontal">
            <div class="rangeslider__fill" style="width: 303px;"></div>
            <div class="rangeslider__handle" tabindex="0" style="left: 303px;">
              <div class="rangeslider__handle-label"></div>
            </div>
            <ul class="rangeslider__labels"></ul>
          </div>
        </div>
      </div>
      <div class="col-span-4 bg-gray-200 bg-opacity-60 blur rounded-xl p-2 pr-4 flex flex-row justify-between items-center space-x-4">
        <img src="//p1.music.126.net/z0IO1vEsowL9mD_5yzUjeA==/109951163936068098.jpg" alt="cover art" class="w-16 rounded-lg">
        <div class="flex flex-col flex-grow justify-start">
          <span class="font-medium">Sunflower</span>
          <span class="font-extralight">Post Malone / Swae Lee</span>
        </div>
        <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 16 16" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M11.596 8.697l-6.363 3.692c-.54.313-1.233-.066-1.233-.697V4.308c0-.63.692-1.01 1.233-.696l6.363 3.692a.802.802 0 010 1.393z"></path></svg>
      </div>
    </div>
  </div>
</template>

<script>
import AdminLayout from "../components/layout";
export default {
  name: "sample",
  components: {AdminLayout},
  data(){
    return{
      openBox:false,
      fullScreenMode: false,
      openDia: false,
      GridData:[
        {title:'Project :', desc:'Lorem ipsum dolor site amet de costa de.'},
        {title:'Company :', desc:'Lorem ipsum dolor site amet de costa de.'},
        {title:'Query ID :', desc:'123654'},
        {title:'Client Name :', desc:'Lorem ipsum dolor site amet de costa de.'},
        {title:'Client Representative :', desc:'Lorem ipsum dolor site amet de costa de.'},
        {title:'Query Time :', desc:'Lorem ipsum dolor site amet de costa de.'},
        {title:'Query Date :', desc:'Lorem ipsum dolor site amet de costa de.'},
      ],
      bottomBar:[
        {id:'launchpad', name:'Launchpad', image:'launchpad.png', alt:'Launchpad', title:'Launchpad',},
        {id:'anydesk', name:'AnyDesk', image:'anydesk.png', alt:'AnyDesk', title:'AnyDesk'},
        {id:'jira', name:'Jira', image:'jira-logo.png', alt:'Jira', title:'Jira', path:'/jira-software'},
        {id:'phpstorm', name:'PhpStorm', image:'phpstorm.png', alt:'PhpStorm', title:'PhpStorm'},
        {id:'whatsapp', name:'WhatsApp', image:'whatsApp.png', alt:'WhatsApp', title:'WhatsApp', path:'/whatsapp'},
        {id:'linkedin', name:'LinkedIn', image:'linkedin.png', alt:'LinkedIn', title:'LinkedIn', path:'/linkedin'},
        {id:'twitter', name:'Twitter', image:'twitter.png', alt:'Twitter', title:'Twitter', path:'/twitter'},
        {id:'github', name:'GitHub', image:'github.png', alt:'GitHub', title:'GitHub', path:'/github'},
      ]
    }
  },
  methods:{
    openFullscreen()  {
      
      var elem = document.documentElement;
      if (elem.requestFullscreen) {
        elem.requestFullscreen();
      } else if (elem.mozRequestFullScreen) { 
        elem.mozRequestFullScreen();
      } else if (elem.webkitRequestFullscreen) { 
        elem.webkitRequestFullscreen();
      } else if (elem.msRequestFullscreen) { 
        elem.msRequestFullscreen();
      }    
      this.openBox = false
    },
  },
  watch:{
    fullScreenMode: function(){
      if(this.fullScreenMode == true){
        this.openFullscreen();
      }
    
    }
  },
}
</script>

<style scoped>
.blur {
  backdrop-filter: blur(40px);
}
.blur-28 {
  backdrop-filter: blur(8px);
}

/* --------- dock --------- */


.dock {
}
.dock li {
  list-style-type: none;
  display: inline-block;
  position: relative;
}
.dock li img {
  -webkit-box-reflect: below 2px
  -webkit-gradient(linear, left top, left bottom, from(transparent),
    color-stop(0.7, transparent), to(rgba(255,255,255,.5)));
  -webkit-transition: all 0.3s;
  -webkit-transform-origin: 50% 100%;
}
.dock li:hover img {
  -webkit-transform: scale(2);
  margin: 0 2em;
}
.dock li:hover + li img,
.dock li.prev img {
  -webkit-transform: scale(1.5);
  margin: 0 1.5em;
}
.dock li p {
  display: none;
}
.dock li:hover p {
  display: block;
}
/* --------- slider --------- */

.slider .rangeslider {
  @apply bg-gray-300 w-full h-7 shadow-none m-0 rounded-r-full border-t border-r border-b border-transparent;
}

.slider .rangeslider .rangeslider__fill {
  @apply bg-gray-100 shadow-none rounded-none;
}

.slider .rangeslider .rangeslider__handle {
  @apply border border-gray-300 outline-none h-7 w-7;
  background-color: #fff;
  color: #fff;
  box-shadow: -3px 0px 8px 0px rgba(17, 17, 17, 0.15);
}

.slider .rangeslider .rangeslider__handle::after {
  @apply hidden;
}


</style>
