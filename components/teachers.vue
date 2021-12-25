<template>
  <div class="bg-black relative p-5">
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
    <div>
      <p
        class="font-sans md:text-8xl text-5xl leading-normal text-white font-bold z-10"
      >
        Наши преподы
      </p>
      <p class="text-white text-2xl font-sans z-10">
        Каждый студент и выпускник является частю <br />семьи IT-Unity.
      </p>
    </div>
    <div class="md:block hidden"><TeamVertical /></div>
    <div class="md:hidden block"><TeamHR /></div>
  </div>
</template>

<script>
import TeamHR from './teamHR.vue'
import TeamVertical from './teamVertical.vue'
export default {
  components: { TeamVertical, TeamHR },
}
</script>

<style scoped></style>
