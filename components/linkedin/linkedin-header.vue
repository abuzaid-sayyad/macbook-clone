<template>
  <div>
    <div class="w-full bg-white border-b-solid fixed z-50 top-0 overflow-hidden hidden md:block">
      <div class="max-w-6xl mx-auto h-14 flex justify-between items-center md:px-3 ">
        <div class="flex h-full items-center ">
          <svg style="color: #0a66c2;" xmlns="http://www.w3.org/2000/svg" width="34" height="34" viewBox="0 0 34 34" class="mr-2">
            <title>LinkedIn</title>
            <g>
              <path d="M34,2.5v29A2.5,2.5,0,0,1,31.5,34H2.5A2.5,2.5,0,0,1,0,31.5V2.5A2.5,2.5,0,0,1,2.5,0h29A2.5,2.5,0,0,1,34,2.5ZM10,13H5V29h5Zm.45-5.5A2.88,2.88,0,0,0,7.59,4.6H7.5a2.9,2.9,0,0,0,0,5.8h0a2.88,2.88,0,0,0,2.95-2.81ZM29,19.28c0-4.81-3.06-6.68-6.1-6.68a5.7,5.7,0,0,0-5.06,2.58H17.7V13H13V29h5V20.49a3.32,3.32,0,0,1,3-3.58h.19c1.59,0,2.77,1,2.77,3.52V29h5Z" fill="currentColor"></path>
            </g>
          </svg>
          <div class="relative">
            <input type="search" class="bg-indigo rounded pl-12 pr-3 py-2 focus:outline-none w-72 placeholder-black text-sm" placeholder="Search">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" data-supported-dps="16x16" fill="currentColor" class="absolute top-2.5 left-4" width="16" height="16" focusable="false">
              <path d="M14.56 12.44L11.3 9.18a5.51 5.51 0 10-2.12 2.12l3.26 3.26a1.5 1.5 0 102.12-2.12zM3 6.5A3.5 3.5 0 116.5 10 3.5 3.5 0 013 6.5z"></path>
            </svg>
          </div>
        </div>
        <div class="flex items-center h-full">
          <div class="flex border-b-2 border-black h-full cursor-pointer" style="min-width: 80px;">
            <div class="my-auto w-full">
              <svg class="mx-auto" id="global-nav-icon--mercado__home--active" height="24" width="24">
                <path d="m23 9v2h-2v7c0 1.7-1.3 3-3 3h-4v-6h-4v6h-4c-1.7 0-3-1.3-3-3v-7h-2v-2l11-7z"></path>
                <path d="m20 2h-3v3.2l3 1.9z"></path>
              </svg>
              <div class="text-sm text-center">Home</div>
            </div>
          </div>
          <div class="flex cursor-pointer" style="min-width: 80px;">
            <div class="my-auto w-full">
              <svg id="global-nav-icon--mercado__my-network" height="24" width="24" class="mx-auto" fill="currentColor" style="color: #00000099">
                <path d="m12 16v6h-9v-6c0-1.7 1.3-3 3-3h3c1.7 0 3 1.3 3 3zm5.5-3c1.9 0 3.5-1.6 3.5-3.5s-1.6-3.5-3.5-3.5-3.5 1.6-3.5 3.5 1.6 3.5 3.5 3.5zm1 2h-2c-1.4 0-2.5 1.1-2.5 2.5v4.5h7v-4.5c0-1.4-1.1-2.5-2.5-2.5zm-11-13c-2.5 0-4.5 2-4.5 4.5s2 4.5 4.5 4.5 4.5-2 4.5-4.5-2-4.5-4.5-4.5z"></path>
              </svg>
              <div class="text-sm text-center font-light text-gray-800">My Network</div>
            </div>
          </div>
          <div class="flex flex-col cursor-pointer" style="min-width: 80px;">
            <svg id="global-nav-icon--mercado__jobs" height="24" width="24" class="mx-auto" fill="currentColor" style="color: #00000099">
              <path d="m17 6v-1c0-1.7-1.3-3-3-3h-4c-1.7 0-3 1.3-3 3v1h-5v4c0 1.7 1.3 3 3 3h14c1.7 0 3-1.3 3-3v-4zm-8-1c0-.6.4-1 1-1h4c.6 0 1 .4 1 1v1h-6zm10 9c1.2 0 2.3-.5 3-1.4v4.4c0 1.7-1.3 3-3 3h-14c-1.7 0-3-1.3-3-3v-4.4c.7.9 1.8 1.4 3 1.4z"></path>
            </svg>
            <div class="text-sm text-center font-light text-gray-800">Jobs</div>
          </div>
          <div class="flex flex-col cursor-pointer" style="min-width: 80px;">
            <svg id="global-nav-icon--mercado__messaging" height="24" width="24" class="mx-auto" fill="currentColor" style="color: #00000099">
              <path d="M16 3H8C6.14348 3 4.36301 3.77847 3.05025 5.16416C1.7375 6.54984 1 8.42923 1 10.3889C1 12.3485 1.7375 14.2279 3.05025 15.6136C4.36301 16.9993 6.14348 17.7778 8 17.7778H12V22L20.16 16.3106C21.0512 15.639 21.7751 14.7495 22.2697 13.7183C22.7643 12.687 23.0148 11.5446 23 10.3889C23 8.42923 22.2625 6.54984 20.9497 5.16416C19.637 3.77847 17.8565 3 16 3ZM8 11.7083C7.75277 11.7083 7.5111 11.631 7.30554 11.486C7.09998 11.341 6.93976 11.1349 6.84515 10.8938C6.75054 10.6527 6.72579 10.3874 6.77402 10.1315C6.82225 9.87553 6.9413 9.64043 7.11612 9.4559C7.29093 9.27137 7.51366 9.14571 7.75614 9.0948C7.99861 9.04389 8.24995 9.07002 8.47835 9.16988C8.70676 9.26975 8.90199 9.43886 9.03934 9.65585C9.17669 9.87283 9.25 10.1279 9.25 10.3889C9.25 10.7388 9.1183 11.0744 8.88388 11.3219C8.64946 11.5693 8.33152 11.7083 8 11.7083ZM12 11.7083C11.7528 11.7083 11.5111 11.631 11.3055 11.486C11.1 11.341 10.9398 11.1349 10.8452 10.8938C10.7505 10.6527 10.7258 10.3874 10.774 10.1315C10.8222 9.87553 10.9413 9.64043 11.1161 9.4559C11.2909 9.27137 11.5137 9.14571 11.7561 9.0948C11.9986 9.04389 12.2499 9.07002 12.4784 9.16988C12.7068 9.26975 12.902 9.43886 13.0393 9.65585C13.1767 9.87283 13.25 10.1279 13.25 10.3889C13.25 10.7388 13.1183 11.0744 12.8839 11.3219C12.6495 11.5693 12.3315 11.7083 12 11.7083ZM16 11.7083C15.7528 11.7083 15.5111 11.631 15.3055 11.486C15.1 11.341 14.9398 11.1349 14.8452 10.8938C14.7505 10.6527 14.7258 10.3874 14.774 10.1315C14.8222 9.87553 14.9413 9.64043 15.1161 9.4559C15.2909 9.27137 15.5137 9.14571 15.7561 9.0948C15.9986 9.04389 16.2499 9.07002 16.4784 9.16988C16.7068 9.26975 16.902 9.43886 17.0393 9.65585C17.1767 9.87283 17.25 10.1279 17.25 10.3889C17.25 10.7388 17.1183 11.0744 16.8839 11.3219C16.6495 11.5693 16.3315 11.7083 16 11.7083Z"></path>
            </svg>
            <div class="text-sm text-center font-light text-gray-800">Messaging</div>
          </div>
          <div class="flex flex-col cursor-pointer" style="min-width: 80px;">
            <svg id="global-nav-icon--mercado__notifications" height="24" width="24" class="mx-auto" fill="currentColor" style="color: #00000099">
              <path d="M13.7 19C13.9 19.3 14 19.6 14 20C14 21.1 13.1 22 12 22C10.9 22 10 21.1 10 20C10 19.6 10.1 19.3 10.3 19H2V18C2 17 2.4 16.1 3.2 15.2L4.2 14H19.9L20.9 15.2C21.7 16.2 22.1 17.1 22.1 18V19H13.7ZM18.2 7.4C17.8 4.3 15.1 2 12 2C8.9 2 6.2 4.3 5.8 7.4L5 13H19L18.2 7.4Z"></path>
            </svg>
            <div class="text-sm text-center font-light text-gray-800">Notification</div>
          </div>
          <div class="flex h-full border-r border-gray-200 cursor-pointer" style="min-width: 80px;">
            <div class="my-auto w-full">
              <img height="24" width="24" class="mx-auto rounded-full" :src="require(`~/assets/images/linkedin/${pro_image}`)">
              <div class="flex justify-center">
                <div class="text-sm text-center font-light text-gray-800">Me</div>
                <svg class="my-auto" width="16" height="16" fill="currentColor" style="color: #00000099">
                  <path d="M8.8 10.66L14 5.12a.07.07 0 00-.07-.12H2.07a.07.07 0 00-.07.12l5.2 5.54a1.1 1.1 0 001.6 0z"></path>
                </svg>
              </div>
            </div>
          </div>
          <div class="flex flex-col cursor-pointer" style="min-width: 80px;">
            <svg id="global-nav-icon--classic__work" height="24" width="24" class="mx-auto" fill="currentColor" style="color: #00000099">
              <path d="M10 10h4v4h-4v-4zm0 11h4v-4h-4v4zm-7-7h4v-4H3v4zm0 7h4v-4H3v4zM3 7h4V3H3v4zm14 7h4v-4h-4v4zm0-11v4h4V3h-4zm-7 4h4V3h-4v4zm7 14h4v-4h-4v4z"></path>
            </svg>
            <div class="flex justify-center">
              <div class="text-sm text-center font-light text-gray-800">Work</div>
              <svg class="my-auto" width="16" height="16" fill="currentColor" style="color: #00000099">
                <path d="M8.8 10.66L14 5.12a.07.07 0 00-.07-.12H2.07a.07.07 0 00-.07.12l5.2 5.54a1.1 1.1 0 001.6 0z"></path>
              </svg>
            </div>
          </div>
          <div class="flex h-full items-center" style="min-width: 80px;">
            <div class="text-xs text-center font-light hover:underline cursor-pointer">Try Premium for <br>free</div>
          </div>
        </div>
      </div>
    </div>
    <div>
      <div class="w-full bg-white h-11 flex justify-between px-2.5 md:hidden items-center overflow-hidden w-full bg-white border-b-solid fixed z-50 top-0">
        <div>
          <img width="40" height="40" src="https://media-exp1.licdn.com/dms/image/C4E03AQF8WMHfDxvbLw/profile-displayphoto-shrink_100_100/0/1628967692068?e=1634774400&v=beta&t=RabwoIpUUcu9t3YPiG5pFgPUlqvbZbd0ZhOJd5WRu0E" loading="lazy" alt="Photo of Abuzaid Sayyad" class="rounded-full border-2 border-white">
        </div>
        <div class="relative w-full px-2 overflow-hidden">
          <input type="search" class="bg-indigo rounded pl-8 pr-3 py-1.5 focus:outline-none w-full placeholder-gray-500 text-sm" placeholder="Search">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" data-supported-dps="16x16" fill="currentColor" class="absolute top-2 left-4 text-gray-700" width="15" height="15" focusable="false">
            <path d="M14.56 12.44L11.3 9.18a5.51 5.51 0 10-2.12 2.12l3.26 3.26a1.5 1.5 0 102.12-2.12zM3 6.5A3.5 3.5 0 116.5 10 3.5 3.5 0 013 6.5z"></path>
          </svg>
        </div>
        <div class="ml-3">
          <svg style="color: #00000073" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" id="messages-medium" data-supported-dps="24x24" fill="currentColor"><path d="M16 4H8a7 7 0 000 14h4v4l8.16-5.39A6.78 6.78 0 0023 11a7 7 0 00-7-7zm-8 8.25A1.25 1.25 0 119.25 11 1.25 1.25 0 018 12.25zm4 0A1.25 1.25 0 1113.25 11 1.25 1.25 0 0112 12.25zm4 0A1.25 1.25 0 1117.25 11 1.25 1.25 0 0116 12.25z"></path></svg>
        </div>
      </div>
      <div class="w-full bg-white h-12 flex justify-between px-3 md:hidden items-center overflow-hidden w-full bg-white border-t-solid fixed z-50 bottom-0">
        <div class="flex items-center justify-between h-full w-full">
          <div class="cursor-pointer">
            <svg class="mx-auto" id="global-nav-icon--mercado__home--active" height="24" width="24">
              <path d="m23 9v2h-2v7c0 1.7-1.3 3-3 3h-4v-6h-4v6h-4c-1.7 0-3-1.3-3-3v-7h-2v-2l11-7z"></path>
              <path d="m20 2h-3v3.2l3 1.9z"></path>
            </svg>
            <div class="text-center font-normal" style="font-size: 11px; color: rgba(0, 0, 0, 0.9)">Home</div>
          </div>
          <div class="cursor-pointer">
            <svg id="global-nav-icon--mercado__my-network" height="24" width="24" class="mx-auto" fill="currentColor" style="color: #00000099">
              <path d="m12 16v6h-9v-6c0-1.7 1.3-3 3-3h3c1.7 0 3 1.3 3 3zm5.5-3c1.9 0 3.5-1.6 3.5-3.5s-1.6-3.5-3.5-3.5-3.5 1.6-3.5 3.5 1.6 3.5 3.5 3.5zm1 2h-2c-1.4 0-2.5 1.1-2.5 2.5v4.5h7v-4.5c0-1.4-1.1-2.5-2.5-2.5zm-11-13c-2.5 0-4.5 2-4.5 4.5s2 4.5 4.5 4.5 4.5-2 4.5-4.5-2-4.5-4.5-4.5z"></path>
            </svg>
            <div class="text-sm text-center font-normal whitespace-nowrap" style="font-size: 11px; color: rgba(0, 0, 0, 0.6)">My Network</div>
          </div>
          <div class="cursor-pointer">
            <svg xmlns="http://www.w3.org/2000/svg" height="24" width="24" class="mx-auto" style="color: #00000099" viewBox="0 0 24 24" id="post-fill-medium" data-supported-dps="24x24" fill="currentColor"><path d="M18 3H6a3 3 0 00-3 3v12a3 3 0 003 3h12a3 3 0 003-3V6a3 3 0 00-3-3zm-5 8h4v2h-4v4h-2v-4H7v-2h4V7h2z"></path></svg>
            <div class="text-sm text-center font-normal" style="font-size: 11px; color: rgba(0, 0, 0, 0.6)">Post</div>
          </div>
          <div class="cursor-pointer">
            <svg id="global-nav-icon--mercado__notifications" height="24" width="24" class="mx-auto" fill="currentColor" style="color: #00000099">
              <path d="M13.7 19C13.9 19.3 14 19.6 14 20C14 21.1 13.1 22 12 22C10.9 22 10 21.1 10 20C10 19.6 10.1 19.3 10.3 19H2V18C2 17 2.4 16.1 3.2 15.2L4.2 14H19.9L20.9 15.2C21.7 16.2 22.1 17.1 22.1 18V19H13.7ZM18.2 7.4C17.8 4.3 15.1 2 12 2C8.9 2 6.2 4.3 5.8 7.4L5 13H19L18.2 7.4Z"></path>
            </svg>
            <div class="text-sm text-center font-normal" style="font-size: 11px; color: rgba(0, 0, 0, 0.6)">Notification</div>
          </div>
          <div class="cursor-pointer">
            <svg id="global-nav-icon--mercado__jobs" height="24" width="24" class="mx-auto" fill="currentColor" style="color: #00000099">
              <path d="m17 6v-1c0-1.7-1.3-3-3-3h-4c-1.7 0-3 1.3-3 3v1h-5v4c0 1.7 1.3 3 3 3h14c1.7 0 3-1.3 3-3v-4zm-8-1c0-.6.4-1 1-1h4c.6 0 1 .4 1 1v1h-6zm10 9c1.2 0 2.3-.5 3-1.4v4.4c0 1.7-1.3 3-3 3h-14c-1.7 0-3-1.3-3-3v-4.4c.7.9 1.8 1.4 3 1.4z"></path>
            </svg>
            <div class="text-sm text-center font-normal" style="font-size: 11px; color: rgba(0, 0, 0, 0.6)">Jobs</div>
          </div>


        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "linkedin-header",
  data(){
    return{
      pro_image:'pro-pic.jpeg',
    }
  }
}
</script>

<style scoped>

</style>
