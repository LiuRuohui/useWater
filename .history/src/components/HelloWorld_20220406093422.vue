<script setup>

</script>

<template>
<div class="w-full h-screen flex flex-row select-none">
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
                <div class="flex flex-col py-2 hover:cursor-pointer">
                    <div class="flex flex-row py-2 hover:bg-blue-200 hover:cursor-pointer">
                      <img src="../assets/数据.svg" alt="" class="h-8 opacity-60">
                      <div class="pl-4 pt-1">数据中心</div>
                      <img src="../assets/下拉.svg" alt="" class="my-1 h-6 opacity-60 flex flex-row-reverse flex-grow">
                    </div>
                    <div class="mt-2 flex flex-col hover:cursor-pointer">
                        <div class="py-2 pl-12 hover:bg-blue-200">预览</div>
                        <div class="py-2 pl-12 hover:bg-blue-200">商品监控</div>
                        <div class="py-2 pl-12 hover:bg-blue-200">会员管理</div>
                        <div class="py-2 pl-12 hover:bg-blue-200">核心指标</div>
                        <div class="py-2 pl-12 hover:bg-blue-200">管理中心</div>
                        <div class="py-2 pl-12 hover:bg-blue-200">其他信息</div>
                    </div>
                </div>
                <div class="flex flex-row py-2 hover:bg-blue-200 hover:cursor-pointer">
                  <img src="../assets/日历.svg" alt="" class="h-8 opacity-60">
                  <div class="pl-4 pt-1">运行日历</div>
                </div>
                <div class="flex flex-row py-2 hover:bg-blue-200 hover:cursor-pointer">
                  <img src="../assets/帮助.svg" alt="" class="h-8 opacity-60">
                  <div class="pl-4 pt-1">帮助</div>
                </div>
                <div class="flex flex-row py-2 hover:bg-blue-200 hover:cursor-pointer">
                  <img src="../assets/设置.svg" alt="" class="h-8 opacity-60">
                  <div class="pl-4 pt-1">设置</div>
                </div>
            </div>
        </div>
    </div>
  </div>
  <div class="flex flex-grow flex-col">
      <div class="flex flex-row h-24">
        <img src="../assets/搜索.svg" alt="" class="h-12 my-4">
      </div>
  </div>
</div>
</template>

<style scoped>

</style>
