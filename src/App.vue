<script setup lang="ts">

const techs = [
  {
    icon:`<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-12 h-12">
  <path d="M3.375 3C2.339 3 1.5 3.84 1.5 4.875v.75c0 1.036.84 1.875 1.875 1.875h17.25c1.035 0 1.875-.84 1.875-1.875v-.75C22.5 3.839 21.66 3 20.625 3H3.375z" />
  <path fill-rule="evenodd" d="M3.087 9l.54 9.176A3 3 0 006.62 21h10.757a3 3 0 002.995-2.824L20.913 9H3.087zm6.163 3.75A.75.75 0 0110 12h4a.75.75 0 010 1.5h-4a.75.75 0 01-.75-.75z" clip-rule="evenodd" />
</svg>
`,
    title:'Apple IOS',
    description:'Apple IOS is a better choice to reach a more engaged  user base. Android has a broader reach',
    active: true
  },

  {
    icon:`<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-12 h-12">
  <path d="M11.7 2.805a.75.75 0 01.6 0A60.65 60.65 0 0122.83 8.72a.75.75 0 01-.231 1.337 49.949 49.949 0 00-9.902 3.912l-.003.002-.34.18a.75.75 0 01-.707 0A50.009 50.009 0 007.5 12.174v-.224c0-.131.067-.248.172-.311a54.614 54.614 0 014.653-2.52.75.75 0 00-.65-1.352 56.129 56.129 0 00-4.78 2.589 1.858 1.858 0 00-.859 1.228 49.803 49.803 0 00-4.634-1.527.75.75 0 01-.231-1.337A60.653 60.653 0 0111.7 2.805z" />
  <path d="M13.06 15.473a48.45 48.45 0 017.666-3.282c.134 1.414.22 2.843.255 4.285a.75.75 0 01-.46.71 47.878 47.878 0 00-8.105 4.342.75.75 0 01-.832 0 47.877 47.877 0 00-8.104-4.342.75.75 0 01-.461-.71c.035-1.442.121-2.87.255-4.286A48.4 48.4 0 016 13.18v1.27a1.5 1.5 0 00-.14 2.508c-.09.38-.222.753-.397 1.11.452.213.901.434 1.346.661a6.729 6.729 0 00.551-1.608 1.5 1.5 0 00.14-2.67v-.645a48.549 48.549 0 013.44 1.668 2.25 2.25 0 002.12 0z" />
  <path d="M4.462 19.462c.42-.419.753-.89 1-1.394.453.213.902.434 1.347.661a6.743 6.743 0 01-1.286 1.794.75.75 0 11-1.06-1.06z" />
</svg>
`,
    title:'Android',
    description:'Android has a broader reach, however particularly in emerging markets, like Asia and Africa',
  },

  {
    icon:`<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-12 h-12">
  <path d="M12 7.5a2.25 2.25 0 100 4.5 2.25 2.25 0 000-4.5z" />
  <path fill-rule="evenodd" d="M1.5 4.875C1.5 3.839 2.34 3 3.375 3h17.25c1.035 0 1.875.84 1.875 1.875v9.75c0 1.036-.84 1.875-1.875 1.875H3.375A1.875 1.875 0 011.5 14.625v-9.75zM8.25 9.75a3.75 3.75 0 117.5 0 3.75 3.75 0 01-7.5 0zM18.75 9a.75.75 0 00-.75.75v.008c0 .414.336.75.75.75h.008a.75.75 0 00.75-.75V9.75a.75.75 0 00-.75-.75h-.008zM4.5 9.75A.75.75 0 015.25 9h.008a.75.75 0 01.75.75v.008a.75.75 0 01-.75.75H5.25a.75.75 0 01-.75-.75V9.75z" clip-rule="evenodd" />
  <path d="M2.25 18a.75.75 0 000 1.5c5.4 0 10.63.722 15.6 2.075 1.19.324 2.4-.558 2.4-1.82V18.75a.75.75 0 00-.75-.75H2.25z" />
</svg>
`,
    title:'Cross-platform',
    description:'Cross-platform app developent allows to roll out new applications simultaneously and lower expreses.',
  },
  {
    icon:`<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-12 h-12">
  <path d="M11.25 4.533A9.707 9.707 0 006 3a9.735 9.735 0 00-3.25.555.75.75 0 00-.5.707v14.25a.75.75 0 001 .707A8.237 8.237 0 016 18.75c1.995 0 3.823.707 5.25 1.886V4.533zM12.75 20.636A8.214 8.214 0 0118 18.75c.966 0 1.89.166 2.75.47a.75.75 0 001-.708V4.262a.75.75 0 00-.5-.707A9.735 9.735 0 0018 3a9.707 9.707 0 00-5.25 1.533v16.103z" />
</svg>
`,
    title:'Progressive',
    description:'Progressive is a finatially attractive alternative just like cross-platforms but not dependent on any app stores',
  },
];


</script>

<template>
  <div class="w-screen h-screen bg-dark-800 flex">
    <div class="w-1/3 h-full bg-dark-600 shadow-4xl flex flex-col">
      <div class="text-2xl font-bold text-white p-8 border-b border-dark-800">
        <h1>Strade</h1>
      </div>
      <div class="w-full h-full p-16 flex flex-col justify-center">
        <p class="text-4xl font-bold text-white">Which <span class="text-yellow-400">Platforms</span></p>
        <p class="text-4xl font-bold text-white">Should we Build</p>
        <p class="text-4xl font-bold text-white mb-10">Application For?</p>
        <p class="text-dark-50">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Veniam voluptatem maxime
          molestias et a aliquam eveniet. Dolore dolor, porro placeat sapiente eligendi tenetur tempore distinctio
          quidem cupiditate quasi molestiae doloremque.</p>
      </div>
      <div class="w-full p-8  border-t border-dark-800 flex justify-between items-center">
        <button class="px-4 py-2 font-semibold text-white bg-dark-200 rounded-lg ">Previous</button>
        <p class="text-dark-50">Question 3 of 20</p>
        <button class="px-8 py-2 font-semibold text-dark-800 bg-yellow-400 rounded-lg ">Next</button>
      </div>
    </div>
    <div class="w-2/3 h-full  p-20 flex flex-col  ">
      <div class="w-full h-full grid grid-cols-2 grid-rows-2 shadow-2xl rounded-lg overflow-hidden bg-dark-600">
        <div v-for="(item,index) in techs" :key="index" :class=" `${item.active?'bg-yellow-400':'text-white'}  p-8 justify-between flex flex-col`">
          <div v-html="item.icon" :class=" `${!item.active?'text-dark-50':'text-dark-800'}  `">

          </div>
          <div>
            <p class="font-medium">{{ item.title }} </p>
            <p class="text-sm opacity-50">{{ item.description }}</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>
