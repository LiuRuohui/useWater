<script setup>

</script>

<template>
<div class="w-full h-screen flex flex-row select-none">
  <div class="w-1/5 h-screen justify-center items-center flex flex-col">
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
  <div class="w-full flex flex-grow flex-col bg-gray-100">
      <div class="flex flex-row h-24">
          <img src="../assets/搜索.svg" alt="" class="h-8 mt-6 pl-12 hover:cursor-pointer">
          <div class="flex flex-col pt-6 px-4 hover:cursor-pointer">
              <div class="text-sm opacity-50">XX科技</div>
              <div class="text-md opacity-80">复水焕能</div>
          </div>
          <div class="text-base px-8 pt-8 hover:cursor-pointer">仪表面板</div>
          <div class="text-base px-8 pt-8 hover:cursor-pointer">资源中心</div>
          <div class="flex flex-grow flex-row-reverse">
              <img src="../assets/设置.svg" alt="" class="h-4 mt-10 mr-4 hover:cursor-pointer hover:bg-blue-100">
              <span class="my-9 mr-4 text-black text-base opacity-70 hover:cursor-pointer hover:bg-blue-100">Susan</span>
              <img src="../assets/用户.svg" alt="" class="h-8 mt-8 mr-2 hover:cursor-pointer hover:bg-blue-100">
              <img src="../assets/搜索.svg" alt="" class="h-6 mt-9 mr-6 hover:cursor-pointer hover:bg-blue-100">
              <img src="../assets/搜索.svg" alt="" class="h-6 mt-9 mr-6 hover:cursor-pointer hover:bg-blue-100">
              <img src="../assets/搜索.svg" alt="" class="h-6 mt-9 mr-6 hover:cursor-pointer hover:bg-blue-100">
          </div>
      </div>
      <div class="m-4 bg-blue-700 h-40 opacity-80 shadow-lg">
          <div class="flex flex-row h-24 my-8">
              <img src="../assets/测试图片.jpg" alt="" class="h-20 my-auto pl-12">
              <div class="flex flex-col pl-6 pt-2">
                  <div class="text-xl text-white">下午好,欢迎登录</div>
                  <div class="text-sm text-white pt-4">阿巴阿巴阿巴阿巴阿巴阿巴</div>
              </div>
          </div>
      </div>
      <div class="h-40 my-2 mx-4">
          <div class="flex flex-col pt-4 pl-8">
              <div class="flex flex-row">
                  <div class="font-black text-black">今日核心指标</div>
                  <div class="flex flex-grow flex-row-reverse opacity-40 pr-8">查看更多</div>
              </div>
              <div class="flex flex-grow flex-row mt-4">
                  <div class="flex flex-col pr-8">
                      <div class="opacity-80">今日污水处理量</div>
                      <div class="text-4xl">67t</div>
                      <div class="opacity-60">同比增长35%</div>
                  </div>
                  <div class="flex flex-col px-12">
                      <div class="opacity-80">今日污水处理量</div>
                      <div class="text-4xl">67t</div>
                      <div class="opacity-60">同比增长35%</div>
                  </div>
                  <div class="flex flex-col px-12">
                      <div class="opacity-80">今日污水处理量</div>
                      <div class="text-4xl">67t</div>
                      <div class="opacity-60">同比增长35%</div>
                  </div>
                  <div class="flex flex-col px-12">
                      <div class="opacity-80">今日蒸馏水产量</div>
                      <div class="text-4xl">36t</div>
                  </div>
                  <div class="flex flex-col px-12">
                      <div class="opacity-80">今日工作时长</div>
                      <div class="text-4xl">18h53min</div>
                  </div>
              </div>
          </div>
      </div>
      <div class="flex flex-grow flex-row">
          <div class="w-1/3 flex flex-col">
              <div class="flex h-40 m-4 bg-pink-200">
                  <div class="font-bold opacity-70 mt-4">月数据趋势</div>
              </div>
              <div class="flex flex-grow bg-blue-400 mx-4 mb-4">
                  <div class="w-full flex flex-col m-4">
                      <div class="w-full flex flex-row">
                          <div class="text-white mb-2 text-base opacity-60">预警提示</div>
                      </div>
                      <div class="text-white font-semibold">产品运行状况正常</div>
                  </div>
              </div>
          </div>
      </div>
  </div>
</div>
</template>

<style scoped>

</style>
