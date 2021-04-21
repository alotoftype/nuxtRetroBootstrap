<template>
  <footer>
    <section class="footer-links">
      <Navigation />
    </section>
    <section>
      <p>website name copyright {{ getYear }}</p>
    </section>
  </footer>
</template>
<script>
export default {
  computed: {
    getYear: function () {
      let d = new Date();
      return d.getFullYear();
    },
  },
};
</script>
<style>
.footer-links {
  text-align: center;
}
</style>
