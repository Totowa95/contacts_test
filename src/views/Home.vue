<template>
  <div class="home">
    <Header/>
    <HelloWorld/>
    <Footer/>
  </div>
</template>

<script>
import HelloWorld from '@/components/mainPage/contactList/HelloWorld.vue';
import Header from '@/components/mainPage/header/Header.vue';
import Footer from '@/components/mainPage/footer/Footer.vue';

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Header,
    Footer,
  },
};
</script>
