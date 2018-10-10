<template>
  <section class="component">
    <div>
      <Toolbar/>
      <nuxt />
    </div>
  </section>
</template>

<script>
import Toolbar from "~/components/Toolbar.vue";

export default {
  data() {
    return {};
  },
  components: {
    Toolbar
  }
};
</script>
