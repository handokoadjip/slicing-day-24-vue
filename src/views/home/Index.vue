<template>
  <ContentComponent />
</template>

<script>
import ContentComponent from "@/components/ContentComponent.vue";

export default {
  name: "HomePage",
  components: {
    ContentComponent,
  },
  mounted() {
    document.title = "Design Inspiration | Dennis Adelmann"
  }
}
</script>
