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
        <div class="header-slogan-navigation">
            <table>
              <tr>
                <td>
                  <p class="header-txt-slogan">The easiest way to start a DAO</p>
                </td>
              </tr>
              <tr>
                <td>
                  <p class="header-txt-slogan-comment">An all-in-one platform to start, manage and grow a decentralized autonomous organization</p>
                </td>
              </tr>
              <tr>
                <td style="text-align: center;">
                  <button class="start">Get started</button>
                </td>
              </tr>
              <tr>
                <td style="text-align: center;">
                  <img class="swop" src="public/swop.svg">
                </td>
              </tr>
            </table>

              
        </div>
      </div>


      <div class="container">
        <div class="cont-nav">
          <ul style="padding: 0px;">
            <li>
              <img class="star-img" src="public/star.svg"> 
            </li>
            <li>
              <p class="container-txt">Ready for every project</p>
              <p class="container-txt-xs">Ready<br>for every project</p>
            </li>
          </ul>
        </div>  
        <div style="height: auto;" class="navigation-daos">
          <ul class="container-list">
            <li>
              <button class="container-btn">Investment DAO</button>
            </li>
            <li>
              <button style="color: #FFC24C;" class="container-btn">Startup DAO</button>
            </li>
            <li class="small-phone-block-none">
              <button style="color: #D387F7;" class="container-btn">Service DAO</button>
            </li>
            <li class="small-phone-block-none">
              <button style="color: #77E6FF;" class="container-btn">Community DAO</button>
            </li>
          </ul>
        </div>
        <div style="height: auto;">
          <ul class="small-phone-block">
            <li>
              <button style="color: #D387F7;" class="container-btn">Service DAO</button>
            </li>
            <li>
              <button style="color: #77E6FF;" class="container-btn">Community DAO</button>
            </li>
          </ul>
        </div>
        <div class="navigation-daos-two" style="height: auto;">
          <ul class="container-list">
            <li>
              <button style="color: #23C9DE;" class="container-btn">Investment DAO</button>
            </li>
            <li>
              <button style="color: #FF9E9E;" class="container-btn">Startup DAO</button>
            </li>
            <li>
              <button style="color: #707F8D;" class="container-btn">
                <img  class="small-star-img" src="public/StarSmall.svg">
                <p class="small-star-txt">More</p>
              </button>
            </li>
          </ul>
        </div>
        <div class="nfr-block-navigation">
          <img class="nft-img" src="public/nft.png">
          <div class="dao-result">
            <p style="height: auto;">1000+ projects launched on Superdao</p>
          </div>
        </div>
      </div>

      <div class="container-middle">
        <div class="container-middle-txt">
          <p>Designed for the full journey</p>
        </div>
        <div class="container-middle-star-img-navigation">
          <img class="container-middle-star-img" src="public/star_middle.svg">
        </div> 
        <div class="container-middle-setting">
          <div>
            <p class="cont-middle-txt">Designed</p>
            <img class="container-middle-star-img" src="public/star_middle.svg">
          </div>
          <div>
            <p class="container-middle-txt-two">for the full journey</p>
          </div>
        </div>
      </div>
      <div class="container-middle-imformation">
        <p class="middle-imformation-txt">Organisation design</p>
        <p class="middle-imformation-txt">Smart contract development</p>
        <p class="middle-imformation-txt">Fundraising</p>
        <p class="middle-imformation-txt">Launch marketing</p>
        <p class="middle-imformation-txt">Member onboarding</p>
        <p class="middle-imformation-txt">Contributor management</p>
        <p class="middle-imformation-txt">DAO operations</p>
      </div>


      <div class="container-tools">
        <div style="float: left; height: auto;">
          <img class="tools-star" src="public/toolsstar.svg" alt="">
        </div>
        <div style="float: left;">
          <p class="container-tools-txt">All the tools in one app</p>
        </div>
      </div>
      <div>
        <ul v-if="isPhone" class="tools-list">
          <div class="tools-list-row">
            <li v-for="(button, index) in buttons.slice(0, 2)" :key="index">
              <button
                @click="toggleButtonColor(index)"
                :class="['tools-list-btn', { active: button.isActive }]"
              >
                {{ button.label }}
              </button>
            </li>
          </div>
          <div class="tools-list-row">
            <li v-for="(button, index) in buttons.slice(2)" :key="index + 2">
              <button
                @click="toggleButtonColor(index + 2)"
                :class="['tools-list-btn', { active: button.isActive }]"
              >
                {{ button.label }}
              </button>
            </li>
          </div>
        </ul>
        <ul v-if="isDesktop" class="tools-list">
          <li v-for="(button, index) in buttons" :key="index">
            <button
              @click="toggleButtonColor(index)"
              :class="['tools-list-btn', { active: button.isActive }]"
            >
              {{ button.label }}
            </button>
          </li>
        </ul> 
        <div class="demo-img-block">
          <img v-if="activeButtonLabel === 'NFT membership'" class="demo-img" src="public/public_app.png"> 
          <img v-if="activeButtonLabel === 'Member directory'" class="demo-img" src="public/public_app.png"> 
          <img v-if="activeButtonLabel === 'Treasury'" class="demo-img" src="public/public_app.png"> 
          <img v-if="activeButtonLabel === 'Feed'" class="demo-img" src="public/public_app.png"> 
          <img v-if="activeButtonLabel === 'Governance'" class="demo-img" src="public/public_app.png"> 
          <img v-if="activeButtonLabel === 'App store'" class="demo-img" src="public/public_app.png"> 
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      windowWidth: window.innerWidth,
      buttons: [
        { label: 'NFT membership', isActive: true },
        { label: 'Member directory', isActive: false },
        { label: 'Treasury', isActive: false },
        { label: 'Feed', isActive: false },
        { label: 'Governance', isActive: false },
        { label: 'App store', isActive: false }
      ]
    }
  },
  computed: {
    isPhone() {
      return this.windowWidth >= 360 && this.windowWidth <= 768;
    },
    isDesktop() {
      return this.windowWidth >= 769 && this.windowWidth <= 3000;
    },
    activeButtonLabel() {
        const activeButtons = this.buttons.filter(button => button.isActive);
        if (activeButtons.length > 0) {
          return activeButtons[0].label;
        }
        return null; // Или какое-то значение по умолчанию, например, `null`
    }
  },
  methods: {
    toggleScroll() {
      document.body.classList.toggle('no-scroll');
    },
    handleResize() {
      this.windowWidth = window.innerWidth;
    },
    toggleButtonColor(index) {
      // Сначала сбрасываем состояние всех кнопок
      this.buttons.forEach((button, i) => {
        button.isActive = (i === index); // Активируем только текущую
      });
      console.log(`Button ${index} toggled:`, this.buttons[index].isActive);
    }
  },
  mounted() {
    window.addEventListener("resize", this.handleResize);
  },
  beforeDestroy() {
    window.removeEventListener("resize", this.handleResize);
  },
  watch: {
    // isButtonActive(newVal) {
    //   const button = document.getElementById('nftMembershipBtn');
    //   if (newVal) {
    //     button.classList.add('active');
    //   } else {
    //     button.classList.remove('active');
    //   }
    // }
  }
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
  height: auto;
}

