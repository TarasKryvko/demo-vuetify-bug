<template>
<div>
  <v-row>
    <h1>Page 2</h1>
  </v-row>
  <v-row>
    <v-btn>Button 2</v-btn>
  </v-row>
  <v-row justify="center" align="center"> 
    <v-menu :close-on-content-click="false" max-width="290">
      <template v-slot:activator="{ on, attrs }">
        <v-text-field clearable label="Formatted with Moment.js" readonly v-bind="attrs" v-on="on"></v-text-field>
      </template>
      <v-date-picker></v-date-picker>
    </v-menu>
  </v-row>
</div>
</template>

<script>
 
export default {
  components: {}
}
</script>
