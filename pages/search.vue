<template>
  <div class="w-full">
    <div class="flex justify-between items-center bg-white border-b py-2">
      <div class="flex items-center pl-4">
        <div class="flex items-center my-auto text-indigo-500 border-b-2 border-indigo-500 pb-1.5 cursor-pointer">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z" />
          </svg>
          <div class="family-poppins  text-sm font-medium ml-1.5">Project List</div>
        </div>
        <div class="flex items-center ml-5 cursor-pointer my-auto">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
          </svg>
          <div class="family-poppins text-gray-700 text-sm font-medium ml-1.5">Visualization</div>
        </div>
        <div class="flex items-center ml-5 cursor-pointer">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 20l-5.447-2.724A1 1 0 013 16.382V5.618a1 1 0 011.447-.894L9 7m0 13l6-3m-6 3V7m6 10l4.553 2.276A1 1 0 0021 18.382V7.618a1 1 0 00-.553-.894L15 4m0 13V4m0 0L9 7" />
          </svg>
          <div class="family-poppins text-gray-700 text-sm font-medium ml-1.5">Map</div>
        </div>
        <div class="flex items-center ml-5 cursor-pointer">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
          </svg>
          <div class="family-poppins text-gray-700 text-sm font-medium ml-1.5">Location</div>
        </div>
      </div>
      <div class="flex items-center my-auto">
        <button class="py-1.5 px-2.5  focus:outline-none rounded-md text-sm font-medium family-poppins text-yellow-500 hover:text-white bg-yellow-100 hover:bg-yellow-500">Save Search</button>
        <button class="py-1.5 px-2.5 my-auto ml-2.5 focus:outline-none rounded-md text-sm font-medium family-poppins text-blue-500 hover:text-white bg-blue-100 hover:bg-blue-500">Admin Export</button>
        <button class="py-1.5 px-2.5 ml-2.5 focus:outline-none rounded-md text-sm font-medium family-poppins text-green-500 hover:text-white bg-green-100 hover:bg-green-500">Sub Export</button>
        <button @click="headerColumn = ! headerColumn" class="py-1.5 px-2.5 mx-2.5 focus:outline-none rounded-md text-sm font-medium family-poppins text-yellow-500 hover:text-white bg-yellow-100 hover:bg-yellow-500">Setting</button>
      </div>
    </div>
    <div class="flex items-center bg-white my-auto py-3 pl-4">
      <div class="family-poppins text-indigo-500 text-sm font-medium">Dashboard</div>
      <svg class="w-6 h-6 mx-1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path fill="#000" d="M7.8 10a2.2 2.2 0 004.4 0 2.2 2.2 0 00-4.4 0z"/></svg>
      <div class="family-poppins text-gray-800 text-sm font-medium">Project Search</div>
    </div>
    <div class="w-full bg-gray-100 px-4 py-3">
      <div class="mx-6 my-4 grid grid-cols-7 gap-4">

        <div class="col-span-2 border bg-white p-4">
          <div class="flex items-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
            </svg>
            <div class="family-poppins text-sm font-medium text-gray-700 ml-3">Keywords</div>
          </div>
          <input class="text-sm family-poppins font-medium py-2.5 px-4 mt-2.5 w-full rounded-lg bg-gray-100 focus:outline-none placeholder-gray-500" placeholder="Enter Keywords">
        </div>

        <div v-for="(item, index) in GData" class="p-4 border bg-white">
          <div class="family-poppins text-xs font-medium text-gray-700">{{item.head}}</div>
          <div class="family-poppins text-xs font-medium text-gray-700 mt-0.5">{{item.subhead}}</div>
          <div class="family-poppins text-xl font-medium text-indigo-500 my-2">{{item.num}}</div>
          <div class="flex items-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 text-indigo-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" :d="item.path" />
            </svg>
            <div class="family-poppins text-vs font-medium text-gray-700 ml-1"><span class="text-indigo-500">{{item.span}}</span>{{item.desc}}</div>
          </div>
        </div>

      </div>
      <div class="mt-4 mx-6 grid grid-cols-7 gap-4">
        <div class="col-span-2 py-2 bg-white border">
          <div class="py-3 px-4 flex justify-between items-center border-b">
            <div class="flex items-center">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 4a1 1 0 011-1h16a1 1 0 011 1v2.586a1 1 0 01-.293.707l-6.414 6.414a1 1 0 00-.293.707V17l-4 4v-6.586a1 1 0 00-.293-.707L3.293 7.293A1 1 0 013 6.586V4z" />
              </svg>
              <div class="family-poppins text-gray-700 text-sm font-medium ml-3">Filters</div>
            </div>
            <div class="family-poppins text-indigo-500 cursor-pointer text-sm font-medium">Clear</div>
          </div>
          <div class="px-4 w-full h-screen-20 overflow-y-auto">
          </div>
        </div>
        <div class="col-span-5 bg-white py-2 border">
          <div class="py-2 px-4 border-b flex justify-between items-center">
            <div class="flex items-center">
              <input type="checkbox" class="rounded h-4 w-4 focus:outline-none">
              <div class="family-poppins text-indigo-600 font-medium text-sm ml-3">Select all</div>
            </div>
            <select class="w-80 my-auto rounded-md bg-gray-100 border-none text-gray-600 focus:outline-none py-2 px-4 text-xs font-medium family-poppins">
              <option>Sort by</option>
              <option>Orders</option>
              <option>Date</option>
            </select>
          </div>
          <div class="p-4 border-b flex justify-between ">
            <div class="flex">
              <div class="flex items-center -mt-24">
                <input type="checkbox" class="rounded w-4 h-4 focus:outline-none">
                <div class="ml-4 rounded-full bg-red-600 flex h-12 w-12">
                  <div class="family-poppins m-auto font-medium text-white text-2xl">T</div>
                </div>
              </div>
              <div class="ml-4">
                <div class="font-medium text-indigo-500 family-poppins text-sm ">Tata Cancer Treatment & Research Hospital, Ratagarh</div>
                <div class="flex items-center">
                  <div class="">
                    <div class="family-poppins text-gray-500 text-sm font-medium mt-1">State :</div>
                    <div class="family-poppins text-gray-500 text-sm font-medium mt-1">Status :</div>
                    <div class="family-poppins text-gray-500 text-sm font-medium mt-1">Building Use :</div>
                    <div class="family-poppins text-gray-500 text-sm font-medium mt-1">Updated :</div>
                    <div class="family-poppins text-gray-500 text-sm font-medium mt-1">Pincode :</div>
                  </div>
                  <div class="ml-6">
                    <div class="family-poppins text-gray-700 text-sm font-medium mt-1">Maharashtra</div>
                    <div class="family-poppins text-gray-700 text-sm font-medium mt-1">Pre-Construction</div>
                    <div class="family-poppins text-gray-700 text-sm font-medium mt-1">Transport Infrastructure</div>
                    <div class="family-poppins text-gray-700 text-sm font-medium mt-1">Dec, 22 2021</div>
                    <div class="family-poppins text-gray-700 text-sm font-medium mt-1">424001</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="flex items-center -mt-24">
              <button class="py-1 px-2.5 bg-indigo-400 hover:bg-indigo-600 text-sm text-white font-medium family-poppins rounded-md focus:outline-none">Follow</button>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 cursor-pointer ml-2.5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 12h.01M12 12h.01M19 12h.01M6 12a1 1 0 11-2 0 1 1 0 012 0zm7 0a1 1 0 11-2 0 1 1 0 012 0zm7 0a1 1 0 11-2 0 1 1 0 012 0z" />
              </svg>
            </div>
          </div>
          <div class="p-4 border-b flex justify-between ">
            <div class="flex">
              <div class="flex items-center -mt-24">
                <input type="checkbox" class="rounded w-4 h-4 focus:outline-none">
                <div class="ml-4 rounded-full bg-red-600 flex h-12 w-12">
                  <div class="family-poppins m-auto font-medium text-white text-2xl">H</div>
                </div>
              </div>
              <div class="ml-4">
                <div class="font-medium text-indigo-500 family-poppins text-sm ">HFWD Bangaluru Central University Campus, Bangalore</div>
                <div class="flex items-center">
                  <div class="">
                    <div class="family-poppins text-gray-500 text-sm font-medium mt-1">State :</div>
                    <div class="family-poppins text-gray-500 text-sm font-medium mt-1">Status :</div>
                    <div class="family-poppins text-gray-500 text-sm font-medium mt-1">Building Use :</div>
                    <div class="family-poppins text-gray-500 text-sm font-medium mt-1">Updated :</div>
                    <div class="family-poppins text-gray-500 text-sm font-medium mt-1">Pincode :</div>
                  </div>
                  <div class="ml-6">
                    <div class="family-poppins text-gray-700 text-sm font-medium mt-1">Maharashtra</div>
                    <div class="family-poppins text-gray-700 text-sm font-medium mt-1">Pre-Construction</div>
                    <div class="family-poppins text-gray-700 text-sm font-medium mt-1">Transport Infrastructure</div>
                    <div class="family-poppins text-gray-700 text-sm font-medium mt-1">Dec, 22 2021</div>
                    <div class="family-poppins text-gray-700 text-sm font-medium mt-1">424001</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="flex items-center -mt-24">
              <button class="py-1 px-2.5 bg-indigo-400 hover:bg-indigo-600 text-sm text-white font-medium family-poppins rounded-md focus:outline-none">Follow</button>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 cursor-pointer ml-2.5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 12h.01M12 12h.01M19 12h.01M6 12a1 1 0 11-2 0 1 1 0 012 0zm7 0a1 1 0 11-2 0 1 1 0 012 0zm7 0a1 1 0 11-2 0 1 1 0 012 0z" />
              </svg>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div v-if="headerColumn" class="main-modal fixed w-full h-100 inset-0 z-50 flex justify-center items-center animated bg-gray-900 bg-opacity-25 fadeIn faster" >
      <div class="shadow-lg modal-container bg-white w-2/4 rounded shadow-lg z-50 overflow-y-auto" style="height: 690px">
        <div class="flex relative justify-between border-solid border-b p-2 text-center items-center">
          <div class="text-left font-semibold ml-4 text-base antialiased leading-snug text-gray-800 tracking-normal">Choose your Columns</div>
          <div class="flex py-1">
            <div @click="headerColumn = false" class="text-gray-600 ml-16 inline-block bg-white hover:bg-red-600 hover:text-white rounded shadow-md no-underline mr-3 focus:outline-none active:shadow-none font-bold">
              <svg class="h-4 w-4 my-2 mx-2 font-bold" fill="currentColor" viewBox="0 0 512.001 512.001" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M512.001 84.853L427.148 0 256.001 171.147 84.853 0 0 84.853 171.148 256 0 427.148l84.853 84.853 171.148-171.147 171.147 171.147 84.853-84.853L340.853 256z"/></svg>
            </div>
          </div>
        </div>
        <div class="px-3 py-1">

        </div>

        <div class="flex mt-4 border-solid border-t text-center items-center">
          <div class="flex-col py-3 px-24">
            <div class="text-sm font-medium text-left text-gray-600 ">
              * Maximum 5 Columns Allowed, Deselect 1 column to add another.
            </div>
            <div class="text-sm font-medium text-left mt-3 text-gray-600 ">
              * Minimum 4 columns should be present.
            </div>
          </div>
        </div>
        <div class="flex justify-end border-solid border-t py-2">
          <button @click="headerColumn = false" class="py-2 rounded-md px-3 text-gray-600 border border-gray-400 antialiased tracking-tight mr-8 text-sm font-medium font-google hover:bg-gray-100 hover:text-black focus:outline-none ">Close</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "search",
  data(){
    return{
      options:{},
      headerColumn: false,
      GData:[
        {id:'1', head:'Total Project(s)', num:'14,907', path:'M7 11l5-5m0 0l5 5m-5-5v12', span:'89', desc:' In last Week'},
        {id:'1', head:'Aggrigate Area', subhead:'(Million-sqft)', num:'8404.06', path:'', span:'', desc:' '},
        {id:'1', head:'Aggrigate Area', subhead:'(INR-Crore)', num:'2,527,07', path:'', span:'', desc:' '},
        {id:'1', head:'Total Appartments', subhead:'Unit(s)', num:'4,115,189', path:'', span:'', desc:' '},
        {id:'1', head:'Location(s)', subhead:'', num:'11,206', path:'', span:'', desc:' '},
      ],
      FData:[
        {id:'1', name:'Date Range',type:'date', Lpath:'M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z', Rpath:'M9 5l7 7-7 7', menu: false},
        {id:'2', name:'Sector', Lpath:'M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z', Rpath:'M9 5l7 7-7 7', menu: false,
          submenu:[
            {id:'1', head:'Public', num:'(9908)'},
            {id:'1', head:'Private', num:'(5012)'},
            {id:'1', head:'Public-Private Venture', num:'(441)'},
          ]},
        {id:'3', name:'Status', Lpath:'M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z', Rpath:'M9 5l7 7-7 7', menu: false,
          submenu: [
            {id:'1', head:'Pre-Construction', num:'(9908)'},
            {id:'1', head:'On-Hold', num:'(5012)'},
            {id:'1', head:'Under Construction', num:'(441)'},
          ]},
        {id:'4', name:'Sub Status', Lpath:'M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z', Rpath:'M9 5l7 7-7 7', menu: false},
        {id:'5', name:'State(s)', Lpath:'M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z', Rpath:'M9 5l7 7-7 7', menu: false,
          submenu: [
            {id:'1', head:'Andaman & Nicobar Islands', num:'(13)'},
            {id:'1', head:'Andra Pradesh', num:'(32)'},
            {id:'1', head:'Arunachal Pradesh', num:'(23)'},
          ]},
        {id:'6', name:'Region(s)', Lpath:'M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z', Rpath:'M9 5l7 7-7 7', menu: false,
          submenu: [
            {id:'1', head:'Agra Metropolitan Aria', num:'(25)'},
            {id:'1', head:'Amritsar Metropolitan Aria ', num:'(29)'},
            {id:'1', head:'Allahabad Metropolitan Aria', num:'(08)'},
          ]},
        {id:'7', name:'Building Use(s)', Lpath:'M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z', Rpath:'M9 5l7 7-7 7', menu: false},
        {id:'8', name:'Category(s)', Lpath:'M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z', Rpath:'M9 5l7 7-7 7', menu: false},
      ],
      availableColumns: [
        { title: 'Construction Cost (INR Crore)', key: 'construction_cost',checked: false},
        { title: 'Construction Area (SqFt)', key: 'construction_area', checked: false, disabled: false},
        { title: 'Sub-Segment', key: 'sub_segment', checked: false, disabled: false, order: 18},
        { title: 'Metropolitan Region', key: 'region', checked: false, disabled: false, order: 8},
        { title: 'Sector', key: 'sector', checked: false, disabled: false, order: 9},
        { title: 'Website', key: 'website', checked: false, disabled: false, order: 10},
        { title: 'Project Type', key: 'project_type', checked: false, disabled: false},
        { title: 'End Product', key: 'end_product', checked: false, disabled: false},
        { title: 'Industrial Development Authority', key: 'authority', checked: false, disabled: false},
        { title: 'Construction Start (Year)', key: 'construction_start', checked: false, disabled: false, order: 11},
        { title: 'Construction End (Year)', key: 'construction_finish', checked: false, disabled: false, order: 12},
      ],
      selectedColumnSort: [
        { title: 'State', key: 'state', order: 3, checked: false},
        { title: 'Status', key: 'status', order: 4, checked: false},
        { title: 'Segment', key: 'segment', order: 5, checked: false},
        { title: 'Updated', key: 'updated_at', order: 6, checked: false},
      ],
      staticColumns: [
        { title: 'Project Name', key: 'name', order: 2, checked: false},
      ],
      finalColumns: [
        { title: 'Sr No.', key: 'index', order: 1, checked: false },
        { title: 'Project Name', key: 'name', order: 2, checked: false},
        { title: 'State', key: 'state', order: 3, checked: false},
        { title: 'Status', key: 'status', order: 4, checked: false},
        { title: 'Building Use', key: 'type', order: 5, checked: false},
        { title: 'Updated', key: 'updated', order: 6, checked: false},
      ],
      selectedColumns: [
        { title: 'Sr No.', key: 'index' },
        { title: 'Project Name', key: 'name'},
        { title: 'State', key: 'state'},
        { title: 'Status', key: 'status'},
        { title: 'Building Use', key: 'type'},
        { title: 'Updated', key: 'updated'},
      ],
      loading: false,
      selectedFields:{},
      searchVariablesData:[
        {var_name: 'sector', menu: false, heading_name:'Sector(s)', Lpath:'M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z', Rpath:'M9 5l7 7-7 7',},
        {var_name: 'status', menu: false, heading_name:'Status',  Lpath:'M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z', Rpath:'M9 5l7 7-7 7'},
        {var_name: 'state', menu: false, heading_name:'State(s)', Lpath:'M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z', Rpath:'M9 5l7 7-7 7'},
      ],
      searchVariables: {
        'sector': [
          {id:'1', name:'Public', count:'(9908)'},
          {id:'2', name:'Private', count:'(5012)'},
          {id:'3', name:'Public-Private Venture', count:'(441)'},
        ],
        'status': [
          {id:'1', name:'Pre-Construction', count:'(9908)'},
          {id:'2', name:'On-Hold', count:'(5012)'},
          {id:'3', name:'Under Construction', count:'(441)'},
        ],
        'state': [
          {id:'1', name:'Andaman & Nicobar Islands', count:'(13)'},
          {id:'2', name:'Andra Pradesh', count:'(32)'},
          {id:'3', name:'Arunachal Pradesh', count:'(23)'},
        ],
      },
    }
  },
}
</script>

<style scoped>

</style>
