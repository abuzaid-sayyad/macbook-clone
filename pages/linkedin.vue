<template>
  <div class="w-full bg-gray-100">
    <linkedin-header></linkedin-header>
    <div class="md:max-w-6xl md:mx-auto md:pt-20 pt-12 md:grid md:grid-cols-10 md:gap-6">
      <div class="md:col-span-2 hidden md:block relative">
        <div class="bg-white rounded-lg border-solid">
          <img class="rounded-t-lg" :src="require(`~/assets/images/linkedin/${cover_image}`)">
          <div class="flex justify-center -mt-10">
            <img width="72"  height="72" :src="require(`~/assets/images/linkedin/${pro_image}`)" loading="lazy" alt="Photo of Abuzaid Sayyad" class="rounded-full border-2 border-white">
          </div>
          <div class="mt-2.5 py-3 border-b">
            <h4 class="text-base font-medium text-center">Abuzaid Sayyad</h4>
            <h4 class="text-sm font-light text-gray-700 text-center">Web Developer</h4>
          </div>
          <div class="py-3 border-b">
            <div class="px-2.5 cursor-pointer hover:bg-gray-100">
              <div class="flex justify-between">
                <h4 class="text-sms font-medium text-black-light">Connections</h4>
                <h4 class="text-sms font-medium text-blue-500">1200</h4>
              </div>
              <h4 class="text-sms font-medium -mt-1.5">Grow your network</h4>
            </div>
            <div class="flex justify-between cursor-pointer px-2.5 mt-1 hover:bg-gray-100">
              <h4 class="text-sms font-medium text-black-light">Who viewed your profile</h4>
              <h4 class="text-sms font-medium text-blue-500">422</h4>
            </div>
          </div>
          <div class="py-3 border-b px-2 cursor-pointer hover:bg-gray-100">
            <h4 class="text-sms font-normal text-black-light">Access exclusive tools & insights</h4>
            <div class="flex">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" class="" width="17" height="17" focusable="false">
                <path d="M20 20a3.36 3.36 0 001-2.39V6.38A3.38 3.38 0 0017.62 3H6.38A3.36 3.36 0 004 4z" fill="#f8c77e"></path>
                <path d="M4 4a3.36 3.36 0 00-1 2.38v11.24A3.38 3.38 0 006.38 21h11.24A3.36 3.36 0 0020 20z" fill="#e7a33e"></path>
              </svg>
              <h4 class="text-sms font-medium tracking-tight my-auto">Try Premium Free for 1 Month</h4>
            </div>
          </div>
          <div class="py-3  px-2 cursor-pointer hover:bg-gray-100">
            <div class="flex">
              <svg xmlns="http://www.w3.org/2000/svg" class="text-black-light" viewBox="0 0 16 16" data-supported-dps="16x16" fill="currentColor" width="16" height="16" focusable="false">
                <path d="M12 1H4a1 1 0 00-1 1v13.64l5-3.36 5 3.36V2a1 1 0 00-1-1z"></path>
              </svg>
              <h4 class="text-sms font-medium ml-1 -mt-0.5">My items</h4>
            </div>
          </div>
        </div>
        <div class="bg-white rounded-lg border-solid mt-1 sticky top-20" style="align-self: start">
          <div class="">
            <h4 class="text-sms font-normal pt-3 px-2.5">Recent</h4>
            <div class="flex mt-2 hover:bg-gray-100 cursor-pointer px-2.5">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" data-supported-dps="16x16" fill="currentColor" class="text-black-light mr-2 my-auto" width="16" height="16" focusable="false">
                <path d="M6.65 11h2l-.33 3h2l.33-3H14V9h-3.13l.26-2H14V5h-2.65l.33-3h-2l-.33 3h-2l.33-3h-2l-.33 3H2v2h3.13l-.26 2H2v2h2.65l-.33 3h2zm.48-4h2l-.26 2h-2z"></path>
              </svg>
              <div class="text-sms font-medium text-black-light ">india</div>
            </div>
            <div class="text-sms font-medium text-blue-500 mt-3.5 px-2.5 hover:underline cursor-pointer">Groups</div>
            <div class="flex justify-between px-2.5">
              <div class="text-sms font-medium text-blue-500 my-auto hover:underline cursor-pointer">Events</div>
              <div class="hover:bg-gray-100 text-black-light rounded-full flex h-7 w-7 cursor-pointer">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" data-supported-dps="16x16" fill="currentColor" class="m-auto" width="16" height="16" focusable="false">
                  <path d="M14 9H9v5H7V9H2V7h5V2h2v5h5z"></path>
                </svg>
              </div>
            </div>
            <div class="text-sms font-medium text-blue-500 hover:underline px-2.5 cursor-pointer">Followed Hashtags</div>
            <div class="flex hover:bg-gray-100 cursor-pointer px-2.5 mt-2">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" data-supported-dps="16x16" fill="currentColor" class="text-black-light mr-2 my-auto" width="16" height="16" focusable="false">
                <path d="M6.65 11h2l-.33 3h2l.33-3H14V9h-3.13l.26-2H14V5h-2.65l.33-3h-2l-.33 3h-2l.33-3h-2l-.33 3H2v2h3.13l-.26 2H2v2h2.65l-.33 3h2zm.48-4h2l-.26 2h-2z"></path>
              </svg>
              <div class="text-sms font-medium text-black-light ">india</div>
            </div>
            <div class="flex hover:bg-gray-100 cursor-pointer px-9 my-2 text-sms font-medium text-black-light ">
              See all
            </div>
            <div class="text-center border-t hover:bg-gray-100 cursor-pointer px-2.5 py-3 text-base font-medium text-black-light">
              Discover more
            </div>
          </div>
        </div>
      </div>
      <div class="md:col-span-5">
        <div class="border-solid rounded-lg bg-white px-3 hidden md:block">
          <div class="flex pt-3">
            <div class="">
              <img class="w-12 h-12 rounded-full mr-4" :src="require(`~/assets/images/linkedin/${pro_image}`)">
            </div>
            <input type="text" class="w-full rounded-full border border-gray-300 px-6 cursor-pointer focus:outline-none hover:bg-gray-200 font-medium text-base-a placeholder-gray-500 hover:border-gray-400" placeholder="Start a post">
          </div>
          <div class="py-1 flex justify-between">
            <button class="text-black-light text-base-a font-medium px-2.5 py-3.5 rounded hover:bg-gray-100 focus:outline-none flex">
              <svg style="color: #70b5f9" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match" width="24" height="24" focusable="false">
                <path d="M19 4H5a3 3 0 00-3 3v10a3 3 0 003 3h14a3 3 0 003-3V7a3 3 0 00-3-3zm1 13a1 1 0 01-.29.71L16 14l-2 2-6-6-4 4V7a1 1 0 011-1h14a1 1 0 011 1zm-2-7a2 2 0 11-2-2 2 2 0 012 2z"></path>
              </svg>
              <span class="my-auto ml-1">Photos</span>
            </button>
            <button class="text-black-light text-base-a font-medium px-2.5 py-3.5 rounded hover:bg-gray-100 focus:outline-none flex">
              <svg style="color: #7fc15e" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match" width="24" height="24" focusable="false">
                <path d="M19 4H5a3 3 0 00-3 3v10a3 3 0 003 3h14a3 3 0 003-3V7a3 3 0 00-3-3zm-9 12V8l6 4z"></path>
              </svg>
              <span class="my-auto ml-1">Video</span>
            </button>
            <button class="text-black-light text-base-a font-medium px-2.5 py-3.5 rounded hover:bg-gray-100 focus:outline-none flex">
              <svg style="color: #e7a33e" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match" width="24" height="24" focusable="false">
                <path d="M3 3v15a3 3 0 003 3h12a3 3 0 003-3V3zm13 1.75A1.25 1.25 0 1114.75 6 1.25 1.25 0 0116 4.75zm-8 0A1.25 1.25 0 116.75 6 1.25 1.25 0 018 4.75zM19 18a1 1 0 01-1 1H6a1 1 0 01-1-1V9h14zm-5.9-3a1 1 0 00-1-1H12a3.12 3.12 0 00-1 .2l-1-.2v-3h3.9v1H11v1.15a3.7 3.7 0 011.05-.15 1.89 1.89 0 012 1.78V15a1.92 1.92 0 01-1.84 2H12a1.88 1.88 0 01-2-1.75 1 1 0 010-.25h1a.89.89 0 001 1h.1a.94.94 0 001-.88z"></path>
              </svg>
              <span class="my-auto ml-1">Event</span>
            </button>
            <button class="text-black-light text-base-a font-medium px-2.5 py-3.5 rounded hover:bg-gray-100 focus:outline-none flex">
              <svg style="color: #f5987e" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match" width="24" height="24" focusable="false">
                <path d="M21 3v2H3V3zm-6 6h6V7h-6zm0 4h6v-2h-6zm0 4h6v-2h-6zM3 21h18v-2H3zM13 7H3v10h10z"></path>
              </svg>
              <span class="my-auto ml-1">Write Article</span>
            </button>
          </div>

        </div>
        <div class="items-center mt-1.5 mb-1 w-full hidden md:flex">
          <div class="w-full h-1  border-b border-gray-400"></div>
          <div>
            <div class="flex items-center w-20 mt-1 ml-2">
              <div class="text-gray-800 font-light text-xs ">Sort by: <span class="font-medium">Top</span></div>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" data-supported-dps="16x16" fill="currentColor" class="mercado-match" width="16" height="16" focusable="false">
                <path d="M8 11L3 6h10z" fill-rule="evenodd"></path>
              </svg>
            </div>
          </div>
        </div>
        <linkedin-post liked_person="Juned Shaikh" author="Nitish Kumar" occupation="CEO at Noetic IT Services" time="8h" :person_image="require(`~/assets/images/linkedin/${nitish_image}`)" :post_image="require(`~/assets/images/linkedin/${nitish_post_image}`)" :description="nitish_sir_desc" likes="11,200" comments="254"></linkedin-post>
        <linkedin-post liked_person="Nitish Kumar" author="Juned Shaikh" occupation="Web Developer at Noetic IT Services" time="8h" :person_image="require(`~/assets/images/linkedin/${without_image}`)" :post_image="require(`~/assets/images/linkedin/${juned_post_image}`)" description="Happy to share that I have joined the Noetic on 30 December 2019 as a Frontend Developer." likes="11,200" comments="254"></linkedin-post>
        <div class="border-solid rounded-lg bg-white py-1.5 px-3">
          <div class="flex items-center justify-between">
            <div class="text-xs font-semibold text-gray-700">Abuzaid Sayyad <span class="font-normal" style="color: rgba(0, 0, 0, 0.6)">Like this</span></div>
            <button class="rounded-full p-1 hover:bg-gray-100" style="color: #00000099">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match" width="24" height="24" focusable="false">
                <path d="M14 12a2 2 0 11-2-2 2 2 0 012 2zM4 10a2 2 0 102 2 2 2 0 00-2-2zm16 0a2 2 0 102 2 2 2 0 00-2-2z"></path>
              </svg>
            </button>

          </div>
          <div class="border-b border-gray-300 my-1"></div>
          <div class="flex items-center py-2">
            <div class="">
              <img class="rounded-full" height="48px" width="48px" :src="require(`~/assets/images/linkedin/${without_image}`)">
            </div>
            <div class="ml-2.5">
              <div class="flex">
                <h5 class="text-sm font-semibold " style="color: #000000e6">Juned Shaikh</h5>
                <div class="text-sm font-normal text-gray-500 ml-2.5"> • 3rd+</div>
              </div>
              <p class="text-xs font-normal" style="color: rgba(0, 0, 0, 0.6)">Software developer at Noetic</p>
              <div class="flex items-center" style="color: #00000099">
                <span class="text-xs font-normal mr-1.5" style="color: rgba(0, 0, 0, 0.6)">8h •</span>
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" data-supported-dps="16x16" fill="currentColor" class="mercado-match" width="16" height="16" focusable="false">
                  <path d="M8 1a7 7 0 107 7 7 7 0 00-7-7zM3 8a5 5 0 011-3l.55.55A1.5 1.5 0 015 6.62v1.07a.75.75 0 00.22.53l.56.56a.75.75 0 00.53.22H7v.69a.75.75 0 00.22.53l.56.56a.75.75 0 01.22.53V13a5 5 0 01-5-5zm6.24 4.83l2-2.46a.75.75 0 00.09-.8l-.58-1.16A.76.76 0 0010 8H7v-.19a.51.51 0 01.28-.45l.38-.19a.74.74 0 01.68 0L9 7.5l.38-.7a1 1 0 00.12-.48v-.85a.78.78 0 01.21-.53l1.07-1.09a5 5 0 01-1.54 9z"></path>
                </svg>
              </div>
            </div>
          </div>
          <p class="text-sm font-normal" style="color: rgba(0, 0, 0, 0.9)">Happy to share that I have joined the Noetic on 30 December 2019 as a Frontend Developer.</p>
          <img class="w-full h-auto mt-3" :src="require(`~/assets/images/linkedin/${image}`)">
          <div class="flex items-center my-2">
            <img width="16px" height="16px" src="https://static-exp1.licdn.com/sc/h/d310t2g24pvdy4pt1jkedo4yb">
            <img class="mx-1" width="16px" height="16px" src="https://static-exp1.licdn.com/sc/h/5thsbmikm6a8uov24ygwd914f">
            <img width="16px" height="16px" src="https://static-exp1.licdn.com/sc/h/jbbw3jbilcm53nvxebxd01gh">
            <div class="text-xs font-normal" style="color: #00000099;padding-left: 2px">11,250</div>
            <div class="text-xs font-normal mx-2" style="color: #00000099">•</div>
            <div class="text-xs font-normal" style="color: #00000099;padding-left: 2px">30 comments</div>
          </div>
          <div class="border-b border-gray-300"></div>
          <div class="flex items-center py-4 md:px-5 justify-between">
            <div class="md:flex items-center" style="color: #00000099">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match hidden md:block" width="24" height="24" focusable="false">
                <path d="M19.46 11l-3.91-3.91a7 7 0 01-1.69-2.74l-.49-1.47A2.76 2.76 0 0010.76 1 2.75 2.75 0 008 3.74v1.12a9.19 9.19 0 00.46 2.85L8.89 9H4.12A2.12 2.12 0 002 11.12a2.16 2.16 0 00.92 1.76A2.11 2.11 0 002 14.62a2.14 2.14 0 001.28 2 2 2 0 00-.28 1 2.12 2.12 0 002 2.12v.14A2.12 2.12 0 007.12 22h7.49a8.08 8.08 0 003.58-.84l.31-.16H21V11zM19 19h-1l-.73.37a6.14 6.14 0 01-2.69.63H7.72a1 1 0 01-1-.72l-.25-.87-.85-.41A1 1 0 015 17l.17-1-.76-.74A1 1 0 014.27 14l.66-1.09-.73-1.1a.49.49 0 01.08-.7.48.48 0 01.34-.11h7.05l-1.31-3.92A7 7 0 0110 4.86V3.75a.77.77 0 01.75-.75.75.75 0 01.71.51L12 5a9 9 0 002.13 3.5l4.5 4.5H19z"></path>
              </svg>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match mx-auto md:hidden" width="20" height="20" focusable="false">
                <path d="M19.46 11l-3.91-3.91a7 7 0 01-1.69-2.74l-.49-1.47A2.76 2.76 0 0010.76 1 2.75 2.75 0 008 3.74v1.12a9.19 9.19 0 00.46 2.85L8.89 9H4.12A2.12 2.12 0 002 11.12a2.16 2.16 0 00.92 1.76A2.11 2.11 0 002 14.62a2.14 2.14 0 001.28 2 2 2 0 00-.28 1 2.12 2.12 0 002 2.12v.14A2.12 2.12 0 007.12 22h7.49a8.08 8.08 0 003.58-.84l.31-.16H21V11zM19 19h-1l-.73.37a6.14 6.14 0 01-2.69.63H7.72a1 1 0 01-1-.72l-.25-.87-.85-.41A1 1 0 015 17l.17-1-.76-.74A1 1 0 014.27 14l.66-1.09-.73-1.1a.49.49 0 01.08-.7.48.48 0 01.34-.11h7.05l-1.31-3.92A7 7 0 0110 4.86V3.75a.77.77 0 01.75-.75.75.75 0 01.71.51L12 5a9 9 0 002.13 3.5l4.5 4.5H19z"></path>
              </svg>
              <div class="md:text-sm text-center md:text-left text-xs font-semibold ml-1.5">Like</div>
            </div>
            <div class="md:flex items-center mx-5" style="color: #00000099">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match hidden md:block" width="24" height="24" focusable="false">
                <path d="M7 9h10v1H7zm0 4h7v-1H7zm16-2a6.78 6.78 0 01-2.84 5.61L12 22v-4H8A7 7 0 018 4h8a7 7 0 017 7zm-2 0a5 5 0 00-5-5H8a5 5 0 000 10h6v2.28L19 15a4.79 4.79 0 002-4z"></path>
              </svg>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match md:hidden mx-auto" width="20" height="20" focusable="false">
                <path d="M7 9h10v1H7zm0 4h7v-1H7zm16-2a6.78 6.78 0 01-2.84 5.61L12 22v-4H8A7 7 0 018 4h8a7 7 0 017 7zm-2 0a5 5 0 00-5-5H8a5 5 0 000 10h6v2.28L19 15a4.79 4.79 0 002-4z"></path>
              </svg>
              <div class="md:text-sm text-xs md:text-center md:text-left font-semibold ml-1.5">Comment</div>
            </div>
            <div class="md:flex items-center" style="color: #00000099">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match hidden md:block" width="24" height="24" focusable="false">
                <path d="M23 12l-4.61 7H16l4-6H8a3.92 3.92 0 00-4 3.84V17a4 4 0 00.19 1.24L5.12 21H3l-.73-2.22A6.4 6.4 0 012 16.94 6 6 0 018 11h12l-4-6h2.39z"></path>
              </svg>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match mx-auto md:hidden" width="20" height="20" focusable="false">
                <path d="M23 12l-4.61 7H16l4-6H8a3.92 3.92 0 00-4 3.84V17a4 4 0 00.19 1.24L5.12 21H3l-.73-2.22A6.4 6.4 0 012 16.94 6 6 0 018 11h12l-4-6h2.39z"></path>
              </svg>
              <div class="md:text-sm text-xs md:text-left text-center font-semibold ml-1.5">Share</div>
            </div>
            <div class="md:flex items-center ml-5" style="color: #00000099">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match hidden md:block" width="24" height="24" focusable="false">
                <path d="M21 3L0 10l7.66 4.26L16 8l-6.26 8.34L14 24l7-21z"></path>
              </svg>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match md:hidden mx-auto" width="20" height="20" focusable="false">
                <path d="M21 3L0 10l7.66 4.26L16 8l-6.26 8.34L14 24l7-21z"></path>
              </svg>
              <div class="md:text-sm text-xs md:text-left text-center font-semibold ml-1.5">Send</div>
            </div>
          </div>
        </div>
        <div class="border-solid rounded-lg bg-white my-2 py-1.5 px-3">
          <div class="flex items-center justify-between">
            <span class="font-normal text-xs" style="color: rgba(0, 0, 0, 0.6)">Jobs recommended for you</span>
            <button class="rounded-full p-1 hover:bg-gray-100" style="color: #00000099">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match" width="24" height="24" focusable="false">
                <path d="M14 12a2 2 0 11-2-2 2 2 0 012 2zM4 10a2 2 0 102 2 2 2 0 00-2-2zm16 0a2 2 0 102 2 2 2 0 00-2-2z"></path>
              </svg>
            </button>
          </div>
          <div class="border-b border-gray-300 my-1"></div>
          <div class="bg-white rounded-lg flex whitespace-nowrap relative -mx-1">
            <button @click="imageCarousel(-1)" :disabled="atHeadOfLists" class="flex border-0 text-white bg-black shadow-lg rounded-full bg-opacity-60 hover:bg-opacity-80 focus:outline-none absolute" style="width: 2.6rem; z-index: 50; height: 2.6rem; top: 44%; left: 8px">
              <svg xmlns="http://www.w3.org/2000/svg" class="m-auto" width="24" height="24" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7" />
              </svg>
            </button>
            <div class="overflow-hidden">
              <div class="flex card-carousel-cards" :style="{ transform: 'translateX' + '(' + currentOffsets + 'px' + ')'}" >
                <div class="flex py-2.5">
                  <div v-for="(item, index) in Slider" class="bg-white border-solid rounded-lg m-1" style="width: 232px;height: 262px;">
                    <img class="rounded-t-lg object-center object-cover bg-cover" style="background-position: 50%; height: 48px; width: 100%" height="200" width="200" :src="require(`~/assets/images/linkedin/${item.cover_image}`)">
                    <div class="p-3 flex flex-col relative" style="height: calc(262px - 38px)">
                      <div class="bg-white rounded-md z-20 flex items-center justify-center -mt-8" style="height: 64px; width: 64px;">
                        <img height="100%" width="100%" :src="require(`~/assets/images/linkedin/${item.image}`)">
                      </div>
                      <div class="text-base font-semibold mt-3" style="color: rgba(0, 0, 0, 0.9)">{{item.field}}</div>
                      <div class="text-base font-semibold" style="color: rgba(0, 0, 0, 0.9)">{{item.company}}</div>
                      <div class="text-xs font-normal" style="color: rgba(0, 0, 0, 0.6)">{{item.location}}</div>
                      <div class="flex items-center w-full mt-auto pb-2.5">
                        <div class="text-xs font-normal" style="color: rgba(0, 0, 0, 0.6)">{{item.updated}}</div>
                        <div class="text-xs font-normal" style="color: rgba(0, 0, 0, 0.6)">•</div>
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" data-supported-dps="16x16" class="mx-2" width="16" height="16" focusable="false">
                          <path d="M15 2v12a1 1 0 01-1 1H2a1 1 0 01-1-1V2a1 1 0 011-1h12a1 1 0 011 1zM5 6H3v7h2zm.25-2A1.25 1.25 0 104 5.25 1.25 1.25 0 005.25 4zM13 9.29c0-2.2-.73-3.49-2.86-3.49A2.71 2.71 0 007.89 7V6H6v7h2V9.73a1.73 1.73 0 011.52-1.92h.14C10.82 7.8 11 8.94 11 9.73V13h2z" fill="#0a66c2"></path>
                        </svg>
                        <div class="text-xs font-normal" style="color: rgba(0, 0, 0, 0.6)">Easily Apply</div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <button @click="imageCarousel(1)" :disabled="atEndOfLists" class="flex border-0 text-white bg-black shadow-lg rounded-full bg-opacity-60 hover:bg-opacity-80 focus:outline-none absolute" style="width: 2.6rem; height: 2.6rem; top: 44%; right: -3px">
              <svg xmlns="http://www.w3.org/2000/svg" class="m-auto" width="24" height="24" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
              </svg>
            </button>
          </div>
        </div>
        <div class="border-solid rounded-lg bg-white py-1.5 ">
          <div class="flex items-center justify-between px-3">
            <div class="text-xs font-semibold text-gray-700">SpaceX <span class="font-normal" style="color: rgba(0, 0, 0, 0.6)">was mentioned in the news</span></div>
            <button class="rounded-full p-1 hover:bg-gray-100" style="color: #00000099">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match" width="24" height="24" focusable="false">
                <path d="M14 12a2 2 0 11-2-2 2 2 0 012 2zM4 10a2 2 0 102 2 2 2 0 00-2-2zm16 0a2 2 0 102 2 2 2 0 00-2-2z"></path>
              </svg>
            </button>
          </div>
          <div class="" >
            <img class="object-center object-cover bg-cover mt-1" style="background-position: 50%; width: 100%; height: 295px" height="600" width="600" :src="require(`~/assets/images/linkedin/${images}`)">
          </div>
          <div class="p-2.5 bg-blue-100">
            <div class="text-sm font-semibold" style="color: rgba(0, 0, 0, 0.9)">SpaceX briefly puts together largest rocket in history at Texas base</div>
            <div class="text-xs font-normal mt-1" style="color: #00000099">spacedaily.com • 1 min read</div>
          </div>
          <div class="flex items-center my-2 pt-1 px-3">
            <img width="16px" height="16px" src="https://static-exp1.licdn.com/sc/h/d310t2g24pvdy4pt1jkedo4yb">
            <img class="mx-1" width="16px" height="16px" src="https://static-exp1.licdn.com/sc/h/5thsbmikm6a8uov24ygwd914f">
            <img width="16px" height="16px" src="https://static-exp1.licdn.com/sc/h/jbbw3jbilcm53nvxebxd01gh">
            <div class="text-xs font-normal" style="color: #00000099;padding-left: 2px">11,250</div>
            <div class="text-xs font-normal mx-2" style="color: #00000099">•</div>
            <div class="text-xs font-normal" style="color: #00000099;padding-left: 2px">30 comments</div>
          </div>
          <div class="border-b border-gray-300 mx-3"></div>
          <div class="flex items-center py-4 md:px-5 justify-between">
            <div class="md:flex items-center" style="color: #00000099">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match hidden md:block" width="24" height="24" focusable="false">
                <path d="M19.46 11l-3.91-3.91a7 7 0 01-1.69-2.74l-.49-1.47A2.76 2.76 0 0010.76 1 2.75 2.75 0 008 3.74v1.12a9.19 9.19 0 00.46 2.85L8.89 9H4.12A2.12 2.12 0 002 11.12a2.16 2.16 0 00.92 1.76A2.11 2.11 0 002 14.62a2.14 2.14 0 001.28 2 2 2 0 00-.28 1 2.12 2.12 0 002 2.12v.14A2.12 2.12 0 007.12 22h7.49a8.08 8.08 0 003.58-.84l.31-.16H21V11zM19 19h-1l-.73.37a6.14 6.14 0 01-2.69.63H7.72a1 1 0 01-1-.72l-.25-.87-.85-.41A1 1 0 015 17l.17-1-.76-.74A1 1 0 014.27 14l.66-1.09-.73-1.1a.49.49 0 01.08-.7.48.48 0 01.34-.11h7.05l-1.31-3.92A7 7 0 0110 4.86V3.75a.77.77 0 01.75-.75.75.75 0 01.71.51L12 5a9 9 0 002.13 3.5l4.5 4.5H19z"></path>
              </svg>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match mx-auto md:hidden" width="20" height="20" focusable="false">
                <path d="M19.46 11l-3.91-3.91a7 7 0 01-1.69-2.74l-.49-1.47A2.76 2.76 0 0010.76 1 2.75 2.75 0 008 3.74v1.12a9.19 9.19 0 00.46 2.85L8.89 9H4.12A2.12 2.12 0 002 11.12a2.16 2.16 0 00.92 1.76A2.11 2.11 0 002 14.62a2.14 2.14 0 001.28 2 2 2 0 00-.28 1 2.12 2.12 0 002 2.12v.14A2.12 2.12 0 007.12 22h7.49a8.08 8.08 0 003.58-.84l.31-.16H21V11zM19 19h-1l-.73.37a6.14 6.14 0 01-2.69.63H7.72a1 1 0 01-1-.72l-.25-.87-.85-.41A1 1 0 015 17l.17-1-.76-.74A1 1 0 014.27 14l.66-1.09-.73-1.1a.49.49 0 01.08-.7.48.48 0 01.34-.11h7.05l-1.31-3.92A7 7 0 0110 4.86V3.75a.77.77 0 01.75-.75.75.75 0 01.71.51L12 5a9 9 0 002.13 3.5l4.5 4.5H19z"></path>
              </svg>
              <div class="md:text-sm text-center md:text-left text-xs font-semibold ml-1.5">Like</div>
            </div>
            <div class="md:flex items-center mx-5" style="color: #00000099">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match hidden md:block" width="24" height="24" focusable="false">
                <path d="M7 9h10v1H7zm0 4h7v-1H7zm16-2a6.78 6.78 0 01-2.84 5.61L12 22v-4H8A7 7 0 018 4h8a7 7 0 017 7zm-2 0a5 5 0 00-5-5H8a5 5 0 000 10h6v2.28L19 15a4.79 4.79 0 002-4z"></path>
              </svg>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match md:hidden mx-auto" width="20" height="20" focusable="false">
                <path d="M7 9h10v1H7zm0 4h7v-1H7zm16-2a6.78 6.78 0 01-2.84 5.61L12 22v-4H8A7 7 0 018 4h8a7 7 0 017 7zm-2 0a5 5 0 00-5-5H8a5 5 0 000 10h6v2.28L19 15a4.79 4.79 0 002-4z"></path>
              </svg>
              <div class="md:text-sm text-xs md:text-center md:text-left font-semibold ml-1.5">Comment</div>
            </div>
            <div class="md:flex items-center" style="color: #00000099">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match hidden md:block" width="24" height="24" focusable="false">
                <path d="M23 12l-4.61 7H16l4-6H8a3.92 3.92 0 00-4 3.84V17a4 4 0 00.19 1.24L5.12 21H3l-.73-2.22A6.4 6.4 0 012 16.94 6 6 0 018 11h12l-4-6h2.39z"></path>
              </svg>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match mx-auto md:hidden" width="20" height="20" focusable="false">
                <path d="M23 12l-4.61 7H16l4-6H8a3.92 3.92 0 00-4 3.84V17a4 4 0 00.19 1.24L5.12 21H3l-.73-2.22A6.4 6.4 0 012 16.94 6 6 0 018 11h12l-4-6h2.39z"></path>
              </svg>
              <div class="md:text-sm text-xs md:text-left text-center font-semibold ml-1.5">Share</div>
            </div>
            <div class="md:flex items-center ml-5" style="color: #00000099">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match hidden md:block" width="24" height="24" focusable="false">
                <path d="M21 3L0 10l7.66 4.26L16 8l-6.26 8.34L14 24l7-21z"></path>
              </svg>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match mx-auto md:hidden" width="20" height="20" focusable="false">
                <path d="M21 3L0 10l7.66 4.26L16 8l-6.26 8.34L14 24l7-21z"></path>
              </svg>
              <div class="md:text-sm text-xs md:text-left text-center font-semibold ml-1.5">Send</div>
            </div>
          </div>
        </div>
        <div class="border-solid rounded-lg bg-white py-1.5 my-2 ">
          <div class="flex items-center px-3 justify-between">
            <div class="text-xs font-semibold text-gray-700">Abuzaid Sayyad <span class="font-normal" style="color: rgba(0, 0, 0, 0.6)">Like this</span></div>
            <button class="rounded-full p-1 hover:bg-gray-100" style="color: #00000099">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match" width="24" height="24" focusable="false">
                <path d="M14 12a2 2 0 11-2-2 2 2 0 012 2zM4 10a2 2 0 102 2 2 2 0 00-2-2zm16 0a2 2 0 102 2 2 2 0 00-2-2z"></path>
              </svg>
            </button>

          </div>
          <div class="border-b border-gray-300 mx-3 my-1"></div>
          <div class="flex items-center px-3 py-2">
            <div class="">
              <img class="rounded-full" height="48px" width="48px" :src="require(`~/assets/images/linkedin/${pro_image}`)">
            </div>
            <div class="ml-2.5">
              <div class="flex">
                <h5 class="text-sm font-semibold " style="color: #000000e6">Abuzaid Sayyad</h5>
                <div class="text-sm font-normal text-gray-500 ml-2.5"> • 3rd+</div>
              </div>
              <p class="text-xs font-normal" style="color: rgba(0, 0, 0, 0.6)">Software developer at Noetic</p>
              <div class="flex items-center" style="color: #00000099">
                <span class="text-xs font-normal mr-1.5" style="color: rgba(0, 0, 0, 0.6)">8h •</span>
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" data-supported-dps="16x16" fill="currentColor" class="mercado-match" width="16" height="16" focusable="false">
                  <path d="M8 1a7 7 0 107 7 7 7 0 00-7-7zM3 8a5 5 0 011-3l.55.55A1.5 1.5 0 015 6.62v1.07a.75.75 0 00.22.53l.56.56a.75.75 0 00.53.22H7v.69a.75.75 0 00.22.53l.56.56a.75.75 0 01.22.53V13a5 5 0 01-5-5zm6.24 4.83l2-2.46a.75.75 0 00.09-.8l-.58-1.16A.76.76 0 0010 8H7v-.19a.51.51 0 01.28-.45l.38-.19a.74.74 0 01.68 0L9 7.5l.38-.7a1 1 0 00.12-.48v-.85a.78.78 0 01.21-.53l1.07-1.09a5 5 0 01-1.54 9z"></path>
                </svg>
              </div>
            </div>
          </div>
          <p class="text-sm font-normal px-3" style="color: rgba(0, 0, 0, 0.9)">Title : UI / UX Research<br>
            Day - 10<br>
            .<br>
            .<br>
            .<br>
            .<br>
            Which Ul is Better?<br>
            Feedback's Appreciate</p>
          <!-- <img class="w-full h-auto mt-3" src="https://media-exp1.licdn.com/dms/image/C4E22AQELtyBozrDZ-A/feedshare-shrink_800/0/1632401036787?e=1635379200&v=beta&t=kuiAJawRcBNxcnzVISX86vT6iipWfkqWnJ4GyfxphQA"> -->
          <div class="flex items-center px-3 my-2">
            <img width="16px" height="16px" src="https://static-exp1.licdn.com/sc/h/d310t2g24pvdy4pt1jkedo4yb">
            <img class="mx-1" width="16px" height="16px" src="https://static-exp1.licdn.com/sc/h/5thsbmikm6a8uov24ygwd914f">
            <img width="16px" height="16px" src="https://static-exp1.licdn.com/sc/h/jbbw3jbilcm53nvxebxd01gh">
            <div class="text-xs font-normal" style="color: #00000099;padding-left: 2px">11,250</div>
            <div class="text-xs font-normal mx-2" style="color: #00000099">•</div>
            <div class="text-xs font-normal" style="color: #00000099;padding-left: 2px">30 comments</div>
          </div>
          <div class="border-b mx-3 border-gray-300"></div>
          <div class="flex items-center py-4 md:px-5 justify-between">
            <div class="md:flex items-center" style="color: #00000099">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match hidden md:block" width="24" height="24" focusable="false">
                <path d="M19.46 11l-3.91-3.91a7 7 0 01-1.69-2.74l-.49-1.47A2.76 2.76 0 0010.76 1 2.75 2.75 0 008 3.74v1.12a9.19 9.19 0 00.46 2.85L8.89 9H4.12A2.12 2.12 0 002 11.12a2.16 2.16 0 00.92 1.76A2.11 2.11 0 002 14.62a2.14 2.14 0 001.28 2 2 2 0 00-.28 1 2.12 2.12 0 002 2.12v.14A2.12 2.12 0 007.12 22h7.49a8.08 8.08 0 003.58-.84l.31-.16H21V11zM19 19h-1l-.73.37a6.14 6.14 0 01-2.69.63H7.72a1 1 0 01-1-.72l-.25-.87-.85-.41A1 1 0 015 17l.17-1-.76-.74A1 1 0 014.27 14l.66-1.09-.73-1.1a.49.49 0 01.08-.7.48.48 0 01.34-.11h7.05l-1.31-3.92A7 7 0 0110 4.86V3.75a.77.77 0 01.75-.75.75.75 0 01.71.51L12 5a9 9 0 002.13 3.5l4.5 4.5H19z"></path>
              </svg>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match mx-auto md:hidden" width="20" height="20" focusable="false">
                <path d="M19.46 11l-3.91-3.91a7 7 0 01-1.69-2.74l-.49-1.47A2.76 2.76 0 0010.76 1 2.75 2.75 0 008 3.74v1.12a9.19 9.19 0 00.46 2.85L8.89 9H4.12A2.12 2.12 0 002 11.12a2.16 2.16 0 00.92 1.76A2.11 2.11 0 002 14.62a2.14 2.14 0 001.28 2 2 2 0 00-.28 1 2.12 2.12 0 002 2.12v.14A2.12 2.12 0 007.12 22h7.49a8.08 8.08 0 003.58-.84l.31-.16H21V11zM19 19h-1l-.73.37a6.14 6.14 0 01-2.69.63H7.72a1 1 0 01-1-.72l-.25-.87-.85-.41A1 1 0 015 17l.17-1-.76-.74A1 1 0 014.27 14l.66-1.09-.73-1.1a.49.49 0 01.08-.7.48.48 0 01.34-.11h7.05l-1.31-3.92A7 7 0 0110 4.86V3.75a.77.77 0 01.75-.75.75.75 0 01.71.51L12 5a9 9 0 002.13 3.5l4.5 4.5H19z"></path>
              </svg>
              <div class="md:text-sm text-center md:text-left text-xs font-semibold ml-1.5">Like</div>
            </div>
            <div class="md:flex items-center mx-5" style="color: #00000099">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match hidden md:block" width="24" height="24" focusable="false">
                <path d="M7 9h10v1H7zm0 4h7v-1H7zm16-2a6.78 6.78 0 01-2.84 5.61L12 22v-4H8A7 7 0 018 4h8a7 7 0 017 7zm-2 0a5 5 0 00-5-5H8a5 5 0 000 10h6v2.28L19 15a4.79 4.79 0 002-4z"></path>
              </svg>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match md:hidden mx-auto" width="20" height="20" focusable="false">
                <path d="M7 9h10v1H7zm0 4h7v-1H7zm16-2a6.78 6.78 0 01-2.84 5.61L12 22v-4H8A7 7 0 018 4h8a7 7 0 017 7zm-2 0a5 5 0 00-5-5H8a5 5 0 000 10h6v2.28L19 15a4.79 4.79 0 002-4z"></path>
              </svg>
              <div class="md:text-sm text-xs md:text-center md:text-left font-semibold ml-1.5">Comment</div>
            </div>
            <div class="md:flex items-center" style="color: #00000099">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match hidden md:block" width="24" height="24" focusable="false">
                <path d="M23 12l-4.61 7H16l4-6H8a3.92 3.92 0 00-4 3.84V17a4 4 0 00.19 1.24L5.12 21H3l-.73-2.22A6.4 6.4 0 012 16.94 6 6 0 018 11h12l-4-6h2.39z"></path>
              </svg>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match mx-auto md:hidden" width="20" height="20" focusable="false">
                <path d="M23 12l-4.61 7H16l4-6H8a3.92 3.92 0 00-4 3.84V17a4 4 0 00.19 1.24L5.12 21H3l-.73-2.22A6.4 6.4 0 012 16.94 6 6 0 018 11h12l-4-6h2.39z"></path>
              </svg>
              <div class="md:text-sm text-xs md:text-left text-center font-semibold ml-1.5">Share</div>
            </div>
            <div class="md:flex items-center ml-5" style="color: #00000099">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match hidden md:block" width="24" height="24" focusable="false">
                <path d="M21 3L0 10l7.66 4.26L16 8l-6.26 8.34L14 24l7-21z"></path>
              </svg>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="currentColor" class="mercado-match mx-auto md:hidden" width="20" height="20" focusable="false">
                <path d="M21 3L0 10l7.66 4.26L16 8l-6.26 8.34L14 24l7-21z"></path>
              </svg>
              <div class="md:text-sm text-xs md:text-left text-center font-semibold ml-1.5">Send</div>
            </div>
          </div>
        </div>

      </div>
      <div class="md:col-span-3 hidden md:block relative">
        <div class="rounded-lg bg-white border-solid py-3">
          <div class="flex justify-between mb-2 px-3">
            <h3 class="text-base text-t-black font-medium">LinkedIn News</h3>
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" data-supported-dps="16x16" fill="currentColor" class="text-black-light mt-auto cursor-pointer" width="16" height="16" focusable="false">
              <path d="M12 2H4a2 2 0 00-2 2v8a2 2 0 002 2h8a2 2 0 002-2V4a2 2 0 00-2-2zm-3 8v2H7.5A1.5 1.5 0 016 10.5a1.56 1.56 0 01.1-.5l1.08-3h2.13l-1.09 3zm0-3.75A1.25 1.25 0 1110.25 5 1.25 1.25 0 019 6.25z"></path>
            </svg>
          </div>
          <div v-for="(item, index) in newsData" class="py-1 my-0.5 flex px-3 hover:bg-gray-100 w-full cursor-pointer">
            <div class="mt-2 mr-3" style="border-radius: 50%;display: inline-block;width: 6px;height: 6px;border: 3px solid #00000099"></div>
            <div>
              <h3 class="text-base-a text-t-black font-medium">{{item.title}}</h3>
              <p class="text-xs font-normal text-gray-500">{{item.subtitle}}</p>
            </div>
          </div>
          <div class="flex mt-2 pl-5">
            <button class="py-0.5 px-2 text-base font-medium flex text-black-light hover:bg-gray-100 rounded focus:outline-none">
              <span class="my-auto mr-1">Show more</span>
              <svg class="my-auto" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" data-supported-dps="16x16" fill="currentColor" width="16" height="16" focusable="false">
                <path d="M1 5l7 4.61L15 5v2.39L8 12 1 7.39z"></path>
              </svg>
            </button>
          </div>
        </div>
        <div class="rounded-lg bg-white border-solid py-3 mt-1.5">
          <div class="flex justify-between mb-2 px-3">
            <h3 class="text-base text-t-black font-medium">Today’s most viewed courses</h3>
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" data-supported-dps="16x16" fill="currentColor" class="text-black-light mt-auto cursor-pointer" width="16" height="16" focusable="false">
              <path d="M12 2H4a2 2 0 00-2 2v8a2 2 0 002 2h8a2 2 0 002-2V4a2 2 0 00-2-2zm-3 8v2H7.5A1.5 1.5 0 016 10.5a1.56 1.56 0 01.1-.5l1.08-3h2.13l-1.09 3zm0-3.75A1.25 1.25 0 1110.25 5 1.25 1.25 0 019 6.25z"></path>
            </svg>
          </div>
          <div v-for="(item, index) in courseData" class="py-1 my-0.5 flex px-3 hover:bg-gray-100 w-full cursor-pointer">
            <div class="text-base-a text-t-black font-medium mr-3">{{index+1}}.</div>
