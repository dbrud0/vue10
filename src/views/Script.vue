<template>
  <div id="wrap" class="light">
    <Header />
    <main>
      <section id="scriptCont">
        <div class="container">
           <WrapTitle name1="script" name2="javascript" />
          <div class="script-cont">
            <div class="script">
              <div class="view">
                <img src="img/script01.png" alt="aaa" />
              </div>
              <div class="desc">
                <h3>animationRequestFrame</h3>
                <div>
                  레이아웃은 사이트를 만드는데 가장 기본적이 요소입니다.
                  레이아웃만 제대로 만들 수 있다면 사이트의 제작에 50%는
                  끝나다고 보셔도 됩니다. 그만큼 레이아웃 제작은 상당히
                  중요합니다. 사이트의 제작에 50%는 끝나다고 보셔도 됩니다.
                  그만큼 레이아웃 제작은 상당히 중요합니다.
                </div>
                <div>
                  레이아웃은 사이트를 만드는데 가장 기본적이 요소입니다.
                  레이아웃만 제대로 만들 수 있다면 사이트의 제작에 50%는
                  끝나다고 보셔도 됩니다. 그만큼 레이아웃 제작은 상당히
                  중요합니다. 사이트의 제작에 50%는 끝나다고 보셔도 됩니다.
                  그만큼 레이아웃 제작은 상당히 중요합니다.
                </div>
                <div class="num">
                  <span href="#" class="active">1</span>
                  <span href="#">2</span>
                  <span href="#">3</span>
                  <span href="#">4</span>
                  <span href="#">5</span>
                  <span href="#">6</span>
                  <span href="#">7</span>
                  <span href="#">8</span>
                  <span href="#">9</span>
                  <span href="#">10</span>
                </div>
              </div>
            </div>
            <div class="script">
              <div class="view">
                <img src="img/script02.png" alt="aaa" />
              </div>
              <div class="desc">
                <h3>animationRequestFrame</h3>
                <div>
                  레이아웃은 사이트를 만드는데 가장 기본적이 요소입니다.
                  레이아웃만 제대로 만들 수 있다면 사이트의 제작에 50%는
                  끝나다고 보셔도 됩니다. 그만큼 레이아웃 제작은 상당히
                  중요합니다. 사이트의 제작에 50%는 끝나다고 보셔도 됩니다.
                  그만큼 레이아웃 제작은 상당히 중요합니다.
                </div>
                <div>
                  레이아웃은 사이트를 만드는데 가장 기본적이 요소입니다.
                  레이아웃만 제대로 만들 수 있다면 사이트의 제작에 50%는
                  끝나다고 보셔도 됩니다. 그만큼 레이아웃 제작은 상당히
                  중요합니다. 사이트의 제작에 50%는 끝나다고 보셔도 됩니다.
                  그만큼 레이아웃 제작은 상당히 중요합니다.
                </div>
                <div class="num">
                  <span href="#" class="active">1</span>
                  <span href="#">2</span>
                  <span href="#">3</span>
                  <span href="#">4</span>
                  <span href="#">5</span>
                  <span href="#">6</span>
                  <span href="#">7</span>
                  <span href="#">8</span>
                  <span href="#">9</span>
                  <span href="#">10</span>
                </div>
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
#scriptCont {
  background-color: #f0eeeb;
}

.script-cont {
  padding-bottom: 0px;
}

.script {
  padding-bottom: 200px;
}

.script h2 {
  font-family: "Chosunilbo_myungjo";
  font-size: 40px;
  padding-bottom: 10px;
}

.script .view {
  width: 100%;
}

.script .desc {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.script .desc h3 {
  flex: 0 0 100%;
  font-size: 30px;
  line-height: 2em;
  margin-top: 20px;
  font-family: "Chosunilbo_myungjo";
}

.script .desc > div {
  flex: 0 0 31%;
  font-family: "Chosunilbo_myungjo";
}

.script .desc > div.num span {
  border: 1px solid #9b9b9b;
  width: 50px;
  height: 50px;
  display: inline-block;
  border-radius: 50%;
  text-align: center;
  line-height: 48px;
  margin: 0px 0px 10px 7px;
  color: #030406;
}

.script .desc > div.num span.active {
  border-style: dashed;
}
</style>