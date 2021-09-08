<template>
  <div id="wrap" class="light">
    <Header />
    <main>
      <section id="youtubeCont">
        <div class="container">
          <WrapTitle name1="youtube" name2="coding" />
          <div class="youtube-cont">
            <div class="site">
              <h2>웹 표준 사이트 만들기</h2>
              <div class="left">
                <img src="img/site01@2x.jpg" alt="웹표준 사이트 만들기" />
              </div>
              <div class="right">
                <dl>
                  <dt>레이아웃</dt>
                  <dd>
                    레이아웃은 사이트를 만드는데 가장 기본적이 요소입니다.
                    레이아웃만 제대로 만들 수 있다면 사이트의 제작에 50%는
                    끝나다고 보셔도 됩니다. 그만큼 레이아웃 제작은 상당히
                    중요합니다.
                  </dd>
                  <dt>플러그인</dt>
                  <dd>
                    제이쿼리를 통하여 이미지슬라이드, 라이트 박스를 구현합니다.
                    스크립트가 어려울 수 있지만 간단하게 설치하여 작동시켜
                    봅니다.
                  </dd>
                  <dt>CSS</dt>
                  <dd>
                    CSS의 다양한 속성을 사용하여 사이트의 디자인 작업을
                    구성합니다. CSS는 통해 디자인을 어떻게 꾸미는지 알아봅니다.
                  </dd>
                </dl>
              </div>
            </div>
            <div class="site">
              <h2>반응형 사이트 만들기</h2>
              <div class="left">
                <img src="img/site02@2x.jpg" alt="웹표준 사이트 만들기" />
              </div>
              <div class="right">
                <dl>
                  <dt>레이아웃</dt>
                  <dd>
                    레이아웃은 사이트를 만드는데 가장 기본적이 요소입니다.
                    레이아웃만 제대로 만들 수 있다면 사이트의 제작에 50%는
                    끝나다고 보셔도 됩니다. 그만큼 레이아웃 제작은 상당히
                    중요합니다.
                  </dd>
                  <dt>플러그인</dt>
                  <dd>
                    제이쿼리를 통하여 이미지슬라이드, 라이트 박스를 구현합니다.
                    스크립트가 어려울 수 있지만 간단하게 설치하여 작동시켜
                    봅니다.
                  </dd>
                  <dt>CSS</dt>
                  <dd>
                    CSS의 다양한 속성을 사용하여 사이트의 디자인 작업을
                    구성합니다. CSS는 통해 디자인을 어떻게 꾸미는지 알아봅니다.
                  </dd>
                </dl>
              </div>
            </div>
            <div class="site">
              <h2>기업 사이트 만들기</h2>
              <div class="left">
                <img src="img/site03@2x.jpg" alt="웹표준 사이트 만들기" />
              </div>
              <div class="right">
                <dl>
                  <dt>레이아웃</dt>
                  <dd>
                    레이아웃은 사이트를 만드는데 가장 기본적이 요소입니다.
                    레이아웃만 제대로 만들 수 있다면 사이트의 제작에 50%는
                    끝나다고 보셔도 됩니다. 그만큼 레이아웃 제작은 상당히
                    중요합니다.
                  </dd>
                  <dt>플러그인</dt>
                  <dd>
                    제이쿼리를 통하여 이미지슬라이드, 라이트 박스를 구현합니다.
                    스크립트가 어려울 수 있지만 간단하게 설치하여 작동시켜
                    봅니다.
                  </dd>
                  <dt>CSS</dt>
                  <dd>
                    CSS의 다양한 속성을 사용하여 사이트의 디자인 작업을
                    구성합니다. CSS는 통해 디자인을 어떻게 꾸미는지 알아봅니다.
                  </dd>
                </dl>
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
#youtubeCont {
  background-color: #f0eeeb;
}

.youtube-cont {
  padding-bottom: 200px;
}

.site {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin-bottom: 200px;
}

.site h2 {
  font-size: 40px;
  padding-bottom: 20px;
  flex: 0 0 100%;
  font-family: "Chosunilbo_myungjo";
}

.site .left {
  flex: 0 0 35%;
}

.site .right {
  font-family: "Chosunilbo_myungjo";
  font-size: 18px;
  flex: 0 0 60%;
}

.site .right dl {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.site .right dt {
  flex: 0 0 20%;
}

.site .right dd {
  flex: 0 0 80%;
  padding-bottom: 30px;
}

.youtube-search {
  font-family: "Chosunilbo_myungjo";
}
.youtube-search .title h2 {
  display: inline-block;
  margin-right: 20px;
  margin-bottom: 30px;
  font-size: 40px;
}
.youtube-search .title input {
  border: 0;
  padding: 10px;
  vertical-align: 5px;
  font-family: "Chosunilbo_myungjo";
}
.youtube-search .title button {
  border: 0;
  padding: 10px 30px;
  background: #000;
  color: #fff;
  vertical-align: 5px;
  margin-left: 5px;
  font-family: "Chosunilbo_myungjo";
}
.youtube-search .list ul {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
.youtube-search .list li {
  flex: 0 0 19%;
  margin-bottom: 2%;
}
.youtube-search .list li strong {
  margin-top: 5px;
  display: block;
}
</style>