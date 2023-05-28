<template>
  <div class="absolute rounded-lg overflow-hidden bg-transparent w-full h-full border border-gray-500 border-opacity-30 shadow-md  react-draggable" id="window-bear" style="position: absolute; user-select: auto; width: 860px; height: 500px; display: inline-block; top: 0px; left: 0px; cursor: auto; transform: translate(198.656px, 42.7412px); max-width: 9.0072e+15px; max-height: 9.0072e+15px; min-width: 200px; min-height: 150px; box-sizing: border-box; flex-shrink: 0; z-index: 3;">
    <div class="window-bar relative h-6 text-center bg-gray-200">
      <div class="traffic_lights flex flex-row absolute left-0 space-x-2 pl-2 mt-1.5">
        <button class="w-3 h-3 rounded-full bg-red-500 outline-none focus:outline-none inline-flex justify-center items-center">
          <svg class="m-auto" stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 512 512" height="11" width="11" xmlns="http://www.w3.org/2000/svg"><path fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="32" d="M368 368L144 144m224 0L144 368"></path></svg>
        </button>
        <button class="w-3 h-3 rounded-full bg-yellow-500 outline-none focus:outline-none inline-flex justify-center items-center">
          <svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" height="11" width="11" xmlns="http://www.w3.org/2000/svg"><line x1="5" y1="12" x2="19" y2="12"></line></svg>
        </button>
        <button class="w-3 h-3 rounded-full bg-green-500 outline-none focus:outline-none  inline-flex justify-center items-center">
          <svg viewBox="0 0 13 13" width="6.5" height="6.5" xmlns="http://www.w3.org/2000/svg" fill-rule="evenodd" clip-rule="evenodd" stroke-linejoin="round" stroke-miterlimit="2"><path fill="none" d="M0 0h12.038v12.038H0z"></path><path d="M9.26 12.03L.006 2.73v9.3H9.26zM2.735.012l9.3 9.3v-9.3h-9.3z"></path></svg>
        </button>
      </div>
      <span class="font-semibold text-gray-700">Bear</span>
    </div>
    <div class="innner-window w-full overflow-y-hidden">
      <div class="bear font-avenir flex flex-row w-full h-full">
        <div class="flex-none w-44">
          <div class="sidebar w-full h-full bg-gray-700 text-white overflow-y-scroll">
            <div class="h-12 pr-3 flex flex-row justify-end items-center">
              <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 512 512" class="mr-3" height="20" width="20" xmlns="http://www.w3.org/2000/svg"><path fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="32" d="M93.72 183.25C49.49 198.05 16 233.1 16 288c0 66 54 112 120 112h184.37m147.45-22.26C485.24 363.3 496 341.61 496 312c0-59.82-53-85.76-96-88-8.89-89.54-71-144-144-144-26.16 0-48.79 6.93-67.6 18.14"></path><path fill="none" stroke-linecap="round" stroke-miterlimit="10" stroke-width="32" d="M448 448L64 64"></path></svg>
              <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 512 512" height="20" width="20" xmlns="http://www.w3.org/2000/svg"><path d="M87 32v71h18V32H87zm160 0v345h18V32h-18zm160 0v167h18V32h-18zM50 121c-5.14 0-9 3.9-9 9v28c0 5.1 3.86 9 9 9h92c5.1 0 9-3.9 9-9v-28c0-5.1-3.9-9-9-9H50zm37 64v295h18V185H87zm283 32c-5.1 0-9 3.9-9 9v28c0 5.1 3.9 9 9 9h92c5.1 0 9-3.9 9-9v-28c0-5.1-3.9-9-9-9h-92zm37 64v199h18V281h-18zM210 395c-5.1 0-9 3.9-9 9v28c0 5.1 3.9 9 9 9h92c5.1 0 9-3.9 9-9v-28c0-5.1-3.9-9-9-9h-92zm37 64v21h18v-21h-18z"></path></svg>
            </div>
            <ul>
              <li class="pl-6 h-8 flex flex-row items-center cursor-default bg-red-500 ">
                <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 512 512" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M256 224c-79.41 0-192 122.76-192 200.25 0 34.9 26.81 55.75 71.74 55.75 48.84 0 81.09-25.08 120.26-25.08 39.51 0 71.85 25.08 120.26 25.08 44.93 0 71.74-20.85 71.74-55.75C448 346.76 335.41 224 256 224zm-147.28-12.61c-10.4-34.65-42.44-57.09-71.56-50.13-29.12 6.96-44.29 40.69-33.89 75.34 10.4 34.65 42.44 57.09 71.56 50.13 29.12-6.96 44.29-40.69 33.89-75.34zm84.72-20.78c30.94-8.14 46.42-49.94 34.58-93.36s-46.52-72.01-77.46-63.87-46.42 49.94-34.58 93.36c11.84 43.42 46.53 72.02 77.46 63.87zm281.39-29.34c-29.12-6.96-61.15 15.48-71.56 50.13-10.4 34.65 4.77 68.38 33.89 75.34 29.12 6.96 61.15-15.48 71.56-50.13 10.4-34.65-4.77-68.38-33.89-75.34zm-156.27 29.34c30.94 8.14 65.62-20.45 77.46-63.87 11.84-43.42-3.64-85.21-34.58-93.36s-65.62 20.45-77.46 63.87c-11.84 43.42 3.64 85.22 34.58 93.36z"></path></svg>
                <span class="ml-2">Profile</span>
              </li>
              <li class="pl-6 h-8 flex flex-row items-center cursor-default bg-transparent hover:bg-gray-600">
                <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 12 16" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"></path></svg>
                <span class="ml-2">Projects</span>
              </li>
            </ul>
          </div>
        </div>
        <div class="flex-none w-60">
          <div class="midbar w-full h-full bg-gray-50 border-r border-gray-300 overflow-y-scroll">
            <ul>
              <li class="h-24 flex flex-col cursor-default border-l-2 border-red-500 bg-white hover:bg-white">
                <div class="h-8 mt-3 flex flex-row flex-none items-center">
                  <div class="-mt-1 w-10 text-gray-500 flex flex-none justify-center">
                    <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 512 512" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M458.949 16.902c-21.23 45.511-62.196 13.713-94.89 12.604-92.464-.8-95.254 47.352-141.296 77.017-9.189-10.02-23.774-16.38-46.738-15.117-15.928.876-30.343 6.34-40.974 15.895-12.34 10.738-21.335 25.549-21.942 39.84 21.03-5.316 41.304-4.385 45.871 5.46 11.508 24.813-21.37 15.961-44.745 23.397-1.248.396-2.472.81-3.684 1.225-2.757 7.733-6.024 15.131-6.024 20.482 0 16.945 13.686 6.16 19.648 20.88.85 2.099 3.778 8.625 12.238 16.833 1.367 1.328 46-35.114 47.487-33.9-14.835 31.6-38.787 42.74-41.127 43.975-21.237 11.202-46.726 20.42-55.691 38.13l-.522-.168s-27.58 65.425-33.509 97.908c.575 16.747 25.672 12.545 25.672 12.545l39.527-11.785 4.686 16.94 119.482-150.627c-26.122-15.67-18.045-38.588-21.927-58.778 13.787-22.475 21.9-34.062 14.597-56.68 7.122-7.318 16.216-14.785 26.61-16.779 21.267-4.08 60.016 16.198 80.997 16.47 27.78.362 42.716-14.296 54.352-31.905-10.666 3.502-14.712 3.5-8.703-15.065-14.177 5.175-23.315 22.6-48.998 18.526-23.87-3.787-60.077-11.021-80.065-4.354 33.926-17.423 60.548-35.253 96.777-39.463 42.453 3.026 80.56 32.916 102.89-17.031zM340.169 153.78l-39.003 49.065 16.54 11.713 39.008-49.067zm-205.509 1.657c-5.303 0-10.607 1.195-10.607 3.584 2.163 2.943 9.788 5.337 13.459 5.42 5.858 0 7.755-.644 7.755-5.42 0-2.389-5.304-3.584-10.607-3.584zm140.864 47.156l-11.702 14.172L312.9 250.85l11.701-14.172zm-4.423 35.984L100.574 453.551s-10.247 8.425-.05 16.773c10.47 8.57 18.622-3.654 18.622-3.654L289.67 251.695zm18.932 41.914s-20.687 26.845-31.22 40.12c-42.147 53.119-125.718 156.698-127.942 158.156l.068 16.332H240.24l15.365-115.264 44.661 9.677s17.915 1.914 17.186-13.823c-4.626-21.768-19.228-74.864-27.42-95.198zm-22.714 48.874l8.746 21.61-14.493-3.73z"></path></svg>
                  </div>
                  <span class="relative text-gray-900 flex-grow font-bold">About Me</span>
                </div>
                <div class="h-16 ml-10 pb-2 pr-1 border-b border-gray-300 text-sm text-gray-500">Hey there! I'm a dragon lost in human world...</div>
              </li>
              <li class="h-24 flex flex-col cursor-default border-l-2 border-transparent bg-transparent hover:bg-white">
                <div class="h-8 mt-3 flex flex-row flex-none items-center">
                  <div class="-mt-1 w-10 text-gray-500 flex flex-none justify-center">
                    <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 24 24" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><g clip-path="url(#clip0)"><path d="M12 0a12 12 0 1 0 0 24 12 12 0 0 0 0-24zm3.163 21.783h-.093a.513.513 0 0 1-.382-.14.513.513 0 0 1-.14-.372v-1.406c.006-.467.01-.94.01-1.416a3.692 3.692 0 0 0-.151-1.028 1.832 1.832 0 0 0-.542-.875 8.014 8.014 0 0 0 2.038-.471 4.051 4.051 0 0 0 1.466-.964c.407-.427.71-.943.885-1.506a6.77 6.77 0 0 0 .3-2.13 4.138 4.138 0 0 0-.26-1.476 3.892 3.892 0 0 0-.795-1.284 2.81 2.81 0 0 0 .162-.582c.033-.2.05-.402.05-.604 0-.26-.03-.52-.09-.773a5.309 5.309 0 0 0-.221-.763.293.293 0 0 0-.111-.02h-.11c-.23.002-.456.04-.674.111a5.15 5.15 0 0 0-.703.26 6.503 6.503 0 0 0-.661.343c-.215.127-.405.249-.573.362a9.578 9.578 0 0 0-5.143 0 13.507 13.507 0 0 0-.572-.362 6.023 6.023 0 0 0-.672-.342 4.516 4.516 0 0 0-.705-.261 2.203 2.203 0 0 0-.662-.111h-.11a.29.29 0 0 0-.11.02 5.845 5.845 0 0 0-.23.763c-.054.254-.08.513-.081.773 0 .202.017.404.051.604.033.199.086.394.16.582A3.888 3.888 0 0 0 5.702 10a4.142 4.142 0 0 0-.263 1.476 6.871 6.871 0 0 0 .292 2.12c.181.563.483 1.08.884 1.516.415.422.915.75 1.466.964.653.25 1.337.41 2.033.476a1.828 1.828 0 0 0-.452.633 2.99 2.99 0 0 0-.2.744 2.754 2.754 0 0 1-1.175.27 1.788 1.788 0 0 1-1.065-.3 2.904 2.904 0 0 1-.752-.824 3.098 3.098 0 0 0-.292-.382 2.692 2.692 0 0 0-.372-.343 1.842 1.842 0 0 0-.432-.24 1.201 1.201 0 0 0-.481-.101c-.04.001-.08.005-.12.01a.649.649 0 0 0-.162.02.408.408 0 0 0-.13.06.115.115 0 0 0-.06.1.33.33 0 0 0 .14.242c.093.074.17.131.232.171l.03.021c.133.103.261.214.382.333.112.098.213.209.3.33.09.119.168.246.231.381.073.134.15.288.231.463.188.474.522.875.954 1.145.453.243.961.364 1.476.351.174 0 .349-.01.522-.03.172-.028.343-.057.515-.091v1.743a.501.501 0 0 1-.533.521h-.062a10.286 10.286 0 1 1 6.324 0v.005z"></path></g><defs><clipPath id="clip0"><path d="M0 0h24v24H0V0z"></path></clipPath></defs></svg>
                  </div>
                  <span class="relative text-gray-900 flex-grow font-bold">Github Stats</span>
                </div>
                <div class="h-16 ml-10 pb-2 pr-1 border-b border-gray-300 text-sm text-gray-500">Here are some status about my github account...</div>
              </li>
              <li class="h-24 flex flex-col cursor-default border-l-2 border-transparent bg-transparent hover:bg-white">
                <div class="h-8 mt-3 flex flex-row flex-none items-center">
                  <div class="-mt-1 w-10 text-gray-500 flex flex-none justify-center">
                    <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 14 16" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M5 3h1v1H5V3zM3 3h1v1H3V3zM1 3h1v1H1V3zm12 10H1V5h12v8zm0-9H7V3h6v1zm1-1c0-.55-.45-1-1-1H1c-.55 0-1 .45-1 1v10c0 .55.45 1 1 1h12c.55 0 1-.45 1-1V3z"></path></svg>
                  </div>
                  <span class="relative text-gray-900 flex-grow font-bold">About This Site</span>
                </div>
                <div class="h-16 ml-10 pb-2 pr-1 border-b border-gray-300 text-sm text-gray-500">Something about this personal portfolio site...</div>
              </li>
            </ul>
          </div>
        </div>
        <div class="flex-grow">
          <div class="markdown w-full h-full bg-gray-50 text-gray-700 overflow-scroll py-6">
            <div class="w-2/3 px-2 mx-auto">
              <h1>About Me</h1>
              <h2>Biography</h2>
              <p>Hey there! I'm <del>a dragon lost in human world</del> now an intern at CETC and a research assistant at Peking University. Before that, I got my bachelor's degree in <a href="http://sse.tongji.edu.cn/" target="_blank">Software Engineering</a> at <a href="https://www.tongji.edu.cn/" target="_blank">Tongji University</a> in 2020. I'm now waiting for starting my graduate study.</p>
              <p>I'm trying to find a balance between research and engineering.</p>
              <p>Research-wise, I'm currently mainly working on topics related to exploring the capability of machines to develop intelligent behavior upon what they have learned, like meta-learning and continual learning.</p>
              <p>I used to work on natural language processing (machine translation and language generation), image captioning and image aesthetic assessment.</p>
              <p>I'm also learning to build machine learning softwares and systems. I'm also learning TypeScript, React, Electron and Golang.</p>
              <h2>Contact</h2>
              <p>Contact me by:</p>
              <ul>
                <li>Email: <a href="mailto:renovamenzxh@gmail.com" target="_blank">renovamenzxh@gmail.com</a> / <a href="mailto:xiaohan.zou@foxmail.com" target="_blank">xiaohan.zou@foxmail.com</a></li>
                <li>Github: <a href="https://github.com/Renovamen" target="_blank">@Renovamen</a></li>
                <li><a href="https://www.linkedin.com/in/xiaohan-zou-55bba0160" target="_blank">Linkedin</a></li>
                <li>知乎: <a href="https://www.zhihu.com/people/chao-neng-gui-su" target="_blank">@Renovamen</a></li>
                <li>Blog: <a href="https://zxh.io" target="_blank">zxh.io</a></li>
              </ul>
              <h2>Résumé</h2>
              <p>My résumé can be found here: <a href="https://zxh.io/files/cv/brief/en.pdf" target="_blank">English</a> / <a href="https://zxh.io/files/cv/brief/cn.pdf" target="_blank">中文</a>.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div>
      <div class="" style="position: absolute; user-select: none; width: 100%; height: 10px; top: -5px; left: 0px; cursor: row-resize;"></div>
      <div class="" style="position: absolute; user-select: none; width: 10px; height: 100%; top: 0px; right: -5px; cursor: col-resize;"></div>
      <div class="" style="position: absolute; user-select: none; width: 100%; height: 10px; bottom: -5px; left: 0px; cursor: row-resize;"></div>
      <div class="" style="position: absolute; user-select: none; width: 10px; height: 100%; top: 0px; left: -5px; cursor: col-resize;"></div>
      <div class="" style="position: absolute; user-select: none; width: 20px; height: 20px; right: -10px; top: -10px; cursor: ne-resize;"></div>
      <div class="" style="position: absolute; user-select: none; width: 20px; height: 20px; right: -10px; bottom: -10px; cursor: se-resize;"></div>
      <div class="" style="position: absolute; user-select: none; width: 20px; height: 20px; left: -10px; bottom: -10px; cursor: sw-resize;"></div>
      <div class="" style="position: absolute; user-select: none; width: 20px; height: 20px; left: -10px; top: -10px; cursor: nw-resize;"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MacBeer"
}
</script>

<style scoped>

</style>
