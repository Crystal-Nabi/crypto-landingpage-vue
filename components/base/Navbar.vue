<template>
  <nav id="navbar" class="sticky top-0 z-10 w-full text-neutral-800 bg-sky-100 dark:bg-[#1E3140]">
    <div class="flex flex-col max-w-screen-xl px-8 mx-auto lg:items-center lg:justify-between lg:flex-row py-4 nav">
      <div class="flex flex-col lg:flex-row items-center space-x-4 xl:space-x-8  nav-bar">
        <div class="w-full flex flex-row items-center justify-between py-3 nav-logo">
          <div>
            <img :src="require('~/assets/img/logo/B5.png')" class="w-36" alt="Logo" />
          </div>
          <button class="rounded-lg lg:hidden focus:outline-none focus:shadow-outline" @click="open = !open">
            <SegmentIcon v-if="!open" :size="24" class="dark:text-white" />
            <CloseIcon v-else :size="24" class="dark:text-white" />
          </button>
        </div>
        <ul :class="[open ? 'flex' : 'hidden lg:flex']"
          class="w-full h-auto flex flex-col dark:text-white lg:items-center pb-4 lg:pb-0 lg:justify-end lg:flex-row origin-top duration-300 xl:space-x-2 space-y-3 lg:space-y-0 nav-item">

          <li class="mr-6">
            <a class="text-[#2f7cf0] hover:text-[#0e65e8]" href="#">Home</a>
          </li>
          <li class="mr-6">
            <a class="text-[#2f7cf0] hover:text-[#0e65e8]" href="#">About Us</a>
          </li>
          <li class="mr-6">
            <a class="text-[#2f7cf0] hover:text-[#0e65e8]" href="#">Speakers</a>
          </li>
          <li class="mr-6">
            <a class="text-[#2f7cf0] hover:text-[#0e65e8]" href="#">Sponsors</a>
          </li>
          <li class="mr-6">
            <a class="text-[#2f7cf0] hover:text-[#0e65e8]" href="#">Partners</a>
          </li>

          <li class="mr-6">
            <a class="text-[#2f7cf0] hover:text-[#0e65e8]" href="#">Floor Plan</a>
          </li>

        </ul>
      </div>
      <div :class="[open ? 'flex' : 'hidden lg:flex']" class="space-x-3 auth-btn">
        <base-button class="px-8 xl:px-10 py-3 mt-2 bg-inherit text-gradient border border-[#0c66ee]">
          Login
        </base-button>
        <base-button class="px-8 xl:px-10 py-3 mt-2 bg-gradient-to-r from-[#468ef9] to-[#0c66ee] text-white">
          Sign Up
        </base-button>
      </div>
    </div>
  </nav>
</template>
<script>
export default {
  name: 'BaseNavbar',
  data() {
    return {
      open: false,
      dropdownNavbar: false,
    }
  },
  methods: {
    dropdownToggler() {
      this.dropdownNavbar = !this.dropdownNavbar
    }
  }
}
</script>
