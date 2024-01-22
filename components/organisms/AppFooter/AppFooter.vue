<template>
  <footer>
    <div>
      <div class="footer-up">
        <div class="footer-up-child">
          <img src="#" alt="#" />
          <p>Interior design<br />&<br />Construction</p>
        </div>

        <div class="footer-up-child">
          <ul>
            <li><a>ホーム</a></li>
            <li><a>私たちについて</a></li>
            <li><a>選ばれる理由</a></li>
            <li><a>ワークフロー</a></li>
            <li><a>FAQ</a></li>
            <li><a>事例紹介</a></li>
          </ul>
        </div>
        <div class="footer-up-child">
          <ul>
            <li><a>会社概要</a></li>
            <li><a>お問い合せ・お見積</a></li>
            <li><a>個人情報保護について</a></li>
          </ul>
        </div>
        <div class="footer-up-child2">
          <div class="company-detail">
            <div>
              <p>
                建築・建築デザイン・原状回復・内装解体・建物解体・アスベスト除去工事はSENTIAにお任せください！
              </p>
            </div>
            <p>
              株式会社SENTIA<br />
              〒454-0982<br />
              愛知県名古屋市高見1-20-2<br />
              TEL:052-1212-2029<br />
            </p>
          </div>
          <div>
            <a href="#"><img src="#" alt="facebook" /></a>
            <a href="#"><img src="#" alt="instagram" /></a>
            <a href="#"><img src="#" alt="ピンタレスト" /></a>
          </div>
        </div>
      </div>
      <div class="footer-under">
        <p>Copyright©️ 店舗設計・デザイン・施工 CYPHER.AllRights Reserved</p>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>
<style lang="scss" scoped>
.footer-up {
  display: flex;
  background-color: #756e6d;
  font-size: 20px;
  height: 450px;
  width: 100%;
  color: #fff;
  padding: 20px;
}

.footer-up-child {
  width: 20%;
  margin: 0 auto;
}

.footer-up-child2 {
  width: 40%;
  margin: 0 auto;
}
.footer-under {
  font-size: 15px;
  text-align: center;
}

ul {
  list-style: none;
}

li {
  line-height: 2em;
}

.company-detail {
  border: 5px double #fff;
  margin: 20px;
  padding: 5px;
}
</style>