button {
  background: none;
  border: none;
}

.header {
  height: 660px;
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

.header-txt-slogan {
  color: rgb(255, 255, 255);
  font-family: 'Russo One';
  font-size: 72px;
  font-weight: 700;
  line-height: 82px;
  letter-spacing: 1px;
  text-align: center;
  margin: 200px 0px 0px 0px;
  width: 642px;
  height: 164px;
}

.header-slogan-navigation {
  display: flex;
  height: 210px;
  flex-direction: column;
  align-items: center;
}

.header-txt-slogan-comment {
  color: rgb(255, 255, 255);
  font-family: 'Montserrat';
  font-size: 26px;
  font-weight: 500;
  line-height: 46px;
  letter-spacing: 0px;
  text-align: center;
  width: 650px;
  height: 92px;
  margin: 32px 0px 0px 0px;
}

.start {
  width: 214px;
  height: 68px;
  border-radius: 16px;
  box-shadow: 0px 9px 44px 0px rgba(255, 207, 1, 0.2);
  background: rgb(255, 207, 1);
  color: rgb(16, 21, 26);
  font-family: 'Montserrat';
  font-size: 20px;
  font-weight: 700;
  line-height: 36px;
  letter-spacing: 0px;
  text-align: center;
  margin: 56px 0px 0px 0px;
}

.a {
  display: flex;
}

.swop {
  height: 21px;
  width: 21px;
  margin: 120px 0px 0px 0px;
  animation: scrollDown 2s infinite alternate ease-in-out;
}

.container {
  height: auto;
  display: flex;
  margin: 240px 0px 0px 0px;
  flex-direction: column;
  align-items: center;
}

.star-img {
  width: 89px;
  height: 89px;
}

.container-txt {
  color: rgb(229, 229, 229);
  font-family: 'Russo One';
  font-size: 54px;
  font-weight: 700;
  line-height: 80px;
  letter-spacing: 0px;
  text-align: center;
  height: 80px;
  margin: 12px 0px 0px 95px;
}

.cont-nav {
  width: 1140px;
  height: auto;
  padding: 0px 0px 0px 65px;
}

.container-btn {
  border-radius: 100px;
  background: rgb(24, 38, 50);
  width: auto;
  height: 56px;
  gap: 8;
  padding: 8px 26px 8px 26px;
  color: rgb(255, 180, 211);
  font-family: 'Montserrat';
  font-size: 20px;
  font-weight: 600;
  line-height: 40px;
  letter-spacing: 0px;
  text-align: center;
  display: flex;
}

.container-list {
  display: flex;
  gap: 24px;
  height: auto;
}

.small-star-img {
  height: 16px;
  width: 16px;
  margin: 12px 8px 0px 0px;
}

.navigation-daos {
  margin: 44px 0px 24px 0px;
}

.small-star-txt {
  height: 40px;
}

.small-phone-block {
  display: none;
}
.small-phone-block-none {
  display: block;
}
.container-txt-xs {
  color: rgb(255, 255, 255);
  font-family: 'Russo One';
  font-size: 28px;
  font-weight: 400;
  line-height: 36px;
  width: 239px;
  letter-spacing: 0px;
  text-align: center;
  height: 43px;
  margin: 0px 0px 0px 0px;
  display: none;
}
@keyframes scrollDown {
  0% {
    transform: translateY(0);
    opacity: 0.2; /* Start with slightly lower opacity */
  }
  100% {
    transform: translateY(10px); /* Move down slightly */
    opacity: 1; /* Full opacity at the end */
  }
}

.nft-img {
  margin: 44px 0px 0px 0px;
  width: 1140px;
  height: 493px;
  position: absolute;
}

.dao-result {
  position: absolute;
  width: 404px;
  height: 44px;
  border: 4px solid rgb(10, 17, 23);
  border-radius: 100px;
  background: rgb(255, 168, 0);
  color: rgb(10, 17, 23);
  font-family: 'Montserrat';
  font-size: 18px;
  font-weight: 700;
  line-height: 32px;
  letter-spacing: 0px;
  text-align: center;
  margin: 512px 0px 0px 0px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.nfr-block-navigation {
  height: 515px;
  display: flex;
  justify-content: center;
}

.container-middle {
  margin: 183px 0px 44px 0px;
  display: flex;
  justify-content: center;
  height: auto;
}

.container-middle-txt {
  color: rgb(229, 229, 229);
  width: auto;
  height: 80px;
  font-family: 'Russo One';
  font-size: 54px;
  font-weight: 400;
  line-height: 80px;
  letter-spacing: 0px;
  text-align: center;
  float: left;
  margin: 27px 36px 0px 72px;
}

.container-middle-star-img {
  width: 76.17px;
  height: 57px;
}

.container-middle-star-img-navigation {
  float: left;
}

.container-middle-setting {
  display: none;
}

.container-middle-imformation {
  gap: 20px;
  display: grid;
  justify-content: center;
  height: auto;
}

.middle-imformation-txt {
  color: rgb(55, 66, 77);
  font-family: 'Montserrat';
  font-size: 54px;
  font-weight: 700;
  line-height: 64px;
  letter-spacing: 0px;
  text-align: center;
  height: 64px;
  animation: highlight 14s infinite;
  transition: color 0.3s ease;
}

.middle-imformation-txt:nth-child(1) { animation-delay: 0s; }
.middle-imformation-txt:nth-child(2) { animation-delay: -12s; }
.middle-imformation-txt:nth-child(3) { animation-delay: -10s; }
.middle-imformation-txt:nth-child(4) { animation-delay: -8s; }
.middle-imformation-txt:nth-child(5) { animation-delay: -6s; }
.middle-imformation-txt:nth-child(6) { animation-delay: -4s; }
.middle-imformation-txt:nth-child(7) { animation-delay: -2s; }

@keyframes highlight {
  0%, 100% {
    color: rgb(55, 66, 77);
  }
  10%, 14.3% {
    color: rgb(35, 201, 222);
  }
}

.container-tools {
  display: flex;
  justify-content: center;
  margin: 174px 0px 0px 0px;
  height: 122px;
}

.tools-star {
  width: 66.96px;
  height: 53.17px;
}

.container-tools-txt {
  color: rgb(229, 229, 229);
  font-family: 'Russo One';
  font-size: 54px;
  font-weight: 400;
  line-height: 80px;
  letter-spacing: 0px;
  text-align: center;
  height: 80px;
  width: 639px;
  margin: 26px 60px 0px 30px;
}

.tools-list {
  height: 40px;
  padding: 0px;
  display: flex;
  gap: 40px;
  justify-items: center;
  justify-content: center;
  margin: 0px 0px 0px 0px;
}

.tools-list-btn {
  color: rgb(131, 149, 167);
  font-family: 'Montserrat';
  font-size: 22px;
  font-weight: 600;
  line-height: 40px;
  letter-spacing: 0px;
  text-align: left;
  transition: color 0.3s ease;
}

#nftMembershipBtn {
  transition: color 0.3s ease;
}

.tools-list-btn.active {
  color: #FFC803;
}

.demo-img {
  width: 1000px;
  height: 700px;
}

.demo-img-block {
  height: auto;
  display: flex;
  justify-content: center;
  margin: 46px 0px 0px 0px;
}

.fade-enter-active, .fade-leave-active {
  transition: opacity 0.5s;
}
.fade-enter, .fade-leave-to /* .fade-leave-active below version 2.1.8 */ {
  opacity: 0;
}
@media (min-width: 769px) and (max-width: 1260px) {
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

  .header-txt-slogan {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 52px;
    font-weight: 700;
    line-height: 60px;
    letter-spacing: 0px;
    text-align: center;
    margin: 120px 0px 0px 0px;
    width: 454px;
    height: 120px;  
  }

  .header-slogan-navigation {
    display: flex;
    height: 210px;
    flex-direction: column;
    align-items: center;
  }

  .header-txt-slogan-comment {
    color: rgb(255, 255, 255);
    font-family: 'Montserrat';
    font-size: 20px;
    font-weight: 500;
    line-height: 34px;
    letter-spacing: 0px;
    text-align: center;
    width: 500px;
    height: 68px;
    margin: 20px 0px 0px 0px;
  }

  .start {
    width: 176px;
    height: 56px;
    border-radius: 12px;
    box-shadow: 0px 7px 36px 0px rgba(255, 207, 1, 0.2);
    background: rgb(255, 207, 1);
    color: rgb(16, 21, 26);
    font-family: 'Montserrat';
    font-size: 17px;
    font-weight: 700;
    line-height: 30px;
    letter-spacing: 0px;
    text-align: center;
    margin: 44px 0px 0px 0px;
  }

  .a {
    display: flex;
  }

  .swop {
    height: 17px;
    width: 17px;
    margin: 64px 0px 0px 0px;
    animation: scrollDown 2s infinite alternate ease-in-out;
  }

  @keyframes scrollDown {
    0% {
      transform: translateY(0);
      opacity: 0.2; /* Start with slightly lower opacity */
    }
    100% {
      transform: translateY(10px); /* Move down slightly */
      opacity: 1; /* Full opacity at the end */
    }
  }

  .container {
    display: flex;
    margin: 30px 0px 0px 0px;
    flex-direction: column;
    align-items: center;
  }

  .star-img {
    width: 61px; 
    height: 61px;
  }

  .container-txt {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 36px;
    font-weight: 400;
    line-height: 43px;
    letter-spacing: 0px;
    text-align: center;
    height: 43px;
    margin: 26px 0px 0px 46px;
  }

  .cont-nav {
    width: 736px;
    height: auto;
    padding: 0px 0px 0px 65px;
  }

  .container-btn {
    border-radius: 100px;
    background: rgb(24, 38, 50);
    width: auto;
    height: 48px;
    gap: 12;
    padding: 8px 24px 8px 24px;
    color: rgb(255, 180, 211);
    font-family: 'Montserrat';
    font-size: 16px;
    font-weight: 600;
    line-height: 32px;
    letter-spacing: 0px;
    text-align: center;
    display: flex;
    align-items: center;
  }

  .container-list {
    display: flex;
    gap: 20px;
    height: auto;
  }

  .small-star-img {
    height: 14px;
    width: 14px;
    margin: 0px 8px 0px 0px;
  }

  .navigation-daos {
    margin: 46px 0px 20px 0px;
  }

  .small-star-txt {
    height: 31px;
  }
  .small-phone-block {
    display: none;
  }
  .small-phone-block-none {
    display: block;
  }
  .container-txt-xs {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 28px;
    font-weight: 400;
    line-height: 36px;
    width: 239px;
    letter-spacing: 0px;
    text-align: center;
    height: 43px;
    margin: 0px 0px 0px 0px;
    display: none;
  }
  .nft-img {
    margin: 44px 0px 0px 0px;
    width: 736px;
    height: 318px;
    position: absolute;
  }

  .dao-result {
    position: absolute;
    width: 356px;
    height: 36px;
    border: 3px solid rgb(10, 17, 23);
    border-radius: 100px;
    background: rgb(255, 168, 0);
    color: rgb(10, 17, 23);
    font-family: 'Montserrat';
    font-size: 16px;
    font-weight: 700;
    line-height: 32px;
    letter-spacing: 0px;
    text-align: center;
    margin: 342px 0px 0px 0px;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .nfr-block-navigation {
    height: 336px;
    display: flex;
    justify-content: center;
  }
  .container-middle {
    margin: 110px 0px 18px 0px;
    display: flex;
    justify-content: center;
  }

  .container-middle-txt {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 36px;
    font-weight: 400;
    line-height: 43px;
    letter-spacing: 0px;
    text-align: center;
    height: 43px;
    width: auto;
    float: left;
    margin: 23px 27px 0px 54px;
  }

  .container-middle-star-img {
    width: 50px;
    height: 37px;
  }

  .container-middle-star-img-navigation {
    float: left;
  }

  .container-middle-setting {
    display: none;
  }
  .container-middle-imformation {
    gap: 0px;
    display: grid;
    justify-content: center;
  }

  .middle-imformation-txt {
    color: rgb(55, 66, 77);
    font-family: 'Montserrat';
    font-size: 32px;
    font-weight: 700;
    line-height: 50px;
    letter-spacing: 0px;
    text-align: center;
    height: 50px;
    animation: highlight 14s infinite;
    transition: color 0.3s ease;
  }

  .middle-imformation-txt:nth-child(1) { animation-delay: 0s; }
  .middle-imformation-txt:nth-child(2) { animation-delay: -12s; }
  .middle-imformation-txt:nth-child(3) { animation-delay: -10s; }
  .middle-imformation-txt:nth-child(4) { animation-delay: -8s; }
  .middle-imformation-txt:nth-child(5) { animation-delay: -6s; }
  .middle-imformation-txt:nth-child(6) { animation-delay: -4s; }
  .middle-imformation-txt:nth-child(7) { animation-delay: -2s; }

  @keyframes highlight {
    0%, 100% {
      color: rgb(55, 66, 77);
    }
    10%, 14.3% {
      color: rgb(35, 201, 222);
    }
  }

  .tools-list {
    height: 28px;
    padding: 0px;
    display: flex;
    gap: 27px;
    justify-items: center;
    justify-content: center;
    margin: 32px 0px 0px 0px;
  }

  .tools-list-btn {
    color: rgb(131, 149, 167);
    font-family: 'Montserrat';
    font-size: 16px;
    font-weight: 600;
    line-height: 28px;
    letter-spacing: 0px;
    text-align: left;
    transition: color 0.3s ease;
  }

  #nftMembershipBtn {
    transition: color 0.3s ease;
  }

  .tools-list-btn.active {
    color: #FFC803;
  }

  .demo-img {
    width: 657px;
    height: 460px;
  }

  .demo-img-block {
    height: auto;
    display: flex;
    justify-content: center;
    margin: 28px 0px 0px 0px;
  }

  .fade-enter-active, .fade-leave-active {
    transition: opacity 0.5s;
  }
  .fade-enter, .fade-leave-to /* .fade-leave-active below version 2.1.8 */ {
    opacity: 0;
  }

  .tools-star {
    width: 40px;
    height: 31px;
  }

  .container-tools-txt {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 36px;
    font-weight: 400;
    line-height: 43px;
    letter-spacing: 0px;
    text-align: center;
    width: 426px;
    height: 43px;
    margin: 19px 38px 0px 19px;
  }

  .container-tools {
    display: flex;
    justify-content: center;
    margin: 174px 0px 0px 0px;
    height: 59px;
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

  .header {
    height: 475px;
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
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .telegram {
    border-radius: 100px;
    background: rgba(119, 149, 255, 0.15);
    width: 56px;
    height: 56px;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .youtube {
    border-radius: 100px;
    background: rgba(247, 135, 135, 0.15);
    width: 56px;
    height: 56px;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .discord {
    border-radius: 100px;
    background: rgba(146, 119, 255, 0.15);
    width: 56px;
    height: 56px;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .sockial-network-list {
    height: 56px;
    padding: 0px;
    display: flex;
    gap: 28px;
    align-items: flex-end;
    margin: 120px 0px 0px 0px;
  }

  .no-scroll {
    overflow: hidden;
  }

  .no-scroll .star-img {
    display: none;
  }

  .header-txt-slogan {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 36px;
    font-weight: 700;
    line-height: 44px;
    letter-spacing: 0px;
    text-align: center;
    margin: 110px 0px 0px 0px;
    width: 334px;
    height: 88px; 
  }

  .header-slogan-navigation {
    display: flex;
    height: 210px;
    flex-direction: column;
    align-items: center;
  }

  .header-txt-slogan-comment {
    color: rgb(255, 255, 255);
    font-family: 'Montserrat';
    font-size: 18px;
    font-weight: 500;
    line-height: 28px;
    letter-spacing: 0px;
    text-align: center;
    width: 334px;
    height: 84px;
    margin: 16px 0px 0px 0px;
  }

  .start {
    width: 145px;
    height: 46px;
    border-radius: 12px;
    box-shadow: 0px 7px 36px 0px rgba(255, 207, 1, 0.2);
    background: rgb(255, 207, 1);
    color: rgb(16, 21, 26);
    font-family: 'Montserrat';
    font-size: 15px;
    font-weight: 700;
    line-height: 30px;
    letter-spacing: 0px;
    text-align: center;
    margin: 40px 0px 0px 0px;
  }

  .a {
    display: flex;
  }

  .swop {
    height: 21px;
    width: 21px;
    margin: 120px 0px 0px 0px;
    display: none;
    animation: scrollDown 2s infinite alternate ease-in-out;
  }

  @keyframes scrollDown {
    0% {
      transform: translateY(0);
      opacity: 0.2; /* Start with slightly lower opacity */
    }
    100% {
      transform: translateY(10px); /* Move down slightly */
      opacity: 1; /* Full opacity at the end */
    }
  }

  .container {
    display: flex;
    margin: 30px 0px 0px 0px;
    flex-direction: column;
    align-items: center;
  }

  .star-img {
    width: 38px; 
    height: 38px;
    position: absolute;
    transform: translateY(-23px);
  }

  .container-txt {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 28px;
    font-weight: 400;
    line-height: 36px;
    width: 239px;
    letter-spacing: 0px;
    text-align: center;
    height: 43px;
    margin: 0px 0px 0px 0px;
    display: none;
  }

  .container-txt-xs {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 28px;
    font-weight: 400;
    line-height: 36px;
    width: 239px;
    letter-spacing: 0px;
    text-align: center;
    height: 72px;
    margin: 0px 0px 0px 0px;
    display: block;
  }
  
  .cont-nav {
    width: auto;
    height: auto;
    padding: 0px 0px 0px 0px;
  }

  .container-btn {
    border-radius: 45px;
    background: rgb(24, 38, 50);
    width: auto;  
    height: 40px;
    gap: 12;
    padding: 12px 14px 12px 14px;
    color: rgb(255, 180, 211);
    font-family: 'Montserrat';
    font-size: 14px;
    font-weight: 600;
    line-height: 16px;
    letter-spacing: 0px;
    text-align: center;
    display: flex;
    align-items: center;
  }
  

  .container-list {
    display: flex;
    gap: 12px;
    height: auto;
    padding: 0px;
  }

  .small-star-img {
    height: 10px;
    width: 10px;
    margin: 0px 8px 0px 0px;
  }

  .navigation-daos {
    margin: 24px 0px 12px 0px;
  }

  .navigation-daos-two {
    margin: 12px 0px 0px 0px;
  }

  .small-star-txt {
    height: 16px;
  }

  .small-phone-block {
    display: flex;
    gap: 12px;
    height: auto;
    padding: 0px;
  }
  .small-phone-block-none {
    display: none;
    height: auto;
  }
  .nft-img {
    margin: 24px 0px 0px 0px;
    width: 328px;
    height: 328px;
    position: absolute;
    object-fit: cover;
    object-position: center center;
    border-radius: 20px;
  }

  .dao-result {
    position: absolute;
    width: 281px;
    height: 28px;
    border: 3px solid rgb(10, 17, 23);
    border-radius: 100px;
    background: rgb(255, 168, 0);
    color: rgb(10, 17, 23);
    font-family: 'Montserrat';
    font-size: 13px;
    font-weight: 700;
    line-height: 24px;
    letter-spacing: 0px;
    text-align: center;
    margin: 336px 0px 0px 0px;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .nfr-block-navigation {
    height: 342px;
    display: flex;
    justify-content: center;
  }

  .container-middle {
    margin: 85px 0px 24px 0px;
    display: flex;
    justify-content: center;
  }

  .container-middle-txt {
    display: none;
  }

  .cont-middle-txt {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 28px;
    font-weight: 400;
    line-height: 36px;
    letter-spacing: 0px;
    text-align: center;
    width: auto;
    height: 40px;
    float: left;
    margin: 15px 20px 0px 40px;
  }

  .container-middle-txt-two {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 28px;
    font-weight: 400;
    line-height: 36px;
    letter-spacing: 0px;
    text-align: center;
    width: auto;
    height: 40px;
    float: left;
    margin: 6px 0px 0px 0px;
  }

  .container-middle-star-img {
    width: 29px;
    height: 21.7px;
  }

  .container-middle-star-img-navigation {
    float: left;
    display: none;
  }

  .container-middle-setting {
    height: 87px;
    display: grid;
    justify-items: center;
  }
  .container-middle-imformation {
    gap: 0px;
    display: grid;
    justify-content: center;
  }

  .middle-imformation-txt {
    color: rgb(55, 66, 77);
    font-family: 'Montserrat';
    font-size: 20px;
    font-weight: 700;
    line-height: 36px;
    letter-spacing: 0px;
    text-align: center;
    height: 36px;
    animation: highlight 14s infinite;
    transition: color 0.3s ease;
  }

  .middle-imformation-txt:nth-child(1) { animation-delay: 0s; }
  .middle-imformation-txt:nth-child(2) { animation-delay: -12s; }
  .middle-imformation-txt:nth-child(3) { animation-delay: -10s; }
  .middle-imformation-txt:nth-child(4) { animation-delay: -8s; }
  .middle-imformation-txt:nth-child(5) { animation-delay: -6s; }
  .middle-imformation-txt:nth-child(6) { animation-delay: -4s; }
  .middle-imformation-txt:nth-child(7) { animation-delay: -2s; }

  @keyframes highlight {
    0%, 100% {
      color: rgb(55, 66, 77);
    }
    10%, 14.3% {
      color: rgb(35, 201, 222);
    }
  }

  .tools-list {
    display: flex;
    flex-direction: column;
    align-items: center; /* Центрируем ряды по горизонтали */
    margin: 32px 0 0 0;
    gap: 12px;
  }

  .tools-list-row {
    display: flex;
    justify-content: center; /* Центрируем элементы в ряду */
    gap: 19px; /* Расстояние между кнопками */
    margin-bottom: 10px; /* Добавляем отступ между рядами */
  }

  .tools-list-btn {
    /* Ваши стили для кнопок */
  }

  .tools-list-btn {
    color: rgb(131, 149, 167);
    font-family: 'Montserrat';
    font-size: 14px;
    font-weight: 600;
    line-height: 16.22px;
    letter-spacing: 0px;
    text-align: center;
    transition: color 0.3s ease;
  }

  #nftMembershipBtn {
    transition: color 0.3s ease;
  }

  .tools-list-btn.active {
    color: #FFC803;
  }

  .demo-img {
    width: 328px;
    height: 230px;
  }

  .demo-img-block {
    height: auto;
    display: flex;
    justify-content: center;
    margin: 28px 0px 0px 0px;
  }

  .fade-enter-active, .fade-leave-active {
    transition: opacity 0.5s;
  }
  .fade-enter, .fade-leave-to /* .fade-leave-active below version 2.1.8 */ {
    opacity: 0;
  }

  .tools-star {
    width: 27px;
    height: 21px;
  }

  .container-tools-txt {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 28px;
    font-weight: 400;
    line-height: 36px;
    letter-spacing: 0px;
    text-align: center;
    width: 176px;
    height: 72px;
    margin: 14px 6px 0px 3px;
  }

  .container-tools {
    display: flex;
    justify-content: center;
    margin: 174px 0px 0px 0px;
    height: 75px;
  }
}
</style>