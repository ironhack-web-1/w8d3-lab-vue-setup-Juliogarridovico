<template>
  <div>
    <p>{{ aboutMe }}</p>
  </div>
</template>
<script>
export default {
  name: "AboutComponent",
  data: () => ({
    aboutMe: "lorem ipsum",
  }),
};
</script>
