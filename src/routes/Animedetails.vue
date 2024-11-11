<template>
  <div>
    <h2>Anime Details for ID: {{ $route.params.id }}</h2>
    </div>
</template>

<script>
export default {
  name: 'AnimeDetails',
  props: ['id'], // To receive the anime ID from the route

  mounted() {
    // You'll likely want to fetch the anime details here using this.id
    // ...
  }
};
</script>
