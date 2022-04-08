<script setup>

</script>

<template>
<div class="w-full h-screen flex flex-row">
  <div class="w-1/4 h-screen bg-blue-50 justify-center items-center flex flex-col">
    <div class="w-full h-20 justify-center items-center flex">
        <div class="w-5/6">
            <button class="btn text-white justify-center items-center shadow-xl">立即购买</button>
        </div>
    </div>
    <div class="flex flex-grow flex-col">
        <div class="w-full flex flex-grow bg-green-100 justify-center items-center">
            <div class="w-5/6 h-20 py-4 relative">
                <input
                    class="box-border rounded-full h-9 pl-14 pr-4 py-3 w-full outline-none bg-gray-100 text-sm select-none"
                    type="text"
                    placeholder="请输入搜索的内容"
                />
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
