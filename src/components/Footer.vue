<template>
  <v-footer>
    <div class="pt-3 foot">
    <div class="container">
            <div>
                <div class="social-media">
                    <a href="#" class="icon fs-2 me-3"><i class="bi bi-facebook"></i></a>
                    <a href="#" class="icon fs-2 me-3"><i class="bi bi-pinterest"></i></a>
                    <a href="#" class="icon fs-2 me-3"><i class="bi bi-instagram"></i></a>
                    <a href="#" class="icon fs-2"><i class="bi bi-linkedin"></i></a>
                </div>
        </div>
        <hr>
        <div class="d-sm-flex justify-content-between">
            <p>2024 © GoalGetter. All Rights Reserved. </p>
            <p>
                <a href="#" class=" text-decoration-none pe-4">Terms of use</a>
                <a href="#" class=" text-decoration-none"> Privacy policy</a>
            </p>
        </div>
    </div>
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

<style>
.foot {
  background: #cccccc;
  display: flex;
  flex-direction: column;
  justify-content: -end; /* Assure que le contenu est aligné en bas */
  margin-top: 100px;
}

.social-media {
  display: flex;
  justify-content: center;
  gap: 1rem;
}

.icon {
  display: inline-block;
  transition: transform 0.3s ease, color 0.3s ease;
}

i {
  color: #491784;
}

.icon i:hover {
  color: #823aa0;
  transform: scale(1.3) rotate(10deg);
}

</style>