<template>
  <div class="p-5 w-full">
    <MainHeader>Board</MainHeader>

    <div class="flex space-x-5">
      <div class="flex-grow">
        <h4 class="text-lg font-bold">To do</h4>
        <div class="bg-gray-200 h-full rounded p-2 space-y-2">
          <div class="bg-white rounded p-2">
            Some issue
          </div>

          <div class="bg-white rounded p-2">
            Some issue
          </div>

          <div class="bg-white rounded p-2">
            Some issue
          </div>
        </div>
      </div>

      <div class="flex-grow">
        <h4 class="text-lg font-bold">In progress</h4>
        <div class="bg-gray-200 h-full rounded p-2">

        </div>
      </div>

      <div class="flex-grow">
        <h4 class="text-lg font-bold">Complete</h4>
        <div class="bg-gray-200 h-full rounded p-2">

        </div>
      </div>
    </div>
  </div>
</template>

<script>
import MainHeader from '@/components/MainHeader';

export default {
  components: {
    MainHeader
  }
}
</script>
