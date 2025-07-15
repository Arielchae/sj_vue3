<template>
  <!-- 자식을 원하는 위치에 넣으려면 slot이라는 기능을 사용한다. -->
  <div class="content-box-container"><slot></slot></div>
</template>

<style lang="css" scoped>
@import 'tailwindcss';

.content-box-container {
  @apply mx-auto mt-10 flex w-7/8 flex-col justify-center rounded-xl bg-blue-950 p-5 font-semibold text-gray-100 shadow-lg transition-all duration-300 hover:shadow-xl;
}
</style>
