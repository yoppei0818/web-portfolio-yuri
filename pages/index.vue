<template>
  <div class="home">
    <div class="home-img">
      <img src="~/assets/images/ポートフォリオ写真 .jpg" alt="由利洋平">
    </div>
    <div class="home-text">
      <p>About</p>
      <ul>
        <li>釧路公立大学　4年生</li>
        <li><span class="name">由利洋平</span>（ゆり ようへい）</li>
        <br>
        <li>趣味：ギター、旅行、音楽鑑賞、アニメ鑑賞、釣り、ダンス</li>
        <br>
        <li>好きな言葉：<br>知識は何よりも宝になる。<br>そして重荷にならない生きていくための力である。</li>
        <br>
        <li>座右の銘：Boys, be ambitious!</li>
      </ul>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.home {
  margin: 0 auto;
  width: 85%;
  display: flex;
  justify-content: space-around;
  // background-color: rgb(156, 156, 156);
  
  .home-img {
    width: 50%;
    height: 700px;

    img {
      height: 700px;
      margin: 0 auto;
    }
  }

  .home-text {
    padding: 20px;
    height: 350px;
    border: solid 1px #000;
    margin-top: 180px;

    p {
      width: 80px;
      text-align: center;
      font-size: 20px;
      font-weight: 600;
      background:linear-gradient(transparent 60%, rgba(2, 156, 97, 0.8) 60%);
    }

    ul {
      list-style: none;

      li {
        letter-spacing: 1px;
        font-weight: 600;
      }

      .name {
          font-size: 23px;
        }
    }
  }
}

</style>
