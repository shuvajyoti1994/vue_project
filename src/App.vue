<template>
  <div class="container">
    <Navigation />
    <RouterView />
    <h1>This is footer</h1>

  </div>
</template>


<script>
import Navigation from './components/Navigation.vue';

  export default{
    data() {
        return {};
    },
    methods: {},
    components: { Navigation }
}
</script>