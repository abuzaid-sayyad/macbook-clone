<template>
  <div class="overflow-hidden">
<!--    <div class="window-bar relative h-6 text-center bg-gray-200 z-50">-->
<!--      <div class="traffic_lights flex flex-row absolute left-0 space-x-2 pl-2 mt-1.5">-->
<!--        <button class="w-3 h-3 rounded-full bg-red-500 outline-none focus:outline-none inline-flex justify-center items-center">-->
<!--          <svg class="m-auto" stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 512 512" height="11" width="11" xmlns="http://www.w3.org/2000/svg"><path fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="32" d="M368 368L144 144m224 0L144 368"></path></svg>-->
<!--        </button>-->
<!--        <button class="w-3 h-3 rounded-full bg-yellow-500 outline-none focus:outline-none inline-flex justify-center items-center">-->
<!--          <svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" height="11" width="11" xmlns="http://www.w3.org/2000/svg"><line x1="5" y1="12" x2="19" y2="12"></line></svg>-->
<!--        </button>-->
<!--        <button class="w-3 h-3 rounded-full bg-green-500 outline-none focus:outline-none  inline-flex justify-center items-center">-->
<!--          <svg viewBox="0 0 13 13" width="6.5" height="6.5" xmlns="http://www.w3.org/2000/svg" fill-rule="evenodd" clip-rule="evenodd" stroke-linejoin="round" stroke-miterlimit="2"><path fill="none" d="M0 0h12.038v12.038H0z"></path><path d="M9.26 12.03L.006 2.73v9.3H9.26zM2.735.012l9.3 9.3v-9.3h-9.3z"></path></svg>-->
<!--        </button>-->
<!--      </div>-->
<!--      <span class="font-semibold text-gray-700">WhatsApp</span>-->
<!--    </div>-->
    <div class="w-full flex h-screen" style="background-color: #D8DBD6">
      <div class="w-full fixed top-0" style="height: 127px; background-color: #009688"></div>
      <div class="z-50 w-full py-5">
        <div class="mx-auto bg-white box-shadow" style="max-width: 86.2rem;background-color: #D8DBD6">
          <div class="grid md:grid-cols-7 h-full">
            <div class="col-span-2 h-full relative h-full overflow-hidden">
              <div class="flex flex-col h-full">
                <div class="hidden md:block">
                  <div class="flex items-center w-full" style="padding: 10px 16px;height: 59px; background-color: #ededed">
                    <div class="flex justify-between w-full">
                      <div class="relative h-10 w-10 rounded-full">
                        <div class="left-0 absolute top-0 flex justify-center items-center w-full h-full">
                          <img class="rounded-full visible h-full w-full cursor-pointer" :src="require(`~/assets/images/${images}`)">
                        </div>
                      </div>
                      <div class="flex">
                        <div class="flex items-center">
                          <svg class="cursor-pointer" style="color: #919191" id="df9d3429-f0ef-48b5-b5eb-f9d27b2deba6" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24"><path fill="currentColor" d="M12.072 1.761a10.05 10.05 0 0 0-9.303 5.65.977.977 0 0 0 1.756.855 8.098 8.098 0 0 1 7.496-4.553.977.977 0 1 0 .051-1.952zM1.926 13.64a10.052 10.052 0 0 0 7.461 7.925.977.977 0 0 0 .471-1.895 8.097 8.097 0 0 1-6.012-6.386.977.977 0 0 0-1.92.356zm13.729 7.454a10.053 10.053 0 0 0 6.201-8.946.976.976 0 1 0-1.951-.081v.014a8.097 8.097 0 0 1-4.997 7.209.977.977 0 0 0 .727 1.813l.02-.009z"></path><path fill="#009588" d="M19 1.5a3 3 0 1 1 0 6 3 3 0 0 1 0-6z"></path></svg>
                          <svg class="mx-6 cursor-pointer" style="color: #919191" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24"><path fill="currentColor" d="M19.005 3.175H4.674C3.642 3.175 3 3.789 3 4.821V21.02l3.544-3.514h12.461c1.033 0 2.064-1.06 2.064-2.093V4.821c-.001-1.032-1.032-1.646-2.064-1.646zm-4.989 9.869H7.041V11.1h6.975v1.944zm3-4H7.041V7.1h9.975v1.944z"></path></svg>
                          <svg class="cursor-pointer" style="color: #919191" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24"><path fill="currentColor" d="M12 7a2 2 0 1 0-.001-4.001A2 2 0 0 0 12 7zm0 2a2 2 0 1 0-.001 3.999A2 2 0 0 0 12 9zm0 6a2 2 0 1 0-.001 3.999A2 2 0 0 0 12 15z"></path></svg>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div style="background-color: #f6f6f6">
                    <div class="px-4 flex" style="height: 49px">
                      <div class="w-full my-auto relative" style="height: 35px">
                        <input class="w-full rounded-full focus:outline-none bg-white h-full text-sm font-normal placeholder-gray-500 pl-16 pr-3" placeholder="Search or start new chat">
                        <svg class="absolute top-1.5 left-3" style="color: #919191" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24"><path fill="currentColor" d="M15.009 13.805h-.636l-.22-.219a5.184 5.184 0 0 0 1.256-3.386 5.207 5.207 0 1 0-5.207 5.208 5.183 5.183 0 0 0 3.385-1.255l.221.22v.635l4.004 3.999 1.194-1.195-3.997-4.007zm-4.808 0a3.605 3.605 0 1 1 0-7.21 3.605 3.605 0 0 1 0 7.21z"></path></svg>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="md:hidden" style="background-color: #009688">
                  <div class="flex items-center w-full" style="padding: 10px 16px;height: 59px;">
                    <div class="flex justify-between items-center w-full h-full">
                      <div class="text-lg font-medium family-poppins text-white">WhatsApp</div>
                      <div class="flex items-center text-white">
                        <svg viewBox="0 0 24 24" class="cursor-pointer" width="24" height="24"><path fill="currentColor" d="M15.9 14.3H15l-.3-.3c1-1.1 1.6-2.7 1.6-4.3 0-3.7-3-6.7-6.7-6.7S3 6 3 9.7s3 6.7 6.7 6.7c1.6 0 3.2-.6 4.3-1.6l.3.3v.8l5.1 5.1 1.5-1.5-5-5.2zm-6.2 0c-2.6 0-4.6-2.1-4.6-4.6s2.1-4.6 4.6-4.6 4.6 2.1 4.6 4.6-2 4.6-4.6 4.6z"></path></svg>

                        <svg class="cursor-pointer ml-6" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24"><path fill="currentColor" d="M12 7a2 2 0 1 0-.001-4.001A2 2 0 0 0 12 7zm0 2a2 2 0 1 0-.001 3.999A2 2 0 0 0 12 9zm0 6a2 2 0 1 0-.001 3.999A2 2 0 0 0 12 15z"></path></svg>
                      </div>
                    </div>
                  </div>
                  <div style="height: 49px">
                    <div class="flex items-center h-full">
                      <div class="px-3">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-200" viewBox="0 0 20 20" fill="currentColor">
                          <path fill-rule="evenodd" d="M4 5a2 2 0 00-2 2v8a2 2 0 002 2h12a2 2 0 002-2V7a2 2 0 00-2-2h-1.586a1 1 0 01-.707-.293l-1.121-1.121A2 2 0 0011.172 3H8.828a2 2 0 00-1.414.586L6.293 4.707A1 1 0 015.586 5H4zm6 9a3 3 0 100-6 3 3 0 000 6z" clip-rule="evenodd" />
                        </svg>
                      </div>
                      <div class="w-full h-full flex justify-between">
                        <div class="w-1/3 h-full  border-b-4 border-white flex justify-center items-center">
                          <div class="text-base font-medium text-white">CHATS</div>
                          <div class="h-6 w-6 rounded-full ml-1 flex bg-white"><span class="m-auto text-xs font-medium">15</span></div>
                        </div>
                        <div class="w-1/3 h-full  border-b-2 border-white flex justify-center items-center">
                          <div class="text-base font-medium text-white">STATUS</div>
                        </div>
                        <div class="w-1/3 h-full  border-b-2 border-white flex justify-center items-center">
                          <div class="text-base font-medium text-white">CALLS</div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>

                <div class="bg-white  flex-grow flex flex-col">
                  <div class="h-screen-whatsapp overflow-y-auto">
                    <div @click="isOpen = !isOpen" v-for="(item, index) in ChatData" class="flex justify-between items-center hover:bg-gray-100 cursor-pointer" style="height: 72px">
                      <div class="flex items-center h-full w-full">
                        <div class="px-4">
                          <div class="mt-0.5" style="height: 49px; width: 49px;" >
                            <img class="rounded-full" height="49px" width="49px" :src="require(`~/assets/images/whatsapp/${item.image}`)">
                          </div>
                        </div>
                        <div class="h-full w-full">
                          <div class="h-full w-full pr-2">
                            <div class="border-b h-full w-full flex">
                              <div class="flex justify-between my-auto w-full">
                                <div>
                                  <div>
                                    <div v-if="item.count" class="font-medium" style="font-size: 17px; color: #000000">{{item.name}}</div>
                                    <div v-else class="font-normal" style="font-size: 17px; color: #000000">{{item.name}}</div>
                                  </div>
                                  <div v-if="item.count" class="flex items-center">
                                    <div class="text-sm font-medium text-black" >{{item.message_sender}}</div>
                                  </div>
                                  <div v-else>
                                    <div v-if="item.sent_message" class="flex items-center">
                                      <svg class="-mt-1 mx-px" style="color: #4fc3f7" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 18 18" width="18" height="18"><path fill="currentColor" d="M17.394 5.035l-.57-.444a.434.434 0 0 0-.609.076l-6.39 8.198a.38.38 0 0 1-.577.039l-.427-.388a.381.381 0 0 0-.578.038l-.451.576a.497.497 0 0 0 .043.645l1.575 1.51a.38.38 0 0 0 .577-.039l7.483-9.602a.436.436 0 0 0-.076-.609zm-4.892 0l-.57-.444a.434.434 0 0 0-.609.076l-6.39 8.198a.38.38 0 0 1-.577.039l-2.614-2.556a.435.435 0 0 0-.614.007l-.505.516a.435.435 0 0 0 .007.614l3.887 3.8a.38.38 0 0 0 .577-.039l7.483-9.602a.435.435 0 0 0-.075-.609z"></path></svg>
                                      <div class="text-sm font-normal" style="color: rgba(0,0,0,0.8)">{{ item.sent_message }}</div>
                                    </div>
                                    <div v-else class="flex items-center">
                                      <svg class="-mt-1" style="color: #0000004d" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 14 18" width="14" height="18"><path fill="currentColor" d="M12.502 5.035l-.57-.444a.434.434 0 0 0-.609.076l-6.39 8.198a.38.38 0 0 1-.577.039l-2.614-2.556a.435.435 0 0 0-.614.007l-.505.516a.435.435 0 0 0 .007.614l3.887 3.8a.38.38 0 0 0 .577-.039l7.483-9.602a.435.435 0 0 0-.075-.609z"></path></svg>
                                      <svg class="mx-px" style="color: #0000004d" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 20" width="16" height="20"><path fill="currentColor" d="M13.822 4.668H7.14l-1.068-1.09a1.068 1.068 0 0 0-.663-.278H3.531c-.214 0-.51.128-.656.285L1.276 5.296c-.146.157-.266.46-.266.675v1.06l-.001.003v6.983c0 .646.524 1.17 1.17 1.17h11.643a1.17 1.17 0 0 0 1.17-1.17v-8.18a1.17 1.17 0 0 0-1.17-1.169zm-5.982 8.63a3.395 3.395 0 1 1 0-6.79 3.395 3.395 0 0 1 0 6.79zm0-5.787a2.392 2.392 0 1 0 0 4.784 2.392 2.392 0 0 0 0-4.784z"></path></svg>
                                      <div class="text-sm font-normal" style="color: rgba(0,0,0,0.8)">Photo</div>
                                    </div>
                                  </div>
                                </div>
                                <div>
                                  <div class="text-xs font-normal px-2 mt-1.5" style="color: rgba(0,0,0,0.45)">{{item.time}}</div>
                                  <div v-if="item.count" class="rounded-full h-5 w-5 float-right flex mx-2 mt-1" style="background-color: #06d755">
                                    <span class="m-auto text-xs font-medium text-white ">{{item.count}}</span>
                                  </div>
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-span-5 h-full relative hidden md:block" style="background-color: #F8F9FA">
              <div v-if="!isOpen" class="py-7 flex justify-center w-full h-full items-center flex-grow box-border border-l">
                <div class="-mt-5 text-center w-4/5" style="max-width: 460px">
                  <img class="m-auto" height="355px" width="356px" style="transform: scale(1); opacity: 1;" :src="require(`~/assets/images/${image}`)">
                  <div style="opacity: 1; transform: translateY(0px);">
                    <h1 class="font-light text-4xl mt-9" style="color: #525252">Keep your phone connected</h1>
                    <div class="mt-6 text-sm font-normal " style="color: rgba(0, 0, 0, 0.45)">WhatsApp connects to your phone to sync messages. To reduce data usage, connect your phone to Wi-Fi.</div>
                    <div class="mt-8 ">
                      <div class="mb-8 h-px" style="background-color: #00000014"></div>
                      <div class="flex justify-center">
                        <div class="flex items-center text-sm" style="color: #00000073">
                      <span class="mt-px" style="color: #919191">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 21 18" width="21" height="18"><path fill="currentColor" d="M10.426 14.235a.767.767 0 0 1-.765-.765c0-.421.344-.765.765-.765s.765.344.765.765-.344.765-.765.765zM4.309 3.529h12.235v8.412H4.309V3.529zm12.235 9.942c.841 0 1.522-.688 1.522-1.529l.008-8.412c0-.842-.689-1.53-1.53-1.53H4.309c-.841 0-1.53.688-1.53 1.529v8.412c0 .841.688 1.529 1.529 1.529H1.25c0 .842.688 1.53 1.529 1.53h15.294c.841 0 1.529-.688 1.529-1.529h-3.058z"></path></svg>
                      </span>
                          <div class="mt-1">
                            WhatsApp is available for Windows.<a href="#" style="color: #0aa545">Get it here</a>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div v-if="isOpen">
                <chat-section></chat-section>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import ChatSection from "../components/WhatsApp/ChatSection";
