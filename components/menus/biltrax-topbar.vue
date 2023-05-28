<template>
    <div class="w-full z-40 bg-white fixed border-b top-0 h-16 flex">
        <div class="w-full max-w-screen-2xl m-auto">
            <div class="flex justify-between items-center">
                <div class="h-full flex">
                    <div class="py-2 px-20">
                      <img src="../../assets/images/biltrax.webp" alt="logo" class="h-9 w-auto"/>
                    </div>
                </div>
                <div class="my-auto px-5 flex">
                    <div class="my-auto h-10 w-10 rounded-md flex mx-2">
                        <svg xmlns="http://www.w3.org/2000/svg"  class="h-5 w-5 m-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9" />
                        </svg>
                    </div>
                    <div class="my-auto h-10 w-10 rounded-md flex mr-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 m-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M11 5.882V19.24a1.76 1.76 0 01-3.417.592l-2.147-6.15M18 13a3 3 0 100-6M5.436 13.683A4.001 4.001 0 017 6h1.832c4.1 0 7.625-1.234 9.168-3v14c-1.543-1.766-5.067-3-9.168-3H7a3.988 3.988 0 01-1.564-.317z" />
                        </svg>
                    </div>
                    <div class="flex my-auto">
                      <div class="text-sm font-medium my-auto mx-2">Super Admin</div>
                      <img class="rounded-full h-11 w-11" src="https://themesbrand.com/qovex/layouts/assets/images/users/avatar-2.jpg">
                      <svg class="h-4 w-4 my-auto mx-2" fill="currentColor" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M13.418 7.859a.695.695 0 01.978 0 .68.68 0 010 .969l-3.908 3.83a.697.697 0 01-.979 0l-3.908-3.83a.68.68 0 010-.969.695.695 0 01.978 0L10 11l3.418-3.141z"/></svg>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "biltrax-topbar"
}
</script>

<style scoped>

.form-control {
    background-color: rgba(243,243,249,.07);
    color: #fff;
    border: none;
    height: 38px;
    padding-left: 40px;
    padding-right: 20px;
    /*background-color: #f3f3f9;*/
    -webkit-box-shadow: none;
    box-shadow: none;
    border-radius: 7px;
}
</style>
