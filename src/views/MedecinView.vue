<template>
  <div>
    <NavbarComponent />
    <RechercheMedecinComponent />
  </div>
</template>

<script>
import NavbarComponent from '../components/NavbarComponent.vue';
import RechercheMedecinComponent from '@/components/RechercheMedecinComponent.vue';

export default {
  components: {
    NavbarComponent,
    RechercheMedecinComponent,
  },
};
</script>