<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <div class="logo">
        <img src="" alt="">
      </div>
      <a class="navbar-brand" href="#">LIZARD WORLD</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#"><span class="high-light">a</span>bout</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"><span class="high-light">s</span>ervice</a>
          </li>
                    <li class="nav-item">
            <a class="nav-link" href="#"><span class="high-light">w</span>orks</a>
          </li>
                    <li class="nav-item">
            <a class="nav-link" href="#"><span class="high-light">b</span>log</a>
          </li>
                    <li class="nav-item">
            <a class="nav-link" href="#"><span class="high-light">a</span>wards</a>
          </li>
                    <li class="nav-item">
            <a class="nav-link" href="#"><span class="high-light">c</span>areer</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <div class="top">
    MAKE YOUR <br> LIZARD WORLD
  </div>
  <div class="menu-toggle">
    <ul>
      <li>
        <a href="#">menu</a>
      </li>
      <li>
        <a href="#">menu</a>
      </li>
      <li>
        <a href="#">menu</a>
      </li>
      <li>
        <a href="#">menu</a>
      </li>
      <li>
        <a href="#">menu</a>
      </li>
      <li>
        <a href="#">menu</a>
      </li>
      <li>
        <a href="#">menu</a>
      </li>
    </ul>
  </div>
  <section class="section">
    <h1>WELCO<span class="high-light2">M</span>E</h1>
    <div class="welcome">
      <div><img src="" alt=""></div>
      <ul>
        <li>new</li>
        <li>best</li>
        <li>today</li>
        <li>my</li>
      </ul>
    </div>
  </section>
  <section class="section">
    <h1>M<span class="high-light2">A</span>KE IT</h1>
    <div class="makeit">
      <ul>
        <li>
          <div><img src="" alt=""></div>
          <p>아프리카 도마뱀</p>
        </li>
        <li>
          <div><img src="" alt=""></div>
          <p>아프리카 도마뱀</p>
        </li>
        <li>
          <div><img src="" alt=""></div>
          <p>아프리카 도마뱀</p>
        </li>
        <li>
          <div><img src="" alt=""></div>
          <p>아프리카 도마뱀</p>
        </li>
        <li>
          <div><img src="" alt=""></div>
          <p>아프리카 도마뱀</p>
        </li>
        <p>저희 홈페이지를 방문해주신 모든 도마뱀 가족여러분 감사드립니다.</p>
      </ul>
    </div>
  </section>
  <section class="section">
    <h1>YO<span class="high-light2">U</span>R BEST</h1>
    <div class="yourbest">
      <div><img src="" alt="">
        <ul>
          <li>
            <h3>news</h3>
            <p>내용<span>날짜</span></p>
          </li>
          <li>
            <h3>information</h3>
            <p>내용<span>날짜</span></p>
          </li>
          <li>
            <h3>community</h3>
            <p>내용<span>날짜</span></p>
          </li>
        </ul>
      </div>
    </div>
  </section>
  <section class="section">
    <h1><span class="high-light2">F</span>RIEND</h1>
    <div class="friend">
      <ul>
        <li>
          <div><img src="" alt=""></div>
          <h3>normal-lizrd</h3>
          <p>내용</p>
          <button>바로가기</button>
        </li>
        <li>
          <div><img src="" alt=""></div>
          <h3>high-lizrd</h3>
          <p>내용</p>
          <button>바로가기</button>
        </li>
        <li>
          <div><img src="" alt=""></div>
          <h3>super-lizrd</h3>
          <p>내용</p>
          <button>바로가기</button>
        </li>
      </ul>
    </div>
  </section>
 <footer>
   MAKE YOUR <br> LIZARD WORLD
 </footer>
</template>

<script>

