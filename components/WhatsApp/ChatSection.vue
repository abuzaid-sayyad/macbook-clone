<template>
  <div class="h-full">
    <div class="flex items-center w-full border-l border-gray-300" style="padding: 10px 16px;height: 59px; background-color: #ededed; border-bottom: 1px solid #F3F4F6">
      <div class="flex justify-between w-full">
        <div class="flex items-center">
          <div class="relative h-10 w-10 rounded-full">
            <div class="left-0 absolute top-0 flex justify-center items-center w-full h-full">
              <img class="rounded-full visible h-full w-full cursor-pointer" :src="require(`~/assets/images/whatsapp/${images}`)">
            </div>
          </div>
          <div class="ml-3">
            <h6 class="text-base font-normal text-black">Noetic UI/UX</h6>
            <p class="font-normal " style="font-size: 13px; color: rgba(0,0,0, 0.6)">Juned, Nitish, Rubal and You</p>
          </div>
        </div>
        <div class="flex">
          <div class="flex items-center">
            <svg viewBox="0 0 24 24" class="cursor-pointer" style="color: #919191" width="24" height="24"><path fill="currentColor" d="M15.9 14.3H15l-.3-.3c1-1.1 1.6-2.7 1.6-4.3 0-3.7-3-6.7-6.7-6.7S3 6 3 9.7s3 6.7 6.7 6.7c1.6 0 3.2-.6 4.3-1.6l.3.3v.8l5.1 5.1 1.5-1.5-5-5.2zm-6.2 0c-2.6 0-4.6-2.1-4.6-4.6s2.1-4.6 4.6-4.6 4.6 2.1 4.6 4.6-2 4.6-4.6 4.6z"></path></svg>

            <svg class="cursor-pointer ml-6" style="color: #919191" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24"><path fill="currentColor" d="M12 7a2 2 0 1 0-.001-4.001A2 2 0 0 0 12 7zm0 2a2 2 0 1 0-.001 3.999A2 2 0 0 0 12 9zm0 6a2 2 0 1 0-.001 3.999A2 2 0 0 0 12 15z"></path></svg>
          </div>
        </div>
      </div>
    </div>
    <div class="w-full overflow-y-auto" style="height: calc(100vh - 157px); background-color: #e5ddd5; padding-left: 9%; padding-right: 9%">
      <div class="w-full flex sticky top-2">
        <button class="mx-auto uppercase cursor-default mb-3 focus:outline-none" style="background-color: #e1f5feeb; padding: 5px 12px 6px; font-size: 13px; color: rgba(0,0,0,0.88); border-radius: 7.5px;">Today</button>
      </div>
      <div v-for="(item, index) in chatData" class="w-full">
        <div v-for="(ele, index) in item.FriendsMessage" class="w-full justify-start flex mb-3">
          <div class="justify-start flex" style="width: 60%">
            <div class="rounded bg-white" style="padding: 6px 7px 0 9px; color: #303030">
              <div class="font-medium" :style="'font-size: 13px; ' +ele.text_color">{{ele.user_name}}</div>
              <div class="text-sm font-normal">{{ele.friend_msg}}</div>
              <div class="flex justify-end">
                <span class="font-normal ml-2.5" style="font-size: 11px; color: rgba(0,0,0,0.45); margin-top: -1px">{{ele.friend_time}}</span>
              </div>
            </div>
          </div>
        </div>
        <div v-if="ele.my_msg" v-for="(ele, index) in item.MyMessage" class="w-full justify-end flex mb-3">
          <div class="flex justify-end" style="width: 60%">
            <div class="rounded" style="padding: 6px 7px 0 9px; color: #303030; background-color: #dcf8c6">
              <div class="text-sm font-normal">{{ele.my_msg}}</div>
              <div class="flex justify-end">
                <span class="font-normal ml-2.5" style="font-size: 11px; color: rgba(0,0,0,0.45); margin-top: -1px">{{ele.my_time}}</span>
                <svg class="ml-1" style="color: #4fc3f7" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 18 18" width="15" height="15"><path fill="currentColor" d="M17.394 5.035l-.57-.444a.434.434 0 0 0-.609.076l-6.39 8.198a.38.38 0 0 1-.577.039l-.427-.388a.381.381 0 0 0-.578.038l-.451.576a.497.497 0 0 0 .043.645l1.575 1.51a.38.38 0 0 0 .577-.039l7.483-9.602a.436.436 0 0 0-.076-.609zm-4.892 0l-.57-.444a.434.434 0 0 0-.609.076l-6.39 8.198a.38.38 0 0 1-.577.039l-2.614-2.556a.435.435 0 0 0-.614.007l-.505.516a.435.435 0 0 0 .007.614l3.887 3.8a.38.38 0 0 0 .577-.039l7.483-9.602a.435.435 0 0 0-.075-.609z"></path></svg>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="flex items-center w-full border-l border-gray-300" style="padding: 10px 16px;height: 59px; background-color: #ededed; border-bottom: 1px solid #F3F4F6">
      <div class="flex items-center w-full">
        <div>
          <svg viewBox="0 0 24 24" width="24" height="24" style="color: #51585c" class="mr-2"><path fill="currentColor" d="M9.153 11.603c.795 0 1.439-.879 1.439-1.962s-.644-1.962-1.439-1.962-1.439.879-1.439 1.962.644 1.962 1.439 1.962zm-3.204 1.362c-.026-.307-.131 5.218 6.063 5.551 6.066-.25 6.066-5.551 6.066-5.551-6.078 1.416-12.129 0-12.129 0zm11.363 1.108s-.669 1.959-5.051 1.959c-3.505 0-5.388-1.164-5.607-1.959 0 0 5.912 1.055 10.658 0zM11.804 1.011C5.609 1.011.978 6.033.978 12.228s4.826 10.761 11.021 10.761S23.02 18.423 23.02 12.228c.001-6.195-5.021-11.217-11.216-11.217zM12 21.354c-5.273 0-9.381-3.886-9.381-9.159s3.942-9.548 9.215-9.548 9.548 4.275 9.548 9.548c-.001 5.272-4.109 9.159-9.382 9.159zm3.108-9.751c.795 0 1.439-.879 1.439-1.962s-.644-1.962-1.439-1.962-1.439.879-1.439 1.962.644 1.962 1.439 1.962z"></path></svg>
        </div>
        <div style="padding: 8px">
          <svg viewBox="0 0 24 24" width="24" height="24" style="color: #51585c" class=""><path fill="currentColor" d="M1.816 15.556v.002c0 1.502.584 2.912 1.646 3.972s2.472 1.647 3.974 1.647a5.58 5.58 0 0 0 3.972-1.645l9.547-9.548c.769-.768 1.147-1.767 1.058-2.817-.079-.968-.548-1.927-1.319-2.698-1.594-1.592-4.068-1.711-5.517-.262l-7.916 7.915c-.881.881-.792 2.25.214 3.261.959.958 2.423 1.053 3.263.215l5.511-5.512c.28-.28.267-.722.053-.936l-.244-.244c-.191-.191-.567-.349-.957.04l-5.506 5.506c-.18.18-.635.127-.976-.214-.098-.097-.576-.613-.213-.973l7.915-7.917c.818-.817 2.267-.699 3.23.262.5.501.802 1.1.849 1.685.051.573-.156 1.111-.589 1.543l-9.547 9.549a3.97 3.97 0 0 1-2.829 1.171 3.975 3.975 0 0 1-2.83-1.173 3.973 3.973 0 0 1-1.172-2.828c0-1.071.415-2.076 1.172-2.83l7.209-7.211c.157-.157.264-.579.028-.814L11.5 4.36a.572.572 0 0 0-.834.018l-7.205 7.207a5.577 5.577 0 0 0-1.645 3.971z"></path></svg>
        </div>
        <input class="w-full px-5 py-2 rounded-full font-normal ml-3 focus:outline-none" placeholder="Type a message..." style="font-size: 15px">
        <div style="padding: 12px">
          <svg viewBox="0 0 24 24" width="24" height="24" style="color: #51585c" class=""><path fill="currentColor" d="M11.999 14.942c2.001 0 3.531-1.53 3.531-3.531V4.35c0-2.001-1.53-3.531-3.531-3.531S8.469 2.35 8.469 4.35v7.061c0 2.001 1.53 3.531 3.53 3.531zm6.238-3.53c0 3.531-2.942 6.002-6.237 6.002s-6.237-2.471-6.237-6.002H3.761c0 4.001 3.178 7.297 7.061 7.885v3.884h2.354v-3.884c3.884-.588 7.061-3.884 7.061-7.885h-2z"></path></svg>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: "ChatSection",
  data(){
    return{
      images:'group.svg',
      whatsapp_bg:'whatsapp-bg.png',
      chatData:[
        {
          FriendsMessage:[
            {user_name:'Nitish Kumar', text_color:'color: #35cd96', friend_msg:'How likely are you to recommend our company to your friends and family?', friend_time:'11:30 AM',},
            {user_name:'Juned Shaikh', text_color:'color: #e542a3', friend_msg:'Hey there, we’re just writing to let you know that you’ve been subscribed to a repository on GitHub.', friend_time:'11:33 AM',},
            {user_name:'Nitish Kumar', text_color:'color: #35cd96', friend_msg:'Ok, Understood!', friend_time:'11:40 AM',},
          ],
          MyMessage:[
            {my_msg:'You’ll receive notifications for all issues, pull requests!', my_time:'11:45 AM',},
          ]
        },
        {
          FriendsMessage:[
            {user_name:'Rubal Gulati', text_color:'color: #6bcbef', friend_msg:'You can unwatch this repository immediately by clicking here: https://github.com', friend_time:'12:00 AM',},
          ],
          MyMessage:[
            {my_msg:'Discover what students who viewed Learn Figma - UI/UX Design. Essential Training also viewed', my_time:'12:10 AM',},
          ]
        },
        {
          FriendsMessage:[
            {user_name:'Nitish Kumar', text_color:'color: #35cd96', friend_msg:'Most purchased Business courses during this sale!', friend_time:'12:11 AM',},
          ],
          MyMessage:[
            {my_msg:'Company BBQ to celebrate the last quater achievements and goals. Food and drinks provided', my_time:'12:30 AM',},
            {my_msg:'ok.', my_time:'12:30 AM',},
          ]
        },
      ]
    }
  }
}
</script>

<style scoped>
/* width */
::-webkit-scrollbar {
  width: 6px;
}
/* Track */
::-webkit-scrollbar-track {
  background: transparent;
}
/* Handle */
::-webkit-scrollbar-thumb {
  background: #b5b6b9;
}
</style>
