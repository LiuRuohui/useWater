<script setup>

</script>

<template>
<div class="w-full h-screen flex flex-row">
  <div class="w-1/4 h-screen justify-center items-center flex flex-col">
    <div class="w-full h-20 justify-center items-center flex">
        <div class="w-5/6">
            <button class="btn text-white justify-center items-center shadow-xl">立即购买</button>
        </div>
    </div>
    <div class="w-full flex flex-grow bg-gray-50 justify-center">
        <div class="w-5/6 pt-4 flex flex-col">
            <div class="h-8 text-xl opacity-40 pl-2">仪表面板</div>
            <div class="mt-4 flex flex-grow flex-col">
                <div class="flex flex-col my-2">
                    <div class="flex flex-row">
                      <img src="../assets/数据.svg" alt="" class="h-8">
                      <div class="pl-4 pt-1">数据中心</div>
                    </div>
                </div>
                <div class="flex flex-row my-2">
                  <img src="../assets/日历.svg" alt="" class="h-8">
                  <div class="pl-4 pt-1">运行日历</div>
                </div>
                <div class="flex flex-row my-2">
                  <img src="../assets/帮助.svg" alt="" class="h-8">
                  <div class="pl-4 pt-1">帮助</div>
                </div>
                <div class="flex flex-row my-2">
                  <img src="../assets/设置.svg" alt="" class="h-8">
                  <div class="pl-4 pt-1">设置</div>
                </div>
            </div>
        </div>
    </div>
  </div>
  <div class="flex flex-grow bg-yellow-50">

  </div>
</div>
</template>

<style scoped>

</style>
