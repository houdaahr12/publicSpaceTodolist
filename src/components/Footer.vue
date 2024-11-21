<template>
  <v-footer
    class="pt-5 bg-indigo-lighten-1 text-center d-flex flex-column"
  >
    <div>
      <v-btn 
        v-for="icon in icons"
        :key="icon"
        class="mx-4"
        variant="text"
      >
        <v-icon :class="icon"></v-icon>
      </v-btn>
    </div>

    <div class="pt-3">
    </div>

    <v-divider></v-divider>

    <div>
        &#169
      {{ new Date().getFullYear() }} — <strong>GoalGetter</strong>
    </div>
  </v-footer>
</template>

<script>
export default {
  name: "Footer",
  data: () => ({
    icons: [
      "fab fa-facebook",
      "fab fa-twitter",
      "fab fa-google-plus",
      "fab fa-linkedin",
      "fab fa-instagram"
    ]
  })
};
</script>
