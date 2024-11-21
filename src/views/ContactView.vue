<template>
  <div class="contact">
    <h1 class="display-4 mt-5 mt-lg-5 title fw-bold">Contactez-Nous</h1>
    <div class="container-fluid">
      <div class="row justify-content-center align-items-center">
        <!-- Text Column (on left) -->
        <div class="col-md-5 text-md-start text-center">
          <p class="lead">
            Si vous avez des questions ou des suggestions, n’hésitez pas à nous contacter !<br><br>
            Nous serons ravis de vous aider.
            Vous pouvez nous joindre par email à <a href="mailto:email@example.com">email@example.com</a> ou nous suivre sur nos réseaux sociaux pour rester à jour avec nos dernières nouveautés.
          </p>
        </div>

        <!-- Image Column (on right) - hidden on medium screens and below -->
        <div class="col-md-5 d-none d-md-block">
          <img src="@/assets/contact.png" alt="Contactez-Nous" title="GoalGetter Contact" class="img-fluid">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.title {
  color: hsl(268, 70%, 30%);
  font-size: 2rem; /* Adjust font size for medium and up */
  margin-bottom: 50px;
}



.lead {
  color: hsl(268, 70%, 30%);
}
</style>