<!--            <div class="mt-2 mr-3" style="border-radius: 50%;display: inline-block;width: 6px;height: 6px;border: 3px solid #00000099"></div>-->
            <div>
              <h3 class="text-base-a text-t-black font-medium">{{item.title}}</h3>
              <p class="text-xs font-normal text-gray-500">{{item.subtitle}}</p>
            </div>
          </div>
          <div class="flex mt-2 pl-5">
            <button class="py-0.5 px-2 text-base font-medium flex text-black-light hover:bg-gray-100 rounded focus:outline-none">
              <span class="my-auto mr-1">Show more on LinkedIn Learning</span>
              <svg class="my-auto" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" data-supported-dps="16x16" fill="currentColor" width="16" height="16" focusable="false">
                <path d="M1 5l7 4.61L15 5v2.39L8 12 1 7.39z"></path>
              </svg>
            </button>
          </div>
        </div>
        <div class="sticky top-20" style="align-self: start;">
          <div class="rounded-lg bg-white border-solid py-3 mt-1.5 h-64 p-3.5">
            <div class="flex justify-end">
              <div class="text-xs font-normal text-black-light mr-2">Ad</div>
              <svg viewBox="0 0 16 16" width="16" height="16" xmlns="http://www.w3.org/2000/svg"><title>overflow-web-small</title><g><g><path d="M3,9.5A1.5,1.5,0,1,1,4.5,8,1.5,1.5,0,0,1,3,9.5ZM11.5,8A1.5,1.5,0,1,0,13,6.5,1.5,1.5,0,0,0,11.5,8Zm-5,0A1.5,1.5,0,1,0,8,6.5,1.5,1.5,0,0,0,6.5,8Z"></path></g></g></svg>
            </div>
            <div class="flex justify-center mt-7">
              <img class="rounded-full mr-5" style="max-width: 70px; max-height: 70px" src="https://media-exp1.licdn.com/dms/image/C4E03AQF8WMHfDxvbLw/profile-displayphoto-shrink_100_100/0/1628967692068?e=1634774400&v=beta&t=RabwoIpUUcu9t3YPiG5pFgPUlqvbZbd0ZhOJd5WRu0E">
              <img style="max-width: 70px; max-height: 70px" src="https://media-exp1.licdn.com/dms/image/C4D0BAQGyOWvr4W0Pow/company-logo_100_100/0/1590003577120?e=1630540800&v=beta&t=vwzN8Kt-UUrUqxZ7qf73pWfGbnGLEgBOXG-xNi0UfA0">
            </div>
            <p class="text-base font-normal text-black-light my-3 text-center px-4">Abuzaid, explore jobs at <span class="font-medium text-black">LinkedIn</span> that match your skills</p>
            <div class="flex justify-center">
              <button class="py-1 px-3.5 rounded-full border border-blue-500 focus:outline-none text-base text-blue-600 hover:bg-blue-100 hover:border-2 hover:border-blue-500 font-medium">See Jobs</button>
            </div>
          </div>
          <div>
            <div class="flex justify-center items-center mt-4">
              <a href="#" class="text-xs font-normal hover:underline" style="color: #00000099">About</a>
              <a href="#" class="text-xs font-normal hover:underline mx-6" style="color: #00000099">Accessibility</a>
              <a href="#" class="text-xs font-normal hover:underline" style="color: #00000099">Help Center</a>
            </div>
            <div class="flex justify-center my-2 items-center">
              <div class="flex items-center" style="color: #00000099">
                <a href="#" class="text-xs font-normal hover:underline">Privacy & Terms</a>
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" data-supported-dps="16x16" fill="currentColor" class="ml-1.5" width="15" height="15" focusable="false">
                  <path d="M1 5l7 4.61L15 5v2.39L8 12 1 7.39z"></path>
                </svg>
              </div>
              <a href="#" class="text-xs font-normal hover:underline ml-6" style="color: #00000099">Ad Choices</a>
            </div>
            <div class="flex justify-center  items-center">
              <a href="#" class="text-xs font-normal hover:underline mr-6" style="color: #00000099">Advertising</a>
              <div class="flex items-center" style="color: #00000099">
                <a href="#" class="text-xs font-normal hover:underline">Business Services</a>
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" data-supported-dps="16x16" fill="currentColor" class="ml-1.5" width="15" height="15" focusable="false">
                  <path d="M1 5l7 4.61L15 5v2.39L8 12 1 7.39z"></path>
                </svg>
              </div>
            </div>
            <div class="flex justify-center my-2 items-center">
              <a href="#" class="text-xs font-normal hover:underline mr-6" style="color: #00000099">Get the LinkedIn app</a>
              <a href="#" class="text-xs font-normal hover:underline" style="color: #00000099">More</a>
            </div>
            <div class="flex justify-center my-2 items-center">
              <svg style="color: #0a66c2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 56 14" data-supported-dps="56x14" fill="currentColor" class="mercado-match" width="56" height="14" focusable="false">
                <g>
                  <path class="background-mercado" d="M22.1 8.2l3.09 3.8h-2.44L20 8.51V12h-2V2h2v5.88L22.54 5h2.55zm-8-3.4A2.71 2.71 0 0011.89 6V5H10v7h2V8.73a1.74 1.74 0 011.66-1.93C14.82 6.8 15 7.94 15 8.73V12h2V8.29c0-2.2-.73-3.49-2.86-3.49zM32 8.66a4.22 4.22 0 010 .44h-5.25v.07a1.79 1.79 0 001.83 1.43 2.51 2.51 0 001.84-.69l1.33 1a4.31 4.31 0 01-3.25 1.29 3.49 3.49 0 01-3.7-3.75 3.58 3.58 0 013.76-3.65C30.44 4.8 32 6.13 32 8.66zm-1.86-.86a1.46 1.46 0 00-1.59-1.4 1.64 1.64 0 00-1.8 1.4zM2 2H0v10h6v-2H2zm36 0h2v10h-1.89v-.7a2.44 2.44 0 01-2 .9 3.41 3.41 0 01-3.31-3.7 3.36 3.36 0 013.3-3.7 2.62 2.62 0 011.9.7zm.15 6.5a1.63 1.63 0 00-1.62-1.85A1.76 1.76 0 0034.9 8.5a1.76 1.76 0 001.63 1.85 1.63 1.63 0 001.62-1.85zM8 1.8A1.27 1.27 0 006.75 3a1.25 1.25 0 002.5 0A1.27 1.27 0 008 1.8zM7 12h2V5H7zM56 1v12a1 1 0 01-1 1H43a1 1 0 01-1-1V1a1 1 0 011-1h12a1 1 0 011 1zM46 5h-2v7h2zm.25-2a1.25 1.25 0 00-2.5 0 1.25 1.25 0 002.5 0zM54 8.29c0-2.2-.73-3.49-2.86-3.49A2.71 2.71 0 0048.89 6V5H47v7h2V8.73a1.74 1.74 0 011.66-1.93C51.82 6.8 52 7.94 52 8.73V12h2z"></path>
                </g>
              </svg>
              <div class="text-xs font-normal ml-2">LinkedIn Corporation © 2021</div>
            </div>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>

