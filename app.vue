<template>
  <div>
    <div class="backround">
      <div class="header">
        <div class="header-list-nav">
          <ul class="header-navigation">
            <li>
              <img class="logo" src="public/logo.svg">
            </li>
            <li>
              <button class="header-txt">Product</button>
            </li>
            <li>
              <button class="header-txt">Use cases</button>
            </li>
            <li>
              <button class="header-txt">Learn</button>
            </li>
            <li>
              <button class="header-txt">About</button>
            </li>
            <li>
              <button class="header-txt">Jobs</button>
            </li>
            <li>
              <button class="reg-btn">Login</button>
            </li>
          </ul>
          <div class="show-burger">
            <div style="float: left;">
              <img class="logo" src="public/logo.svg">
            </div>
            <div style="float: left;">
              <div class="menu">
                <input type="checkbox" id="burger-checkbox" @change="toggleScroll" class="burger-checkbox">
                <label for="burger-checkbox" class="burger">
                  <span></span>
                </label>
                <ul class="menu-list">
                  <li style="height:107px; margin-bottom: 32px;">
                    <button class="login-berger-btn"><p class="login-berger-btn-txt">Login</p></button>
                  </li>
                  <li style="height: 52px;">
                    <button class="burger-btn">
                      <ul class="burger-list">
                        <li>
                          <p class="burger-btn-txt">Product</p>
                        </li>
                        <li>
                          <img class="arrow-img" src="public/arrow.svg" alt="">
                        </li>
                      </ul>
                    </button>
                  </li>
                  <li style="height: 52px; margin-top: 12px;">
                    <button class="burger-btn">
                      <ul class="burger-list">
                        <li>
                          <p class="burger-btn-txt">Use cases</p>
                        </li>
                        <li>
                          <img class="arrow-img" src="public/arrow.svg" alt="">
                        </li>
                      </ul>
                    </button>
                  </li>
                  <li style="height: 52px; margin-top: 12px;">
                    <button class="burger-btn">
                      <ul class="burger-list">
                        <li>
                          <p class="burger-btn-txt">Learn</p>
                        </li>
                        <li>
                          <img class="arrow-img" src="public/arrow.svg" alt="">
                        </li>
                      </ul>
                    </button>
                  </li>
                  <li style="height: 52px; margin-top: 12px;">
                    <button class="burger-btn">
                      <ul class="burger-list">
                        <li>
                          <p class="burger-btn-txt">About</p>
                        </li>
                        <li>
                          <img class="arrow-img" src="public/arrow.svg" alt="">
                        </li>
                      </ul>
                    </button>
                  </li>
                  <li style="height: 52px; margin-top: 12px;">
                    <button class="burger-btn">
                      <ul class="burger-list">
                        <li>
                          <p class="burger-btn-txt">Jobs</p>
                        </li>
                        <li>
                          <img class="arrow-img" src="public/arrow.svg" alt="">
                        </li>
                      </ul>
                    </button>
                  </li>
                  <ul class="sockial-network-list">
                    <li>
                      <button class="twitter">
                        <img class="sockial-network" src="public/twitter.svg">
                      </button>
                    </li>
                    <li>
                      <button class="telegram">
                        <img class="sockial-network" src="public/telegram.svg">
                      </button>
                    </li>
                    <li>
                      <button class="youtube">
                        <img class="sockial-network" src="public/youtube.svg">
                      </button>
                    </li>
                    <li>
                      <button class="discord">
                        <img class="sockial-network" src="public/discord.svg">
                      </button>
                    </li>
                  </ul>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {

    }
  },
    computed: {

    },
    methods: {
      toggleScroll() {
        document.body.classList.toggle('no-scroll');
      }
    },
}
</script>

<style>
* {
  margin: 0px;
  height: 0px;
}

.backround {
  width: 100%;
  height: 8647px;
  background-image: url(public/back1920.svg);
  background-position: center; /* Фиксирует изображение по центру */
  background-size: cover; /* Масштабирует изображение так, чтобы оно покрывало всю область, обрезая лишнее */
  background-repeat: no-repeat; /* Запрещает повторение изображения */
}

