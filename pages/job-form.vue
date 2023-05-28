<template>
  <div class="w-full family-poppins">
    <!--        header start here-->
    <div class="w-full absolute top-0" style="z-index: 97">
      <header class="md:h-16 h-10 w-full box-shadow bg-white fixed top-0 border-none">
        <div class="md:mx-auto mx-4 flex items-center justify-between h-full" style="max-width: 1150px">
          <div class="flex items-center">
            <a href="/news-feed">
              <img class="md:h-12 h-8 w-auto" alt="logo" src="">
            </a>
          </div>
          <div class="flex items-center ml-3">
            <div class="flex items-center cursor-pointer text-gray-900 font-medium text-sm hover:text-blue-500">
              <img class="h-10 w-10 rounded-full" src="https://media-exp1.licdn.com/dms/image/C4E03AQF8WMHfDxvbLw/profile-displayphoto-shrink_100_100/0/1628967692068?e=1634774400&v=beta&t=RabwoIpUUcu9t3YPiG5pFgPUlqvbZbd0ZhOJd5WRu0E">
              <span class="ml-1.5 mr-0.5">Me</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
              </svg>
            </div>
          </div>
        </div>
      </header>
    </div>
    <!--        header end here-->
    <div class="w-full bg-gray-100 py-20">
      <div class="mx-auto" style="max-width: 1150px">
        <div class="grid grid-cols-6 gap-8">
          <div class="col-span-2 h-full relative">
            <div class="sticky top-20">
              <button v-on:click="toggleTab(1)" :class="{'bg-white border border-gray-200 ring-2 ring-offset-2 ring-indigo-500' : openTab === 1, 'bg-gray-50 border border-gray-200' : openTab !== 1}" class="rounded-lg px-4 py-2.5 flex justify-between items-center w-full">
                <div :class="{'text-blue-600 font-medium' : openTab === 1, 'text-gray-900 font-normal' : openTab !== 1}" class="flex items-center">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 16h-1v-4h-1m1-4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                  </svg>
                  <div style="font-size: 15px">Basic Information</div>
                </div>
                <svg v-if="openTab === 2 || openTab === 3 || openTab === 4 || openTab === 5 || openTab === 6 || openTab === 7 || openTab === 8" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-green-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
              </button>
              <button v-on:click="toggleTab(2)" :class="{'bg-white border border-gray-200 ring-2 ring-offset-2 ring-indigo-500' : openTab === 2, 'bg-gray-50 border border-gray-200' : openTab !== 2}" class="rounded-lg px-4 py-2.5 my-3.5 flex justify-between items-center w-full">
                <div :class="{'text-blue-600 font-medium' : openTab === 2, 'text-gray-900 font-normal' : openTab !== 2}" class="flex items-center">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                  </svg>
                  <div style="font-size: 15px">Project's Preference</div>
                </div>
                <svg v-if="openTab === 3 || openTab === 4 || openTab === 5 || openTab === 6 || openTab === 7 || openTab === 8" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-green-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
              </button>
              <button v-on:click="toggleTab(3)" :class="{'bg-white border border-gray-200 ring-2 ring-offset-2 ring-indigo-500' : openTab === 3, 'bg-gray-50 border border-gray-200' : openTab !== 3}" class="rounded-lg px-4 py-2.5 flex justify-between items-center w-full">
                <div :class="{'text-blue-600 font-medium' : openTab === 3, 'text-gray-900 font-normal' : openTab !== 3}" class="flex items-center">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z" />
                  </svg>
                  <div style="font-size: 15px">Privacy</div>
                </div>
                <svg v-if="openTab === 4 || openTab === 5 || openTab === 6 || openTab === 7 || openTab === 8" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-green-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
              </button>
              <button v-on:click="toggleTab(4)" :class="{'bg-white border border-gray-200 ring-2 ring-offset-2 ring-indigo-500' : openTab === 4, 'bg-gray-50 border border-gray-200' : openTab !== 4}" class="rounded-lg px-4 py-2.5 my-3.5 flex justify-between items-center w-full">
                <div :class="{'text-blue-600 font-medium' : openTab === 4, 'text-gray-900 font-normal' : openTab !== 4}" class="flex items-center">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
                  </svg>
                  <div style="font-size: 15px">Methods of communication</div>
                </div>
                <svg v-if="openTab === 5 || openTab === 6 || openTab === 7 || openTab === 8" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-green-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
              </button>
              <button v-on:click="toggleTab(5)" :class="{'bg-white border border-gray-200 ring-2 ring-offset-2 ring-indigo-500' : openTab === 5, 'bg-gray-50 border border-gray-200' : openTab !== 5}" class="rounded-lg px-4 py-2.5 flex justify-between items-center w-full">
                <div :class="{'text-blue-600 font-medium' : openTab === 5, 'text-gray-900 font-normal' : openTab !== 5}" class="flex items-center">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                  </svg>
                  <div style="font-size: 15px">Budget</div>
                </div>
                <svg v-if="openTab === 6 || openTab === 7 || openTab === 8" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-green-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
              </button>
              <button v-on:click="toggleTab(6)" :class="{'bg-white border border-gray-200 ring-2 ring-offset-2 ring-indigo-500' : openTab === 6, 'bg-gray-50 border border-gray-200' : openTab !== 6}" class="rounded-lg px-4 py-2.5 my-3.5 flex justify-between items-center w-full">
                <div :class="{'text-blue-600 font-medium' : openTab === 6, 'text-gray-900 font-normal' : openTab !== 6}" class="flex items-center">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z" />
                  </svg>
                  <div style="font-size: 15px">Working Preference</div>
                </div>
                <svg v-if="openTab === 7 || openTab === 8" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-green-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
              </button>
              <button v-on:click="toggleTab(7)" :class="{'bg-white border border-gray-200 ring-2 ring-offset-2 ring-indigo-500' : openTab === 7, 'bg-gray-50 border border-gray-200' : openTab !== 7}" class="rounded-lg px-4 py-2.5 flex justify-between items-center w-full">
                <div :class="{'text-blue-600 font-medium' : openTab === 7, 'text-gray-900 font-normal' : openTab !== 7}" class="flex items-center">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z" />
                  </svg>
                  <div style="font-size: 15px">Review</div>
                </div>
              </button>
            </div>
          </div>
          <div class="col-span-4">
            <div v-if="openTab === 1" :class="{'block' : openTab === 1, 'hidden' : openTab !== 1}">
              <div class="bg-white rounded-lg pb-5">
                <div class="border-b p-5">
                  <h5 class="text-xl font-semibold">Basic Information</h5>
                </div>
                <div class="py-5 pl-8 pr-12">
                  <div class="w-full flex-col">
                    <div class="text-sm font-normal mb-1">Project Name</div>
                    <textarea class="w-full border border-gray-200 rounded-md"></textarea>
                  </div>
                  <div class="w-full flex-col my-4">
                    <div class="text-sm font-normal mb-1">Start Date</div>
                    <div>
                      <input type="date" class="border border-gray-200 px-4 py-2.5 text-sm font-medium w-full">
                    </div>
                  </div>
                  <div class="w-full flex-col">
                    <div class="text-sm font-normal mb-1">Proposed Completion Date</div>
                    <input type="date" class="border border-gray-200 px-4 py-2.5 text-sm font-medium w-full">
                  </div>

                </div>
              </div>
              <div class="bg-white rounded-lg pb-5 mt-5">
                <div class="border-b p-5">
                  <h5 class="text-lg font-medium">How many experts you want to hire?</h5>
                </div>
                <div class="py-5 pl-8 pr-12">
                  <div class="grid grid-cols-3 gap-5">
                    <div class="h-28 w-full bg-gray-100 rounded-md"></div>
                    <div class="h-28 w-full bg-gray-100 rounded-md"></div>
                  </div>
                </div>
                <div class="flex items-center py-3.5 px-8 border-t border-gray-200">
                  <input type="checkbox" class="h-5 w-5 rounded mr-2">
                  <p class="text-sm font-normal text-gray-600">I want to hire consultant and member both.</p>
                </div>
              </div>
              <div class="bg-white rounded-lg pb-5 mt-5">
                <div class="pl-8 pr-12 py-5">
                  <h5 class="text-lg font-medium mb-1">Select Category</h5>
                  <div class="flex items-center">
                    <input type="text" class="px-5 py-2.5 rounded border border-gray-200 text-sm w-full focus:outline-none" placeholder="Search Category">
                    <button class="bg-blue-500 text-white px-10 focus:outline-none py-2.5 text-sm rounded-md ml-2">Add</button>
                  </div>
                  <div class="flex mt-1 flex-wrap">
                    <div v-for="(item, index) in tableFields"  class="rounded-lg bg-gray-100 px-4 text-center h-7 m-1 flex items-center">
                      <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M12 6v6m0 0v6m0-6h6m-6 0H6" />
                      </svg>
                      <span class="font-medium whitespace-nowrap text-center m-auto leading-tight" style="font-size: 12px">{{item.name}}</span>
                    </div>
                  </div>
                  <button class="text-blue-600 focus:outline-none mt-1 px-2 text-sm font-semibold">See more</button>
                </div>
                <div class="pl-8 pr-12 py-5">
                  <h5 class="text-lg font-medium mb-1">Select Sub Category</h5>
                  <div class="flex items-center">
                    <input type="text" class="px-5 py-2.5 rounded border border-gray-200 text-sm w-full focus:outline-none" placeholder="Search Category">
                    <button class="bg-blue-500 text-white px-10 focus:outline-none py-2.5 text-sm rounded-md ml-2">Add</button>
                  </div>
                  <div class="flex mt-1 flex-wrap">
                    <div v-for="(item, index) in tableFields"  class="rounded-lg bg-gray-100 px-4 text-center h-7 m-1 flex items-center">
                      <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M12 6v6m0 0v6m0-6h6m-6 0H6" />
                      </svg>
                      <span class="font-medium whitespace-nowrap text-center m-auto leading-tight" style="font-size: 12px">{{item.name}}</span>
                    </div>
                  </div>
                  <button class="text-blue-600 focus:outline-none mt-1 px-2 text-sm font-semibold">See more</button>
                </div>
                <div class="pl-8 pr-12 py-5">
                  <h5 class="text-lg font-medium mb-2">Suggested Categories</h5>
                  <div class="text-sm font-normal text-blue-600 cursor-pointer">Architecture & Engineer>3D Architecture</div>
                  <div class="text-sm font-normal text-blue-600 my-2 cursor-pointer">Architecture & Engineer>3D Architecture</div>
                  <div class="text-sm font-normal text-blue-600 cursor-pointer">Architecture & Engineer>3D Architecture</div>
                </div>
                <div class="pl-8 pr-12 py-5">
                  <h5 class="text-lg font-medium mb-1">Select Skills</h5>
                  <div class="flex items-center">
                    <input type="text" class="px-5 py-2.5 rounded border border-gray-200 text-sm w-full focus:outline-none" placeholder="Search Skills/Knowledge">
                    <button class="bg-blue-500 text-white px-10 focus:outline-none py-2.5 text-sm rounded-md ml-2">Add</button>
                  </div>
                  <div class="flex mt-1 flex-wrap">
                    <div v-for="(item, index) in Skills"  class="rounded-lg bg-gray-100 px-4 text-center h-7 m-1 flex items-center">
                      <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M12 6v6m0 0v6m0-6h6m-6 0H6" />
                      </svg>
                      <span class="font-medium whitespace-nowrap text-center m-auto leading-tight" style="font-size: 12px">{{item.name}}</span>
                    </div>
                  </div>
                  <button class="text-blue-600 focus:outline-none mt-1 px-2 text-sm font-semibold">See more</button>
                </div>
              </div>
              <div class="bg-white rounded-lg pb-5 mt-5">
                <div class="pl-8 pr-12 py-5">
                  <h5 class="text-lg font-medium mb-1">Add Objectives</h5>
                  <div class="flex items-center">
                    <input type="text" class="px-5 py-2.5 rounded border border-gray-200 text-sm w-full focus:outline-none" placeholder="Search (Auto full fill format)">
                    <button class="bg-blue-500 text-white px-10 focus:outline-none py-2.5 text-sm rounded-md ml-2">Add</button>
                  </div>
                  <div class="flex mt-1 flex-wrap">
                    <div v-for="(item, index) in tableFields"  class="rounded-lg bg-gray-100 px-4 text-center h-7 m-1 flex items-center">
                      <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M12 6v6m0 0v6m0-6h6m-6 0H6" />
                      </svg>
                      <span class="font-medium whitespace-nowrap text-center m-auto leading-tight" style="font-size: 12px">{{item.name}}</span>
                    </div>
                  </div>
                  <button class="text-blue-600 focus:outline-none mt-1 px-2 text-sm font-semibold">See more</button>
                </div>
                <div class="pl-8 pr-12 py-5">
                  <h5 class="text-lg font-medium mb-1">Add Deliverables</h5>
                  <div class="flex items-center">
                    <input type="text" class="px-5 py-2.5 rounded border border-gray-200 text-sm w-full focus:outline-none" placeholder="Search (Auto full fill format)">
                    <button class="bg-blue-500 text-white px-10 focus:outline-none py-2.5 text-sm rounded-md ml-2">Add</button>
                  </div>
                  <div class="flex mt-1 flex-wrap">
                    <div v-for="(item, index) in tableFields"  class="rounded-lg bg-gray-100 px-4 text-center h-7 m-1 flex items-center">
                      <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M12 6v6m0 0v6m0-6h6m-6 0H6" />
                      </svg>
                      <span class="font-medium whitespace-nowrap text-center m-auto leading-tight" style="font-size: 12px">{{item.name}}</span>
                    </div>
                  </div>
                  <button class="text-blue-600 focus:outline-none mt-1 px-2 text-sm font-semibold">See more</button>
                </div>
              </div>
              <div class="bg-white rounded-lg pb-5 mt-5">
                <div class="pl-8 pr-12 py-5">
                  <h5 class="text-lg font-medium mb-1">Brief Description</h5>
                  <textarea class="border border-gray-200 rounded-lg px-5 py-3 text-sm font-normal w-full focus:outline-none"></textarea>
                </div>
                <div class="pl-8 pr-12 py-5">
                  <h5 class="text-lg font-medium mb-1">Add Deliverables</h5>
                  <div class="h-20 w-full border-2 border-dashed flex items-center justify-center rounded-lg">
                    <div>
                      <input type="file">
                    </div>
                  </div>
                </div>
                <div class="pl-8 pr-12 py-5">
                  <h5 class="text-lg font-medium mb-1">Any other Requirement (optional)</h5>
                  <textarea class="border border-gray-200 rounded-lg px-5 py-3 text-sm font-normal w-full focus:outline-none"></textarea>
                </div>
              </div>
              <div class="bg-white rounded-lg pb-5 mt-5">
                <div class="pl-8 pr-12 py-5">
                  <h5 class="text-xl font-semibold mb-1">Screening Questions (optional)</h5>
                  <p class="text-xs font-normal text-gray-500">Lorem ipsum dolor site amet de costa.</p>
                </div>
                <div class="pl-8 pr-12 py-3">
                  <button class="flex items-center text-blue-600 text-sm font-semibold focus:outline-none">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6v6m0 0v6m0-6h6m-6 0H6" />
                    </svg>
                    <span class="ml-2 ">Add Questions</span>
                  </button>
                  <div class="flex items-center my-2.5">
                    <input type="text" class="text-sm font-normal text-gray-900 border border-gray-200 focus:outline-none px-4 py-2.5 w-full rounded-md" placeholder="Do you have any questions about job description?">
                    <div>
                      <button class="focus:outline-none text-gray-600 ml-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 14l2-2m0 0l2-2m-2 2l-2-2m2 2l2 2m7-2a9 9 0 11-18 0 9 9 0 0118 0z" />
                        </svg>
                      </button>
                    </div>
                  </div>
                  <div class="flex items-center">
                    <input type="text" class="text-sm font-normal text-gray-900 border border-gray-200 focus:outline-none px-4 py-2.5 w-full rounded-md" placeholder="Do you have any questions about job description?">
                    <div>
                      <button class="focus:outline-none text-gray-600 ml-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 14l2-2m0 0l2-2m-2 2l-2-2m2 2l2 2m7-2a9 9 0 11-18 0 9 9 0 0118 0z" />
                        </svg>
                      </button>
                    </div>
                  </div>
                </div>
                <div class="flex items-center py-3.5 px-8 border-t border-gray-200">
                  <input type="checkbox" class="h-5 w-5 rounded mr-2">
                  <p class="text-sm font-normal text-gray-600">Yes, require a cover letter from experts</p>
                </div>
                <div class="border-t border-gray-200 py-3.5 px-8 flex items-center">
                  <button class="bg-gray-50 text-gray-900 px-6 py-3 text-sm font-medium focus:outline-none rounded border">Save</button>
                  <button class="bg-gray-100 text-gray-900 px-6 py-3 text-sm font-medium focus:outline-none mx-3 rounded border border-gray-200">Back</button>
                  <button class="bg-blue-500 text-white px-6 py-3 text-sm font-medium focus:outline-none rounded">Next</button>
                </div>
              </div>
            </div>
            <div v-if="openTab === 2" :class="{'block' : openTab === 2, 'hidden' : openTab !== 2}">
              <div class="bg-white rounded-lg pb-5">
                <div class="border-b p-5">
                  <h5 class="text-xl font-semibold">Project's Preference (optional)</h5>
                </div>
                <div class="py-5 pl-8 pr-12">
                  <div class="text-lg font-medium mb-3">Level of Expertise</div>
                  <div v-for="(item, index) in Expertise" class="flex items-center my-2">
                    <input type="radio" class="h-5 w-5 mr-2">
                    <div class="text-sm font-normal text-gray-900">{{item.name}}</div>
                  </div>
                  <div class="mt-7">
                    <div class="text-lg font-medium mb-1">Add Regions/Countries</div>
                    <div class="relative">
                      <input type="text" class="px-5 py-2.5 rounded border border-gray-200 text-sm w-full focus:outline-none" placeholder="Search Location">
                      <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 absolute top-2.5 right-4 text-blue-500" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd" />
                      </svg>
                    </div>
                  </div>
                </div>
              </div>
              <div class="bg-white rounded-lg pb-5 mt-5">
                <div class="pl-8 pr-12 py-5">
                  <h5 class="text-lg font-medium mb-1">Other Languages</h5>
                  <div class="flex items-center mt-5">
                    <input type="text" class="px-5 py-2.5 rounded border border-gray-200 text-sm w-1/2 focus:outline-none" placeholder="Search Category">
                    <select class="px-5 py-2.5 rounded border border-gray-200 text-sm w-1/2 focus:outline-none mx-2.5">
                      <option selected>Any Level</option>
                      <option>Conversational Level</option>
                      <option>Fluent or Better</option>
                      <option>Native or Billingual</option>
                    </select>
                    <button class="bg-blue-500 text-white px-10 focus:outline-none py-2.5 text-sm rounded-md">Add</button>
                  </div>
                  <div class="flex mt-1 flex-wrap">
                    <div class="rounded-md bg-gray-100 px-4 text-center h-7 m-1 flex items-center">
                      <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 cursor-pointer mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                      </svg>
                      <span class="font-medium whitespace-nowrap text-center m-auto leading-tight" style="font-size: 12px">English - <span class="font-light">Fluent</span> </span>
                    </div>
                    <div class="rounded-md bg-gray-100 px-4 text-center h-7 m-1 flex items-center">
                      <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 cursor-pointer mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                      </svg>
                      <span class="font-medium whitespace-nowrap text-center m-auto leading-tight" style="font-size: 12px">English - <span class="font-light">Fluent</span> </span>
                    </div>
                    <div class="rounded-md bg-gray-100 px-4 text-center h-7 m-1 flex items-center">
                      <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 cursor-pointer mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                      </svg>
                      <span class="font-medium whitespace-nowrap text-center m-auto leading-tight" style="font-size: 12px">English - <span class="font-light">Fluent</span> </span>
                    </div>
                  </div>
                </div>
                <div class="border-t border-gray-200 py-4 px-8 flex items-center">
                  <button class="bg-gray-50 text-gray-900 px-6 py-3 text-sm font-medium focus:outline-none rounded border">Save</button>
                  <button class="bg-gray-100 text-gray-900 px-6 py-3 text-sm font-medium focus:outline-none mx-3 rounded border border-gray-200">Back</button>
                  <button class="bg-blue-500 text-white px-6 py-3 text-sm font-medium focus:outline-none rounded">Next</button>
                </div>
              </div>

            </div>
            <div v-if="openTab === 3" :class="{'block' : openTab === 3, 'hidden' : openTab !== 3}">
              <div class="bg-white rounded-lg pb-5">
                <div class="border-b p-5">
                  <h5 class="text-xl font-semibold">Privacy</h5>
                </div>
                <div class="py-5 pl-8 pr-12">
                  <div class="h-24"></div>
                  <div class="text-7xl font-semibold text-center">Under Construction</div>
                  <div class="h-36"></div>
                </div>
                <div class="border-t border-gray-200 py-4 px-8 flex items-center">
                  <button class="bg-gray-50 text-gray-900 px-6 py-3 text-sm font-medium focus:outline-none rounded border">Save</button>
                  <button class="bg-gray-100 text-gray-900 px-6 py-3 text-sm font-medium focus:outline-none mx-3 rounded border border-gray-200">Back</button>
                  <button class="bg-blue-500 text-white px-6 py-3 text-sm font-medium focus:outline-none rounded">Next</button>
                </div>
              </div>

            </div>
            <div v-if="openTab === 4" :class="{'block' : openTab === 4, 'hidden' : openTab !== 4}">
              <div class="bg-white rounded-lg pb-5">
                <div class="border-b p-5">
                  <h5 class="text-xl font-semibold">Methods of Communication</h5>
                </div>
                <div class="py-5">
                  <div class="py-3.5 border-b border-gray-200 flex items-center justify-between px-8">
                    <div class="flex items-center">
                      <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-gray-700" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z" />
                      </svg>
                      <div class="font-normal text-base font-gray-900 ml-3">Messaging</div>
                    </div>
                  </div>
                  <div class="py-3.5 border-b border-gray-200 flex items-center justify-between px-8">
                    <div class="flex items-center">
                      <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-gray-700" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 3l-6 6m0 0V4m0 5h5M5 3a2 2 0 00-2 2v1c0 8.284 6.716 15 15 15h1a2 2 0 002-2v-3.28a1 1 0 00-.684-.948l-4.493-1.498a1 1 0 00-1.21.502l-1.13 2.257a11.042 11.042 0 01-5.516-5.517l2.257-1.128a1 1 0 00.502-1.21L9.228 3.683A1 1 0 008.279 3H5z" />
                      </svg>
                      <div class="font-normal text-base font-gray-900 ml-3">Audio</div>
                    </div>
                  </div>
                  <div class="py-3.5 flex items-center justify-between px-8">
                    <div class="flex items-center">
                      <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-gray-700" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 10l4.553-2.276A1 1 0 0121 8.618v6.764a1 1 0 01-1.447.894L15 14M5 18h8a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v8a2 2 0 002 2z" />
                      </svg>
                      <div class="font-normal text-base font-gray-900 ml-3">Messaging</div>
                    </div>
                  </div>
                </div>
                <div class="border-t border-gray-200 py-4 px-8 flex items-center">
                  <button class="bg-gray-50 text-gray-900 px-6 py-3 text-sm font-medium focus:outline-none rounded border">Save</button>
                  <button class="bg-gray-100 text-gray-900 px-6 py-3 text-sm font-medium focus:outline-none mx-3 rounded border border-gray-200">Back</button>
                  <button class="bg-blue-500 text-white px-6 py-3 text-sm font-medium focus:outline-none rounded">Next</button>
                </div>
              </div>

            </div>
            <div v-if="openTab === 5" :class="{'block' : openTab === 5, 'hidden' : openTab !== 5}">
              <div class="bg-white rounded-lg pb-5">
                <div class="border-b p-5">
                  <h5 class="text-xl font-semibold">Budgets</h5>
                </div>
                <div class="py-5 pl-8 pr-12">
                  <div class="h-24"></div>
                  <div class="text-7xl font-semibold text-center">Under Construction</div>
                  <div class="h-36"></div>
                </div>
                <div class="border-t border-gray-200 py-4 px-8 flex items-center">
                  <button class="bg-gray-50 text-gray-900 px-6 py-3 text-sm font-medium focus:outline-none rounded border">Save</button>
                  <button class="bg-gray-100 text-gray-900 px-6 py-3 text-sm font-medium focus:outline-none mx-3 rounded border border-gray-200">Back</button>
                  <button class="bg-blue-500 text-white px-6 py-3 text-sm font-medium focus:outline-none rounded">Next</button>
                </div>
              </div>

            </div>
            <div v-if="openTab === 6" :class="{'block' : openTab === 6, 'hidden' : openTab !== 6}">
              <div class="bg-white rounded-lg pb-5">
                <div class="border-b p-5">
                  <h5 class="text-xl font-semibold">Working Preference (optional)</h5>
                </div>
                <div class="py-5 pl-8 pr-12">
                  <div class="text-lg font-medium mb-2">Please select how the work will be undertaken</div>
                  <div v-for="(item, index) in work" class="flex items-center py-3 border-b border-gray-200">
                    <input type="checkbox" class="h-5 w-5 mr-2 rounded">
                    <div class="text-sm font-normal text-gray-900">{{item.name}}</div>
                  </div>
                </div>
                <div class="py-5 pl-8 pr-12">
                  <div class="text-lg font-medium mb-2">Please select how the work will be undertaken</div>
                </div>
                <div class="border-t border-gray-200 py-4 px-8 flex items-center">
                  <button class="bg-gray-50 text-gray-900 px-6 py-3 text-sm font-medium focus:outline-none rounded border">Save</button>
                  <button class="bg-gray-100 text-gray-900 px-6 py-3 text-sm font-medium focus:outline-none mx-3 rounded border border-gray-200">Back</button>
                  <button class="bg-blue-500 text-white px-6 py-3 text-sm font-medium focus:outline-none rounded">Next</button>
                </div>
              </div>
            </div>
            <div v-if="openTab === 7" :class="{'block' : openTab === 7, 'hidden' : openTab !== 7}">
              <div class="bg-white rounded-lg pb-5">
                <div class="border-b px-5 py-2.5 flex items-center justify-between">
                  <h5 class="text-xl font-semibold">Review and Submit</h5>
                  <button class="bg-blue-500 text-white px-6 py-3 text-sm font-medium focus:outline-none rounded">Submit Project</button>
                </div>
                <div class="py-5 pl-8 pr-12">
                  <div class="">
                    <div class="flex items-center mb-3 justify-between">
                      <div class="text-lg font-semibold mb-2">Basic Information</div>
                      <button class="h-8 w-8 rounded-full bg-blue-400 flex hover:bg-blue-500">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 m-auto text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15.232 5.232l3.536 3.536m-2.036-5.036a2.5 2.5 0 113.536 3.536L6.5 21.036H3v-3.572L16.732 3.732z" />
                        </svg>
                      </button>
                    </div>
                    <div class="grid grid-cols-2 gap-5">
                      <div>
                        <h6 class="text-sm font-medium text-gray-400 mb-1">Project Title</h6>
                        <p class="text-sm font-normal">2D and 3D Rendering</p>
                      </div>
                      <div>
                        <h6 class="text-sm font-medium text-gray-400 mb-1">Start Date</h6>
                        <p class="text-sm font-normal">December 22, 2020</p>
                      </div>
                      <div>
                        <h6 class="text-sm font-medium text-gray-400 mb-1">Proposed Completion Date</h6>
                        <p class="text-sm font-normal">Within 4 months</p>
                      </div>

                    </div>
                  </div>
                  <div class="border-b border-dashed border-gray-200 my-3.5"></div>
                  <div class="">
                    <h6 class="text-lg font-medium mb-2">How many Employees you want to hire?</h6>
                    <div class="pb-5">
                      <span class="text-sm font-medium text-gray-400 mb-1">Number of Employees you want to hire?</span>
                      <p class="text-sm font-normal">5</p>
                    </div>
                  </div>
                  <div class="border-b border-dashed border-gray-200 my-3.5"></div>
                  <div class="">
                    <h6 class="text-lg font-medium mb-2">About Categories and Skills</h6>
                    <div class="pb-5">
                      <div>
                        <span class="text-sm font-medium text-gray-400 mb-0.5">Category</span>
                        <div class="flex flex-wrap">
                          <div class="rounded-full bg-gray-100 px-4 text-center h-7 m-1 flex items-center">
                            <span class="font-medium whitespace-nowrap text-center m-auto leading-tight" style="font-size: 13px">Architecture and Engineering</span>
                          </div>
                        </div>
                      </div>
                      <div class="mt-6">
                        <span class="text-sm font-medium text-gray-400 mb-0.5">Sub Category</span>
                        <div class="flex flex-wrap">
                          <div v-for="(item, index) in SubCategory" class="rounded-full bg-gray-100 px-4 text-center h-7 m-1 flex items-center">
                            <span class="font-medium whitespace-nowrap text-center m-auto leading-tight" style="font-size: 13px">{{item.name}}</span>
                          </div>
                          <div class="rounded-full bg-gray-100 px-4 text-center h-7 m-1 flex items-center">
                            <span class="font-medium whitespace-nowrap text-center m-auto leading-tight" style="font-size: 13px">Architecture and Engineering</span>
                          </div>
                        </div>
                      </div>
                      <div class="mt-6">
                        <span class="text-sm font-medium text-gray-400 mb-0.5">Skills</span>
                        <div class="flex flex-wrap">
                          <div v-for="(item, index) in SubCategory" class="rounded-full bg-gray-100 px-4 text-center h-7 m-1 flex items-center">
                            <span class="font-medium whitespace-nowrap text-center m-auto leading-tight" style="font-size: 13px">{{item.name}}</span>
                          </div>
                          <div class="rounded-full bg-gray-100 px-4 text-center h-7 m-1 flex items-center">
                            <span class="font-medium whitespace-nowrap text-center m-auto leading-tight" style="font-size: 13px">Architecture and Engineering</span>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="border-b border-dashed border-gray-200 my-3.5"></div>
                  <div class="">
                    <h6 class="text-lg font-medium mb-2">About Objectives and Deliverables</h6>
                    <div class="pb-5">
                      <div class="">
                        <span class="text-sm font-medium text-gray-400 mb-0.5">Objectives</span>
                        <div class="flex flex-wrap">
                          <div v-for="(item, index) in SubCategory" class="rounded-full bg-gray-100 px-4 text-center h-7 m-1 flex items-center">
                            <span class="font-medium whitespace-nowrap text-center m-auto leading-tight" style="font-size: 13px">{{item.name}}</span>
                          </div>
                          <div class="rounded-full bg-gray-100 px-4 text-center h-7 m-1 flex items-center">
                            <span class="font-medium whitespace-nowrap text-center m-auto leading-tight" style="font-size: 13px">Architecture and Engineering</span>
                          </div>
                        </div>
                      </div>
                      <div class="mt-6">
                        <span class="text-sm font-medium text-gray-400 mb-0.5">Deliverables</span>
                        <div class="flex flex-wrap">
                          <div v-for="(item, index) in SubCategory" class="rounded-full bg-gray-100 px-4 text-center h-7 m-1 flex items-center">
                            <span class="font-medium whitespace-nowrap text-center m-auto leading-tight" style="font-size: 13px">{{item.name}}</span>
                          </div>
                          <div class="rounded-full bg-gray-100 px-4 text-center h-7 m-1 flex items-center">
                            <span class="font-medium whitespace-nowrap text-center m-auto leading-tight" style="font-size: 13px">Architecture and Engineering</span>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="border-b border-dashed border-gray-200 my-3.5"></div>
                  <div class="">
                    <h6 class="text-lg font-medium mb-2">Project Description and Attachments</h6>
                    <div class="pb-5">
                      <div class="">
                        <span class="text-sm font-medium text-gray-400 mb-0.5">Descriptions</span>
                        <p class="text-sm font-normal">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </p>
                      </div>
                      <div class="mt-6">
                        <span class="text-sm font-medium text-gray-400 mb-0.5">Documents & Attachments (6 Attachments)</span>
                        <div v-for="item in 6" :key="item" class="bg-gray-100 rounded-md p-1 w-48 flex items-center my-0.5">
                          <img class="h-8 w-auto mr-2" src="https://images.unsplash.com/photo-1634660246958-868f05ccaf3a?ixid=MnwxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHwyNHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60">
                          <p class="text-sm font-normal">IMG235467575.JPG</p>
                        </div>
                      </div>
                      <div class="mt-6">
                        <span class="text-sm font-medium text-gray-400 mb-0.5">Any other Requirements (optional)</span>
                        <p class="text-sm font-normal">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </p>
                      </div>
                    </div>
                  </div>
                  <div class="border-b border-dashed border-gray-200 my-3.5"></div>
                  <div class="">
                    <h6 class="text-lg font-medium mb-4">Screening Questions</h6>
                    <div class="pb-5">
                      <div v-for="item in 3" :key="item" class="my-1.5 h-10 w-full rounded-lg border border-gray-200 flex items-center px-4">
                        <p class="text-sm font-normal text-gray-800">Do you have suggestions to make this project run successfully?</p>
                      </div>
                    </div>
                  </div>
                  <div class="border-b border-dashed border-gray-200 my-3.5"></div>
                  <div class="">
                    <h6 class="text-lg font-medium mb-4">Expert's Preferences</h6>
                    <div class="pb-5">
                      <div class="flex items-center my-2">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-blue-500 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                        </svg>
                        <p class="text-sm font-normal text-gray-800">Yes, require a cover letter from experts</p>
                      </div>
                      <div class="flex items-center my-2">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-blue-500 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                        </svg>
                        <p class="text-sm font-normal text-gray-800">Require Local Expert from <span class="text-blue-500">Delhi, India</span></p>
                      </div>
                      <div class="flex items-center my-2">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-blue-500 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                        </svg>
                        <p class="text-sm font-normal text-gray-800">I want to hire Consultant and Member both</p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="bg-white rounded-lg pb-5 mt-5">
                <div class="border-b px-5 py-4 flex items justify-between">
                  <h5 class="text-xl font-semibold">Project's Preferences (optional)</h5>
                  <button class="h-8 w-8 rounded-full bg-blue-400 flex hover:bg-blue-500">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 m-auto text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15.232 5.232l3.536 3.536m-2.036-5.036a2.5 2.5 0 113.536 3.536L6.5 21.036H3v-3.572L16.732 3.732z" />
                    </svg>
                  </button>
                </div>
                <div class="py-5 pl-8 pr-12">
                  <div class="">
                    <div>
                      <h6 class="text-sm font-medium text-gray-400 mb-1">Level of Expertise</h6>
                      <p class="text-sm font-normal">Intermediate</p>
                    </div>
                    <div class="my-6">
                      <h6 class="text-sm font-medium text-gray-400 mb-1">Location/Region</h6>
                      <p class="text-sm font-normal">New York City, NY, USA</p>
                    </div>
                    <div>
                      <h6 class="text-sm font-medium text-gray-400 mb-1">Project Success Score</h6>
                      <p class="text-sm font-normal">20% - 60%</p>
                    </div>
                    <div class="my-6">
                      <h6 class="text-sm font-medium text-gray-400 mb-1">Earn Amount</h6>
                      <p class="text-sm font-normal">10k+ earned</p>
                    </div>
                    <div>
                      <h6 class="text-sm font-medium text-gray-400 mb-1">English Level</h6>
                      <p class="text-sm font-normal">Conversational Level</p>
                    </div>
                    <div class="my-6">
                      <h6 class="text-sm font-medium text-gray-400 mb-1">Other Languages</h6>
                      <div class="flex flex-wrap">
                        <div class="rounded-md bg-gray-100 px-4 text-center h-7 m-1 flex items-center">
                          <span class="font-medium whitespace-nowrap text-center m-auto leading-tight" style="font-size: 12px">English - <span class="font-light">Fluent</span> </span>
                        </div>
                        <div class="rounded-md bg-gray-100 px-4 text-center h-7 m-1 flex items-center">
                          <span class="font-medium whitespace-nowrap text-center m-auto leading-tight" style="font-size: 12px">English - <span class="font-light">Fluent</span> </span>
                        </div>
                        <div class="rounded-md bg-gray-100 px-4 text-center h-7 m-1 flex items-center">
                          <span class="font-medium whitespace-nowrap text-center m-auto leading-tight" style="font-size: 12px">English - <span class="font-light">Fluent</span> </span>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="bg-white rounded-lg pb-5 mt-5">
                <div class="border-b px-5 py-4 flex items justify-between">
                  <h5 class="text-xl font-semibold">Project's Privacy</h5>
                  <button class="h-8 w-8 rounded-full bg-blue-400 flex hover:bg-blue-500">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 m-auto text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15.232 5.232l3.536 3.536m-2.036-5.036a2.5 2.5 0 113.536 3.536L6.5 21.036H3v-3.572L16.732 3.732z" />
                    </svg>
                  </button>
                </div>
                <div class="py-5 pl-8 pr-12">
                  <div class="">
                    <div>
                      <h6 class="text-sm font-medium text-gray-400 mb-1">Project Privacy</h6>
                      <div class="flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2 text-gray-600" viewBox="0 0 20 20" fill="currentColor">
                          <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zM4.332 8.027a6.012 6.012 0 011.912-2.706C6.512 5.73 6.974 6 7.5 6A1.5 1.5 0 019 7.5V8a2 2 0 004 0 2 2 0 011.523-1.943A5.977 5.977 0 0116 10c0 .34-.028.675-.083 1H15a2 2 0 00-2 2v2.197A5.973 5.973 0 0110 16v-2a2 2 0 00-2-2 2 2 0 01-2-2 2 2 0 00-1.668-1.973z" clip-rule="evenodd" />
                        </svg>
                        <p class="text-sm font-normal">Public</p>

                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="bg-white rounded-lg pb-5 mt-5">
                <div class="border-b px-5 py-4 flex items justify-between">
                  <h5 class="text-xl font-semibold">Methods of Communication</h5>
                  <button class="h-8 w-8 rounded-full bg-blue-400 flex hover:bg-blue-500">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 m-auto text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15.232 5.232l3.536 3.536m-2.036-5.036a2.5 2.5 0 113.536 3.536L6.5 21.036H3v-3.572L16.732 3.732z" />
                    </svg>
                  </button>
                </div>
                <div class="py-5 pl-8 pr-12">
                  <div class="">
                    <div>
                      <h6 class="text-sm font-medium text-gray-400 mb-1">Methods of Communication</h6>
                      <div class="flex items-center mt-3">
                        <svg data-v-0fc77766="" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="h-5 w-5 mr-2 text-gray-600"><path data-v-0fc77766="" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z"></path></svg>
                        <p class="text-sm font-normal">Messaging</p>
                      </div>
                      <div class="flex items-center mt-2.5">
                        <svg data-v-0fc77766="" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="h-5 w-5 mr-2 text-gray-600"><path data-v-0fc77766="" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 3l-6 6m0 0V4m0 5h5M5 3a2 2 0 00-2 2v1c0 8.284 6.716 15 15 15h1a2 2 0 002-2v-3.28a1 1 0 00-.684-.948l-4.493-1.498a1 1 0 00-1.21.502l-1.13 2.257a11.042 11.042 0 01-5.516-5.517l2.257-1.128a1 1 0 00.502-1.21L9.228 3.683A1 1 0 008.279 3H5z"></path></svg>
                        <p class="text-sm font-normal">Audio</p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="bg-white rounded-lg pb-5 mt-5">
                <div class="border-b px-5 py-4 flex items justify-between">
                  <h5 class="text-xl font-semibold">Budget</h5>
                  <button class="h-8 w-8 rounded-full bg-blue-400 flex hover:bg-blue-500">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 m-auto text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15.232 5.232l3.536 3.536m-2.036-5.036a2.5 2.5 0 113.536 3.536L6.5 21.036H3v-3.572L16.732 3.732z" />
                    </svg>
                  </button>
                </div>
                <div class="py-5 pl-8 pr-12">
                  <div class="">
                    <div>
                      <h6 class="text-sm font-medium text-gray-400 mb-1">Pay by</h6>
                      <p class="text-sm font-normal">Pay by the hour</p>
                    </div>
                    <div class="my-6">
                      <h6 class="text-sm font-medium text-gray-400 mb-1">Currency</h6>
                      <p class="text-sm font-normal">USD</p>
                    </div>
                    <div>
                      <h6 class="text-sm font-medium text-gray-400 mb-1">Minimum Amount</h6>
                      <p class="text-sm font-normal">$24/hr</p>
                    </div>
                    <div class="my-6">
                      <h6 class="text-sm font-medium text-gray-400 mb-1">Maximum Amount</h6>
                      <p class="text-sm font-normal">$25/hr</p>
                    </div>
                    <div>
                      <h6 class="text-sm font-medium text-gray-400 mb-1">Maximum Working Hours</h6>
                      <p class="text-sm font-normal">8 Hours</p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="bg-white rounded-lg pb-5 mt-5">
                <div class="border-b px-5 py-4 flex items justify-between">
                  <h5 class="text-xl font-semibold">Working Preferences</h5>
                  <button class="h-8 w-8 rounded-full bg-blue-400 flex hover:bg-blue-500">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 m-auto text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15.232 5.232l3.536 3.536m-2.036-5.036a2.5 2.5 0 113.536 3.536L6.5 21.036H3v-3.572L16.732 3.732z" />
                    </svg>
                  </button>
                </div>
                <div class="py-5 pl-8 pr-12">
                  <div class="">
                    <div>
                      <h6 class="text-sm font-medium text-gray-400 mb-1">How the work will be undertaken</h6>
                      <p class="text-sm font-normal">Online Only</p>
                    </div>
                    <div class="my-6">
                      <h6 class="text-sm font-medium text-gray-400 mb-1">In what capacity are you looking to employee professionals?</h6>
                      <p class="text-sm font-normal">Full time</p>
                    </div>
                  </div>
                </div>
                <div class="border-t border-gray-200 py-3.5 px-8 flex items-center">
                  <button class="bg-gray-100 text-gray-900 px-6 py-3 text-sm font-medium focus:outline-none mr-3 rounded border border-gray-200">Save & Exit</button>
                  <button class="bg-blue-500 text-white px-6 py-3 text-sm font-medium focus:outline-none rounded">Submit Project</button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: "job-form",
  data(){
    return{
      openTab: 7,
      start_date: '',
      completion_date: '',
      formatter : {
        date: 'YYYY-MM-DD',
        month: 'MMM'
      },
      tableFields:[
        {name:'Architecture & Engineer'},
        {name:'Education'},
        {name:'Business'},
        {name:'Graphic Designing'},
        {name:'Architecture & Engineer'},
        {name:'Education'},
        {name:'Business'},

      ],
      Skills:[
        {name:'Wordpress/Website'},
        {name:'UI/UX'},
        {name:'HTML/CSS/JS'},
        {name:'Angular.js'},
        {name:'Python'},
        {name:'Full Stack Developer'},
        {name:'Php and React'},
      ],
      Expertise:[
        {name:'Rising'},
        {name:'Intermediate'},
        {name:'Expert'},
        {name:'Rising And Intermediate both'},
        {name:'Intermediate and Expert both'},
        {name:'Rising and Expert both'},
        {name:'All'},
      ],
      work:[
        {name:'Online Only'},
        {name:'in Person'},
        {name:'Online or In Person'},
        {name:'Availability to travel to other cities'},
      ],
      SubCategory:[
        {name:'Architecture'},
        {name:'2D & 3D'},
        {name:'Landscape Designing'},
        {name:'2BHK'},
        {name:'3BHK'},
        {name:'2D & 3D Rendering'},
      ],
      plans:[
        {
          name: 'Startup',
          ram: '12GB',
          cpus: '6 CPUs',
          disk: '160 GB SSD disk',
        },
        {
          name: 'Business',
          ram: '16GB',
          cpus: '8 CPUs',
          disk: '512 GB SSD disk',
        },
        {
          name: 'Enterprise',
          ram: '32GB',
          cpus: '12 CPUs',
          disk: '1024 GB SSD disk',
        },
      ]
    }
  },
  methods:{
    toggleTab(Number){
      this.openTab = Number
    }
  }
}
</script>

<style scoped>

</style>
