<template>
  <div id="app">
    <div class="bg-secondary py-1">
      <div class="container text-right">
        <a href="#" class="text-white">
          <i class="fab fa-facebook-square"></i>
        </a>
        <a href="#" class="text-white ml-1">
          <i class="fab fa-twitter-square"></i>
        </a>
      </div>
    </div>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <div class="container">
        <a class="navbar-brand" href="#">
          <img src="./assets/generatedtext.png" width="120" height="auto" alt="logo" />
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarNavDropdown"
          aria-controls="navbarNavDropdown"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavDropdown">
          <ul class="navbar-nav">
            <li class="nav-item active">
              <a class="nav-link" href="#">
                首頁
                <span class="sr-only">(current)</span>
              </a>
            </li>
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdownMenuLink"
                role="button"
                data-toggle="dropdown"
                aria-haspopup="true"
                aria-expanded="false"
              >課程清單</a>
              <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                <a class="dropdown-item" href="#">Action</a>
                <a class="dropdown-item" href="#">Another action</a>
                <a class="dropdown-item" href="#">Something else here</a>
              </div>
            </li>
          </ul>
          <form class="form-inline ml-auto">
            <a
              href="#"
              class="btn btn-outline-light mr-1"
              data-toggle="modal"
              data-target="#signin"
            >登入</a>
            <a
            href="#"
            class="btn btn-outline-light"
            data-toggle="modal"
            data-target="#signup"
            >註冊</a>
          </form>
        </div>
      </div>
    </nav>
    <header>
      <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
          <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
          <div
            class="carousel-item header-carousel-item bg-cover active"
            style="background-image: url(https://images.unsplash.com/photo-1549060279-7e168fcee0c2?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=750&q=80)"
          >
            <div class="carousel-caption d-none d-md-block px-3">
              <h5>痛 就是軟弱離開身體的感覺</h5>
              <p>
                如果不疼，你練它幹嘛？
                撐不住時，可以對自己說「我好累」
                <br />但永遠不要在心裡承認說「我不行」
              </p>
            </div>
          </div>
          <div
            class="carousel-item header-carousel-item bg-cover"
            style="background-image: url(https://images.unsplash.com/photo-1532384748853-8f54a8f476e2?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=750&q=80)"
          >
            <div class="carousel-caption d-none d-md-block px-3">
              <h5>時間會證明一切，汗水從不會騙人</h5>
              <p>給自己定一個目標，雖然最後不一定到達終點，但你每天都在超越自己</p>
            </div>
          </div>
          <div
            class="carousel-item header-carousel-item bg-cover"
            style="background-image: url(https://images.unsplash.com/photo-1528304270437-714a2d6fbb6b?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1500&q=80)"
          >
            <div class="carousel-caption d-none d-md-block px-3">
              <h5>最大的愉悅，就是做了別人說你做不了的事</h5>
            </div>
          </div>
        </div>
        <a
          class="carousel-control-prev"
          href="#carouselExampleIndicators"
          role="button"
          data-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a
          class="carousel-control-next"
          href="#carouselExampleIndicators"
          role="button"
          data-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>
    </header>
    <section class="bg-success text-white py-5">
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <div class="mb-2">
              <i class="fas fa-dumbbell fa-5x"></i>
            </div>
            <h3>訓練菜單</h3>
            <p>開始健身之前確定目標。希望達到什麼效果？可以花多少時間鍛鍊？</p>
          </div>
          <div class="col-md-4">
            <div class="mb-2">
              <i class="fas fa-utensils fa-5x"></i>
            </div>
            <h3>飲食計畫</h3>
            <p>三成靠運動七成靠飲食!!兩者都要兼顧才能事半功倍</p>
          </div>
          <div class="col-md-4">
            <div class="mb-2">
              <i class="fas fa-bed fa-5x"></i>
            </div>
            <h3>睡眠作息</h3>
            <p>
              沒睡好會有瘦素、胰島素敏感度、飢餓素、皮質醇、睪酮、生長激素、類胰島素生長因素等荷爾蒙異常的狀況
              會讓你較容易堆積脂肪不容易長出肌肉，讓你食慾很夠加上血糖控制出問題，等於就是在幫你增脂減肌
            </p>
          </div>
        </div>
      </div>
    </section>
    <section class="container-fluid py-5 bg-light position-r text-light">
      <div class="row">
        <div
          class="col-md-5 bg-cover"
          style="
          position: absolute; top: 0; bottom: 0;
          background-image: url(https://images.unsplash.com/photo-1517343985841-f8b2d66e010b?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=750&q=80)
          "
        ></div>
        <div class="container">
          <div class="row justify-content-end text-md-dark">
            <div class="col-md-7">
              <h3>歡迎前來體驗</h3>
              <p>
                仉浺炚釤柤纗葒溾伬朹珈沋侗姁牣楈兀迋箂碙。旡郟沭聃峊屭骫鉬圴甪峈扽炔怭岍腠乜佹廑楄。
                仉釕姖紵朐鸃徭楀圪伄郈沇芛泮芑碚屮呺嫙頍。
                掾泙扞輷誄氄襾一殽唶娭枅圣毠乇，銢棫亍怦垝艅芚阞兀疌踅柺勼冾。郿炔阣鋋睚嬛屼一惸镺珙怙仨砒亍，椴腏乜抩砐趑枃尻屮宕蓇垌夃丳。
              </p>
              <a href="#" class="btn btn-outline-dark">查看更多</a>
              <div class="row mt-3">
                <div class="col-md-6">
                  <h3>掾泙扞輷誄氄襾一殽唶娭枅圣毠乇</h3>
                  <p>
                    仉浺炚釤柤纗葒溾伬朹珈沋侗姁牣楈兀迋箂碙。旡郟沭聃峊屭骫鉬圴甪峈扽炔怭岍腠乜佹廑楄。
                    仉釕姖紵朐鸃徭楀圪伄郈沇芛泮芑碚屮呺嫙頍。
                    掾泙扞輷誄氄襾一殽唶娭枅圣毠乇，銢棫亍怦垝艅芚阞兀疌踅柺勼
                  </p>
                </div>
                <div class="col-md-6">
                  <h3>掾泙扞輷誄氄襾一殽唶娭枅圣毠乇</h3>
                  <p>
                    仉浺炚釤柤纗葒溾伬朹珈沋侗姁牣楈兀迋箂碙。旡郟沭聃峊屭骫鉬圴甪峈扽炔怭岍腠乜佹廑楄。
                    仉釕姖紵朐鸃徭楀圪伄郈沇芛泮芑碚屮呺嫙頍。
                    掾泙扞輷誄氄襾一殽唶娭枅圣毠乇，銢棫亍怦垝艅芚阞兀疌踅柺勼
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="py-5">
      <div class="container">
        <h2 class="text-center my-3">小標題</h2>
        <div class="row">
          <div class="col-md-6">
            <div class="d-flex">
              <div class="mr-3">
                <i class="fas fa-american-sign-language-interpreting fa-4x"></i>
              </div>
              <div>
                <h3>副標題</h3>
                <p>
                  仉浺炚釤柤纗葒溾伬朹珈沋侗姁牣楈兀迋箂碙。旡郟沭聃峊屭骫鉬圴甪峈扽炔怭岍腠乜佹廑楄。
                  仉釕姖紵朐鸃徭楀圪伄郈沇芛泮芑碚屮呺嫙頍。
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-6">
            <div class="d-flex">
              <div class="mr-3">
                <i class="fas fa-american-sign-language-interpreting fa-4x"></i>
              </div>
              <div>
                <h3>副標題</h3>
                <p>
                  仉浺炚釤柤纗葒溾伬朹珈沋侗姁牣楈兀迋箂碙。旡郟沭聃峊屭骫鉬圴甪峈扽炔怭岍腠乜佹廑楄。
                  仉釕姖紵朐鸃徭楀圪伄郈沇芛泮芑碚屮呺嫙頍。
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-md-6">
            <div class="d-flex">
              <div class="mr-3">
                <i class="fas fa-american-sign-language-interpreting fa-4x"></i>
              </div>
              <div>
                <h3>副標題</h3>
                <p>
                  仉浺炚釤柤纗葒溾伬朹珈沋侗姁牣楈兀迋箂碙。旡郟沭聃峊屭骫鉬圴甪峈扽炔怭岍腠乜佹廑楄。
                  仉釕姖紵朐鸃徭楀圪伄郈沇芛泮芑碚屮呺嫙頍。
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-6">
            <div class="d-flex">
              <div class="mr-3">
                <i class="fas fa-american-sign-language-interpreting fa-4x"></i>
              </div>
              <div>
                <h3>副標題</h3>
                <p>
                  仉浺炚釤柤纗葒溾伬朹珈沋侗姁牣楈兀迋箂碙。旡郟沭聃峊屭骫鉬圴甪峈扽炔怭岍腠乜佹廑楄。
                  仉釕姖紵朐鸃徭楀圪伄郈沇芛泮芑碚屮呺嫙頍。
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="py-5 bg-light">
      <div class="container">
        <div class="row">
          <div class="col-md-6">
            <iframe
              src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d24317.107772798205!2d121.54709106414697!3d25.042230399367835!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3442a9727e339109%3A0xc34a31ce3a4abecb!2z5Y-w5YyX6LuK56uZ!5e0!3m2!1szh-TW!2stw!4v1579679612412!5m2!1szh-TW!2stw"
              width="100%"
              height="450"
              frameborder="0"
              style="border:0;"
              allowfullscreen
            ></iframe>
          </div>
          <div class="col-md-6">
            <form action class="needs-validation" novalidate>
              <div class="form-group">
                <label for="username">姓名*</label>
                <input
                  type="text"
                  class="form-control"
                  aria-describedby="helpId"
                  id="username"
                  placeholder="請輸入姓名"
                  required
                />
              </div>
              <div class="form-group">
                <label for="tel">電話*</label>
                <input
                  type="tel"
                  class="form-control"
                  aria-describedby="helpId"
                  id="tel"
                  placeholder="請輸入電話"
                  required
                />
              </div>
              <div class="form-group">
                <label for="email">Email*</label>
                <input
                  type="email"
                  class="form-control"
                  aria-describedby="helpId"
                  id="email"
                  placeholder="請輸入Email"
                  required
                />
              </div>
              <div class="form-group">
                <label for="lineId">line_ID</label>
                <input
                  type="text"
                  class="form-control"
                  aria-describedby="helpId"
                  id="lineId"
                  placeholder
                />
              </div>
              <label>是否想要收到最新優惠 Email</label>
              <div class="custom-control custom-radio">
                <input
                  type="radio"
                  id="customRadio1"
                  name="customRadio"
                  class="custom-control-input"
                />
                <label class="custom-control-label" for="customRadio1">是</label>
              </div>
              <div class="custom-control custom-radio">
                <input
                  type="radio"
                  id="customRadio2"
                  name="customRadio"
                  class="custom-control-input"
                />
                <label class="custom-control-label" for="customRadio2">否</label>
              </div>
              <div class="text-right">
                <button type="button" class="btn btn-secondary mr-2">取消</button>
                <button type="submit" class="btn btn-primary">送出</button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>
    <section class="container-fluid">
      <div class="row">
        <div
          class="col-md-6 bg-cover p-4 text-light"
          style="background-image: url(https://images.unsplash.com/photo-1534368959876-26bf04f2c947?ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80)"
        >
          <div class="row">
            <div class="col-md-9">
              <small>小小標</small>
              <h3>標題</h3>
              <p>
                仉浺炚釤柤纗葒溾伬朹珈沋侗姁牣楈兀迋箂碙。旡郟沭聃峊屭骫鉬圴甪峈扽炔怭岍腠乜佹廑楄。
                仉釕姖紵朐鸃徭楀圪伄郈沇芛泮芑碚屮呺嫙頍。
              </p>
              <a href="#" class="btn btn-outline-warning">查看更多</a>
            </div>
          </div>
        </div>
        <div
          class="col-md-6 bg-cover p-4 text-light"
          style="background-image: url(https://images.unsplash.com/photo-1437935690510-49ce2c715aee?ixlib=rb-1.2.1&auto=format&fit=crop&w=889&q=80)"
        >
          <div class="row">
            <div class="col-md-9">
              <small>小小標</small>
              <h3>標題</h3>
              <p>
                仉浺炚釤柤纗葒溾伬朹珈沋侗姁牣楈兀迋箂碙。旡郟沭聃峊屭骫鉬圴甪峈扽炔怭岍腠乜佹廑楄。
                仉釕姖紵朐鸃徭楀圪伄郈沇芛泮芑碚屮呺嫙頍。
              </p>
              <a href="#" class="btn btn-outline-warning">查看更多</a>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- singin modal -->
    <div
      class="modal fade"
      id="signin"
      tabindex="-1"
      role="dialog"
      aria-labelledby="exampleModalLabel"
      aria-hidden="true"
    >
      <div class="modal-dialog" role="document">
        <div class="modal-content">
          <div class="modal-header bg-primary text-white">
            <h5 class="modal-title" id="exampleModalLabel">登入</h5>
            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
              <span aria-hidden="true">&times;</span>
            </button>
          </div>
          <div class="modal-body">...</div>
          <div class="modal-footer">
            <a
            href="#"
            data-dismiss="modal"
            data-toggle="modal"
            data-target="#signup"
            class="mr-auto"
            >還沒有帳號嗎?</a>
            <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
            <button type="button" class="btn btn-primary">Save changes</button>
          </div>
        </div>
      </div>
    </div>
    <!-- singup modal -->
    <div
      class="modal fade"
      id="signup"
      tabindex="-1"
      role="dialog"
      aria-labelledby="exampleModalLabel"
      aria-hidden="true"
    >
      <div class="modal-dialog" role="document">
        <div class="modal-content">
          <div class="modal-header bg-warning text-white">
            <h5 class="modal-title" id="exampleModalLabel">註冊</h5>
            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
              <span aria-hidden="true">&times;</span>
            </button>
          </div>
          <div class="modal-body">...</div>
          <div class="modal-footer">
            <a
              href="#"
              data-dismiss="modal"
              data-toggle="modal"
              data-target="#signin"
              class="mr-auto"
              @click="addModalClass"
            >已經有帳號了?</a>
            <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
            <button type="button" class="btn btn-primary">Save changes</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  methods: {
    addModalClass(e) {
      console.log(e);
    },
  },
};
</script>
<style lang="scss" scope>
@import "~bootstrap/scss/bootstrap";
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  //text-align: center;
  color: #2c3e50;
}
.btn {
  border-width: 2px;
}
.header-carousel-item {
  height: 450px;
}
.bg-cover {
  background-size: cover;
  background-position: 50% 20%;
}
.carousel-caption {
  background-color: rgba($color: #000000, $alpha: 0.5);
}
.position-r {
  position: relative;
}
.form-control {
  border-width: 2px;
}
@media (min-width: 767.98px) {
  .text-md-dark {
    color: #333;
  }
}
</style>
