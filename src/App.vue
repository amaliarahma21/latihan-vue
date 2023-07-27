<template>
  <div>
    <navbar-component></navbar-component>
    <head-component></head-component>
    <br>  
    <satu-component></satu-component>
    <br>
    <dua-component></dua-component>
    <br>
    <tiga-component> </tiga-component>
    <footer-component></footer-component>
    
    
  </div>
</template>

<script setup>
  import 'flowbite/dist/flowbite.js';

  import NavbarComponent from './NavbarComponent.vue';
  import HeadComponent from './HeadComponent.vue';
  import SatuComponent from './SatuComponent.vue';
  import DuaComponent from './DuaComponents.vue';
  import TigaComponent from './TigaComponent.vue'
  import FooterComponent from './FooterComponent.vue';
  
  
  
</script>