<script>
import LinkedinHeader from "../components/linkedin/linkedin-header";
import LinkedinPost from "../components/linkedin/linkedin-post";
export default {
  name: "linkedin",
  components: {LinkedinPost, LinkedinHeader},
  data(){
    return{
      currentOffset: 0,
      currentOffsets: 0,
      windowSize: 3,
      windowSizes: 3,
      paginationFactor: 150,
      paginationFactors: 500,
      image:'man.jpeg',
      images:'tcs.jpeg',
      cover_image:'co-pic.jpeg',
      pro_image:'pro-pic.jpeg',
      without_image:'without.svg',
      nitish_image:'nitiish.jpeg',
      nitish_post_image:'glass.jpeg',
      juned_post_image:'which-ui.jpeg',
      nitish_sir_desc:'Glassmorphism, the newest trend in UI. What separates Glassmorphism from Neuomorphism is that the latter is one layer while the former takes a vertical approach. The defining characteristics of Glassmorphism are',
      person_image:'https://media-exp1.licdn.com/dms/image/C4E03AQHL-EvSwCFElw/profile-displayphoto-shrink_400_400/0/1613388523043?e=1638403200&v=beta&t=Ndipi-tIslyaE49VxyP8Tkar6a0Bn1T4NR2II4ulSEU',
      post_image:'https://media-exp1.licdn.com/dms/image/C4E22AQEFiaqBA_MV8A/feedshare-shrink_800/0/1630749674308?e=1635379200&v=beta&t=TdbcmX3IEhHI383pOTXJjSJO1JQP2dW-71rq0trcKg8',
      newsData:[
        {id:1, title:'New COVID cases under 2 lakh for a week', subtitle:'Top news • 97,109 readers'},
        {id:1, title:'White-collar hiring sees an uptick', subtitle:'1d ago • 704 readers'},
        {id:1, title:'A promotion gap may be looming', subtitle:'15h ago • 96,452 readers'},
        {id:1, title:'India\'s top-ranked universities', subtitle:'2h ago • 182 readers'},
        {id:1, title:'Yes, there\'s a subscription for that', subtitle:'15h ago • 10,252 readers'},
      ],
      courseData:[
        {id:1, title:'What is Graphic Design?', subtitle:'Sean Adams'},
        {id:1, title:'The Six Morning Habits of High Performers', subtitle:'Pete Mockaitis | How to Be Awesome at Your Job'},
        {id:1, title:'Communication within Teams', subtitle:'Daisy Lovelace'},
      ],
      Slider:[
        {id:1, image:'11.jpeg', field:'Web Designer', company:'Porlab Technology Pvt Ltd', cover_image:'1.jpeg'},
        {id:1, image:'22.jpeg', field:'Web Designer', company:'Porlab Technology Pvt Ltd', cover_image:'2.jpeg', location:'Mumbai, Maharashtra, India', updated:'5 days ago',},
        {id:1, image:'33.jpeg', field:'Web Designer', company:'Porlab Technology Pvt Ltd', cover_image:'3.jpeg', location:'Mumbai, Maharashtra, India', updated:'5 days ago',},
        {id:1, image:'11.jpeg', field:'Web Designer', company:'Porlab Technology Pvt Ltd', cover_image:'1.jpeg'},
        {id:1, image:'22.jpeg', field:'Web Designer', company:'Porlab Technology Pvt Ltd', cover_image:'2.jpeg', location:'Mumbai, Maharashtra, India', updated:'5 days ago',},
        {id:1, image:'33.jpeg', field:'Web Designer', company:'Porlab Technology Pvt Ltd', cover_image:'3.jpeg', location:'Mumbai, Maharashtra, India', updated:'5 days ago',},
        {id:1, image:'11.jpeg', field:'Web Designer', company:'Porlab Technology Pvt Ltd', cover_image:'1.jpeg'},
        {id:1, image:'22.jpeg', field:'Web Designer', company:'Porlab Technology Pvt Ltd', cover_image:'2.jpeg', location:'Mumbai, Maharashtra, India', updated:'5 days ago',},
        {id:1, image:'33.jpeg', field:'Web Designer', company:'Porlab Technology Pvt Ltd', cover_image:'3.jpeg', location:'Mumbai, Maharashtra, India', updated:'5 days ago',},
      ],
    }
  },
  methods:{
    imageCarousel(direction) {
      // Find a more elegant way to express the :style. consider using props to make it truly generic
      if (direction === 1 && !this.atEndOfLists) {
        this.currentOffsets -= this.paginationFactors;
      } else if (direction === -1 && !this.atHeadOfLists) {
        this.currentOffsets += this.paginationFactors;
      }
    },
  },
  computed: {
    atEndOfLists() {
      return this.currentOffsets <= (this.paginationFactors * -1) * (this.Slider.length - this.windowSizes);
    },
    atHeadOfLists() {
      return this.currentOffsets === 0;
    },
  },
}
</script>

<style scoped>
.card-carousel-cards {
  transition: transform 150ms ease-out;
  transform: translatex(0px);
}
</style>
