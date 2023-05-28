<template>
  <nav class="bg-gray-900">
    <div class="px-4 mx-auto sm:px-6 lg:px-8">
      <div class="flex items-center justify-between h-16">
        <div class="flex items-center">
          <div class="">
            <div class="justify-center w-1/5 text-center">
              <svg class="w-8 h-8 mx-auto text-white cursor-pointer fill-current hover:text-gray-300" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                <path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"/></svg>
            </div>
          </div>
          <div class="hidden md:block">
            <div class="flex items-center ml-4">
              <div class="relative">
                <input type="text" class="hidden border-gray-500 border px-4 h-7 bg-transparent text-sm placeholder-gray-400 rounded-md focus:outline-none focus:shadow-none lg:block" style="width: 17rem" placeholder="Search or jump to...">
                <div class="h-5 w-5 rounded bg-transparent border border-gray-500 absolute top-1 right-1 flex">
                  <span class="m-auto text-xs font-normal text-gray-500">/</span>
                </div>
              </div>
              <a href="#" class="px-3 py-2 ml-1 text-sm font-semibold text-white bg-gray-900 rounded-md focus:outline-none hover:bg-gray-700 focus:text-white focus:bg-gray-700">Pull requests</a>
              <a href="#" class="px-3 py-2 text-sm font-semibold text-gray-300 rounded-md hover:text-white hover:bg-gray-700 focus:outline-none focus:text-white focus:bg-gray-700">Issues</a>
              <a href="#" class="px-3 py-2 text-sm font-semibold text-gray-300 rounded-md hover:text-white hover:bg-gray-700 focus:outline-none focus:text-white focus:bg-gray-700">Marketplace</a>
              <a href="#" class="px-3 py-2 text-sm font-semibold text-gray-300 rounded-md hover:text-white hover:bg-gray-700 focus:outline-none focus:text-white focus:bg-gray-700">Explore</a>
            </div>
          </div>
        </div>
        <div class="hidden md:block">
          <div class="flex items-center ml-4 md:ml-6">
            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" fill="currentColor" class="text-white">
              <path d="M8 16a2 2 0 001.985-1.75c.017-.137-.097-.25-.235-.25h-3.5c-.138 0-.252.113-.235.25A2 2 0 008 16z"></path><path fill-rule="evenodd" d="M8 1.5A3.5 3.5 0 004.5 5v2.947c0 .346-.102.683-.294.97l-1.703 2.556a.018.018 0 00-.003.01l.001.006c0 .002.002.004.004.006a.017.017 0 00.006.004l.007.001h10.964l.007-.001a.016.016 0 00.006-.004.016.016 0 00.004-.006l.001-.007a.017.017 0 00-.003-.01l-1.703-2.554a1.75 1.75 0 01-.294-.97V5A3.5 3.5 0 008 1.5zM3 5a5 5 0 0110 0v2.947c0 .05.015.098.042.139l1.703 2.555A1.518 1.518 0 0113.482 13H2.518a1.518 1.518 0 01-1.263-2.36l1.703-2.554A.25.25 0 003 7.947V5z"></path>
            </svg>
            <div class="flex items-center text-white hover:text-gray-200 cursor-pointer mx-4">
              <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" fill="currentColor">
                <path fill-rule="evenodd" d="M7.75 2a.75.75 0 01.75.75V7h4.25a.75.75 0 110 1.5H8.5v4.25a.75.75 0 11-1.5 0V8.5H2.75a.75.75 0 010-1.5H7V2.75A.75.75 0 017.75 2z"></path>
              </svg>
              <svg class="rotate-90 transform" xmlns="http://www.w3.org/2000/svg" height="12" width="13" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M15 10.001c0 .299-.305.514-.305.514l-8.561 5.303C5.51 16.227 5 15.924 5 15.149V4.852c0-.777.51-1.078 1.135-.67l8.561 5.305c-.001 0 .304.215.304.514z"/></svg>
            </div>
            <div class="relative">
              <div class="flex items-center text-white hover:text-gray-200">
                <img class="rounded-full" height="20" width="20" :src="require(`~/assets/images/github/${user}`)">
                <svg class="rotate-90 transform" xmlns="http://www.w3.org/2000/svg" height="12" width="13" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M15 10.001c0 .299-.305.514-.305.514l-8.561 5.303C5.51 16.227 5 15.924 5 15.149V4.852c0-.777.51-1.078 1.135-.67l8.561 5.305c-.001 0 .304.215.304.514z"/></svg>
              </div>
              <div class="rounded-full h-3.5 w-3.5 border-2 border-gray-800 bg-blue-500 absolute -top-1.5 right-1.5"></div>
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
    </div>
  </nav>
</template>

<script>
export default {
  name: "GithubHeader",
  data(){
    return{
      user:'user.png'
    }
  }
}
</script>

<style scoped>

</style>
