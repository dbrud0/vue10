<template>
  <div id="wrap">
    <Header />
    <main>
      <section id="portCont">
        <div class="container">
          <WrapTitle name1="portfolio" name2="site" />
          <div class="port__cont">
            <div class="port__item">
              <figure class="port__item__img">
                <a href="#"><img src="img/port01.jpg" alt="포트폴리오1" /></a>
              </figure>
              <div class="port__item__txt">
                <h2>PORTFOLIO<br />ukyoung</h2>
                <p>PORTFOLIO</p>
              </div>
            </div>
            <div class="port__item">
              <figure class="port__item__img">
                <a href="#"><img src="img/port02.jpg" alt="포트폴리오1" /></a>
              </figure>
              <div class="port__item__txt">
                <h2>PORTFOLIO<br />ukyoung</h2>
                <p>PORTFOLIO</p>
              </div>
            </div>
            <div class="port__item">
              <figure class="port__item__img">
                <a href="#"><img src="img/port03.jpg" alt="포트폴리오1" /></a>
              </figure>
              <div class="port__item__txt">
                <h2>PORTFOLIO<br />ukyoung</h2>
                <p>PORTFOLIO</p>
              </div>
            </div>
            <div class="port__item">
              <figure class="port__item__img">
                <a href="#"><img src="img/port03.jpg" alt="포트폴리오1" /></a>
              </figure>
              <div class="port__item__txt">
                <h2>PORTFOLIO<br />ukyoung</h2>
                <p>PORTFOLIO</p>
              </div>
            </div>
            <div class="port__item">
              <figure class="port__item__img">
                <a href="#"><img src="img/port02.jpg" alt="포트폴리오1" /></a>
              </figure>
              <div class="port__item__txt">
                <h2>PORTFOLIO<br />ukyoung</h2>
                <p>PORTFOLIO</p>
              </div>
            </div>
            <div class="port__item">
              <figure class="port__item__img">
                <a href="#"><img src="img/port01.jpg" alt="포트폴리오1" /></a>
              </figure>
              <div class="port__item__txt">
                <h2>PORTFOLIO<br />ukyoung</h2>
                <p>PORTFOLIO</p>
              </div>
            </div>
            <div class="port__item">
              <figure class="port__item__img">
                <a href="#"><img src="img/port02.jpg" alt="포트폴리오1" /></a>
              </figure>
              <div class="port__item__txt">
                <h2>PORTFOLIO<br />ukyoung</h2>
                <p>PORTFOLIO</p>
              </div>
            </div>
            <div class="port__item">
              <figure class="port__item__img">
                <a href="#"><img src="img/port03.jpg" alt="포트폴리오1" /></a>
              </figure>
              <div class="port__item__txt">
                <h2>PORTFOLIO<br />ukyoung</h2>
                <p>PORTFOLIO</p>
              </div>
            </div>
            <div class="port__item">
              <figure class="port__item__img">
                <a href="#"><img src="img/port01.jpg" alt="포트폴리오1" /></a>
              </figure>
              <div class="port__item__txt">
                <h2>PORTFOLIO<br />ukyoung</h2>
                <p>PORTFOLIO</p>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>
    <FooterInfo />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import FooterInfo from "@/components/FooterInfo.vue";
import WrapTitle from "@/components/WrapTitle.vue";

export default {
  components: {
    Header,
    FooterInfo,
    WrapTitle,
  },
};
</script>

<style lang="scss">
#portCont {
  background-color: #000;
}

.port__cont {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
.port__item {
  flex: 0 0 32%;
  margin-bottom: 2%;
}
.port__item__txt {
  padding: 35px 35px 25px 35px;
  background: #151517;
}
.port__item__txt h2 {
  font-family: "Saol Display Regular";
  font-size: 50px;
  line-height: 1;
  color: #fff;
}
.port__item__txt p {
  font-size: 16px;
  color: #b0aead;
  font-family: "Rajdhani";
}
</style>