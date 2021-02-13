<template>
  <v-app dark> 
    <v-app-bar fixed app >
      <NLink class="nuxt-link mx-5" to="page1">Page 1</NLink>
      <NLink class="nuxt-link mx-5" to="page2">Page 2</NLink>
    </v-app-bar>
    <v-main>
      <v-container>
        <nuxt />
      </v-container>
    </v-main> 
    <v-footer app> 
    </v-footer>
  </v-app>
</template>

<script>
export default {
 
}
</script>
