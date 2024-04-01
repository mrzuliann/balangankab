<html>

</html>
<template>
  <div class="diamond-menu">
    <div class="video-background">
      <video autoplay muted loop>
        <source src="~/assets/balanganvid.webm" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
    <p class="" style="font-size: larger; stroke-opacity: 20;">SANGGUP BAGAWI GASAN MASYARAKAT</p>
    
    <div class="diamond-row">
      <div class="diamond-column" @mouseover="rotateDiamond(1)" @mouseleave="resetRotation(1)">
        <NuxtLink to="/home">
        <div class="w-20 h-20 flex justify-center items-center relative cursor-pointer">
          <div
            class="hidden md:block rounded-[10px] bg-green-500 border border-dashed border-white absolute inset-0 rotate-45 hover:rotate-0 hover:bg-opacity-50 transition-all"
          ></div>
          <img src="/assets/cell-phone.svg" class="w-8 h-8 relative text-gray-700 md:text-white">
        </div>
        </NuxtLink>
        <NuxtLink to="/home" class="px-3 md:bg-white relative rounded-md hover:bg-opacity-50 transition-all">
        HOME
        </NuxtLink>
      </div>
      <div class="diamond-column" @mouseover="rotateDiamond(2)" @mouseleave="resetRotation(2)">
        <NuxtLink to="/wisata">
        <div class="w-20 h-20 flex justify-center items-center relative cursor-pointer">
          <div
            class="hidden md:block rounded-[10px] bg-green-500 border border-dashed border-white absolute inset-0 rotate-45 hover:rotate-0 hover:bg-opacity-50 transition-all"
          ></div>
          <img src="/assets/globe.svg" class="w-8 h-8 relative text-gray-700 md:text-white">
        </div>
        </NuxtLink>
        <NuxtLink to="/wisata" class="px-3 md:bg-white relative rounded-md hover:bg-opacity-50 transition-all">
        WISATA
        </NuxtLink>
      </div>
      <div class="diamond-column" @mouseover="rotateDiamond(3)" @mouseleave="resetRotation(3)">
        <NuxtLink to="/layanan">
        <div class="w-20 h-20 flex justify-center items-center relative cursor-pointer">
          <div
            class="hidden md:block rounded-[10px] bg-green-500 border border-dashed border-white absolute inset-0 rotate-45 hover:rotate-0 hover:bg-opacity-50 transition-all"
          ></div>
          <img src="/assets/hand-account.svg" class="w-8 h-8 relative text-gray-700 md:text-white">
        </div>
        </NuxtLink>
        <NuxtLink to="/layanan" class="px-3 md:bg-white relative rounded-md hover:bg-opacity-50 transition-all">
        LAYANAN
        </NuxtLink>
      </div> 
      <div class="diamond-column" @mouseover="rotateDiamond(4)" @mouseleave="resetRotation(4)">
        <NuxtLink to="/berita">
        <div class="w-20 h-20 flex justify-center items-center relative cursor-pointer">
          <div
            class="hidden md:block rounded-[10px] bg-green-500 border border-dashed border-white absolute inset-0 rotate-45 hover:rotate-0 hover:bg-opacity-50 transition-all"
          ></div>
          <img src="/assets/life-buoy.svg" class="w-8 h-8 relative text-gray-700 md:text-white">
        </div>
        </NuxtLink>
        <NuxtLink to="/berita" class="px-3 md:bg-white relative rounded-md hover:bg-opacity-50 transition-all">
        BERITA
        </NuxtLink>
      </div>
    </div>
    <div class="menu-row">
      <div class="diamond-column" @mouseover="rotateDiamond(1)" @mouseleave="resetRotation(1)">
        <NuxtLink to="/posts">
        <div class="w-20 h-20 flex justify-center items-center relative cursor-pointer">
          <div
            class="hidden md:block rounded-[10px] bg-green-500 border border-dashed border-white absolute inset-0 rotate-45 hover:rotate-0 hover:bg-opacity-50 transition-all"
          ></div>
          <img src="/assets/stamp.svg" class="w-8 h-8 relative text-gray-700 md:text-white">
        </div>
        </NuxtLink>
        <NuxtLink to="/posts" class="px-3 md:bg-white relative rounded-md hover:bg-opacity-50 transition-all">
        POSTS
        </NuxtLink>
      </div>
      <div class="diamond-column" @mouseover="rotateDiamond(2)" @mouseleave="resetRotation(2)">
        <NuxtLink to="/darurat">
        <div class="w-20 h-20 flex justify-center items-center relative cursor-pointer">
          <div
            class="hidden md:block rounded-[10px] bg-green-500 border border-dashed border-white absolute inset-0 rotate-45 hover:rotate-0 hover:bg-opacity-50 transition-all"
          ></div>
          <img src="/assets/telescope.svg" class="w-8 h-8 relative text-gray-700 md:text-white">
        </div>
        </NuxtLink>
        <NuxtLink to="/darurat" class="px-3 md:bg-white relative rounded-md hover:bg-opacity-50 transition-all">
        DARURAT
        </NuxtLink>
      </div>
      <div class="diamond-column" @mouseover="rotateDiamond(3)" @mouseleave="resetRotation(3)">
        <NuxtLink to="/home">
        <div class="w-20 h-20 flex justify-center items-center relative cursor-pointer">
          <div
            class="hidden md:block rounded-[10px] bg-green-500 border border-dashed border-white absolute inset-0 rotate-45 hover:rotate-0 hover:bg-opacity-50 transition-all"
          ></div>
          <img src="/assets/castle.svg" class="w-8 h-8 relative text-gray-700 md:text-white">
        </div>
        </NuxtLink>
        <NuxtLink to="/home" class="px-3 md:bg-white relative rounded-md hover:bg-opacity-50 transition-all">
        HOME
        </NuxtLink>
      </div>
    </div>
    <div class="diamond-row">
      <div class="diamond-column" @mouseover="rotateDiamond(5)" @mouseleave="resetRotation(5)">
        <NuxtLink to="/websiteskpd">
        <div class="w-20 h-20 flex justify-center items-center relative cursor-pointer">
          <div
            class="hidden md:block rounded-[10px] bg-green-500 border border-dashed border-white absolute inset-0 rotate-45 hover:rotate-0 hover:bg-opacity-50 transition-all"
          ></div>
          <img src="/assets/castle.svg" class="w-8 h-8 relative text-gray-700 md:text-white">

        </div>
        </NuxtLink>
        <NuxtLink to="/WEBSITESKPD" class="px-3 md:bg-white relative rounded-md hover:bg-opacity-50 transition-all">
        SKPD
        </NuxtLink>
      </div>
    </div> 

        
  </div>
