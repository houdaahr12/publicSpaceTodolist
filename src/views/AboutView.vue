<template>
  <div class="about">
    <h1 class="display-4 mt-5 mt-md-3 title fw-bold">À Propos</h1>
    <div class="container-fluid">
      <div class="row justify-content-center align-items-center">
        <!-- Image Column (hidden on medium screens and below) -->
        <div class="col-md-5 d-none d-md-block">
          <img src="@/assets/apropos.png" alt="apropos" title="GoalGetter todolist" class="img-fluid" />
        </div>

        <!-- Text Column -->
        <div class="col-md-5 text-center text-md-start mt-5">
          <p class="lead">
            Nous savons à quel point il peut être difficile de jongler entre plusieurs tâches importantes au quotidien. C’est pour cela que GoalGetter a été conçu pour vous aider à prioriser vos actions et suivre vos progrès.
          </p>
        </div>
      </div>
    </div>

    
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.title {
  color: hsl(268, 70%, 30%);
  font-size: 2rem;
  margin-top: 300px;
}

.lead {
  color: hsl(268, 70%, 30%);
}

.features h2 {
  color: hsl(268, 70%, 30%);
}

.v-card {
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.v-card:hover {
  transform: scale(1.05);
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
}
</style>
