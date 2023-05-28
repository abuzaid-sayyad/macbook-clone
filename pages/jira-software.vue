<template>
  <div class="bg-white relative">
    <nav class="bg-white fixed top-0 shadow w-full" style="height: 56px;}">
      <div class="px-3 h-full flex justify-between items-center w-full">
        <div class="flex items-center">
          <div class="justify-center hover:text-blue-500 hover:bg-blue-100 rounded-full p-2 text-center">

            <svg width="24" height="24" viewBox="0 0 24 24" role="presentation"><path fill="currentColor" fill-rule="evenodd" d="M4 5.01C4 4.451 4.443 4 5.01 4h1.98C7.549 4 8 4.443 8 5.01v1.98C8 7.549 7.557 8 6.99 8H5.01C4.451 8 4 7.557 4 6.99V5.01zm0 6c0-.558.443-1.01 1.01-1.01h1.98c.558 0 1.01.443 1.01 1.01v1.98C8 13.549 7.557 14 6.99 14H5.01C4.451 14 4 13.557 4 12.99v-1.98zm6-6c0-.558.443-1.01 1.01-1.01h1.98c.558 0 1.01.443 1.01 1.01v1.98C14 7.549 13.557 8 12.99 8h-1.98C10.451 8 10 7.557 10 6.99V5.01zm0 6c0-.558.443-1.01 1.01-1.01h1.98c.558 0 1.01.443 1.01 1.01v1.98c0 .558-.443 1.01-1.01 1.01h-1.98c-.558 0-1.01-.443-1.01-1.01v-1.98zm6-6c0-.558.443-1.01 1.01-1.01h1.98c.558 0 1.01.443 1.01 1.01v1.98C20 7.549 19.557 8 18.99 8h-1.98C16.451 8 16 7.557 16 6.99V5.01zm0 6c0-.558.443-1.01 1.01-1.01h1.98c.558 0 1.01.443 1.01 1.01v1.98c0 .558-.443 1.01-1.01 1.01h-1.98c-.558 0-1.01-.443-1.01-1.01v-1.98zm-12 6c0-.558.443-1.01 1.01-1.01h1.98c.558 0 1.01.443 1.01 1.01v1.98C8 19.549 7.557 20 6.99 20H5.01C4.451 20 4 19.557 4 18.99v-1.98zm6 0c0-.558.443-1.01 1.01-1.01h1.98c.558 0 1.01.443 1.01 1.01v1.98c0 .558-.443 1.01-1.01 1.01h-1.98c-.558 0-1.01-.443-1.01-1.01v-1.98zm6 0c0-.558.443-1.01 1.01-1.01h1.98c.558 0 1.01.443 1.01 1.01v1.98c0 .558-.443 1.01-1.01 1.01h-1.98c-.558 0-1.01-.443-1.01-1.01v-1.98z"></path></svg>

          </div>
          <div class="flex px-1 py-1 self-center text-sm font-medium text-gray-800 antialiased rounded-md focus:outline-none hover:bg-blue-100 hover:text-blue-500 focus:bg-blue-100">
              <span style="display: flex;max-height: 24px;max-width: 260px;color: rgb(38, 132, 255);fill: rgb(37, 56, 88);height: 32px;position: relative;user-select: none;" aria-label="Jira Software" role="img">
                <svg viewBox="0 0 179 32" xmlns="http://www.w3.org/2000/svg" focusable="false" aria-hidden="true">
                  <defs>
                    <linearGradient x1="97.6553341%" y1="35.6591143%" x2="37.202032%" y2="75.4891864%" id="uid1-1">
                      <stop stop-color="#0052CC" offset="7%"></stop>
                      <stop stop-color="#2684FF" offset="100%"></stop>
                    </linearGradient>
                    <linearGradient x1="8.43371138%" y1="60.1495759%" x2="64.1161517%" y2="23.5790285%" id="uid1-2">
                      <stop stop-color="#0052CC" offset="0%"></stop>
                      <stop stop-color="#2684FF" offset="100%"></stop>
                    </linearGradient>
                  </defs>
                  <g stroke="none" stroke-width="1" fill-rule="nonzero">
                    <path d="M11.3881081,27.9242105 C12.4881804,26.8071817 13.1062496,25.2917664 13.1062496,23.7115789 C13.1062496,22.1313915 12.4881804,20.6159762 11.3881081,19.4989474 L11.3881081,19.4989474 L3.74837838,11.7621053 L0.273513514,15.2926316 C-0.0900771727,15.6625064 -0.0900771727,16.2617042 0.273513514,16.6315789 L11.3881081,27.9242105 L11.3881081,27.9242105 Z" fill="currentColor" fill-rule="nonzero"></path>
                    <path d="M22.5027027,15.2926316 L11.3881081,4 L11.3881081,4 L11.3539189,4.03473684 L11.3539189,4.03473684 C9.08852466,6.36456187 9.09963243,10.1156459 11.3787838,12.4315789 L19.0247297,20.1652632 L22.5027027,16.6315789 C22.8662934,16.2617042 22.8662934,15.6625064 22.5027027,15.2926316 Z" fill="currentColor" fill-rule="nonzero"></path>
                    <path d="M11.3881081,12.4252632 C9.10895676,10.1093301 9.09784899,6.35824608 11.3632432,4.02842105 L3.43445946,12.0810526 L7.58067568,16.2936842 L11.3881081,12.4252632 Z" fill="url(#uid1-1)" fill-rule="nonzero"></path>
                    <path d="M15.1893243,15.6368421 L11.3881081,19.4989474 C12.4881804,20.6159762 13.1062496,22.1313915 13.1062496,23.7115789 C13.1062496,25.2917664 12.4881804,26.8071817 11.3881081,27.9242105 L19.3355405,19.8494737 L15.1893243,15.6368421 Z" fill="url(#uid1-2)" fill-rule="nonzero"></path>
                    <path d="M36.07,18.956 C36.07,20.646 35.394,21.842 33.418,21.842 C32.56,21.842 31.702,21.686 31,21.4 L31,23.662 C31.65,23.896 32.586,24.104 33.808,24.104 C37.032,24.104 38.41,21.946 38.41,18.8 L38.41,6.918 L36.07,6.918 L36.07,18.956 Z M41.894,7.568 C41.894,8.556 42.544,9.128 43.454,9.128 C44.364,9.128 45.014,8.556 45.014,7.568 C45.014,6.58 44.364,6.008 43.454,6.008 C42.544,6.008 41.894,6.58 41.894,7.568 Z M42.31,24 L44.546,24 L44.546,11 L42.31,11 L42.31,24 Z M47.926,24 L50.11,24 L50.11,16.33 C50.11,13.574 51.852,12.716 54.712,13.002 L54.712,10.818 C52.164,10.662 50.864,11.754 50.11,13.288 L50.11,11 L47.926,11 L47.926,24 Z M65.45,24 L65.45,21.66 C64.618,23.376 63.058,24.26 61.056,24.26 C57.598,24.26 55.856,21.322 55.856,17.5 C55.856,13.834 57.676,10.74 61.316,10.74 C63.214,10.74 64.67,11.598 65.45,13.288 L65.45,11 L67.686,11 L67.686,24 L65.45,24 Z M58.092,17.5 C58.092,20.62 59.34,22.18 61.654,22.18 C63.656,22.18 65.45,20.906 65.45,18.02 L65.45,16.98 C65.45,14.094 63.812,12.82 61.914,12.82 C59.392,12.82 58.092,14.484 58.092,17.5 Z M86.926,19.294 C86.926,16.226 84.898,15.056 81.284,14.146 C78.268,13.392 77.176,12.69 77.176,11.286 C77.176,9.726 78.502,8.946 80.738,8.946 C82.506,8.946 84.352,9.258 86.068,10.246 L86.068,7.906 C84.898,7.256 83.312,6.658 80.842,6.658 C76.864,6.658 74.836,8.634 74.836,11.286 C74.836,14.094 76.552,15.42 80.4,16.356 C83.65,17.136 84.586,17.942 84.586,19.45 C84.586,20.958 83.624,21.972 81.05,21.972 C78.788,21.972 76.344,21.374 74.758,20.542 L74.758,22.934 C76.084,23.61 77.618,24.26 80.92,24.26 C85.158,24.26 86.926,22.258 86.926,19.294 Z M95.09,24.26 C91.19,24.26 88.902,21.374 88.902,17.474 C88.902,13.574 91.19,10.74 95.09,10.74 C98.964,10.74 101.226,13.574 101.226,17.474 C101.226,21.374 98.964,24.26 95.09,24.26 Z M95.09,12.82 C92.308,12.82 91.086,15.004 91.086,17.474 C91.086,19.944 92.308,22.18 95.09,22.18 C97.846,22.18 99.042,19.944 99.042,17.474 C99.042,15.004 97.846,12.82 95.09,12.82 Z M106.92,9.622 C106.92,8.452 107.596,7.646 108.974,7.646 C109.494,7.646 109.988,7.698 110.378,7.776 L110.378,5.722 C109.988,5.618 109.546,5.514 108.87,5.514 C106.088,5.514 104.736,7.152 104.736,9.57 L104.736,11 L102.63,11 L102.63,13.08 L104.736,13.08 L104.736,24 L106.92,24 L106.92,13.08 L110.274,13.08 L110.274,11 L106.92,11 L106.92,9.622 Z M115.786,19.892 L115.786,13.08 L119.244,13.08 L119.244,11 L115.786,11 L115.786,8.244 L113.602,8.244 L113.602,11 L111.496,11 L111.496,13.08 L113.602,13.08 L113.602,19.944 C113.602,22.362 114.954,24 117.736,24 C118.412,24 118.854,23.896 119.244,23.792 L119.244,21.634 C118.854,21.712 118.36,21.816 117.84,21.816 C116.462,21.816 115.786,21.036 115.786,19.892 Z M125.432,24 L128.292,24 L130.528,17.708 L131.724,13.704 L132.92,17.708 L135.156,24 L138.016,24 L142.8,11 L140.33,11 L136.586,22.024 L132.79,11 L130.658,11 L126.862,22.024 L123.118,11 L120.648,11 L125.432,24 Z M153.538,24 L153.538,21.66 C152.706,23.376 151.146,24.26 149.144,24.26 C145.686,24.26 143.944,21.322 143.944,17.5 C143.944,13.834 145.764,10.74 149.404,10.74 C151.302,10.74 152.758,11.598 153.538,13.288 L153.538,11 L155.774,11 L155.774,24 L153.538,24 Z M146.18,17.5 C146.18,20.62 147.428,22.18 149.742,22.18 C151.744,22.18 153.538,20.906 153.538,18.02 L153.538,16.98 C153.538,14.094 151.9,12.82 150.002,12.82 C147.48,12.82 146.18,14.484 146.18,17.5 Z M159.154,24 L161.338,24 L161.338,16.33 C161.338,13.574 163.08,12.716 165.94,13.002 L165.94,10.818 C163.392,10.662 162.092,11.754 161.338,13.288 L161.338,11 L159.154,11 L159.154,24 Z M178.108,23.48 C177.042,24.052 175.404,24.26 174.078,24.26 C169.216,24.26 167.084,21.452 167.084,17.474 C167.084,13.548 169.268,10.74 173.22,10.74 C177.224,10.74 178.836,13.522 178.836,17.474 L178.836,18.488 L169.346,18.488 C169.658,20.698 171.088,22.128 174.156,22.128 C175.664,22.128 176.938,21.842 178.108,21.426 L178.108,23.48 Z M173.116,12.768 C170.75,12.768 169.554,14.302 169.32,16.564 L176.574,16.564 C176.444,14.146 175.352,12.768 173.116,12.768 Z" fill="inherit" fill-rule="evenodd"></path>
                  </g>
                </svg>
              </span>


            <div class="justify-center mt-1 mr-1">
              <!--                <img class="h-5 w-5" src="https://biltrax.atlassian.net/s/-egccmf/b/23/b6b48b2829824b869586ac216d119363/_/favicon-software.ico">-->
            </div>
            <div class="justify-center text-xl font-semibold text-center">

            </div>
          </div>

          <div class="hidden md:block">
            <div class="flex items-center ml-3 ">
              <a href="#" class="px-3 py-1 ml-2 self-center text-sm font-medium text-gray-800 antialiased rounded-md focus:outline-none hover:bg-blue-100 hover:text-blue-500 focus:bg-blue-100">Your work
              </a>
              <div class="flex px-3 py-1 ml-2 self-center text-sm font-medium text-gray-800 antialiased rounded-md focus:outline-none bg-blue-100 text-blue-500 focus:bg-blue-100">
                <a href="#" class="">Projects</a>
                <svg class="h-4 w-4 mt-1 ml-1" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M4.516 7.548c.436-.446 1.043-.481 1.576 0L10 11.295l3.908-3.747c.533-.481 1.141-.446 1.574 0 .436.445.408 1.197 0 1.615-.406.418-4.695 4.502-4.695 4.502a1.095 1.095 0 01-1.576 0S4.924 9.581 4.516 9.163c-.409-.418-.436-1.17 0-1.615z"/>
                </svg>
              </div>
              <div class="flex px-3 py-1 ml-2 self-center text-sm font-medium text-gray-800 antialiased rounded-md focus:outline-none hover:bg-blue-100 hover:text-blue-500 focus:bg-blue-100">
                <a href="#" class="">Filters</a>
                <svg class="h-4 w-4 mt-1 ml-1" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M4.516 7.548c.436-.446 1.043-.481 1.576 0L10 11.295l3.908-3.747c.533-.481 1.141-.446 1.574 0 .436.445.408 1.197 0 1.615-.406.418-4.695 4.502-4.695 4.502a1.095 1.095 0 01-1.576 0S4.924 9.581 4.516 9.163c-.409-.418-.436-1.17 0-1.615z"/>
                </svg>
              </div>
              <div class="flex px-3 py-1 ml-2 self-center text-sm font-medium text-gray-800 antialiased rounded-md focus:outline-none hover:bg-blue-100 hover:text-blue-500 focus:bg-blue-100">
                <a href="#" class="">Dashboards</a>
                <svg class="h-4 w-4 mt-1 ml-1" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M4.516 7.548c.436-.446 1.043-.481 1.576 0L10 11.295l3.908-3.747c.533-.481 1.141-.446 1.574 0 .436.445.408 1.197 0 1.615-.406.418-4.695 4.502-4.695 4.502a1.095 1.095 0 01-1.576 0S4.924 9.581 4.516 9.163c-.409-.418-.436-1.17 0-1.615z"/>
                </svg>
              </div>
              <a href="#" class="px-3 py-1 ml-2 self-center text-sm font-medium text-gray-800 antialiased rounded-md focus:outline-none hover:bg-blue-100 hover:text-blue-500 focus:bg-blue-100">People</a>

              <div class="flex px-3 py-1 ml-2 self-center text-sm font-medium text-gray-800 antialiased rounded-md focus:outline-none hover:bg-blue-100 hover:text-blue-500 focus:bg-blue-100">
                <a href="#" class="">App</a>
                <svg class="h-4 w-4 mt-1 ml-1" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M4.516 7.548c.436-.446 1.043-.481 1.576 0L10 11.295l3.908-3.747c.533-.481 1.141-.446 1.574 0 .436.445.408 1.197 0 1.615-.406.418-4.695 4.502-4.695 4.502a1.095 1.095 0 01-1.576 0S4.924 9.581 4.516 9.163c-.409-.418-.436-1.17 0-1.615z"/>
                </svg>
              </div>
              <a href="#" class="px-3 py-1 self-center ml-2 text-sm font-medium antialiased rounded bg-blue-800 text-white">Create</a>
            </div>
          </div>
        </div>
        <div class="hidden md:block">
          <div class="flex items-center ml-4 md:ml-6">
            <input type="text" class="hidden px-4 py-1 text-sm text-gray-600 border-2 rounded focus:outline-none focus:shadow-none lg:block" placeholder="Search ...">
            <button class="p-1 ml-2 hover:text-blue-500 text-gray-700 border-2 border-transparent rounded-full hover:bg-blue-100 focus:outline-none" aria-label="Notifications">
              <svg width="24" height="24" viewBox="0 0 24 24" role="presentation"><path d="M6.485 17.669a2 2 0 002.829 0l-2.829-2.83a2 2 0 000 2.83zm4.897-12.191l-.725.725c-.782.782-2.21 1.813-3.206 2.311l-3.017 1.509c-.495.248-.584.774-.187 1.171l8.556 8.556c.398.396.922.313 1.171-.188l1.51-3.016c.494-.988 1.526-2.42 2.311-3.206l.725-.726a5.048 5.048 0 00.64-6.356 1.01 1.01 0 10-1.354-1.494c-.023.025-.046.049-.066.075a5.043 5.043 0 00-2.788-.84 5.036 5.036 0 00-3.57 1.478z" fill="currentColor" fill-rule="evenodd"></path></svg>
            </button>

            <button class="p-1 ml-2 hover:text-blue-500 text-gray-700 border-2 border-transparent rounded-full hover:bg-blue-100 focus:outline-none" aria-label="Notifications">
              <svg width="24" height="24" viewBox="0 0 24 24" role="presentation"><g fill-rule="evenodd"><circle fill="currentColor" cx="12" cy="12" r="10"></circle><circle fill="white" cx="12" cy="18" r="1"></circle><path d="M15.89 9.05a3.975 3.975 0 00-2.957-2.942C10.321 5.514 8.017 7.446 8 9.95l.005.147a.992.992 0 00.982.904c.552 0 1-.447 1.002-.998a2.004 2.004 0 014.007-.002c0 1.102-.898 2-2.003 2H12a1 1 0 00-1 .987v2.014a1.001 1.001 0 002.004 0v-.782c0-.217.145-.399.35-.472A3.99 3.99 0 0015.89 9.05" fill="white"></path></g></svg>
            </button>
            <button class="p-1 ml-2 hover:text-blue-500 text-gray-700 border-2 border-transparent rounded-full hover:bg-blue-100 focus:outline-none" aria-label="Notifications">
              <svg width="24" height="24" viewBox="0 0 24 24" role="presentation"><path d="M11.701 16.7a5.002 5.002 0 110-10.003 5.002 5.002 0 010 10.004m8.368-3.117a1.995 1.995 0 01-1.346-1.885c0-.876.563-1.613 1.345-1.885a.48.48 0 00.315-.574 8.947 8.947 0 00-.836-1.993.477.477 0 00-.598-.195 2.04 2.04 0 01-1.29.08 1.988 1.988 0 01-1.404-1.395 2.04 2.04 0 01.076-1.297.478.478 0 00-.196-.597 8.98 8.98 0 00-1.975-.826.479.479 0 00-.574.314 1.995 1.995 0 01-1.885 1.346 1.994 1.994 0 01-1.884-1.345.482.482 0 00-.575-.315c-.708.2-1.379.485-2.004.842a.47.47 0 00-.198.582A2.002 2.002 0 014.445 7.06a.478.478 0 00-.595.196 8.946 8.946 0 00-.833 1.994.48.48 0 00.308.572 1.995 1.995 0 011.323 1.877c0 .867-.552 1.599-1.324 1.877a.479.479 0 00-.308.57 8.99 8.99 0 00.723 1.79.477.477 0 00.624.194c.595-.273 1.343-.264 2.104.238.117.077.225.185.302.3.527.8.512 1.58.198 2.188a.473.473 0 00.168.628 8.946 8.946 0 002.11.897.474.474 0 00.57-.313 1.995 1.995 0 011.886-1.353c.878 0 1.618.567 1.887 1.353a.475.475 0 00.57.313 8.964 8.964 0 002.084-.883.473.473 0 00.167-.631c-.318-.608-.337-1.393.191-2.195.077-.116.185-.225.302-.302.772-.511 1.527-.513 2.125-.23a.477.477 0 00.628-.19 8.925 8.925 0 00.728-1.793.478.478 0 00-.314-.573" fill="currentColor" fill-rule="evenodd"></path></svg>
            </button>

            <div class="relative ml-2">
              <button class="p-1 flex hover:bg-blue-100 items-center max-w-xs text-sm text-white rounded-full focus:outline-none focus:shadow-solid" id="user-menu" aria-label="User menu" aria-haspopup="true">
                <img class="w-6 h-6 rounded-full" :src="require(`~/assets/images/jira/${zaid}`)" alt="" />
              </button>
            </div>
          </div>
        </div>
        <div class="flex -mr-2 md:hidden">
          <button class="inline-flex items-center justify-center p-2 text-gray-400 rounded-md hover:text-white hover:bg-gray-700 focus:outline-none focus:bg-gray-700 focus:text-white">
            <svg class="block w-6 h-6" stroke="currentColor" fill="none" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
            </svg>
          </button>
        </div>
      </div>
    </nav>
    <div class="flex w-full h-screen">
      <div class="flex-col border-r mt-14 pl-5 w-1/5 bg-gray-100 h-auto">
        <div class="flex ml-3 py-8">
          <div class="my-auto rounded">
            <img class="h-7 w-10 my-auto" :src="require(`~/assets/images/${logo}`)">
          </div>
          <div class="flex-col">
            <div class="items-center cursor-pointer px-2  mb-1 text-sm font-medium text-gray-700 hover:underline">
              Noetic IT Service
            </div>
            <!--            <img src="../public/images/noetic_logo.png" height="856" width="1212"/>-->

            <div class="px-2 text-xs leading-none text-gray-600">
              Classic software company
            </div>
          </div>
        </div>
        <div class="px-3">
          <div class="flex py-2 px-4 cursor-pointer hover:bg-blue-100 rounded">
            <svg class="h-3 w-3 mt-1 text-gray-600" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 447.243 447.243">
              <path fill-rule="evenodd" d="M420.361 192.229a31.967 31.967 0 00-5.535-.41H99.305l6.88-3.2a63.998 63.998 0 0018.08-12.8l88.48-88.48c11.653-11.124 13.611-29.019 4.64-42.4-10.441-14.259-30.464-17.355-44.724-6.914a32.018 32.018 0 00-3.276 2.754l-160 160c-12.504 12.49-12.515 32.751-.025 45.255l.025.025 160 160c12.514 12.479 32.775 12.451 45.255-.063a32.084 32.084 0 002.745-3.137c8.971-13.381 7.013-31.276-4.64-42.4l-88.32-88.64a64.002 64.002 0 00-16-11.68l-9.6-4.32h314.24c16.347.607 30.689-10.812 33.76-26.88 2.829-17.445-9.019-33.88-26.464-36.71z"/>
            </svg>
            <div class="ml-5 text-sm text-gray-600  font-normal antialiased tracking-normal">
              Back to project
            </div>
          </div>
        </div>

        <div class="border-t border-gray-300 mt-5"></div>
        <div class="overflow-auto h-screen-24">
          <div class="flex-col px-3">
            <div class="items-center ml-2 py-4  mb-1 text-sm font-medium text-gray-700">
              Issues and filters
            </div>
            <div class="py-3 px-3 hover:bg-blue-100 cursor-pointer rounded text-sm text-gray-600  font-normal antialiased tracking-normal">
              My open issues
            </div>
            <div class="py-3 px-3 hover:bg-blue-100 cursor-pointer rounded text-sm text-gray-600  font-normal antialiased tracking-normal">
              Reported by me
            </div>
            <div class="py-3 px-3 bg-blue-100 cursor-pointer rounded text-sm text-gray-600  font-normal antialiased tracking-normal">
              All issues
            </div>
            <div class="py-3 px-3 hover:bg-blue-100 cursor-pointer rounded text-sm text-gray-600  font-normal antialiased tracking-normal">
              Open issues
            </div>
            <div class="py-3 px-3 hover:bg-blue-100 cursor-pointer rounded text-sm text-gray-600  font-normal antialiased tracking-normal">
              Done issues
            </div>
            <div class="py-3 px-3 hover:bg-blue-100 cursor-pointer rounded text-sm text-gray-600  font-normal antialiased tracking-normal">
              Viewed recently
            </div>
            <div class="py-3 px-3 hover:bg-blue-100 cursor-pointer rounded text-sm text-gray-600  font-normal antialiased tracking-normal">
              Created recently
            </div>
            <div class="py-3 px-3 hover:bg-blue-100 cursor-pointer rounded text-sm text-gray-600  font-normal antialiased tracking-normal">
              Resolved recently
            </div>
            <div class="py-3 px-3 hover:bg-blue-100 cursor-pointer rounded text-sm text-gray-600  font-normal antialiased tracking-normal">
              Updated recently
            </div>
            <div class="border border-gray-300 mt-5"></div>
            <div class="cursor-pointer py-3 px-3 mb-5 mt-5 hover:bg-blue-100 rounded text-sm text-gray-600  font-normal antialiased tracking-normal">
              View all filters
            </div>
          </div>
        </div>

      </div>
      <div class="flex w-4/5 h-screen">
        <div class=" ml-10 mt-auto" style="width: 400px">
          <div class="text-sm text-gray-600 font-normal antialiased tracking-normal">
            Projects &nbsp; / &nbsp; Biltrax IT Project
          </div>
          <div class="text-2xl mt-3 text-black font-semibold antialiased tracking-normal">
            All Issues
          </div>
          <div class="flex mt-5 w-full">
            <input type="text" class="w-1/2 h-7 px-2 text-gray-500 border rounded text-xs" placeholder="Filter Issue ...">
            <div class="items-center cursor-pointer px-2  mb-1 text-sm text-blue-500 hover:underline">Advanced search</div>
          </div>
          <div class="bg-gray-100 mt-4 rounded">
            <div class="flex  justify-between px-1 text-center items-center">
              <div class="flex px-3 py-1 self-center text-sm font-medium text-gray-800 antialiased rounded-md focus:outline-none hover:bg-blue-100 text-blue-500 focus:bg-blue-100">
                <a href="#" class="">Priority</a>
                <svg class="h-4 w-4 mt-1 ml-1" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M4.516 7.548c.436-.446 1.043-.481 1.576 0L10 11.295l3.908-3.747c.533-.481 1.141-.446 1.574 0 .436.445.408 1.197 0 1.615-.406.418-4.695 4.502-4.695 4.502a1.095 1.095 0 01-1.576 0S4.924 9.581 4.516 9.163c-.409-.418-.436-1.17 0-1.615z"/>
                </svg>
              </div>
              <div class="p-2">
                <button class="flex rounded px-4 py-2 focus:outline-none text-gray-500 hover:bg-blue-100 justify-around">
                  <svg class="h-3 w-3 " xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 512 512"><path fill-rule="evenodd" d="M441.156 322.876L392.49 275.49a8.523 8.523 0 00-11.93.017l-81.894 80.299V8.533A8.536 8.536 0 00290.133 0h-68.267a8.536 8.536 0 00-8.533 8.533v347.273l-81.894-80.299a8.528 8.528 0 00-11.921-.017l-48.666 47.386a8.503 8.503 0 00-2.586 6.11c0 2.304.939 4.506 2.586 6.11l179.2 174.481A8.508 8.508 0 00256 512c2.15 0 4.292-.811 5.956-2.423l179.2-174.481a8.526 8.526 0 002.577-6.11c0-2.304-.93-4.506-2.577-6.11z"/></svg>
                </button>
              </div>
            </div>



            <div class="mx-2 bg-white rounded">
              <div class="overflow-auto flex-col" style="height: 350px">
                <div class="flex-col cursor-pointer rounded hover:bg-blue-100">
                  <div class="py-3 px-3 cursor-pointer text-gray-700 rounded text-sm font-normal antialiased tracking-normal">
                    Selected Options : Tracked
                  </div>
                  <div class="flex px-3 justify-between">
                    <div class="flex">
                      <div class="bg-red-500 rounded h-4 w-4 p-1">
                        <svg class="h-2 w-2 text-white" fill="currentColor " xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 3a7 7 0 10.001 13.999A7 7 0 0010 3z"/></svg>
                      </div>
                      <div class="font-bold text-gray-500 ml-1 text-xs">
                        NITSWEBAPP-01
                      </div>
                    </div>
                    <button class="flex rounded-full p-1 pb-1 h-6 w-6 bg-orange-500 justify-around">
                      <span class="text-xs font-bold">AS</span>
                    </button>
                  </div>
                  <div class="border mt-3"></div>
                </div>
                <div class="flex-col cursor-pointer bg-blue-100">
                  <div class="py-3 px-3 cursor-pointer text-gray-700 rounded text-sm font-normal antialiased tracking-normal">
                    Project & Company Slug
                  </div>
                  <div class="flex px-3 justify-between">
                    <div class="flex">
                      <div class="bg-red-500 rounded h-4 w-4 p-1">
                        <svg class="h-2 w-2 text-white" fill="currentColor " xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 3a7 7 0 10.001 13.999A7 7 0 0010 3z"/></svg>
                      </div>
                      <div class="font-bold line-through text-gray-500 ml-1 text-xs">
                        NITSWEBAPP-02
                      </div>
                    </div>
                    <button class="flex rounded-full p-1 pb-1 h-6 w-6 bg-orange-500 justify-around">
                      <span class="text-xs font-bold">AS</span>
                    </button>
                  </div>
                  <div class="border mt-3"></div>
                </div>
                <div class="flex-col cursor-pointer hover:bg-blue-100">
                  <div class="py-3 px-3 cursor-pointer text-gray-700 rounded text-sm font-normal antialiased tracking-normal">
                    Selected Options : Tracked
                  </div>
                  <div class="flex px-3 justify-between">
                    <div class="flex">
                      <div class="bg-red-500 rounded h-4 w-4 p-1">
                        <svg class="h-2 w-2 text-white" fill="currentColor " xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 3a7 7 0 10.001 13.999A7 7 0 0010 3z"/></svg>
                      </div>
                      <div class="font-bold text-gray-500 ml-1 text-xs">
                        NITSWEBAPP-03
                      </div>
                    </div>
                    <button class="flex rounded-full p-1 pb-1 h-6 w-6 bg-orange-500 justify-around">
                      <span class="text-xs font-bold">AS</span>
                    </button>
                  </div>
                  <div class="border mt-3"></div>
                </div>
                <div class="flex-col cursor-pointer hover:bg-blue-100">
                  <div class="py-3 px-3 cursor-pointer text-gray-700 rounded text-sm font-normal antialiased tracking-normal">
                    Project & Company Slug
                  </div>
                  <div class="flex px-3 justify-between">
                    <div class="flex">
                      <div class="bg-red-500 rounded h-4 w-4 p-1">
                        <svg class="h-2 w-2 text-white" fill="currentColor " xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 3a7 7 0 10.001 13.999A7 7 0 0010 3z"/></svg>
                      </div>
                      <div class="font-bold line-through text-gray-500 ml-1 text-xs">
                        NITSWEBAPP-04
                      </div>
                    </div>
                    <button class="flex rounded-full p-1 pb-1 h-6 w-6 bg-orange-500 justify-around">
                      <span class="text-xs font-bold">AS</span>
                    </button>
                  </div>
                  <div class="border mt-3"></div>
                </div>
                <div class="flex-col cursor-pointer hover:bg-blue-100">
                  <div class="py-3 px-3 cursor-pointer text-gray-700 rounded text-sm font-normal antialiased tracking-normal">
                    Selected Options : Tracked
                  </div>
                  <div class="flex px-3 justify-between">
                    <div class="flex">
                      <div class="bg-red-500 rounded h-4 w-4 p-1">
                        <svg class="h-2 w-2 text-white" fill="currentColor " xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 3a7 7 0 10.001 13.999A7 7 0 0010 3z"/></svg>
                      </div>
                      <div class="font-bold text-gray-500 ml-1 text-xs">
                        NITSWEBAPP-05
                      </div>
                    </div>
                    <button class="flex rounded-full p-1 pb-1 h-6 w-6 bg-orange-500 justify-around">
                      <span class="text-xs font-bold">AS</span>
                    </button>
                  </div>
                  <div class="border mt-3"></div>
                </div>
                <div class="flex-col cursor-pointer hover:bg-blue-100">
                  <div class="py-3 px-3 cursor-pointer text-gray-700 rounded text-sm font-normal antialiased tracking-normal">
                    Project & Company Slug
                  </div>
                  <div class="flex px-3 justify-between">
                    <div class="flex">
                      <div class="bg-red-500 rounded h-4 w-4 p-1">
                        <svg class="h-2 w-2 text-white" fill="currentColor " xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 3a7 7 0 10.001 13.999A7 7 0 0010 3z"/></svg>
                      </div>
                      <div class="font-bold text-gray-500 ml-1 text-xs">
                        NITSWEBAPP-06
                      </div>
                    </div>
                    <button class="flex rounded-full p-1 pb-1 h-6 w-6 bg-orange-500 justify-around">
                      <span class="text-xs font-bold">AS</span>
                    </button>
                  </div>
                  <div class="border mt-3"></div>
                </div>
              </div>
            </div>



            <div class="flex  justify-between px-1 text-center items-center">

              <div class="p-2">
                <button class="flex rounded px-4 py-2 focus:outline-none text-gray-500 hover:bg-blue-100 justify-around">
                  <!--                                    <svg class="h-3 w-3 " xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 512 512"><path fill-rule="evenodd" d="M441.156 322.876L392.49 275.49a8.523 8.523 0 00-11.93.017l-81.894 80.299V8.533A8.536 8.536 0 00290.133 0h-68.267a8.536 8.536 0 00-8.533 8.533v347.273l-81.894-80.299a8.528 8.528 0 00-11.921-.017l-48.666 47.386a8.503 8.503 0 00-2.586 6.11c0 2.304.939 4.506 2.586 6.11l179.2 174.481A8.508 8.508 0 00256 512c2.15 0 4.292-.811 5.956-2.423l179.2-174.481a8.526 8.526 0 002.577-6.11c0-2.304-.93-4.506-2.577-6.11z"/></svg>-->
                  <svg class="h-4 w-4 " xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M5.516 14.224c-2.262-2.432-2.222-6.244.128-8.611a6.074 6.074 0 013.414-1.736L8.989 1.8a8.112 8.112 0 00-4.797 2.351c-3.149 3.17-3.187 8.289-.123 11.531l-1.741 1.752 5.51.301-.015-5.834-2.307 2.323zm6.647-11.959l.015 5.834 2.307-2.322c2.262 2.434 2.222 6.246-.128 8.611a6.07 6.07 0 01-3.414 1.736l.069 2.076a8.122 8.122 0 004.798-2.35c3.148-3.172 3.186-8.291.122-11.531l1.741-1.754-5.51-.3z"/>
                  </svg>
                </button>
              </div>
              <div class="flex px-3 py-1 self-center text-sm antialiased rounded-md text-gray-600 ">
                issue 48 of 88
              </div>
            </div>
          </div>
        </div>

        <div class="w-full relative ml-10 mt-auto">
          <div class="flex w-full justify-between px-1 text-center items-center">
            <div class="p-2 flex">
              <div class="py-3 cursor-pointer text-sm text-gray-600  font-normal antialiased tracking-normal">
                NITSWEBAPP-49 /
              </div>
              <div class="flex ml-2 mt-3">
                <div class="bg-red-500 mt-1 rounded h-4 w-4 p-1">
                  <svg class="h-2 w-2 text-white" fill="currentColor " xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 3a7 7 0 10.001 13.999A7 7 0 0010 3z"/></svg>
                </div>
                <div class="cursor-pointer ml-1 text-sm text-gray-600  font-normal antialiased tracking-normal">
                  NITSWEBAPP-05
                </div>
              </div>
            </div>
            <div class="flex mr-6">
              <div class="p-2 rounded hover:bg-blue-100 text-blue-700">
                <svg class="h-5 w-5 " xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10 4.4C3.439 4.4 0 9.232 0 10c0 .766 3.439 5.6 10 5.6 6.56 0 10-4.834 10-5.6 0-.768-3.44-5.6-10-5.6zm0 9.907c-2.455 0-4.445-1.928-4.445-4.307S7.545 5.691 10 5.691s4.444 1.93 4.444 4.309-1.989 4.307-4.444 4.307zM10 10c-.407-.447.663-2.154 0-2.154-1.228 0-2.223.965-2.223 2.154s.995 2.154 2.223 2.154c1.227 0 2.223-.965 2.223-2.154 0-.547-1.877.379-2.223 0z"/>
                </svg>
              </div>
              <div class="p-2 rounded ml-2 hover:bg-blue-100 text-gray-700">
                <svg class="h-5 w-5 " xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M15 13.442c-.633 0-1.204.246-1.637.642l-5.938-3.463c.046-.188.075-.384.075-.584s-.029-.395-.075-.583L13.3 6.025A2.48 2.48 0 0015 6.7c1.379 0 2.5-1.121 2.5-2.5S16.379 1.7 15 1.7s-2.5 1.121-2.5 2.5c0 .2.029.396.075.583L6.7 8.212A2.485 2.485 0 005 7.537c-1.379 0-2.5 1.121-2.5 2.5s1.121 2.5 2.5 2.5a2.48 2.48 0 001.7-.675l5.938 3.463a2.339 2.339 0 00-.067.546A2.428 2.428 0 1015 13.442z"/>
                </svg>
              </div>
              <div class="p-2 rounded ml-2 hover:bg-blue-100 text-gray-700">
                <svg class="h-5 w-5 " xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10.001 7.8a2.2 2.2 0 100 4.402A2.2 2.2 0 0010 7.8zm-7 0a2.2 2.2 0 100 4.402A2.2 2.2 0 003 7.8zm14 0a2.2 2.2 0 100 4.402A2.2 2.2 0 0017 7.8z"/>
                </svg>
              </div>
            </div>
          </div>


          <div class="flex overflow-auto" style="height: 465px">
            <div class="mr-10" style="width: 458px">
              <div class="w-full px-2 hover:bg-blue-100 py-2 text-2xl font-semibold">
                Project & Company Slug
              </div>
              <div class="flex mt-1">
                <div class="flex py-1 px-3 mr-2 cursor-pointer bg-gray-200 hover:bg-gray-300 rounded">
                  <svg class="h-5 w-5 text-gray-700" fill="currentColor" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M5.602 19.8c-1.293 0-2.504-.555-3.378-1.44-1.695-1.716-2.167-4.711.209-7.116l9.748-9.87c.988-1 2.245-1.387 3.448-1.06 1.183.32 2.151 1.301 2.468 2.498.322 1.22-.059 2.493-1.046 3.493l-9.323 9.44c-.532.539-1.134.858-1.738.922-.599.064-1.17-.13-1.57-.535-.724-.736-.828-2.117.378-3.337l6.548-6.63c.269-.272.705-.272.974 0s.269.714 0 .986l-6.549 6.631c-.566.572-.618 1.119-.377 1.364.106.106.266.155.451.134.283-.029.606-.216.909-.521l9.323-9.439c.64-.648.885-1.41.69-2.145a2.162 2.162 0 00-1.493-1.513c-.726-.197-1.48.052-2.12.7l-9.748 9.87c-1.816 1.839-1.381 3.956-.209 5.143 1.173 1.187 3.262 1.629 5.079-.212l9.748-9.87a.683.683 0 01.974 0 .704.704 0 010 .987L9.25 18.15c-1.149 1.162-2.436 1.65-3.648 1.65z"/></svg>
                  <div class="ml-2 text-sm text-gray-700  font-normal antialiased tracking-normal">
                    Attach
                  </div>
                </div>
                <div class="flex py-1 px-3 mr-2 cursor-pointer bg-gray-200 hover:bg-gray-300 rounded">
                  <svg class="h-5 w-5 text-gray-700" fill="currentColor" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M11 0H3a1 1 0 00-1 1v12a1 1 0 001 1h5v2h2v-2H8.001v-2H10v-2H8v2H4V2h6v4h2V1a1 1 0 00-1-1zM8 7v1h2V6H9a1 1 0 00-1 1zm4 13h2v-2h-2v2zm0-12h2V6h-2v2zM8 19a1 1 0 001 1h1v-2H8v1zm9-13h-1v2h2V7a1 1 0 00-1-1zm-1 14h1a1 1 0 001-1v-1h-2v2zm0-8h2v-2h-2v2zm0 4h2v-2h-2v2z"/></svg>
                  <div class="ml-2 text-sm text-gray-700  font-normal antialiased tracking-normal">
                    Create Subtask
                  </div>
                </div>
                <div class="flex py-1 px-3 mr-1 cursor-pointer bg-gray-200 hover:bg-gray-300 rounded">
                  <svg class="h-5 w-5 text-gray-700" fill="currentColor" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M7.859 14.691l-.81.805a1.814 1.814 0 01-2.545 0 1.762 1.762 0 010-2.504l2.98-2.955c.617-.613 1.779-1.515 2.626-.675a.992.992 0 101.397-1.407c-1.438-1.428-3.566-1.164-5.419.675l-2.98 2.956A3.719 3.719 0 002 14.244a3.72 3.72 0 001.108 2.658c.736.73 1.702 1.096 2.669 1.096s1.934-.365 2.669-1.096l.811-.805a.988.988 0 00.005-1.4.995.995 0 00-1.403-.006zm9.032-11.484c-1.547-1.534-3.709-1.617-5.139-.197l-1.009 1.002a.99.99 0 101.396 1.406l1.01-1.001c.74-.736 1.711-.431 2.346.197.336.335.522.779.522 1.252s-.186.917-.522 1.251l-3.18 3.154c-1.454 1.441-2.136.766-2.427.477a.99.99 0 10-1.396 1.406c.668.662 1.43.99 2.228.99.977 0 2.01-.492 2.993-1.467l3.18-3.153A3.732 3.732 0 0018 5.866a3.726 3.726 0 00-1.109-2.659z"/></svg>
                  <div class="ml-2 text-sm text-gray-700  font-normal antialiased tracking-normal">
                    Link Issue
                  </div>
                </div>
                <div class="py-1 px-2 cursor-pointer bg-gray-200 hover:bg-gray-300 rounded">
                  <svg class="h-4 w-4 text-gray-700" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M4.516 7.548c.436-.446 1.043-.481 1.576 0L10 11.295l3.908-3.747c.533-.481 1.141-.446 1.574 0 .436.445.408 1.197 0 1.615-.406.418-4.695 4.502-4.695 4.502a1.095 1.095 0 01-1.576 0S4.924 9.581 4.516 9.163c-.409-.418-.436-1.17 0-1.615z"/>
                  </svg>
                </div>
              </div>
              <div class="items-center py-1 mt-5 mb-1 text-sm font-medium text-gray-800">
                Description
              </div>
              <div class="flex-col p-2 rounded hover:bg-gray-200">
                <div class="flex">
                  <div class="h-5 w-5">
                    <svg class="h-5 w-5 text-gray-600" fill="currentColor" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M7.8 10a2.2 2.2 0 004.4 0 2.2 2.2 0 00-4.4 0z"/></svg>
                  </div>
                  <div class="text-sm ml-1 text-gray-800 antialiased tracking-normal font-normal ">
                    Lorem ipsum is typically a corrupted version of De finibus bonorum et malorum, a first-century BC text by the Roman statesman and philosopher
                    Cicero, with words altered, added, and removed to make it nonsensical, improper Latin.
                  </div>
                </div>
                <div class="flex mt-10">
                  <div class="h-5 w-5">
                    <svg class="h-5 w-5 text-gray-600" fill="currentColor" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M7.8 10a2.2 2.2 0 004.4 0 2.2 2.2 0 00-4.4 0z"/></svg>
                  </div>
                  <div class="text-sm ml-1 text-gray-800 antialiased tracking-normal font-normal ">
                    Lorem ipsum is typically a corrupted version of De finibus bonorum et malorum, a first-century BC text by the Roman statesman and philosopher
                    Cicero, with words altered, added, and removed to make it nonsensical, improper Latin.
                  </div>
                </div>
              </div>
              <div class="items-center py-1 mt-5 text-sm font-medium text-gray-800">
                Environment
              </div>
              <div class="flex-col p-2 rounded hover:bg-gray-200">
                <div class="flex">
                  <div class="text-sm ml-1 text-gray-800 antialiased tracking-normal font-normal ">
                    None
                  </div>
                </div>
              </div>
              <div class="items-center py-1 mt-5 text-sm font-medium text-gray-800">
                Activity
              </div>
              <div class="flex p-2 rounded">
                <div class="flex">
                  <div class="text-sm ml-1 py-1 text-gray-800 antialiased tracking-normal font-normal ">
                    Show :
                  </div>
                  <div class="text-sm ml-2 py-1 cursor-pointer rounded px-2 text-white bg-gray-700 antialiased tracking-normal font-normal ">
                    Comments
                  </div>
                  <div class="text-sm ml-2 py-1 cursor-pointer rounded px-2 text-gray-800 bg-gray-200 antialiased tracking-normal font-normal ">
                    History
                  </div>
                  <div class="text-sm ml-2 py-1 cursor-pointer rounded px-2 text-gray-800 bg-gray-200 text-gray-800 antialiased tracking-normal font-normal ">
                    Work Log
                  </div>
                </div>
              </div>
              <div class="border mt-3"></div>
              <div class="items-center flex py-1 mt-5 text-sm font-medium text-gray-800">
                <img class="h-10 w-10 rounded-full mr-8" :src="require(`~/assets/images/jira/${zaid}`)">
                <input type="text" placeholder="Add a Comment" class="text-xs rounded border border-gray-500 py-2 px-2 w-full">
              </div>
            </div>
            <div class="bg-white rounded" style="width: 240px">
              <div class=" px-1 text-center items-center">
                <div class="flex w-24 px-3 py-2 self-center text-sm font-medium antialiased rounded bg-blue-800 text-white">
                  <a href="#" class="">Testing</a>
                  <svg class="h-4 w-4 mt-1 ml-1" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M4.516 7.548c.436-.446 1.043-.481 1.576 0L10 11.295l3.908-3.747c.533-.481 1.141-.446 1.574 0 .436.445.408 1.197 0 1.615-.406.418-4.695 4.502-4.695 4.502a1.095 1.095 0 01-1.576 0S4.924 9.581 4.516 9.163c-.409-.418-.436-1.17 0-1.615z"/>
                  </svg>
                </div>
              </div>
              <div class="mx-2 bg-white rounded">
                <div class="flex-col">
                  <div class="flex-col mt-3 rounded">
                    <div class="py-1 px-1 text-gray-700 rounded text-xs font-semibold antialiased tracking-normal">
                      Assignee
                    </div>
                    <div class="flex px-2 py-2 hover:bg-gray-200">
                      <img class="w-6 h-6 rounded-full" :src="require(`~/assets/images/jira/${zaid}`)" alt="" />

                      <div class="font-normal text-gray-700 ml-3 text-xs">
                        Abuzaid Sayyad
                      </div>
                    </div>
                  </div>
                  <div class="flex-col mt-3 rounded">
                    <div class="py-1 px-1 text-gray-700 rounded text-xs font-semibold antialiased tracking-normal">
                      Reporter
                    </div>
                    <div class="flex px-2 py-2 hover:bg-gray-200">
                      <img class="w-6 h-6 rounded-full" :src="require(`~/assets/images/jira/${nitish}`)" alt="" />
                      <div class="font-normal text-gray-700 ml-3 text-xs">
                        Nitish Kumar
                      </div>
                    </div>
                  </div>
                  <div class="flex-col mt-3 rounded">
                    <div class="py-1 px-1 text-gray-700 rounded text-xs font-semibold antialiased tracking-normal">
                      Labels
                    </div>
                    <div class="px-2 py-2 hover:bg-gray-200">
                      <div class="font-normal text-gray-700 ml-3 text-xs">
                        None
                      </div>
                    </div>
                  </div>
                  <div class="flex-col mt-3 rounded">
                    <div class="py-1 px-1 text-gray-700 rounded text-xs font-semibold antialiased tracking-normal">
                      Epic Link
                    </div>
                    <div class="flex px-1 py-2 hover:bg-gray-200">
                      <div class="font-normal bg-purple-300 p-1 underline hover:bg-transparent rounded text-gray-700 ml-3 text-xs">
                        Nitseditor-frontend
                      </div>
                    </div>
                  </div>
                  <div class="flex-col mt-3 rounded">
                    <div class="py-1 px-1 text-gray-700 rounded text-xs font-semibold antialiased tracking-normal">
                      Sprint
                    </div>
                    <div class="px-2 py-2 hover:bg-gray-200">
                      <div class="font-normal text-gray-700 hover:text-blue-500 hover:underline ml-3 text-xs">
                        Bugs, Subs Excel, Forecast
                      </div>
                    </div>
                  </div>
                  <div class="flex-col mt-3 rounded">
                    <div class="py-1 px-1 text-gray-700 rounded text-xs font-semibold antialiased tracking-normal">
                      Priority
                    </div>
                    <div class="flex px-2 py-2 hover:bg-gray-200">
                      <svg class="h-4 w-4 text-yellow-500 " fill="currentColor " xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20">
                        <path fill-rule="evenodd" d="M10 .75L15.5 6H12v13H8V6H4.5L10 .75z"/>
                      </svg>
                      <div class="font-normal text-gray-700 ml-3 text-xs">
                        Medium
                      </div>
                    </div>
                  </div>
                  <div class="flex-col mt-3 rounded">
                    <div class="px-2 py-2 hover:bg-gray-200">
                      <div class="flex self-center text-sm font-medium antialiased rounded text-blue-500">
                        <svg class="h-4 w-4 mt-1 ml-1" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
                          <path fill-rule="evenodd" d="M4.516 7.548c.436-.446 1.043-.481 1.576 0L10 11.295l3.908-3.747c.533-.481 1.141-.446 1.574 0 .436.445.408 1.197 0 1.615-.406.418-4.695 4.502-4.695 4.502a1.095 1.095 0 01-1.576 0S4.924 9.581 4.516 9.163c-.409-.418-.436-1.17 0-1.615z"/>
                        </svg>
                        <a href="#" class="text-blue-600">Show 5 More Field</a>
                      </div>
                      <div class="text-xs pl-3 font-light antialiased rounded text-gray-500">
                        Original Estimate, Time tracking
                      </div>
                    </div>
                  </div>
                  <div class="border mt-2"></div>
                </div>
              </div>
              <div class="flex justify-between px-1 text-left ">
                <div class="p-2 text-xs text-gray-600 antialiased tracking-normal">
                  Created July 3, 2020, 6:24 PM<br>
                  Updated 4 days ago<br>
                  Configure
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="absolute hover:text-blue-500  right-16 top-24 underline cursor-pointer text-sm text-gray-700  font-semibold antialiased tracking-normal">Give feedback</div>

  </div>
</template>

<script>
export default {
  name: "jira-software",
  data(){
    return{
      zaid:'zaid.jpeg',
      nitish:'nitish-sir.jpeg',
      logo:'noetic_Final_logo.png'

    }
  }
}
</script>

<style scoped>
.h-screen-24{
  height: calc(100vh - 215px);
}
</style>
