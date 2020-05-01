<template>
  <div
    class="flex h-screen"
    style="background: #1d1626 url(/img/background.svg) repeat;"
  >
    <div class="m-auto">
      <div class="text-white font-lato font-normal text-xl">Welcome!</div>
      <div class="text-white font-lato font-bold text-xl py-2">
        丝蓝数码策略
      </div>
      <div class="text-white font-lato font-black text-3xl py-2">
        CILERE Digital Strategy
      </div>
      <div
        @click="toPriviledger"
        class="cursor-pointer rounded rounded-t-lg overflow-hidden w-full px-10 my-3 bg-white text-grey hover:text-blue"
      >
        <p class="mt-2 font-lato font-normal text-xs lg:text-base xl:text-xl">
          Thank you for your interest in our flagship project
        </p>
        <div class="flex py-5 justify-center">
          <img
            style="width: 80px; height: 80px;"
            src="/img/logo.jpg"
            class="rounded-full border-solid border-white border-2"
          />
        </div>
        <div class="text-center px-3 pb-6 pt-2">
          <h3 class="text-sm font-romina font-medium">贝维悠悦</h3>
          <p class="mt-2 font-romina font-medium">
            P R I V I L E D G E R
          </p>
          <p class="mt-2 font-lato text-xs font-light">
            TREASURES AROUND THE GLOBAL
          </p>
        </div>
        <div class="flex justify-center font-normal pb-3">
          <div>The Lastest trends from Paris, London, Milan & more</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
  methods: {
    toPriviledger() {
      window.location.href = "https://www.priviledger.fr/";
    },
  },
};
</script>
