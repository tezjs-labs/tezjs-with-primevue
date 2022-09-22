<template>
  <div class="grid mt-1">
    <div class="col-2"></div>
    <div class="col-8 border-bottom-1 border-gray-300">
      <div class="grid">
        <div class="md:col-6 lg:col-9 xl:col-9 sm:col-5 mt-2">
          <tez-link to="/">
            <img src="https://tailwindui.com/img/logos/workflow-mark-indigo-600.svg" class="h-3rem" />
          </tez-link>
        </div>
        <div class="md:col-2 lg:col-3 xl:col-3 sm:col-7 sm:block hidden">
          <div class="flex sm:column-gap-2 md:column-gap-3 xl:column-gap-3 lg:column-gap-2 mt-4 md:ml-8 lg:-ml-3 xl:ml-8">
            <tez-link to="/" class="no-underline flex-initial font-family text-lg text-color-secondary font-medium hover:text-gray-900">
              Home
            </tez-link>
            <tez-link to="/primeVue-example" class="no-underline flex-initial font-family text-lg text-color-secondary font-medium hover:text-gray-900">
              PrimeVue
            </tez-link>
            <a href="https://github.com/tezjs/tezjs" target="blank" class="flex-initial font-family text-lg text-color-secondary font-medium no-underline hover:text-gray-900">TezJS</a>
          </div>
        </div>
        <div class="col-6 sm:hidden mt-2 ml-8">
          <div class="text-right">
            <a href="">
              <svg xmlns="http://www.w3.org/2000/svg" class="text-gray-300" height="30" width="30" viewBox="0 0 448 512"><path d="M0 96C0 78.3 14.3 64 32 64H416c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32H416c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32H416c17.7 0 32 14.3 32 32z"/></svg>
            </a>
          </div>
        </div>
      </div>  
    </div>
    <div class="col-2"></div>
  </div>
</template>

<style>

  .font-family{
    font-family: ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, Noto Sans, sans-serif, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol, Noto Color Emoji;
  }

</style>