<template>
  <Home></Home>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import Home from '@/components/Home.vue';

@Options({
  components: {
    Home,
  },
})
export default class home extends Vue {

}
</script>
