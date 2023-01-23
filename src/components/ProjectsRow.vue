<script lang="ts" setup>

</script>

<template>
<div class="py-24 px-6 mx-auto cubes">

<section class="text-gray-800 dark:text-white text-center">

  <h2 class="text-3xl font-bold mb-4 pb-4 text-center">Projects</h2>

  <div class="grid lg:grid-cols-3 gap-6 xl:gap-x-12">
    <div class="mb-6 lg:mb-0">
      <div class="cursor-pointer pt-10 relative block  rounded-lg " data-bs-toggle="modal" data-bs-target="#lf_project">
        <div class="flex">
          <div
            class="relative overflow-hidden bg-no-repeat bg-cover relative overflow-hidden bg-no-repeat bg-cover rounded-lg mx-auto -mt-4"
            data-mdb-ripple="true" data-mdb-ripple-color="light">
            <img src="/assets/images/mockups/rg-LF-ip12pro.png" class="w-1/2 mx-auto" />
            
              <div
                class="absolute top-0 right-0 bottom-0 left-0 w-full h-full overflow-hidden bg-fixed opacity-0 hover:opacity-100 transition duration-300 ease-in-out"
                style="background-color: rgba(251, 251, 251, 0.15)"></div>
            
          </div>
        </div>
        <div class="p-6">
          <h5 class="font-bold text-lg mb-3">Loan Finder Application</h5>
        </div>
      </div>
    </div>
    <div class="modal fade fixed top-0 left-0 hidden w-full h-full outline-none overflow-x-hidden overflow-y-auto" id="lf_project" tabindex="-1" aria-labelledby="exampleModalCenterTitle" aria-modal="true" role="dialog">
      <div class="modal-dialog modal-dialog-centered relative w-auto max-w-full h-auto pointer-events-none lg:px-60 px-10 sm:px-10">
        <div class="pb-10 modal-content border-none shadow-lg relative flex flex-col w-full pointer-events-auto bg-white dark:bg-gray-900/90 dark:text-white bg-clip-padding rounded-md outline-none text-current">
          <button type="button"
          class="ml-auto btn-close box-content w-4 h-4 p-1 pt-0 pr-10 pb-10 text-black border-none rounded-none opacity-50 focus:shadow-none focus:outline-none focus:opacity-100 hover:text-black hover:opacity-75 hover:no-underline"
          data-bs-dismiss="modal" aria-label="Close"></button>          
          <h1 class="mb-10">Loan Finder</h1>
          <div class="flex flex-wrap">
            <div class="block w-full lg:flex grow-0 shrink-0 basis-auto mx-auto">

              <img-comparison-slider hover="hover" tabindex="0" class="rendered mx-auto" value="100">
                <img slot="first" src="/assets/images/mockups/rg-LF-ip12pro.png" class="max-h-[60vh]"/>
                <img slot="second" src="/assets/images/mockups/rg-LF-ip12pro2.png" class="max-h-[60vh]"/>
                <svg slot="handle" class="custom-animated-handle" xmlns="http://www.w3.org/2000/svg" width="100" viewBox="-8 -3 16 6">
                  <path stroke="#fff" d="M -5 -2 L -7 0 L -5 2 M -5 -2 L -5 2 M 5 -2 L 7 0 L 5 2 M 5 -2 L 5 2" stroke-width="1" fill="#000" vector-effect="non-scaling-stroke"></path>
                </svg>
              </img-comparison-slider>

            </div>
            <!-- <div class="grow-0 shrink-0 basis-auto w-full">
              <div class="px-6 md:px-12">
                <p class="mb-12">
                  
                  
                </p>
              </div>
            </div> -->
          </div>

        </div>
      </div>
    </div>
    <div class="mb-6 lg:mb-0">
      <div class="cursor-pointer pt-10 relative block  rounded-lg " data-bs-toggle="modal" data-bs-target="#ft_project">
        <div class="flex">
          <div
            class="relative overflow-hidden bg-no-repeat bg-cover relative overflow-hidden bg-no-repeat bg-cover rounded-lg mx-auto -mt-4"
            data-mdb-ripple="true" data-mdb-ripple-color="light">
            <img src="/assets/images/mockups/rg-FT-ip12pro2.png" class="w-1/2 mx-auto" />
              <div
                class="absolute top-0 right-0 bottom-0 left-0 w-full h-full overflow-hidden bg-fixed opacity-0 hover:opacity-100 transition duration-300 ease-in-out"
                style="background-color: rgba(251, 251, 251, 0.15)"></div>
          </div>
        </div>
        <div class="p-6">
          <h5 class="font-bold text-lg mb-3">Auto Refinance Application</h5>
        </div>
      </div>
    </div>
    <div class="modal fade fixed top-0 left-0 hidden w-full h-full outline-none overflow-x-hidden overflow-y-auto" id="ft_project" tabindex="-1" aria-labelledby="exampleModalCenterTitle" aria-modal="true" role="dialog">
      <div class="modal-dialog modal-dialog-centered relative w-auto max-w-full h-auto pointer-events-none lg:px-60 px-10 sm:px-10">
        <div class="pb-10 modal-content border-none shadow-lg relative flex flex-col w-full pointer-events-auto bg-white dark:bg-gray-900/90 dark:text-white bg-clip-padding rounded-md outline-none text-current">
          <button type="button"
          class="ml-auto btn-close box-content w-4 h-4 p-1 pt-0 pr-10 pb-10 text-black border-none rounded-none opacity-50 focus:shadow-none focus:outline-none focus:opacity-100 hover:text-black hover:opacity-75 hover:no-underline"
          data-bs-dismiss="modal" aria-label="Close"></button>
          <h1 class="mb-10">Fast Track</h1>
          <div class="flex flex-wrap">
            <div class="block w-full lg:flex grow-0 shrink-0 basis-auto mx-auto">

              <img-comparison-slider hover="hover" tabindex="0" class="rendered mx-auto" value="100">
                <img slot="first" src="/assets/images/mockups/rg-FT-ip12pro.png" class="max-h-[60vh]"/>
                <img slot="second" src="/assets/images/mockups/rg-FT-ip12pro2.png" class="max-h-[60vh]"/>
                <svg slot="handle" class="custom-animated-handle" xmlns="http://www.w3.org/2000/svg" width="100" viewBox="-8 -3 16 6">
                  <path stroke="#fff" d="M -5 -2 L -7 0 L -5 2 M -5 -2 L -5 2 M 5 -2 L 7 0 L 5 2 M 5 -2 L 5 2" stroke-width="1" fill="#000" vector-effect="non-scaling-stroke"></path>
                </svg>
              </img-comparison-slider>


            </div>
            <!-- <div class="grow-0 shrink-0 basis-auto w-full">
              <div class="px-6 md:px-12">
                <p class="mb-12">
                  


                </p>
              </div>
            </div> -->
          </div>
        </div>
      </div>
    </div>
    <div class="mb-6 lg:mb-0">
      <div class="cursor-pointer pt-10 relative block  rounded-lg " data-bs-toggle="modal" data-bs-target="#web_projects">
        <div class="flex">
          <div
            class="relative overflow-hidden bg-no-repeat bg-cover relative overflow-hidden bg-no-repeat bg-cover rounded-lg mx-auto -mt-4"
            data-mdb-ripple="true" data-mdb-ripple-color="light">
            <img src="/assets/images/mockups/ap-web.png" class="w-1/2 mx-auto" />
              <div
                class="absolute top-0 right-0 bottom-0 left-0 w-full h-full overflow-hidden bg-fixed opacity-0 hover:opacity-100 transition duration-300 ease-in-out"
                style="background-color: rgba(251, 251, 251, 0.15)">
              </div>
          </div>
        </div>
        <div class="p-6">
          <h5 class="font-bold text-lg mb-3">Websites</h5>
        </div>
      </div>
    </div>
    <div class="modal fade fixed top-0 left-0 hidden w-full h-full outline-none overflow-x-hidden overflow-y-auto" id="web_projects" tabindex="-1" aria-labelledby="exampleModalCenterTitle" aria-modal="true" role="dialog">

      <div class="modal-dialog modal-dialog-centered relative w-auto max-w-full h-auto pointer-events-none lg:px-60 px-10 sm:px-10">
        <div class="pb-10 modal-content border-none shadow-lg relative flex flex-col w-full pointer-events-auto bg-white dark:bg-gray-900/90 dark:text-white bg-clip-padding rounded-md outline-none text-current">
          <button type="button"
          class="ml-auto btn-close box-content w-4 h-4 p-1 pt-0 pr-10 pb-10 text-black border-none rounded-none opacity-50 focus:shadow-none focus:outline-none focus:opacity-100 hover:text-black hover:opacity-75 hover:no-underline"
          data-bs-dismiss="modal" aria-label="Close"></button>
          <h1 class="mb-10">Websites</h1>
          <div class="flex flex-wrap">
            <div class="block w-full lg:flex grow-0 shrink-0 basis-auto mx-auto">

              <img-comparison-slider hover="hover" tabindex="0" class="rendered mx-auto" value="100">
                <img slot="first" src="/assets/images/mockups/ap-web-ip12pro.png" class="max-h-[60vh]"/>
                <img slot="second" src="/assets/images/mockups/ap-web-ip12pro2.png" class="max-h-[60vh]"/>
                <svg slot="handle" class="custom-animated-handle" xmlns="http://www.w3.org/2000/svg" width="100" viewBox="-8 -3 16 6">
                  <path stroke="#fff" d="M -5 -2 L -7 0 L -5 2 M -5 -2 L -5 2 M 5 -2 L 7 0 L 5 2 M 5 -2 L 5 2" stroke-width="1" fill="#000" vector-effect="non-scaling-stroke"></path>
                </svg>
              </img-comparison-slider>

            </div>
            <!-- <div class="grow-0 shrink-0 basis-auto w-full">
              <div class="px-6 md:px-12">
                <p class="mb-12">


                </p>
              </div>
            </div> -->
          </div>

        </div>
      </div>

    </div>
  </div>

</section>


</div>
</template>

<style scoped>

.custom-animated-handle {
    transition: transform 0.2s;
  }

  .slider-with-animated-handle:hover .custom-animated-handle {
    transform: scale(1.2);
  }

  .btn-close {
    background: transparent url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' fill='%23000'%3e%3cpath d='M.293.293a1 1 0 011.414 0L8 6.586 14.293.293a1 1 0 111.414 1.414L9.414 8l6.293 6.293a1 1 0 01-1.414 1.414L8 9.414l-6.293 6.293a1 1 0 01-1.414-1.414L6.586 8 .293 1.707a1 1 0 010-1.414z'/%3e%3c/svg%3e") center/1em auto no-repeat;
  }
  .dark .btn-close {
    background: transparent url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' fill='white'%3e%3cpath d='M.293.293a1 1 0 011.414 0L8 6.586 14.293.293a1 1 0 111.414 1.414L9.414 8l6.293 6.293a1 1 0 01-1.414 1.414L8 9.414l-6.293 6.293a1 1 0 01-1.414-1.414L6.586 8 .293 1.707a1 1 0 010-1.414z'/%3e%3c/svg%3e") center/1em auto no-repeat;
  }
</style>
