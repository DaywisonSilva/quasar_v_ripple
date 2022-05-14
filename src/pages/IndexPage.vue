<template>
  <div>
    <q-card v-ripple>
      <q-card-section
        ><h1 class="text-h5">{{ title }}</h1></q-card-section
      >
      <q-separator></q-separator>
      <q-card-section
        >Lorem ipsum dolor, sit amet consectetur adipisicing elit. Inventore
        esse voluptate nemo quia aperiam sunt voluptatibus alias maiores
        dolores? Tenetur, minus cupiditate officia consectetur delectus quo
        eaque numquam voluptas sit!
      </q-card-section>
    </q-card>
  </div>
</template>
<script setup lang="ts">
const title = 'v-ripple test';
</script>
