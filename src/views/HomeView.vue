<template>
  <div class="home">
    <div>
      <HeaderWithSearch />
    </div>
  </div>
</template>

<script>
  import HeaderWithSearch from "@/components/HeaderWithSearch.vue";

export default {
  name: 'HomeView',
  components: {
    HeaderWithSearch
  },
}
</script>
