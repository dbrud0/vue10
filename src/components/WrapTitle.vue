<template>
  <div class="wrap__title">
    <h1>
      <strong>{{ name1 }}</strong>
      <em>{{ name2 }}</em>
    </h1>
  </div>
</template>

<script>
export default {
  props: {
    name1: String,
    name2: String,
  },
};
</script>

<style lang="scss">
/* wrap__title */
.wrap__title {
  padding: 18rem 0 10rem;
}

.wrap__title h1 {
  color: #000;
  font-size: 10vmax;
  line-height: 0.85;
  letter-spacing: -0.0275em;
  font-family: "Saol Display Regular";
  text-transform: uppercase;
}

.wrap__title h1 strong {
  display: block;
  opacity: 1;
}

.wrap__title.light h1 {
  color: #fff;
}

.wrap__title h1 strong,
.wrap__title h1 em {
  display: block;
  padding-top: 10px;
}
</style>