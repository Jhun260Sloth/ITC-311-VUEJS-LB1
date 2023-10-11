<template>
    <Manage />
  </template>
  
  <script>
  import { defineComponent } from 'vue';
  
  // Components
  import Manage from '../components/Manage.vue';
  
  export default defineComponent({
    name: 'ManagementView',
  
    components: {
        Manage,
    },
  });
  </script>
  