<template>
  <div class="w-full family-poppins">

    <!--    topbar start here-->
    <div class="w-full bg-gray flex justify-between items-center px-4 h-15" style="position: fixed; top: 0px; background: #EFF2F7">
      <div class="flex items-center">
        <img class="h-8" :src="require(`~/assets/images/${image}`)">
        <div style="margin-left: 49px; position: relative">
          <input type="search" class="rounded-full text-sm font-normal bg-white focus:outline-none" placeholder="Search. . . ." style="height: 33px; width: 420px; padding-left: 50px; padding-right: 10px">
          <svg class="absolute top-2 left-3" xmlns="http://www.w3.org/2000/svg" style="height: 19px; width: 19px; color: #60686B" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
          </svg>
        </div>
      </div>
      <div class="flex items-center">
        <div class="flex items-center" style="margin-right: 49px;">
          <svg style="height: 26px; width: 26px"><g id="icon-stopwatch-24"><path id="Union" fill-rule="evenodd" clip-rule="evenodd" d="M9 3a1 1 0 011-1h4a1 1 0 110 2h-1v1.062a7.96 7.96 0 013.906 1.618l.887-.887a1 1 0 111.414 1.414l-.887.887A8 8 0 1111 5.062V4h-1a1 1 0 01-1-1zm3 4a6 6 0 100 12 6 6 0 000-12zM8.793 9.793a1 1 0 011.414 0l2.5 2.5a1 1 0 01-1.414 1.414l-2.5-2.5a1 1 0 010-1.414z"></path></g></svg>
          <svg class="mx-3.5" style="height: 26px; width: 26px"><g id="icon-bookmark-24"><path id="Union" fill-rule="evenodd" clip-rule="evenodd" d="M6 6a3 3 0 013-3h6a3 3 0 013 3v14a1 1 0 01-1.625.78L12 17.28l-4.375 3.5A1 1 0 016 20V6zm3-1a1 1 0 00-1 1v11.92l3.375-2.7a1 1 0 011.25 0L16 17.92V6a1 1 0 00-1-1H9z"></path></g></svg>
          <svg style="height: 26px; width: 26px"><g id="icon-bell-24"><path id="Union" fill-rule="evenodd" clip-rule="evenodd" d="M7 10c0-2.83 2.17-5 5-5s5 2.17 5 5h1-1v4c0 1.12.27 2.205.53 3H6.47c.26-.795.53-1.88.53-3v-4H6h1zm3 9H5a1 1 0 01-.895-1.446v-.001l.006-.012.026-.054c.023-.05.058-.126.1-.225.085-.198.2-.484.314-.828.234-.7.449-1.585.449-2.434v-4h1-1c0-3.935 3.065-7 7-7s7 3.065 7 7h-1 1v4c0 .849.215 1.734.449 2.434a10.772 10.772 0 00.414 1.053l.026.055.005.01v.001A1 1 0 0119 19h-5a2 2 0 11-4 0z"></path></g></svg>
          <svg class="mx-3.5" style="height: 26px; width: 26px"><g id="icon-add-24"><path id="Union" fill-rule="evenodd" clip-rule="evenodd" d="M8 3a5 5 0 00-5 5v8a5 5 0 005 5h8a5 5 0 005-5V8a5 5 0 00-5-5H8zM5 8a3 3 0 013-3h8a3 3 0 013 3v8a3 3 0 01-3 3H8a3 3 0 01-3-3V8zm8 1a1 1 0 10-2 0v2H9a1 1 0 100 2h2v2a1 1 0 102 0v-2h2a1 1 0 100-2h-2V9z"></path></g></svg>
        </div>
        <button class="flex items-center rounded-full" style="height: 39px;width: 185px;background: #F7F9FD">
          <img :src="require(`/assets/images/biltrax-icon/${user}`)" style="height: 32px;margin-left: 5px; margin-top:1px">
          <div class="mx-2">
            <div class="font-medium text-sm family-poppins">abuzaid sayyad</div>
            <div class="font-light text-left text-xs">Noetic</div>
          </div>
        </button>
      </div>
    </div>
    <!--    topbar end here-->

    <!--    sidebar start here-->
    <div class="h-screen-46 fixed left-0 bottom-0 bg-biltrax w-88" style="padding-right: 7px; padding-left: 7px">
      <div class="w-full p-2 bg-gray-150 rounded-md mt-7">
        <img class="mx-auto" style="height: 31px" :src="require(`/assets/images/biltrax-icon/${companies}`)">
        <div class="font-medium text-center mt-1 text-gray-250" style="font-size: 11px">List of Companies</div>
      </div>
      <div class="w-full p-2 rounded-md my-4">
        <img class="mx-auto" style="height: 24px" :src="require(`/assets/images/biltrax-icon/${dash}`)">
        <div class="font-medium text-center mt-1 text-gray-150" style="font-size: 11px">Dashboard</div>
      </div>
      <div class="w-full p-2 rounded-md my-4">
        <img class="mx-auto" style="height: 24px" :src="require(`/assets/images/biltrax-icon/${login}`)">
        <div class="font-medium text-center mt-1 text-gray-150" style="font-size: 11px">Login Details</div>
      </div>
      <div class="w-full p-2 rounded-md my-4">
        <img class="mx-auto" style="height: 24px" :src="require(`/assets/images/biltrax-icon/${dash}`)">
        <div class="font-medium text-center mt-1 text-gray-150" style="font-size: 11px">List of Companies</div>
      </div>
    </div>
    <!--    sidebar end here-->

    <!--    internal content start here-->
    <div class="w-full bg-white">
      <div class="w-full family-lato" style="padding-left: 88px; padding-top: 46px;background: #EFF2F7;">
        <div class="w-full flex items-center justify-between px-4 bg-white border-b" style="height: 58px">
          <h4 class="text-lg font-semibold ">Dashboard</h4>
        </div>
        <div class="w-full p-4">
          <div class="w-full flex items-center gap-4">
            <div style="width: 50%">
              <div class="text-lg font-semibold mb-1">Summary</div>
              <div class="bg-white rounded-lg p-4">
                <div class="grid grid-cols-3 gap-5">
                  <div>
                    <div class="text-sm font-medium text-gray-500">Total Active Clients</div>
                    <div class="text-xl font-semibold text-gray-900">526</div>
                  </div>
                  <div>
                    <div class="text-sm font-medium text-gray-500">Total Clients</div>
                    <div class="text-xl font-semibold text-gray-900">526</div>
                  </div>
                  <div>
                    <div class="text-sm font-medium text-gray-500">Total Active Client Representatives</div>
                    <div class="text-xl font-semibold text-gray-900">526</div>
                  </div>
                  <div>
                    <div class="text-sm font-medium text-gray-500">Total Client Representatives</div>
                    <div class="text-xl font-semibold text-gray-900">526</div>
                  </div>
                  <div>
                    <div class="text-sm font-medium text-gray-500">Total Interactions</div>
                    <div class="text-xl font-semibold text-gray-900">526</div>
                  </div>
                  <div>
                    <div class="text-sm font-medium text-gray-500">Total Client Queries</div>
                    <div class="text-xl font-semibold text-gray-900">526</div>
                  </div>
                </div>
              </div>
            </div>
            <div style="width: 25%">
              <div class="text-lg font-semibold mb-1">Summary BX1</div>
              <div class="bg-white rounded-lg p-4">
                <div class="grid grid-cols-2 gap-5">
                  <div>
                    <div class="text-sm font-medium text-gray-500">Active Clients</div>
                    <div class="text-xl font-semibold text-gray-900">526</div>
                  </div>
                  <div>
                    <div class="text-sm font-medium text-gray-500">Active Client Representative</div>
                    <div class="text-xl font-semibold text-gray-900">526</div>
                  </div>
                  <div>
                    <div class="text-sm font-medium text-gray-500">Biltrax Analysts</div>
                    <div class="text-xl font-semibold text-gray-900">526</div>
                  </div>
                </div>
              </div>
            </div>
            <div style="width: 25%">
              <div class="text-lg font-semibold mb-1">Summary BX2</div>
              <div class="bg-white rounded-lg p-4">
                <div class="grid grid-cols-2 gap-5">
                  <div>
                    <div class="text-sm font-medium text-gray-500">Active Clients</div>
                    <div class="text-xl font-semibold text-gray-900">526</div>
                  </div>
                  <div>
                    <div class="text-sm font-medium text-gray-500">Active Client Representative</div>
                    <div class="text-xl font-semibold text-gray-900">526</div>
                  </div>
                  <div>
                    <div class="text-sm font-medium text-gray-500">Biltrax Analysts</div>
                    <div class="text-xl font-semibold text-gray-900">526</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          p-4
          <div class="grid grid-cols-12 gap-4 my-5">
            <div class="h-28 px-5 py-2.5 flex bg-red-100" style="border-radius: 5px">
              <div class="w-full my-auto">
                <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">50</div>
                <div class="text-base font-semibold " style="line-height: 20px">Active Clients</div>
              </div>
            </div>
            <div class="h-28 px-5 py-2.5 flex bg-blue-100" style="border-radius: 5px">
              <div class="w-full my-auto">
                <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">250</div>
                <div class="text-base font-semibold " style="line-height: 20px">Active Client Representative</div>
              </div>
            </div>
            <div class="h-28 px-5 py-2.5 flex bg-green-100" style="border-radius: 5px">
              <div class="w-full my-auto">
                <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">320</div>
                <div class="text-base font-semibold " style="line-height: 20px">Biltrax Analysts</div>
              </div>
            </div>
            <div class="h-28 px-5 py-2.5 flex bg-red-100" style="border-radius: 5px">
              <div class="w-full my-auto">
                <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">236</div>
                <div class="text-base font-semibold " style="line-height: 20px">Active Clients</div>
              </div>
            </div>
            <div class="h-28 px-5 py-2.5 flex bg-blue-100" style="border-radius: 5px">
              <div class="w-full my-auto">
                <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">324</div>
                <div class="text-base font-semibold " style="line-height: 20px">Active Client Representative</div>
              </div>
            </div>
            <div class="h-28 px-5 py-2.5 flex bg-green-100" style="border-radius: 5px">
              <div class="w-full my-auto">
                <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">321</div>
                <div class="text-base font-semibold " style="line-height: 20px">Biltrax Analysts</div>
              </div>
            </div>
            <div class="h-28 px-5 py-2.5 flex bg-red-100" style="border-radius: 5px">
              <div class="w-full my-auto">
                <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">500</div>
                <div class="text-base font-semibold " style="line-height: 20px">Total Active Clients</div>
              </div>
            </div>
            <div class="h-28 px-5 py-2.5 flex bg-blue-100" style="border-radius: 5px">
              <div class="w-full my-auto">
                <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">850</div>
                <div class="text-base font-semibold " style="line-height: 20px">Total Clients</div>
              </div>
            </div>
            <div class="h-28 px-5 py-2.5 flex bg-green-100" style="border-radius: 5px">
              <div class="w-full my-auto">
                <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">254</div>
                <div class="text-base font-semibold " style="line-height: 20px">Total Active Client Representatives</div>
              </div>
            </div>
            <div class="h-28 px-5 py-2.5 flex bg-red-100" style="border-radius: 5px">
              <div class="w-full my-auto">
                <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">500</div>
                <div class="text-base font-semibold " style="line-height: 20px">Total Client Representatives</div>
              </div>
            </div>
            <div class="h-28 px-5 py-2.5 flex bg-blue-100" style="border-radius: 5px">
              <div class="w-full my-auto">
                <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">850</div>
                <div class="text-base font-semibold " style="line-height: 20px">Total Interactions</div>
              </div>
            </div>
            <div class="h-28 px-5 py-2.5 flex bg-green-100" style="border-radius: 5px">
              <div class="w-full my-auto">
                <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">254</div>
                <div class="text-base font-semibold " style="line-height: 20px">Total Client Queries</div>
              </div>
            </div>
          </div>
          <div class="grid grid-cols-2 gap-4 ">
            <div class="bg-white p-5 col-span-2" style="border-radius: 5px">
              <div class="text-lg font-semibold mb-4">Summary</div>
              <div class="grid grid-cols-6 gap-4">
                <div class="h-28 px-5 py-2.5 flex bg-red-100" style="border-radius: 5px">
                  <div class="w-full my-auto">
                    <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">500</div>
                    <div class="text-base font-semibold " style="line-height: 20px">Total Active Clients</div>
                  </div>
                </div>
                <div class="h-28 px-5 py-2.5 flex bg-blue-100" style="border-radius: 5px">
                  <div class="w-full my-auto">
                    <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">850</div>
                    <div class="text-base font-semibold " style="line-height: 20px">Total Clients</div>
                  </div>
                </div>
                <div class="h-28 px-5 py-2.5 flex bg-green-100" style="border-radius: 5px">
                  <div class="w-full my-auto">
                    <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">254</div>
                    <div class="text-base font-semibold " style="line-height: 20px">Total Active Client Representatives</div>
                  </div>
                </div>
                <div class="h-28 px-5 py-2.5 flex bg-red-100" style="border-radius: 5px">
                  <div class="w-full my-auto">
                    <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">500</div>
                    <div class="text-base font-semibold " style="line-height: 20px">Total Client Representatives</div>
                  </div>
                </div>
                <div class="h-28 px-5 py-2.5 flex bg-blue-100" style="border-radius: 5px">
                  <div class="w-full my-auto">
                    <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">850</div>
                    <div class="text-base font-semibold " style="line-height: 20px">Total Interactions</div>
                  </div>
                </div>
                <div class="h-28 px-5 py-2.5 flex bg-green-100" style="border-radius: 5px">
                  <div class="w-full my-auto">
                    <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">254</div>
                    <div class="text-base font-semibold " style="line-height: 20px">Total Client Queries</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="bg-white p-5" style="border-radius: 5px">
              <div class="text-lg font-semibold mb-4">BX1 Summary</div>
              <div class="grid grid-cols-3 gap-4">
                <div class="h-28 px-5 py-2.5 flex bg-red-100" style="border-radius: 5px">
                  <div class="w-full my-auto">
                    <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">50</div>
                    <div class="text-base font-semibold " style="line-height: 20px">Active Clients</div>
                  </div>
                </div>
                <div class="h-28 px-5 py-2.5 flex bg-blue-100" style="border-radius: 5px">
                  <div class="w-full my-auto">
                    <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">250</div>
                    <div class="text-base font-semibold " style="line-height: 20px">Active Client Representative</div>
                  </div>
                </div>
                <div class="h-28 px-5 py-2.5 flex bg-green-100" style="border-radius: 5px">
                  <div class="w-full my-auto">
                    <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">320</div>
                    <div class="text-base font-semibold " style="line-height: 20px">Biltrax Analysts</div>
                  </div>
                </div>
              </div>

            </div>
            <div class="bg-white p-5" style="border-radius: 5px">
              <div class="text-lg font-semibold mb-4">BX2 Summary</div>
              <div class="grid grid-cols-3 gap-4">
                <div class="h-28 px-5 py-2.5 flex bg-red-100" style="border-radius: 5px">
                  <div class="w-full my-auto">
                    <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">236</div>
                    <div class="text-base font-semibold " style="line-height: 20px">Active Clients</div>
                  </div>
                </div>
                <div class="h-28 px-5 py-2.5 flex bg-blue-100" style="border-radius: 5px">
                  <div class="w-full my-auto">
                    <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">324</div>
                    <div class="text-base font-semibold " style="line-height: 20px">Active Client Representative</div>
                  </div>
                </div>
                <div class="h-28 px-5 py-2.5 flex bg-green-100" style="border-radius: 5px">
                  <div class="w-full my-auto">
                    <div class="font-light mb-2.5" style="font-size: 30px; line-height: 30px">321</div>
                    <div class="text-base font-semibold " style="line-height: 20px">Biltrax Analysts</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="grid grid-cols-2 gap-4 my-4">
            <div v-for="item in 4" class="bg-white rounded-lg h-96"></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data(){
    return{
      name: "dashboard",
      image:'biltrax.png',
      companies:'companies.png',
      login:'login.png',
      user:'user.png',
      dash:'dash.png',
    }
  }
}
</script>

<style scoped>

.h-15{
  height: 46px;
}
.h-screen-46{
  height: calc(100vh - 46px);
}
.w-88{
  width: 88px;
}
.bg-biltrax{
  background-color: #B8112E;
}
.text-biltrax{
  color: #B8112E;
}
.bg-gray-150{
  background-color: #F0F0F7;
}
.text-gray-250{
  color: #494949;
}
.text-gray-150{
  color: #F0F0F7;
}
.p-tr-20{
  padding-left: 88px;
  padding-top: 46px;
}
.bg-light-red{
  background-color: #FDEDF0;
}
.h-screen--10px{
  height: calc(100vh - 70px);
}
.col-span-3-5{
  grid-column: span 3.5 / span 3.5;
}
</style>
