<template>
  <div class="wrap">
    <Header />
    <section id="mainCont">
      <div class="main__cont">
        <!-- <div>{{ msg1 }}</div>
        <div>{{ msg2 }}</div>
        <div>{{ msg3 }}</div>
        <div>{{ msg4 }}</div> -->
        <div v-for="todo in todos" v-bind:key="todo.text">
          {{ todo.text }}
        </div>
      </div>
    </section>
    <FooterInfo />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import FooterInfo from "@/components/FooterInfo.vue";

export default {
  components: {
    Header,
    FooterInfo,
  },

  // data() {
  //   return {
  //     msg1: "we provide",
  //     msg2: "visual coding",
  //     msg3: "solutions",
  //     msg4: "for you webs",
  //   };
  // },

  data: function () {
    return {
      todos: [
        { text: "we provide" },
        { text: "visual coding" },
        { text: "solutions" },
        { text: "for you webs" },
      ],
    };
  },
};
</script>

<style lang="scss">
#mainCont {
  height: 100vh;
  background-color: #000;
  display: flex;
  justify-content: center;
  align-items: center;
}

.main__cont {
  color: #fff;
  font-size: 10vw;
  line-height: 0.85;
  letter-spacing: -0.0275em;
  transition: all 2s;
  font-family: "Saol Display Regular";
  text-transform: uppercase;
}
</style>