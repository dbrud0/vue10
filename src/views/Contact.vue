<template>
  <div id="wrap">
    <Header />
    <main>
      <section id="contactCont">
        <div class="contact-cont">
          <div>YOU ARE</div>
          <div>ALREADY</div>
          <div>DOING WELL.</div>
        </div>
      </section>
    </main>
  </div>
</template>

<script>
import Header from "@/components/Header.vue";


export default {
  components: {
    Header,
  },
};
</script>

<style lang="scss">
#contactCont {
  height: 100vh;
  background-color: #000;
}

.contact-cont {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  white-space: nowrap;
}

.contact-cont div {
  font-size: 100px;
  font-family: "Saol Display Regular";
  font-weight: normal;
  padding-top: 1.6vw;
  text-transform: uppercase;
  color: #fff;
  font-size: 180px;
  line-height: 130px;
}
</style>