export default {
  name: 'App',
  data(){
    return{
    }
  },
  components: {
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  max-width: 1200px;
  width: 100%;
  margin: 0 auto;
}

.top {
  width: 100%;
  height: 250px;
  background: linear-gradient(89.92deg, #2CD4AD 7.26%, #4988D3 92.58%);
  text-align: center;
  font-size: 50px;
  color: aliceblue;
  line-height: 100px;
  border-radius: 0  0 50% 50%;
  text-shadow: -1px 0 black, 0 1px black, 1px 0 black, 0 -1px black;
}

.high-light {
  color: #2CD4AD;
}

.logo {
  width: 30px;
  height: 30px;
  background-color: #2CD4AD;
  margin-right: 10px;
  
}

ul {
  list-style: none;
  padding-left: 0rem !important;
}

img {
  box-sizing: unset;
}

.menu-toggle ul li{
  display: inline-block;
  width: 100px;
  height: 100px;
  line-height: 100px;
  border-radius: 50%;
  margin: 15px;
  background-color:#eee;
}

.menu-toggle ul li a {
  text-decoration: none;
  display: block;
  width: 100px;
  height: 100px;
  color: #2CD4AD;
}

.section {
  position: relative;
  width: 100%;
  height: 400px;
  background-color: white ;
}

.section:nth-child(2n) {
  background-color: #f9f9f9;
}

.section h1 {
  padding-top: 10px;
  color: #e1e1e1;
  font-size: 80px;
  font-weight: 700;
}

.section h1 .high-light2 {
  background: linear-gradient(89.92deg, #2CD4AD 7.26%, #4988D3 92.58%);
  color: transparent;
  -webkit-background-clip: text;
  position: relative;
  z-index: 10;
}

.welcome > div img {
  position: absolute;
  max-width: 280px;
  width: 100%;
  height: 280px;
  background-color: #eee;
  top:  50%;
  left: 50%;
  transform: translate(-50%, -50%);
  border: 5px solid transparent ;
  border-radius: 30px;
  background-image: linear-gradient(#333, #333), linear-gradient(89.92deg, #2CD4AD 7.26%, #4988D3 92.58%);
  background-origin: border-box;
  background-clip: content-box, border-box;
}

.welcome > ul {
  position: absolute;
  width: 280px;
  height: 280px;
  top:  50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 10;
  color: white;
  padding-top: 40px;
}

.welcome > ul > li {
  margin-bottom: 30px;
}

.welcome > ul > li:nth-child(2) {
  color: #2CD4AD;
}

.makeit ul {
  margin-top: 30px;
}

.makeit ul li {
  display: inline-block;
  width: 120px;
  margin-left: 20px;
}

.makeit ul li div img {
  box-sizing: border-box;
  border-radius: 25px;
  margin: 0 auto;
  margin-bottom: 5px;
  width: 110px;
  height: 100px;
  background-color: #eee;
}

.yourbest div{
  position: absolute;
  top: 60px;
  left: 25%;
  display: inline-block;
}

.yourbest div img {
  width: 280px;
  height: 280px;
  background-color: #eee;
  border: 5px solid transparent ;
  border-radius: 30px;
  background-image: linear-gradient(#333, #333), linear-gradient(89.92deg, #2CD4AD 7.26%, #4988D3 92.58%);
  background-origin: border-box;
  background-clip: content-box, border-box;
}

.yourbest div ul {
  float: right;
}

.yourbest div ul{
  width: 250px;
  margin-top: 50px;
  margin-left: 10px;
}

.yourbest div ul li h3 {
  font-size: 24px;
  text-align: left;
  color: #2CD4AD;
}
.yourbest div ul li p {
  text-align: left;
  margin-left: 20px;
}

.yourbest div ul li p span {
  float: right;
}

.friend ul {
  position: absolute;
  width: 100%;
  top:  50%;
  left: 50%;
  transform: translate(-50%, -45%);
}

.friend ul li {
  display: inline-block;
  margin-right: 20px;
}

.friend ul li img {
  width: 200px;
  height: 200px;
  background-color: #eee;
  border-radius: 30px;
}

.friend ul li h3 {
  margin-top: 5px;
  margin-bottom: 3px;
  font-size: 24px;
}

.friend ul li p {
  margin-bottom: 3px;
}

.friend ul li button {
  background: linear-gradient(89.92deg, #2CD4AD 7.26%, #4988D3 92.58%);
  border: none;
  border-radius: 3em;
  width: 150px;
  color: white;
}

footer {
  padding-top: 50px;
  width: 100%;
  height: 300px;
  background: linear-gradient(89.92deg, #2CD4AD 7.26%, #4988D3 92.58%);
  font-size: 50px;
  color: aliceblue;
  line-height: 100px;
  border-radius: 50% 50% 0 0;
  text-shadow: -1px 0 black, 0 1px black, 1px 0 black, 0 -1px black;
}
</style>
