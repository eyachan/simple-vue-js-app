<template>
  <div>
    <FileUpload :maxSize="5" />
  </div>
</template>

<script>
import FileUpload from "@/components/FileUpload.vue";

export default {
  name: "App",
  components: {
    FileUpload,
  },
};
</script>