<template>
  <div id="wrap" class="light">
    <Header />
    <main>
      <section id="referCont">
        <div class="container">
          <WrapTitle name1="reference" name2="book" />
          <div class="refer-cont">
            <div class="refer-table">
              <ul>
                <li>
                  <a href="#">
                    <span class="alpha">A</span>
                    <span class="attr">align-content</span>
                    <span class="desc"
                      >align-content 속성은 콘텐츠의 상하관계 정렬 상태를
                      정의합니다.</span
                    >
                  </a>
                </li>
                <li>
                  <a href="#">
                    <span class="attr">align-items</span>
                    <span class="desc"
                      >align-items 속성은 콘텐츠 내부의 정렬 상태를
                      정의합니다.</span
                    >
                  </a>
                </li>
                <li>
                  <a href="#">
                    <span class="attr">align-items</span>
                    <span class="desc"
                      >align-items 속성은 콘텐츠 내부의 정렬 상태를
                      정의합니다.</span
                    >
                  </a>
                </li>
                <li>
                  <a href="#">
                    <span class="attr">align-items</span>
                    <span class="desc"
                      >align-items 속성은 콘텐츠 내부의 정렬 상태를
                      정의합니다.</span
                    >
                  </a>
                </li>
                <li>
                  <a href="#">
                    <span class="attr">align-items</span>
                    <span class="desc"
                      >align-items 속성은 콘텐츠 내부의 정렬 상태를
                      정의합니다.</span
                    >
                  </a>
                </li>
                <li>
                  <a href="#">
                    <span class="attr">align-items</span>
                    <span class="desc"
                      >align-items 속성은 콘텐츠 내부의 정렬 상태를
                      정의합니다.</span
                    >
                  </a>
                </li>
                <li>
                  <a href="#">
                    <span class="attr">align-items</span>
                    <span class="desc"
                      >align-items 속성은 콘텐츠 내부의 정렬 상태를
                      정의합니다.</span
                    >
                  </a>
                </li>
                <li>
                  <a href="#">
                    <span class="attr">align-items</span>
                    <span class="desc"
                      >align-items 속성은 콘텐츠 내부의 정렬 상태를
                      정의합니다.</span
                    >
                  </a>
                </li>
                <li>
                  <a href="#">
                    <span class="attr">align-items</span>
                    <span class="desc"
                      >align-items 속성은 콘텐츠 내부의 정렬 상태를
                      정의합니다.</span
                    >
                  </a>
                </li>
                <li>
                  <a href="#">
                    <span class="attr">align-items</span>
                    <span class="desc"
                      >align-items 속성은 콘텐츠 내부의 정렬 상태를
                      정의합니다.</span
                    >
                  </a>
                </li>
                <li>
                  <a href="#">
                    <span class="attr">align-items</span>
                    <span class="desc"
                      >align-items 속성은 콘텐츠 내부의 정렬 상태를
                      정의합니다.</span
                    >
                  </a>
                </li>
                <li>
                  <a href="#">
                    <span class="attr">align-items</span>
                    <span class="desc"
                      >align-items 속성은 콘텐츠 내부의 정렬 상태를
                      정의합니다.</span
                    >
                  </a>
                </li>
              </ul>
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
/* referCont */
#referCont {
  background-color: #f0eeeb;
}
.refer-cont {
  padding-bottom: 200px;
}
.refer-cont .refer-title li {
  display: inline;
  font-family: "Rajdhani";
}
.refer-cont .refer-title li a {
  font-size: 1.2rem;
  display: inline-block;
  padding: 0.5rem 2rem;
  border: 1px solid #222;
  border-radius: 5px;
  margin-bottom: 1rem;
  margin-right: 10px;
}
.refer-cont .refer-title li.active a {
  background: #000;
  color: #fff;
}
.refer-cont .refer-table {
  border-bottom: 2px solid #000;
  margin-top: 1.2rem;
}
.refer-cont .refer-table li {
  margin: 0;
  list-style: none;
  border-top: 1px solid #000;
  position: relative;
  transition: all 0.3s;
}
.refer-cont .refer-table li:hover {
  background: rgba(0, 0, 0, 0.081);
}
.refer-cont .refer-table li span {
  display: inline-block;
  padding: 25px 10px;
  font-size: 14px;
  font-family: "S-CoreDream-3Light";
  box-sizing: border-box;
}
.refer-cont .refer-table li span.alpha {
  position: absolute;
  left: 0;
  top: 0;
}
.refer-cont .refer-table li span.attr {
  padding-left: 10%;
  width: 35%;
}
.refer-cont .refer-table li span.desc {
  width: 64.5%;
}
</style>