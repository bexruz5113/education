<template>
  <div class="p-5 bg-black relative">
    <div class="absolute right-0 top-0">
      <svg
        width="730"
        height="772"
        viewBox="0 0 1230 972"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <g filter="url(#filter0_f_10_65)">
          <rect
            x="500"
            y="268.736"
            width="405"
            height="519.642"
            rx="202.5"
            fill="#3FD700"
          />
        </g>
        <defs>
          <filter
            id="filter0_f_10_65"
            x="0"
            y="-231.264"
            width="1405"
            height="1519.64"
            filterUnits="userSpaceOnUse"
            color-interpolation-filters="sRGB"
          >
            <feFlood flood-opacity="0" result="BackgroundImageFix" />
            <feBlend
              mode="normal"
              in="SourceGraphic"
              in2="BackgroundImageFix"
              result="shape"
            />
            <feGaussianBlur
              stdDeviation="250"
              result="effect1_foregroundBlur_10_65"
            />
          </filter>
        </defs>
      </svg>
    </div>
    <div class="absolute bottom-0 left-0">
      <svg
        style="width: 100%; max-width: 702px"
        height="772"
        viewBox="0 0 902 972"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <g filter="url(#filter0_f_10_66)">
          <rect
            x="-140"
            y="444"
            width="542"
            height="546"
            rx="271"
            fill="#5D86EF"
          />
        </g>
        <defs>
          <filter
            id="filter0_f_10_66"
            x="-640"
            y="-56"
            width="1542"
            height="1546"
            filterUnits="userSpaceOnUse"
            color-interpolation-filters="sRGB"
          >
            <feFlood flood-opacity="0" result="BackgroundImageFix" />
            <feBlend
              mode="normal"
              in="SourceGraphic"
              in2="BackgroundImageFix"
              result="shape"
            />
            <feGaussianBlur
              stdDeviation="250"
              result="effect1_foregroundBlur_10_66"
            />
          </filter>
        </defs>
      </svg>
    </div>

    <div class="pb-5">
      <div class="flex justify-between">
        <p
          class="font-sans md:text-8xl text-5xl leading-normal text-white font-bold z-10"
        >
          Все курсы
        </p>
        <p
          class="font-sans md:text-8xl lg:block hidden text-5xl leading-normal text-gray-600 font-bold z-10"
        >
          Разработка
        </p>
      </div>
      <div>
        <p class="font-sans text-white md:text-2xl text-xl font-bold my-3 z-10">
          Наша цель: Вырасти специалистов и трудоустройства их
        </p>
      </div>
    </div>

    <div class="md:block hidden z-10"><SwiperVertical /></div>
    <div class="md:hidden block z-10"><SwiperHR /></div>
  </div>
</template>

<script>
import SwiperHR from './swiperHR.vue'
import SwiperVertical from './swiperVertical.vue'
export default {
  components: {
    SwiperVertical,
    SwiperHR,
  },
}
</script>

<style></style>
