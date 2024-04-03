<template>
  <div class="header text-white">
    <header
      class="px-8 py-6 text-sm font-semibold max-md:flex-wrap max-md:px-5"
    >
      <div
        class="box-logo my-auto text-white max-md:flex-wrap max-md:max-w-full"
      >
        <nav class="my-auto flex gap-4">
          <a href="#" class="flex gap-1">
            <img
              loading="lazy"
              src="~/public/images/icon/airplane.svg"
              alt="Find Flight icon"
              class="shrink-0 w-6 aspect-square"
            />
            <span class="my-auto">Find Flight</span>
          </a>
          <a href="#" class="flex gap-1">
            <img
              loading="lazy"
              src="~/public/images/icon/ion_bed.svg"
              alt="Find Stays icon"
              class="shrink-0 w-6 aspect-square"
            />
            <span class="my-auto">Find Stays</span>
          </a>
        </nav>
        <div class="text-center flex justify-center item-center">
          <img
            loading="lazy"
            src="~/public/images/Logo.png"
            alt="Logo"
            class="h-[36px] w-[110px]"
          />
        </div>
        <div class="flex gap-5 justify-end">
          <a href="#" class="my-auto text-white">Login</a>
          <button
            class="justify-center px-6 py-4 text-center bg-white rounded-lg text-neutral-900 max-md:px-5"
          >
            Sign up
          </button>
        </div>
      </div>
    </header>
    <div class="text-center py-[100px] pb-[170px]">
      <h1 class="text-5xl max-md:text-4xl">Helping Others</h1>
      <p
        class="self-stretch mt-1 w-full text-7xl uppercase max-md:max-w-full max-md:text-4xl"
      >
        <span class="text-white">Live</span> &
        <span class="text-white">Travel</span>
      </p>
      <p class="mt-4 text-xl font-semibold">Special offers to suit your plan</p>
    </div>
  </div>
  <div class="box-search shadow-lg p-4 mx-8">
    <!-- <ul class="tab">
      <li class="cursor-pointer tab-active">
        <a href="#" class="flex gap-1">
          <img
            loading="lazy"
            src="~/public/images/icon/airplane.svg"
            alt="Find Flight icon"
            class="shrink-0 w-6 aspect-square icon-dark"
          />
          <span class="my-auto">Flight</span>
        </a>
      </li>
      <li class="cursor-pointer">
        <a href="#" class="flex gap-1">
          <img
            loading="lazy"
            src="~/public/images/icon/ion_bed.svg"
            alt="Find Stays icon"
            class="shrink-0 w-6 aspect-square icon-dark"
          />
          <span class="my-auto">Stays</span>
        </a>
      </li>
    </ul> -->
    <p class="font-bold">Tìm kiếm khách sạn</p>
    <div class="relative">
      <input
        type="text"
        id="floating_outlined"
        class="block px-2.5 pb-2.5 pt-4 w-full text-sm text-gray-900 bg-transparent rounded-lg border-1 border-gray-300 appearance-none dark:text-white dark:border-gray-600 dark:focus:border-blue-500 focus:outline-none focus:ring-0 focus:border-blue-600 peer"
        placeholder=" "
      />
      <label
        for="floating_outlined"
        class="absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-4 scale-75 top-2 z-10 origin-[0] bg-white dark:bg-gray-900 px-2 peer-focus:px-2 peer-focus:text-blue-600 peer-focus:dark:text-blue-500 peer-placeholder-shown:scale-100 peer-placeholder-shown:-translate-y-1/2 peer-placeholder-shown:top-1/2 peer-focus:top-2 peer-focus:scale-75 peer-focus:-translate-y-4 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto start-1"
        >Floating outlined</label
      >
      <input
        type="text"
        id="floating_outlined"
        class="block px-2.5 pb-2.5 pt-4 w-full text-sm text-gray-900 bg-transparent rounded-lg border-1 border-gray-300 appearance-none dark:text-white dark:border-gray-600 dark:focus:border-blue-500 focus:outline-none focus:ring-0 focus:border-blue-600 peer"
        placeholder=" "
      />
      <label
        for="floating_outlined"
        class="absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-4 scale-75 top-2 z-10 origin-[0] bg-white dark:bg-gray-900 px-2 peer-focus:px-2 peer-focus:text-blue-600 peer-focus:dark:text-blue-500 peer-placeholder-shown:scale-100 peer-placeholder-shown:-translate-y-1/2 peer-placeholder-shown:top-1/2 peer-focus:top-2 peer-focus:scale-75 peer-focus:-translate-y-4 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto start-1"
        >Floating outlined</label
      >
    </div>
  </div>
</template>

<script lang="ts" setup></script>

<style lang="scss"></style>
