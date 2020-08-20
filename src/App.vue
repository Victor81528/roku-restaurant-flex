<template>
  <div id="app">
    <div id="nav">
      <div class="nav-inside">
        <div class="nav-tittle">
          <h1>六角西餐廳</h1>
        </div>
          <ul class="nav-list">
            <li><a href="#secret">特色</a></li>
            <li><a href="#chef">主廚</a></li>
            <li><a href="#booking">地圖</a></li>
          </ul>
      </div>
    </div>
    <div id="banner">
      <div class="banner-inside">
        <div class="banner-content">
          <h1>咬一口就無法忘懷的漢堡</h1><br>
          <div>
            <p>七夕絕對無法錯過的好滋味</p>
            <p>六角大漢堡</p>
          </div>
        </div>
      </div>
    </div>
    <div id="secret">
      <div class="secret-inside">
        <div class="secret-tittle">
          <div class="line"></div>
          <h1>客人總是在詢問<br>這麼好吃的秘訣是什麼</h1>
          <div class="line"></div>
        </div>
        <div class="secret-content">
          <div class="secret-items secret-1">
            <img id="img1" src="/img/feature_1.png">
            <h1 class="secret-kind">台灣本土蔬菜</h1>
            <p>In hac habitasse platea dictumst. Vivamus adipiscing fermentum quam volutpat aliquam. Integer et elit eget elit facilisis tristique. Nam vel iaculis mauris.</p>
          </div>
          <div class="secret-items secret-2">
            <img id="img2" src="/img/feature_2.png">
            <h1 class="secret-kind">專業米其林廚師</h1>
            <p>Sed ullamcorper tellus erat, non ultrices sem tincidunt euismod. Fusce rhoncus porttitor velit, eu bibendum nibh aliquet vel. Fusce lorem leo, vehicula at nibh quis, facilisis accumsan turpis.</p>
          </div>
          <div class="secret-items secret-3">
            <img id="img3" src="/img/feature_3.png">
            <h1 class="secret-kind">對於專業不能退讓</h1>
            <p>Fusce rhoncus porttitor velit, eu bibendum nibh aliquet vel. Fusce lorem leo, vehicula at nibh quis, facilisis accumsan turpis.</p>
          </div>
        </div>
      </div>
    </div>
    <div id="chef">
      <div class="chef-inside">
        <img src="/img/main_chef_brown.png" alt="chef">
        <div class="chef-content">
          <h1>今日主廚：帕金森、梅在帕</h1>
          <h2>Tody Chef: Plum in Shock</h2>
          <p>Mauris non tempor quam, et lacinia sapien. Mauris accumsan eros eget libero posuere vulputate. Etiam elit elit, elementum sed varius at, adipiscing vitae est. Sed nec felis pellentesque, lacinia dui sed, ultricies sapien. Pellentesque orci lectus, consectetur vel posuere posuere, rutrum eu ipsum. Aliquam eget odio sed ligula iaculis consequat at eget orci. Mauris molestie sit amet metus mattis varius. Donec sit amet ligula eget nisi sodales egestas. Aliquam interdum dolor aliquet dolor sollicitudin fermentum. Donec congue lorem a molestie bibendum.</p>
        </div>
      </div>
    </div>
    <div id="feedback">
      <div class="feedback-inside">
        <div class="feedback-tittle">
          <h1>聽聽別人的感想</h1>
        </div>
        <div class="feedback-content">
          <div class="feedback-items item-1">
            <img src="/img/avatar_1.png" alt="產品經理">
            <div class="word-part">
              <h1>高雄一口吃</h1>
              <p>自從吃了這家餐廳以後，我口水連續流了一個多月都沒停，下次不要再被我遇到，不然我一定連他們桌子都啃下去。</p>
              <h2>--產品經理</h2>
            </div>
          </div>
          <div class="feedback-items item-2">
            <img src="/img/avatar_2.png" alt="金身道士">
            <div class="word-part">
              <h1>廟口小霸王</h1>
              <p>自從吃了這家餐廳以後，我口水連續流了一個多月都沒停，下次不要再被我遇到，不然我一定連他們桌子都啃下去。</p>
              <h2>--金身道士</h2>
            </div>
          </div>
          <div class="feedback-items item-3">
            <img src="/img/avatar_3.png" alt="美麗萬分">
            <div class="word-part">
              <h1>春天也來了</h1>
              <p>自從吃了這家餐廳以後，我口水連續流了一個多月都沒停，下次不要再被我遇到，不然我一定連他們桌子都啃下去。</p>
              <h2>--美麗萬分</h2>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div id="booking">
      <div class="booking-inside">
        <div class="booking-tittle">
          <h1>我們的位置不太夠坐<br>要不要先定位呢？</h1>
        </div>
        <div class="booking-content">
          <img src="/img/Map.png" alt="map">
          <form class="booking-info">
            <label for="name">姓名</label>
            <input type="text" name="name" placeholder="六角講師吃尾牙">
            <label for="tele">電話</label>
            <input type="text" name="tele" placeholder="02-12345678">
            <label for="email">信箱</label>
            <input type="email" name="email" placeholder="test@gmail.com">
            <label for="email">人數</label>
            <input type="number" name="people" placeholder="">
            <label for="vegetarian">是否需要素食</label>
            <div class="vegetarian">
              <div class="yes">
                <input type="radio" name="vegetarian" value="是"><p>是</p>
              </div>
              <div class="no">
                <input type="radio" name="vegetarian" value="否"><p>否</p>
              </div>
            </div>
            <div class="button">
              <button id="cancel">取消</button>
              <input id="send" type="submit" value="送出">
            </div>
          </form>
        </div>
      </div>
    </div>
    <div id="footer">
      <div class="footer-inside">
        <div class="footer-left">
          <div class="footer-about">
            <h1>關於 六角西餐廳</h1>
            <p>Curabitur lobortis id lorem id bibndum. Ut id consectetur magna. Quisque volutpat augue enim, pulvinar lobortis nibh lacinia at. </p>
          </div>
          <div class="footer-contact">
            <h1>聯絡方式</h1>
            <ul>
              <li>高雄市中正五路到底</li>
              <li>+886 886 886</li>
              <li>service@hexschool.com</li>
            </ul>
          </div>
        </div>
        <div class="footer-right">
          <div class="footer-logo">
            <h1>六角西餐廳</h1>
            <div class="social">
              <i class="fab fa-google-plus-square"></i>
              <i class="fab fa-twitter-square"></i>
              <i class="fab fa-facebook-square"></i>
              <div class="aaa"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
@import 'scss/all.scss';
.nav {
  a {
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
