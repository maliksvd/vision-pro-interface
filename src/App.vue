<script setup>
import IconsClock from "./components/Icons/Clock.vue";
import IconsMicro from "./components/Icons/Micro.vue";
import IconsFolder from "./components/Icons/Folder.vue";
import IconsMusic from "./components/Icons/Music.vue";
import IconsUser from "./components/Icons/User.vue";
</script>

<template>
  <div class="flex flex-col justify-center h-screen">
    <div class="main-card w-full">
      <div class="left-side">
        <div>
          <h1 class="text-white font-bold text-2xl">Library</h1>
          <p class="text-[#EBEBF599] text-sm">All music</p>
        </div>
        <div>
          <ul id="user-category">
            <li>
              <IconsClock />Recently Added
            </li>
            <li>
              <IconsMicro />Artists
            </li>
            <li>
              <IconsFolder />Albums
            </li>
            <li>
              <IconsMusic /> Songs
            </li>
            <li>
              <IconsUser /> Made for you
            </li>
          </ul>
        </div>
      </div>
      <div class="right-side">right</div>
    </div>
  </div>
</template>