</template>
<style scoped>
@media (max-width: 768px) {
  .diamond-menu {
    height: auto;
    padding: 20px;
  }

  .diamond-row,
  .menu-row {
    flex-direction: column;
    align-items: center;
  }

  .diamond-column {
    margin: 10px 0;
  }
}
</style>

<script setup lang="ts">
import { ref } from 'vue';

const rotationDegrees = ref([0, 0, 0, 0, 0]);

const rotateDiamond = (index: number) => {
  rotationDegrees.value[index - 1] = 45;
};

const resetRotation = (index: number) => {
  rotationDegrees.value[index - 1] = 0;
};
</script>

<style scoped>
.diamond-menu {
  position: relative; /* Diperlukan agar elemen video-background bisa diatur secara absolut */
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.video-background {
  position: absolute; /* Menempatkan elemen video-background di atas elemen lain */
  top: 0;
  left: 0;
  width: 100%; /* Mengisi seluruh lebar layar */
  height: 100%; /* Mengisi seluruh tinggi layar */
  overflow: hidden; /* Memastikan video tidak keluar dari batas layar */
}

.video-background video {
  min-width: 100%; /* Memastikan video selalu mengisi seluruh lebar layar */
  min-height: 100%; /* Memastikan video selalu mengisi seluruh tinggi layar */
  width: auto;
  height: auto;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.diamond-row {
  display: flex;
}

.menu-row {
  display: flex;
  margin-top: 20px;
}

.diamond-column {
  margin: 10px;
}

.diamond-button {
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 50px 30px 0 30px;
  border-color: green transparent transparent transparent;
  background-color: transparent;
  cursor: pointer;
  transform-origin: bottom;
  transform: rotate(0deg);
  transition: transform 0.5s ease;
}

.diamond-button:hover {
  transform: rotate(45deg) scale(1.1);
}

.fa-bars {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.menu-button {
  margin: 0 10px;
  padding: 10px 20px;
  background-color: green;
  border: none;
  border-radius: 5px;
  color: white;
  cursor: pointer;
}
</style>
