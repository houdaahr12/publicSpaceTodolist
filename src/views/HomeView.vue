<template>
  <div class="home">
    <section class="hero d-flex align-items-center justify-content-between px-5">
      <div class="container-fluid">
        <div class="row align-items-center">
          <!-- Left Column: Text Content (with margin-top adjustment for large screens) -->
          <div class="col-12 col-md-6 text-center text-md-start mb-md-5">
            <div class="hero-text">
              <h1 class="display-5 fw-bold quote text-center text-md-start">Planifiez votre journée,<br>Accomplissez plus!</h1>
              <p class="fs-5 desc mt-md-3">
                Conçu pour vous aider à prioriser vos tâches, afin que vous puissiez vous concentrer sur ce qui vous fait avancer !
              </p>
              <!-- Button -->
              <router-link to="/register" class="custom-btn btn btn-lg mt-3 start">Démarrez maintenant</router-link>
            </div>
          </div>

          <!-- Right Column: Image (Hidden on small screens) -->
          <div class="col-12 col-md-6 text-center">
            <div class="hero-image">
              <img :src="require('@/assets/hero.png')" alt="Illustration" class="img-fluid d-none d-md-block">
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {  
  name: 'HomeView',
  components: {}
}
</script>

<style scoped>
/* Styling for the quote */
.quote{
  color: hsl(268, 70%, 30%);
  text-align: start;
}

/* Styling for the description */
.desc{
  color: hsl(268, 70%, 30%);
  text-align: start;
}

/* Button customizations */
.custom-btn {
  background: #491784; /* Set background color to #491784 */
  color: white;
  display: inline-block; /* Ensure the button width is based on its content */
  padding: 12px 20px;
  border-radius: 5px;
  transition: transform 0.3s ease, background-color 0.3s ease, box-shadow 0.3s ease;
  margin-top: 20px; /* Space it from the text */
  font-size: 16px; /* Increase font size for better visibility */
  border: none; /* Ensure no border */
  text-align: center; /* Center the text */
}

/* Button hover effects */
.custom-btn:hover {
  background: #613c8b; /* Lighter shade on hover */
  transform: scale(1.1); /* Scale effect on hover */
  cursor: pointer; /* Change cursor to pointer on hover */
}

/* Adjusting image position */
.hero-image img {
  margin-left: 30px; /* Push the image a little bit more to the right */
}

.start{
    background-color: hsl(268, 70%, 30%);
    color: whitesmoke;
}
.start:hover{
    background-color: hsl(268, 70%, 50%);
    color: black;
    transform: scale(1.1);

}



</style>
