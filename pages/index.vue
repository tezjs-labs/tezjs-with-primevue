<script>
export default {
  layoutName:'default'
};
</script>

<template>
  <div class="grid">
    <div class="col-2"></div>
    <div class="col-8">
      <p class="md:text-center mt-6 p-0 text-gray-900 heading font-family">
        Build ultra-modern, super-fast, secure, and scalable websites
      </p>
      <p class="md:text-center -mt-3 text-gray-600 sub-heading font-family">
        The fastest and future-proof framework that enables developers to build
        <br />
        blazing-fast websites.
      </p>
      <div class="grid mt-5">
        <div class="md:col-6 col-12">
          <div class="grid">
            <div class="col-2">
              <div class=" h-3rem w-3rem border-round bg-indigo-500 text-center">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" aria-hidden="true" class="h-2rem w-2rem mt-2 text-white"><path stroke-linecap="round" stroke-linejoin="round" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"></path></svg>
              </div> 
            </div>
            <div class="col-10">
              <div class="md:ml-4 lg:ml-4 xl:-ml-3">
                <span class="text-lg text-gray-900 font-family font-medium">An Open-Source Framework with Endless Possibilities</span>
                <p class="text-base mt-1 font-family text-color-secondary line-height-3">The primary goal of TezJS is to improve core web vitals without compromising the user experience. This provides endless possibilities for <br/> every team member</p>
              </div>  
            </div>         
          </div>
          <div class="grid md:mt-2 lg:mt-3 xl:mt-5">
            <div class="col-2">
              <div class=" h-3rem w-3rem border-round bg-indigo-500 text-center">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" aria-hidden="true" class="h-2rem w-2rem mt-2 text-white"><path stroke-linecap="round" stroke-linejoin="round" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
              </div>
            </div>
            <div class="col-10">
              <div class="md:ml-4 lg:ml-4 xl:-ml-3">
                <span class="text-lg text-gray-900 font-family font-medium">Short Page Load Time for Amazing User Experience</span>
                <p class="text-base mt-1 font-family text-color-secondary line-height-3">When every millisecond counts and every byte is precious, you must ensure that you’re only loading the data your users need. TezJS lets you <br/> load only the required data which is asked.</p>
              </div>
            </div>
          </div>
        </div>
        <div class="md:col-6 col-12">
          <div class="grid">
            <div class="col-2">
              <div class=" h-3rem w-3rem border-round bg-indigo-500 text-center">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" aria-hidden="true" class="h-2rem w-2rem mt-2 text-white"><path stroke-linecap="round" stroke-linejoin="round" d="M3 6l3 1m0 0l-3 9a5.002 5.002 0 006.001 0M6 7l3 9M6 7l6-2m6 2l3-1m-3 1l-3 9a5.002 5.002 0 006.001 0M18 7l3 9m-3-9l-6-2m0-2v2m0 16V5m0 16H9m3 0h3"></path></svg>            
              </div>
            </div> 
            <div class="col-10">
              <div class="md:ml-4 lg:ml-4 xl:-ml-3">
                <span class="text-lg text-gray-900 font-family font-medium">Development and Deployment in the Blink of an Eye</span>
                <p class="text-base mt-1 font-family text-color-secondary line-height-3">The incredible community, broad ecosystem, headless framework, and component-driven architecture of TezJS help you develop and deploy your <br/> website in minutes.</p>
              </div>
            </div>          
          </div>
          <div class="grid md:mt-2 lg:mt-3 xl:mt-5">
            <div class="col-2">
              <div class=" h-3rem w-3rem border-round bg-indigo-500 text-center">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" aria-hidden="true" class="h-2rem w-2rem mt-2 text-white"><path stroke-linecap="round" stroke-linejoin="round" d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z"></path></svg>            
              </div>
            </div>
            <div class="col-10">
              <div class="md:ml-4 lg:ml-4 xl:-ml-3">
                <span class="text-lg text-gray-900 font-family font-medium">Combine Data and Create Rich Web Experiences</span>
                <p class="text-base mt-1 font-family text-color-secondary line-height-3">TezJS has a common data layer that makes it simple for developers to combine data from various sources and render it side by side. It’s easy to <br/> consistently add content to your site from Strapi, etc.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="col-2"></div>
  </div>
</template>

<style>

@media only screen and (min-width: 600px) {
  .heading {
    font-size: 36px;
    font-weight: 900;
  }
}

@media only screen and (max-width: 600px) {
  .heading {
    font-size: 24px;
    font-weight: 800;
  }
}

@media only screen and (min-width:600px){
  .sub-heading {
    font-size: 22px;
    font-size: 22px;
  }
}

@media only screen and (max-width:600px){
  .sub-heading {
    font-size: 16px;
  }
}

.font-family{
    font-family: ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, Noto Sans, sans-serif, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol, Noto Color Emoji;
  }

</style>