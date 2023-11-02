<template>
  <div class="text-sm text-gray-900">
    <div class="flex items-center px-4 py-3 bg-gray-900 justify-between">
      <div class="text-white flex space-x-3 items-center">
        <a href="#" class="w-6 fill-current hover:text-green-600">
          <svg class="w-6" aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true">
            <path
              d="M8 0c4.42 0 8 3.58 8 8a8.013 8.013 0 0 1-5.45 7.59c-.4.08-.55-.17-.55-.38 0-.27.01-1.13.01-2.2 0-.75-.25-1.23-.54-1.48 1.78-.2 3.65-.88 3.65-3.95 0-.88-.31-1.59-.82-2.15.08-.2.36-1.02-.08-2.12 0 0-.67-.22-2.2.82-.64-.18-1.32-.27-2-.27-.68 0-1.36.09-2 .27-1.53-1.03-2.2-.82-2.2-.82-.44 1.1-.16 1.92-.08 2.12-.51.56-.82 1.28-.82 2.15 0 3.06 1.86 3.75 3.64 3.95-.23.2-.44.55-.51 1.07-.46.21-1.61.55-2.33-.66-.15-.24-.6-.83-1.23-.82-.67.01-.27.38.01.53.34.19.73.9.82 1.13.16.45.68 1.31 2.69.94 0 .67.01 1.3.01 1.49 0 .21-.15.45-.55.38A7.995 7.995 0 0 1 0 8c0-4.42 3.58-8 8-8Z">
            </path>
          </svg>
        </a>
        <div class="relative">
          <input type="text" class="rounded bg-gray-900 border border-gray-600 placeholder-gray-500 w-72 px-3 py-1"
            placeholder="xxx">
          <div class="absolute top-0 right-0 flex items-center h-full">
            <div class="border border-gray-600 rounded text-xs text-gray-400 px-2 mr-2">/</div>
          </div>
        </div>
        <ul class="flex items-center font-semibold space-x-3">
          <li>
            <a href="#" class="hover:text-gray-300">TailWindTest</a>
          </li>
          <li>
            <a href="#" class="hover:text-gray-300">TailWindTest</a>
          </li>
          <li>
            <a href="#" class="hover:text-gray-300">TailWindTest</a>
          </li>
        </ul>
      </div>
      <div class="text-white flex items-center space-x-3">
        <a href="#" class="relative hover:text-gray-400">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"
            class="w-5 h-5">
            <path stroke-linecap="round" stroke-linejoin="round"
              d="M14.857 17.082a23.848 23.848 0 005.454-1.31A8.967 8.967 0 0118 9.75v-.7V9A6 6 0 006 9v.75a8.967 8.967 0 01-2.312 6.022c1.733.64 3.56 1.085 5.455 1.31m5.714 0a24.255 24.255 0 01-5.714 0m5.714 0a3 3 0 11-5.714 0" />
          </svg>
          <div class="bg-green-600 rounded-full w-2 h-2 absolute top-0 right-0"></div>
        </a>
        <a href="#" class="flex items-center hover:text-gray-400">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"
            class="w-5 h-5">
            <path stroke-linecap="round" stroke-linejoin="round" d="M12 4.5v15m7.5-7.5h-15" />
          </svg>
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"
            class="w-3 h-3">
            <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 8.25l-7.5 7.5-7.5-7.5" />
          </svg>
      </a>
    </div>
  </div>
</div>

  <div class="about">
  <!-- 布局 -->
   <!-- <div class="flex flex-row bg-green-400 w-[700px] h-[400px] text-center leading-[100px] flex-wrap m-auto content-start justify-between place-content-start justify-items-start"> -->
  <div class="grid grid-cols-[repeat(auto-fill,200px)]  justify-between text-center content-start w-[700px] h-[400px] bg-green-400 leading-[100px] m-auto">
  <!-- <div class="basis-1/4 h-[100px] bg-red-400" >01</div> -->
  <div class="w-[200px] h-[100px] bg-red-400 mb-3">01</div>
  <div class="w-[200px] h-[100px] bg-red-400">02</div>
  <div class="w-[200px] bg-red-400 h-[100px]">03</div>
  <div class="w-[200px] h-[100px] bg-red-400 mb-3">03</div>
  <div class="w-[200px] h-[100px] bg-red-400">03</div> 
  <div class="w-[200px] h-[100px] bg-red-400">03</div> 
  <div class="w-[200px] h-[100px] bg-red-400">03</div> 
  <div class="w-[200px] h-[100px] bg-red-400">03</div> 
</div>
<!-- 按钮 -->
  <div class="w-[700px] m-auto mt-2">
   <a href="#" class="m-auto w-40 h-8 bg-green-500 block text-center leading-8 text-white rounded-lg  backdrop-opacity-10 hover:bg-green-400">按钮</a>
  </div>
  </div>
  <!-- 定位 -->
  <div class="relative w-[600px] h-[500px] bg-green-400 mt-3 m-auto">
    <div class="absolute w-[300px] h-[250px] bg-red-200 top-1/2 left-1/2 ml-[-150px] mt-[-125px] "></div>
  </div>
</template>
  
<style>

</style>
