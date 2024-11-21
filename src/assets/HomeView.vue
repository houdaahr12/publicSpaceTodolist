<template>
  <div class="home">
    <section class="hero d-flex align-items-center justify-content-between p-5">
      <div class="hero-text">
        <h1 class="display-5 fw-bold quote">Planifiez votre journée,<br>Accomplissez plus!</h1>
        <p class="fs-5 desc">
          Conçu pour vous aider à prioriser vos tâches, afin que vous puissiez vous concentrer sur ce qui vous fait avancer !
        </p>
        <button class="btn btn-lg mt-5">Démarrez maintenant</button>
      </div>
      <div class="hero-image">
        <img :src="require('@/assets/hero.png')" alt="Illustration" class="img-fluid d-none d-md-block">
      </div>
    </section>

  </div>
</template>

<script>
// @ is an alias to /src

export default {  
  name: 'HomeView',
  components: {
    
  }
}
</script>

<style>
.quote{
  color: hsl(268, 70%, 30%);
  text-align: start;
}
.desc{
  color: hsl(268, 70%, 30%);
  text-align: start;
}

.btn-lg{
  display: flex;
  background: hsl(268, 70%, 30%);
  color: white;
  
}
.btn-lg:hover{
  background: hsl(268, 70%, 60%);
}

</style>
