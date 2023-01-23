<script lang="ts" setup>
import { ref } from 'vue'

defineProps({
  imagelink: String,
  iname: String
})

</script>

<template>
  <img
    :src="imagelink"
    class="tile max-w-sm h-auto transition-shadow ease-in-out duration-300 shadow-none hover:shadow-xl w-1/4 grayscale hover:grayscale-0"
    alt=""
    data-bs-toggle="modal" :data-bs-target="'#'+iname"
  />


  <div class="modal fade fixed top-0 left-0 hidden w-full h-full outline-none overflow-x-hidden overflow-y-auto" :id="iname" tabindex="-1" aria-labelledby="exampleModalCenterTitle" aria-modal="true" role="dialog">
    <div class="modal-dialog modal-dialog-centered relative w-auto max-w-full h-auto pointer-events-none lg:px-28 xs:px-10">
      <div class="modal-content border-none shadow-lg relative flex flex-col w-full pointer-events-auto bg-white bg-clip-padding rounded-md outline-none text-current">

        <img
          :src="imagelink"
          class="max-w-auto max-h-screen h-auto transition-shadow ease-in-out duration-50 shadow-none hover:shadow-xl"
          alt=""
        />
      </div>
    </div>
  </div>





</template>

<style scoped>
img.tile:hover {
  cursor: pointer;
}


</style>