.logo {
  width: 193px;
  height: 32.03px;
  margin: 4px 112px 0px 0px;
}

ul li {
  float: left;
  list-style: none;
}

button {
  background: none;
  border: none;
}

.header-txt {
  color: rgb(255, 255, 255);
  font-family: 'Montserrat';
  font-size: 20px;
  font-weight: 600;
  line-height: 24px;
  letter-spacing: 0%;
  text-align: left;
  height: auto;
  margin: 11px 40px 0px 0px;
}

.header-navigation {
  display: flex;
  justify-content: center;
}

.reg-btn {
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 12px;
  width: 92px;
  height: 44px;
  background: rgb(36, 50, 65);
  color: rgb(255, 255, 255);
  font-family: 'Montserrat';
  font-size: 18px;
  font-weight: 500;
  line-height: 22px;
  letter-spacing: 0%;
  text-align: left;
  margin: 0px 0px 0px 170px;
}

.header-list-nav {
  height: 30px;
  display: flex;
  align-items: flex-end;
  justify-content: center;
}

.show-burger {
    display: none;
  }
@media (min-width: 769px) and (max-width: 1200px) {
  * {
    margin: 0px;
    height: 0px;
  } 

  .logo {
    width: 140px;
    height: 23.24px;
    margin: 3px 55px 0px 0px;
  }

  ul li {
    float: left;
    list-style: none;
  }

  .backround {
    width: 100%;
    height: 5695px;
    background-image: url(public/back768.svg);
    background-position: center; /* Фиксирует изображение по центру */
    background-size: cover; /* Масштабирует изображение так, чтобы оно покрывало всю область, обрезая лишнее */
    background-repeat: no-repeat; /* Запрещает повторение изображения */
  }

  button {
    background: none;
    border: none;
  }

  .header-txt {
    color: rgb(255, 255, 255);
    font-family: 'Montserrat';
    font-size: 14px;
    font-weight: 600;
    line-height: 17px;
    letter-spacing: 0%;
    text-align: left;
    height: auto;
    margin: 7px 24px 0px 0px;
  }



  .header-navigation {
    display: flex;
    justify-content: center;
  }

  .reg-btn {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 67px;
    height: 31px;
    border-radius: 8px;
    background: rgb(36, 50, 65);
    color: rgb(255, 255, 255);
    font-family: 'Montserrat';
    font-size: 12px;
    font-weight: 500;
    line-height: 15px;
    letter-spacing: 0%;
    text-align: left;
    margin: 0px 0px 0px 104px;
  }

  .header-list-nav {
    height: 30px;
    display: flex;
    align-items: flex-end;
    justify-content: center;
  }
  
  .show-burger {
    display: none;
  }
}

