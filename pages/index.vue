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
  // background-color: aqua;

  @include sp {
    justify-content: center;
    flex-direction: column;
  }
  
  .home-img {
    width: 50%;
    height: 700px;

    @include sp {
      width: 100%;
      height: 320px;

    }

    img {
      height: 700px;
      margin: 0 auto;

      @include sp {
      height: 300px;
    }
    }
  }

  .home-text {
    padding: 20px;
    height: 350px;
    border: solid 1px #000;
    margin-top: 180px;

    @include sp {
      padding: 20px;
      margin-top: 0px;
      height: 350px;
    }

    p {
      width: 80px;
      text-align: center;
      font-size: 20px;
      font-weight: 600;
      background:linear-gradient(transparent 60%, rgba(2, 156, 97, 0.8) 60%);
    
      @include sp {
        font-size: 18px;
        width: 75px;
      }
    }

    ul {
      list-style: none;

      li {
        letter-spacing: 1px;
        font-weight: 600;

        @include sp {
          letter-spacing: 0px;
          font-size: 14px;
          // line-height: 25px;
        }
      }

      .name {
          font-size: 23px;

          @include sp {
            font-size: 18px;
          }
        }
    }
  }
}

</style>
