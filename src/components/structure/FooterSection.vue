<template>
    <div>
      <div class="w-full bg-black text-gray-100">
        <div
          class="container mx-auto max-w-4xl h-full
            flex flex-wrap md:flex-no-wrap justify-between
            items-start text-sm p-6 pt-8 pb-4"
        >
          <div class="mb-4">
            <h4 class="mb-4">Quick links</h4>
            <router-link to="/" class="block mb-2">Home</router-link>
          </div>
          <div class="mb-4">
            <h4 class="mb-4">About Our Company</h4>
  
            <p class="mb-4 leading-normal">
              123 Main Street<br />
              London<br />
              SW1 SW1
            </p>
  
            <p class="text-sm">079 6293 6068</p>
          </div>
        </div>
        <div class="container mx-auto max-w-4xl py-6 flex flex-wrap md:flex-no-wrap justify-between items-center text-sm">
          &copy;2019 Your Company. All rights reserved.
          <div class="pt-4 md:p-0 text-center md:text-right text-xs">
            <a href="#" class="no-underline hover:underline">Privacy Policy</a>
            <a href="#" class="no-underline hover:underline ml-4">Terms &amp; Conditions</a>
            <a href="#" class="no-underline hover:underline ml-4">Contact Us</a>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script setup></script>
  
  