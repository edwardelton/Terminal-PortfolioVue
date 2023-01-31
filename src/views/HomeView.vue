<template>
  <Terminal />
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import Terminal from "../components/Terminal.vue"; // @ is an alias to /src

@Options({
  components: {
    Terminal,
  },
})
export default class HomeView extends Vue {}
</script>
