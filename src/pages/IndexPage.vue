<template>
  <q-page class="flex flex-center text-textheader">

    <div class="row full-width">
      <div class="col text-center text-h3 text-weight-bolder">
      Choose A Gamemode
      </div>
    </div>

    <div class="row full-width">
      <div class="col text-center text-h4 text-weight-bolder q-pb-xl">
      3 Buttons
      </div>
    </div>

        <div class="row full-width">
      <div class="col text-center text-h3 text-weight-bolder q-pb-xl">
      Choose Your Difficulty
      </div>
    </div>

            <div class="row full-width">
      <div class="col text-center text-weight-bolder q-gutter-sm">

        <q-btn unelevated color="accent" label="Easy" size="lg" @click="mode = easy"/>
        <q-btn unelevated color="accent" label="Medium" size="lg" @click="mediummode = true"/>
        <q-btn unelevated color="accent" label="Hard" size="lg" @click="hardmode = true"/>
        <q-btn unelevated color="accent" label="Master" size="lg" @click="mastermode = true"/>
<br>
<br>
        <q-btn unelevated color="accent" label="Go!" size="xl" padding="xl" :disable="mode = none"/>

      </div>
    </div>

            <div class="row full-width">
      <div class="col text-center text-h3 text-weight-bolder q-pb-xl">
      mode
      </div>
    </div>
    
  </q-page>
</template>

<script setup>
</script>