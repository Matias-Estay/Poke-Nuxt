<template>
  <layout>
    <template v-slot:default>
      <b-row class="justify-content-center">
        <b-img responsive alt="Vue logo" src="~/assets/images/logo_pikachu.png" fluid class="ml-5" style="width:600px;"/>
      </b-row>
      <b-row class="justify-content-center"> 
        <h3 style="text-align:center;">
          Welcome to the pokédex
        </h3>
      </b-row>
      <b-row class="justify-content-center">
        <p class="text-justify text-center">
          The digital encyclopedia created by Professor Oak is an invaluable tool 
          to Trainers in the Pokémon world.
        </p>
        <p class="text-justify text-center">
          Programado por Matías Ignacio Estay Cubillos.
        </p>
      </b-row>
      <b-row class="justify-content-center">
        <NuxtLink class="poke-btn btn" to="/home">Get Started</NuxtLink>
      </b-row>
    </template>
  </layout>
</template>
<script>
export default {
  name: 'app',
}
</script>