export default {
  name: "whatsapp",
  components: {ChatSection},
  data(){
    return{
      isOpen: false,
      image:'intro-connection-light_c98cc75f2aa905314d74375a975d2cf2.jpg',
      images:'zaid.jpeg',
      image2:'zaid.jpeg',
      ChatData:[
        {id:1, image:'noetic-group.jpeg', isOpen:'true', name:'Noetic IT Services Core', time:'1:21 AM', count:'1', message_sender:'Nitish Kumar Sir: Ok'},
        {id:1, image:'zaid.jpeg', name:'Abuzaid Sayyad', isOpen:'true', time:'2:30 AM'},
        {id:1, image:'juned.jpeg', name:'Juned Shaikh', time:'2:33 AM', count: '2', message_sender: 'Where are you?'},
        {id:1, image:'nitish-sir.jpeg', name:'Nitish Kumar Sir', time:'2:40 AM', sent_message:'Ok'},
        {id:1, image:'group.svg', name:'Noetic Marketing Work', time:'2:45 AM'},
        {id:1, image:'rubal.jpeg', name:'Rubal Gulati', time:'3:21 AM'},
        {id:1, image:'group.svg', name:'Noetic UI/UX', time:'4:52 AM',  sent_message:'We are working on it'},
        {id:1, image:'solo.svg', name:'Pooja Bisht', time:'6:45 AM'},
        {id:1, image:'solo.svg', name:'Ruchira', time:'7:21 AM'},
        {id:1, image:'solo.svg', name:'Pooja Bisht', time:'8:30 AM'},
        {id:1, image:'solo.svg', name:'Ruchira', time:'8:35 AM'},
        {id:1, image:'solo.svg', name:'Pooja Bisht', time:'9:30 AM'},
        {id:1, image:'solo.svg', name:'Ruchira', time:'10:21 AM'},
        {id:1, image:'solo.svg', name:'Pooja Bisht', time:'11:00 AM'},
        {id:1, image:'solo.svg', name:'Ruchira', time:'5:21 AM'},
      ]
    }
  }
}
</script>

<style scoped>
.box-shadow{
  box-shadow: 0 1px 1px 0 rgba(0,0,0,0.08),0 2px 5px 0 rgba(0,0,0,0.08);
}
.h-screen-whatsapp{
  height: calc(100vh - 147px);
}

/* width */
::-webkit-scrollbar {
  width: 6px;
}
/* Track */
::-webkit-scrollbar-track {
  background: white;
}
/* Handle */
::-webkit-scrollbar-thumb {
  background: #b5b6b9;
}
</style>
