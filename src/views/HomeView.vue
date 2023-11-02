<script setup>
</script>

<template>
  <div class="w-[500px] m-auto p-5">
    <div class="w-[48px] h-[48px] m-auto">
      <a href="#" class="fill-current w-full">
        <svg
          class="w-full"
          aria-hidden="true"
          viewBox="0 0 16 16"
          version="1.1"
          data-view-component="true"
        >
          <path
            d="M8 0c4.42 0 8 3.58 8 8a8.013 8.013 0 0 1-5.45 7.59c-.4.08-.55-.17-.55-.38 0-.27.01-1.13.01-2.2 0-.75-.25-1.23-.54-1.48 1.78-.2 3.65-.88 3.65-3.95 0-.88-.31-1.59-.82-2.15.08-.2.36-1.02-.08-2.12 0 0-.67-.22-2.2.82-.64-.18-1.32-.27-2-.27-.68 0-1.36.09-2 .27-1.53-1.03-2.2-.82-2.2-.82-.44 1.1-.16 1.92-.08 2.12-.51.56-.82 1.28-.82 2.15 0 3.06 1.86 3.75 3.64 3.95-.23.2-.44.55-.51 1.07-.46.21-1.61.55-2.33-.66-.15-.24-.6-.83-1.23-.82-.67.01-.27.38.01.53.34.19.73.9.82 1.13.16.45.68 1.31 2.69.94 0 .67.01 1.3.01 1.49 0 .21-.15.45-.55.38A7.995 7.995 0 0 1 0 8c0-4.42 3.58-8 8-8Z"
          ></path>
        </svg>
      </a>
    </div>
    <div class="text-xl font-thin text-center mt-5">Sign in to GitHub</div>
    <div
      class="w-[308px] h-[220px] border rounded-md bg-gray-100 mx-auto mt-3 px-3 py-3"
    >
      <form>
        <label for="login_field" class="font-normal text-sm">
          Username or email address
        </label>
        <input
          id="login_field"
          type="text"
          value=""
          class="mt-2 block w-full px-3 h-[30px] border border-slate-300 rounded-md text-sm shadow-sm focus:outline-none focus:border-sky-500 focus:ring-1"
        />
        <div class="relative w-full">
          <div class="absolute right-0 top-0 text-xs">
            <a href="#" class="text-blue-600">Forgot password?</a>
          </div>
          <label for="passwd" class="font-normal text-sm block mt-3"
            >Password
          </label>
          <input
            id="passwd"
            type="password"
            value=""
            class="mt-2 block w-full px-3 h-[30px] border border-slate-300 rounded-md text-sm shadow-sm focus:outline-none focus:border-sky-500 focus:ring-1"
          />
        </div>
        <input
          type="button"
          value="登录"
          class="w-full bg-green-700 h-[30px] mt-5 rounded-md text-white hover:bg-green-800 cursor-pointer"
        />
      </form>
    </div>
    <div class="w-[308px] h-[80px] border rounded-md bg-slate-50 mx-auto mt-3 px-3 py-3">
      <div class="w-full text-center">
        <a href="#" class="text-sm text-blue-600 cursor-pointer hover:underline">Sign in with a passkey</a>
      </div>
      <div class="w-full text-center text-sm mt-2">
        New to GitHub? <a href="#" class="text-blue-600 cursor-pointer hover:underline">Create an account</a>
      </div>
    </div>
    <div class="w-[308px] mx-auto px-3 py-3 text-center text-xs space-x-3 mt-16">
      <a href="#" class="text-blue-600 cursor-pointer hover:underline">Terms</a>
      <a href="#" class="text-blue-600 cursor-pointer hover:underline">Privacy</a>
      <a href="#" class="text-blue-600 cursor-pointer hover:underline">Docs</a>
      <a href="#" class="cursor-pointer hover:underline hover:text-blue-600">Contact GitHub Support</a>


    </div>
  </div>
</template>
