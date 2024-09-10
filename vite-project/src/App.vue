<!-- per utilizzare un componente va :
 1) prima importato
 2) poi dichiarato
 3) e infine utilizzato -->
<script>
import HeaderTop from './components/HeaderTop.vue';

export default {
  data() {
    return{
      message: 'ciao',
    };
  },
  components: {
    HeaderTop,
  },
  methods:{

  }
}

</script>

<template>

<HeaderTop />
 
</template>

<style scoped>


</style>
