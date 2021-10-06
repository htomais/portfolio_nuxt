<template>
  <v-container>
    <div id="component-profile" class="d-flex flex-column justify-center align-center">
      <img src="~assets/img/leticia.jpeg" />
      <h1>{{ name }}</h1>
      <p>{{ description }}</p>
      <div class="d-flex">
      <i class="fab fa-stack-overflow"> </i>
      <i class="fab fa-linkedin mx-2"> </i>
      <i class="far fa-envelope mx-2"> </i>
      </div>
    </div>
  </v-container>
</template>

<script>
export default {
  data() {
    return {
      name: 'Dra. Letícia Nery da Silva Tomais',
      description: 'Olá. Iniciando em NuxtJS',
    }
  },
}
</script>

<style lang="scss" scoped>
#component-profile {
  height: 100vh;
  img {
    max-height: 100px;
    border-radius: 100px;
  }
  i {
    font-size: 44px;
    color: orange;
  }
}
</style>>

</style>
