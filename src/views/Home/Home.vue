<template>
<layout>
  <div class="home">
   
  </div>
   </layout>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "@/components/HelloWorld.vue";
import Layout from "@/components/Layout/Layout.vue";

export default defineComponent({
  name: "Home",
  components: {
    HelloWorld,
    Layout
  },
});
</script>