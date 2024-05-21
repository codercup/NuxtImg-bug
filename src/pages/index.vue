<template>
  <div>
    <!-- <img class="w-full" src="~/assets/images/pretty-girl.png" /> -->
    <img class="w-full" src="/images/pretty-girl.png" />
    <p class="text-center">下面是 NuxtImg 组件显示图片，mac正常，windows不正常！</p>
    <NuxtImg class="w-full" src="/images/pretty-girl.png" />
    <div class="container m-auto bg-yellow-100 p-4">
      <fg-content :line="40" />
    </div>
  </div>
</template>
