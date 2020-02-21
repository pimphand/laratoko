<template>
  <div class="home">
    <Headerlara />
    <hero />
    <banner />
    <insta />
    <patner />
    <footerlara />
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import Headerlara from '@/components/Headerlara.vue';
import hero from '@/components/hero.vue';
import banner from '@/components/banner.vue';
import insta from '@/components/insta.vue';
import patner from '@/components/patner.vue';
import footerlara from '@/components/footerlara.vue'


export default {
  name: 'Home',
  components: {
    //HelloWorld
    Headerlara,
    hero,
    banner,
    insta,
    patner,
    footerlara
  }
}
</script>
