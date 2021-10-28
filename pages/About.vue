<template>
  <div>
    <h1>About DadJokes</h1>
    <p>This is an app the displays corny dad jokes</p>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "About Us",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Best place for corny dad jokes",
        },
      ],
    };
  },
};
</script>

<style scoped></style>
