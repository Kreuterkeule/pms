<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HeaderComponentVue from './components/HeaderComponent.vue';
import MainFrame from './components/MainFrame.vue';
</script>

<template>
  <div class="Mom">
    <HeaderComponentVue class="HeaderComponent"></HeaderComponentVue>
    <MainFrame class="MainFrame"></MainFrame>
  </div>
</template>

<script>

export default {
  data() {
    return {

    }
  },
  components: {
    HeaderComponentVue,
    MainFrame,
  }

}

</script>

<style lang="scss">

* {
  margin : 0;
  padding : 0;
}

.HeaderComponent {
  margin-bottom: 20px;
}

.MainFrame {
  height : calc(100vh - 100px);
}

.Mom {
  height : calc(100vh - 16px);
  margin : 8px;
}

.container {
  height : 100%;
  width: 100%;
}

</style>
