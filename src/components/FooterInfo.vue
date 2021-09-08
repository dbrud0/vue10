<template>
  <footer id="footerInfo">
    <div class="container">
      <div class="footer__inner">
        <div>
          <p>Let’s create something new</p>
          <h3>
            LET`S Get IN
            <br />
            TOUCH
          </h3>
          <a href="/" class="contact"> Contact Me </a>
        </div>
      </div>
    </div>
  </footer>
</template>

<style lang="scss">
/* 모든 페이지의 푸터
  #footer
  .footer__inner
  */
#footerInfo {
  background-color: #000;
  height: 100vh;
}

.footer__inner {
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  color: #fff;
}

.footer__inner p {
  font-size: 20px;
  font-weight: 400;
  margin-bottom: 80px;
  font-family: "Rajdhani", "Chosunilbo_myungjo";
}

.footer__inner h3 {
  font-size: 144px;
  line-height: 1;
  text-transform: uppercase;
  margin-bottom: 5rem;
  font-family: "Saol Display Regular";
}

.footer__inner a {
  color: #fff;
  border: 1px solid #fff;
  border-radius: 50px;
  padding: 18px 53px 18px 53px;
  font-size: 16px;
  font-weight: 400;
  text-transform: uppercase;
  font-family: "Rajdhani", "Chosunilbo_myungjo";
}
</style>