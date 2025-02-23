<template>
    <ProfileInfo
      :photo="photo"
      title="Amanda dos Santos Oliveira"
      subtitle="@amanda.s18.08"
      headline="Software Engineering | C# Developer | MBA"
    />
  
    <div class="max-w-xs mx-auto">
      <ButtonAction link="https://www.linkedin.com/in/amanda-s-319b0b114" icon="💼" text="Linkedin" />
      <ButtonAction link="https://github.com/Amandaoliveira18" icon="🛠" text="Github" />
      <ButtonAction link="https://www.instagram.com/amanda.s18.08/#" icon="👨🏽‍💻" text="Instagram" />
      <ButtonAction @openModal="isModalOpen = true"  icon="🎵" text="Playlist Spotify" />
    </div>
  
    <ModalSpotify :isOpen="isModalOpen" @close="isModalOpen = false" />
  </template>
  
  <script setup>
  import { ref } from "vue";
  import photo from "../assets/img/picture.png";
  import ModalSpotify from "../components/ModalSpotify.vue";
  import ButtonAction from "../components/ButtonAction.vue";
  
  const isModalOpen = ref(false);
  </script>
  