@media (min-width: 360px) and (max-width: 768px) {
  * {
    margin: 0px;
    height: 0px;
  }

  .logo {
    width: 140px;
    height: 23.24px;
    margin: 0px 0px 0px 0px;
    position: relative;
    z-index: 1;
  }

  ul li {
    float: left;
    list-style: none;
  }

  .backround {
    width: 100%;
    height: 5695px;
    background-image: url(public/back768.svg);
    background-position: center; /* Фиксирует изображение по центру */
    background-size: cover; /* Масштабирует изображение так, чтобы оно покрывало всю область, обрезая лишнее */
    background-repeat: no-repeat; /* Запрещает повторение изображения */
  }

  .header-txt {
    color: rgb(255, 255, 255);
    font-family: 'Montserrat';
    font-size: 14px;
    font-weight: 600;
    line-height: 17px;
    letter-spacing: 0%;
    text-align: left;
    height: auto;
    margin: 7px 24px 0px 0px;
  }

  button {
    background: none;
    border: none;
  }

  .header-navigation {
    display: none;
    justify-content: center;
  }

  .reg-btn {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 67px;
    height: 31px;
    border-radius: 8px;
    background: rgb(36, 50, 65);
    color: rgb(255, 255, 255);
    font-family: 'Montserrat';
    font-size: 12px;
    font-weight: 500;
    line-height: 15px;
    letter-spacing: 0%;
    text-align: left;
    margin: 0px 0px 0px 104px;
  }

  .header-list-nav {
    height: 30px;
    display: flex;
    align-items: flex-end;
    justify-content: center;
  }

  .burger-checkbox {
    position: absolute;
    visibility: hidden;
  }
  .burger {
    position: relative;
    z-index: 1;
    cursor: pointer;
    display: block;
    border: none;
    background: transparent;
    width: 17px;
    height: 17px;
    margin: 3px 0px 0px 168px;
  }
  .burger::before,
  .burger::after,
  .burger span {
    content: '';
    position: absolute;
    left: 0;
    display: block;
    width: 100%;
    height: 2px;
    border-radius: 2px;
    background: #FFCF01;
    transition: all 0.3s ease-in-out;
  }
  .burger::before {
    top: 2px;
  }
  .burger span {
    top: 7.5px;
  }
  .burger::after {
    bottom: 2px;
  }
  .burger-checkbox:checked + .burger::before {
    top: 7.5px;
    transform: rotate(45deg);
  }
  .burger-checkbox:checked + .burger span {
    opacity: 0;
    transform: scale(0);
  }
  .burger-checkbox:checked + .burger::after {
    bottom: 7.5px;
    transform: rotate(-45deg);
  }
  .menu-list {
    top: 0;
    left: 0;
    position: absolute;
    display: flex;
    padding: 42px 0;
    margin: 0;
    background: rgb(18, 30, 40);;
    list-style-type: none;
    transform: translateX(-100%);
    transition: .3s;
    width: 100%;
    height: 100%;
    justify-items: center;
    flex-direction: column;
    align-items: center;
  }

  .burger-checkbox:checked ~ .menu-list {
    transform: translateX(0);
  }

  .show-burger {
    display: flex;
  }

  .login-berger-btn {
    border-radius: 10px;
    width: 320px;
    height: 52px;
    background: rgba(255, 200, 3, 0.2);
    display: block;
    padding: 0;
    margin: 55px 0px 0px 0px;

  }

  .login-berger-btn-txt {
    color: rgb(255, 200, 3);
    font-family: 'Montserrat';
    font-size: 15px;
    font-weight: 600;
    line-height: 32px;
    letter-spacing: 0px;
    text-align: left;
    margin: 0px 0px 0px 20px;
    height: 32px;
  }

  .burger-btn {
    border-radius: 10px;
    width: 320px;
    height: 52px;
    background: rgb(24, 38, 50);
    padding: 0px;
  }

  .burger-btn-txt {
    color: rgb(255, 255, 255);
    font-family: 'Montserrat';
    font-size: 15px;
    font-weight: 600;
    line-height: 18px;
    letter-spacing: 0px;
    text-align: left;
    margin: 0px 0px 0px 20px;
    height: 16px;
    width: 266px;
  }

  .arrow-img {
    height: 18px;
    width: 18px;
  }

  .burger-list { 
    height: 18px;
    display: flex;
    padding: 0px;
  }

  .sockial-network {
    height: 28px;
    width: 28px;
  }

  .twitter {
    border-radius: 100px;
    background: rgba(119, 230, 255, 0.15);
    width: 56px;
    height: 56px;
  }

  .telegram {
    border-radius: 100px;
    background: rgba(119, 149, 255, 0.15);
    width: 56px;
    height: 56px;
  }

  .youtube {
    border-radius: 100px;
    background: rgba(247, 135, 135, 0.15);
    width: 56px;
    height: 56px;
  }

  .discord {
    border-radius: 100px;
    background: rgba(146, 119, 255, 0.15);
    width: 56px;
    height: 56px;
  }

  .sockial-network-list {
    height: 56px;
    padding: 0px;
    display: flex;
    gap: 28px;
    align-items: flex-end;
  }

  .no-scroll {
    overflow: hidden;
  }
}
</style>