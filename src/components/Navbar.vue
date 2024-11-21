<template>
  <header>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg px-4 mb-5">
      <div class="container-fluid">
        <!-- Brand (Left) -->
        <a class="navbar-brand d-flex align-items-center" href="#">
            <img src="@/assets/logoo.png" alt="GoalGetter logo" width="45" height="24">
            <span>GoalGetter</span>
        </a>

        <!-- Toggler for small screens -->
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

      <!-- Navbar Links and Buttons -->
<div class="collapse navbar-collapse" id="navbarNav">
  <!-- Centered Links -->
  <ul class="navbar-nav mx-auto">
    <li class="nav-item">
      <!-- Use router-link for Vue Router navigation -->
      <router-link to="/" class="nav-link" exact-active-class="active">Accueil</router-link>
    </li>
    <li class="nav-item">
      <router-link to="/about" class="nav-link" exact-active-class="active">A Propos</router-link>
    </li>
    <li class="nav-item">
      <router-link to="/contact" class="nav-link" exact-active-class="active">Contact</router-link>
    </li>
  </ul>
  <!-- Buttons (Right-Aligned) -->
  <div class="d-flex">
  <router-link to="/login" class="btn me-3 login">Se Connecter</router-link>
  <router-link to="/register" class="btn start ">Démarrez Maintenant</router-link>
</div>

</div>


          
        </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
/* Custom styles for the navbar */
.navbar{
    background: hsl(0, 0%, 80%);
    transition: transform 0.3s ease, background-color 0.3s ease, box-shadow 0.3s ease;

}
.navbar-brand span {
  font-weight: bold;
  font-size: 16px;
  color: hsl(268, 70%, 30%);
}

.nav-link {
  font-size: 16px;
  font-weight: 500;
  color: hsl(268, 70%, 30%);
}

.nav-link:hover{
    color: hsl(268, 70%, 60%);
    transform: scale(1.1);

}

.nav-link.active {
  color: #42204b !important;
  font-weight: bold;
}

button {
    font-size: 14px;
    transition: transform 0.3s ease, background-color 0.3s ease, box-shadow 0.3s ease;

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
.login{
    background: hsl(0, 0%, 65%);
}
.login:hover{
      transform: scale(1.1);
      background: hsl(0, 0%, 35%);
      color: white;

}
</style>
