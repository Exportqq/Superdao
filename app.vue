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
            <div class="show-burder-logos" >
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
      <div class="tools-block">
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
        <div class="video-btn-navigation">
          <button class="video-btn">
            <img class="video-img" src="public/video.svg">
            <p class="video-txt">Watch video</p>
          </button>
        </div>
      </div>



      <div class="container-works">
        <div class="works-txt-navigation">
          <p class="works-txt">Works with</p>
          <img class="works-star-img" src="public/works_star.svg">
        </div>
        <div v-if="isDesktop" class="blockchain-blocks-display">
          <div class="blockchain-blocks-navigation">
            <div class="blockchain-blocks">
              <img class="blockchain-img" src="public/ethereum.svg">
            </div>
            <p class="blockchain-txt">Ethereum</p>
          </div>
          <div class="blockchain-blocks-navigation">
            <div class="blockchain-blocks">
              <img class="blockchain-img" src="public/polygon.svg">
            </div>
            <p class="blockchain-txt">Polygon</p>
          </div>
          <div class="blockchain-blocks-navigation">
            <div class="blockchain-blocks">
              <img class="blockchain-img" src="public/green.svg">
            </div>
            <p class="blockchain-txt">Gnosis Safe</p>
          </div>
          <div class="blockchain-blocks-navigation">
            <div class="blockchain-blocks">
              <img class="blockchain-img" src="public/snapshot.svg">
            </div>
            <p class="blockchain-txt">Snapshot</p>
          </div>
          <div class="blockchain-blocks-navigation">
            <div class="blockchain-blocks">
              <img class="blockchain-img" src="public/ens.svg">
            </div>
            <p class="blockchain-txt">ENS</p>
          </div>
          <div class="blockchain-blocks-navigation">
            <div class="blockchain-blocks">
              <img class="blockchain-img" src="public/opensea.svg">
            </div>
            <p class="blockchain-txt">OpenSea</p>
          </div>
        </div>

        <div v-if="isPhone" class="blockchain-blocks-display">
          <div class="blockchain-blocks-display-navigation">
            <div class="blockchain-blocks-navigation">
              <div class="blockchain-blocks">
                <img class="blockchain-img" src="public/ethereum.svg">
              </div>
              <p class="blockchain-txt">Ethereum</p>
            </div>
            <div class="blockchain-blocks-navigation">
              <div class="blockchain-blocks">
                <img class="blockchain-img" src="public/polygon.svg">
              </div>
              <p class="blockchain-txt">Polygon</p>
            </div>
            <div class="blockchain-blocks-navigation">
              <div class="blockchain-blocks">
                <img class="blockchain-img" src="public/green.svg">
              </div>
              <p class="blockchain-txt">Gnosis Safe</p>
            </div>
          </div>
          <div class="blockchain-blocks-display-navigation-first">
            <div class="blockchain-blocks-navigation">
              <div class="blockchain-blocks">
                <img class="blockchain-img" src="public/snapshot.svg">
              </div>
              <p class="blockchain-txt">Snapshot</p>
            </div>
            <div class="blockchain-blocks-navigation">
              <div class="blockchain-blocks">
                <img class="blockchain-img" src="public/ens.svg">
              </div>
              <p class="blockchain-txt">ENS</p>
            </div>
            <div class="blockchain-blocks-navigation">
              <div class="blockchain-blocks">
                <img class="blockchain-img" src="public/opensea.svg">
              </div>
              <p class="blockchain-txt">OpenSea</p>
            </div>
          </div>
        </div>
      </div>
      <div class="container-devs">
        <p class="devs-txt">Help at every step</p>
      </div>
      <div class="container-devs-two">
        <div class="devs-nav-one">
          <img class="devs-img" src="public/dev1.jpeg">
          <img class="devs-img" src="public/dev2.jpeg">
        </div>
        <div class="devs-nav-two">
          <img class="devs-img" src="public/dev3.jpeg">
          <img class="devs-img" src="public/dev4.jpeg">
          <img class="devs-img" src="public/dev5.jpeg">
        </div>
      </div>
      <div class="roles-navigation">
        <div class="devs-roles-block">
          <div  class="devs-roles-block-navigation">
            <p class="devs-roles">Success managers</p>
            <img src="public/blue.svg" class="dev-stars-roles">
            <p class="devs-roles">Knowledge base</p>
            <p class="devs-roles">Chat support</p>
            <img src="public/violet.svg" class="dev-stars-roles">
            <p class="devs-roles">Tutorials</p>
            <img src="public/gryellow.svg" class="dev-stars-roles">
            <p class="devs-roles">Templates</p>
            <p class="devs-roles">Smart Contract development</p>
            <img src="public/orange.svg" class="dev-stars-roles">
            <p class="devs-roles">Events</p>
            <p class="devs-roles">Education</p>
            <img src="public/yellow_light.svg" class="dev-stars-roles">
            <p class="devs-roles">Guides</p>
          </div>
        </div>
      </div>

      <div class="form">
        <div class="form-block">
          <p class="form-txt">Weekly digest</p>
          <p class="form-txt-comment">Latest news in DAOs and Web3</p>
          <div class="form-setting">
            <input placeholder="Your email" class="form-style">
            <button class="form-btn">Subscribe</button>
          </div>
        </div>
      </div>
      

      <div class="sponsors">
        <div class="sponsors-txt-block">
          <p class="sponsors-txt">Backed by</p>
          <img class="sponsor-star-img" src="public/sponsor-star.svg">
        </div>
        <div class="sponsors-block">
          <div class="logos">
            <div class="logos-slide">
              <!-- Используем вычисляемое свойство infiniteLogos для бесконечного списка -->
              <img
                v-for="(logo, index) in infiniteLogos"
                :key="index"
                class="logos-img"
                :src="logo"
              />
            </div>
          </div>
        </div>
        <div class="sponsors-blockTwo">
          <div class="logos">
            <div class="logos-slideTwo">
              <!-- Используем вычисляемое свойство infiniteLogos для бесконечного списка -->
              <img
                v-for="(logo, index) in infiniteLogosTwo"
                :key="index"
                class="logos-img"
                :src="logo"
              />
            </div>
          </div>
        </div>
      </div>


      <div class="press-block">
        <div class="press-block-settings">
          <div class="press-txt-block-settings">
            <p class="press-txt">Press</p>
            <img class="press-img" src="public/press_star.svg">
          </div>
          <buton class="press-btn">
            <p class="press-btn-txt">See all</p>
            <img class="press_arrow" src="public/press_arrow.svg">
          </buton>
        </div>
      </div>
      <div class="press-cads-block">
        <div class="press-card-blue">
          <div style="height: auto;">
            <img class="logo-img" src="public/decrypt.svg">
            <p class="card-txt">Superdao Raises $10.5 Million to Build an 'All-in-One' DAO Platform</p>
            <p class="card-txt-comment">Superdao aims to make it easier for online communities to build and launch DAOs</p>
            <button class="press-cards-btn-read">
              <p class="press-cards-btn-read-txt">Read</p>
              <img class="press-cards-img-read" src="public/black_arrow.svg">
            </button>
          </div>
        </div>
        <div class="press-card-viol">
          <div style="height: auto;">
            <img class="logo-img" src="public/blockworks.svg">
            <p class="card-txt">The Y Combinator of Web3 Attracts Record Number of DAO Startups</p>
            <p class="card-txt-comment">DAOs and related startups made up an “overwhelming number of applicants” for a Web3 accelerator’s cohort this year</p>
            <button class="press-cards-btn-read">
              <p class="press-cards-btn-read-txt">Read</p>
              <img class="press-cards-img-read" src="public/black_arrow.svg">
            </button>
          </div>
        </div>
        <div class="press-card-yellow">
          <div style="height: auto;">
            <img class="logo-img" src="public/techcrunch.svg">
            <p class="card-txt">VC-backed DAO startups are racing to define what DAOs actually are</p>
            <p class="card-txt-comment">Not all 'decentralized autonomous organizations' are autonomous... or decentralized</p>
            <button class="press-cards-btn-read">
              <p class="press-cards-btn-read-txt">Read</p>
              <img class="press-cards-img-read" src="public/black_arrow.svg">
            </button>
          </div>
        </div>
        <buton class="press-btn-xs">
          <p class="press-btn-txt">See all</p>
          <img class="press_arrow" src="public/press_arrow.svg">
        </buton>
      </div>



      <div class="podcasts-block">
        <div v-if="isDesktop" class="podcast-star">
          <img class="podcast-star-img" src="public/podcasts_star.svg">
        </div>
        <div>
          <div >
            <div class="press-block-settings">
              <div v-if="isPhone" class="podcast-star">
                <img class="podcast-star-img" src="public/podcasts_star.svg">
              </div>
              <div v-if="isPhone" class="press-txt-block-settings">
                <p class="podc-txt">Podсasts</p>
              </div>
              <div v-if="isDesktop" class="press-txt-block-settings">
                <p class="press-txt">Podсasts</p>
              </div>
              <buton class="press-btn">
                <p class="press-btn-txt">See all</p>
                <img class="press_arrow" src="public/press_arrow.svg">
              </buton>
            </div>
            <div class="press-cads-block">
              <div class="press-card">
                <div style="height: auto;">
                  <img class="podcast-img" src="public/podcast1.svg">
                  <p class="podcast-txt">Understanding DAOs with Yury Lifshits</p>
                  <p class="podcast-txt-comment">The Pomp Podcast by Anthony Pompliano</p>
                  <button class="press-cards-btn-read">
                    <p class="podcast-cards-btn-read-txt">Listen</p>
                    <img class="press-cards-img-read" src="public/podcast_arrow.svg">
                  </button>
                </div>
              </div>
              <div class="press-card">
                <div style="height: auto;">
                  <img class="podcast-img" src="public/podcast2.svg">
                  <p class="podcast-txt">Everything You Need to Know About DAOs with Yury Lifshits from Superdao</p>
                  <p class="podcast-txt-comment">The Unstoppable Podcast by Josh Gordon</p>
                  <button class="press-cards-btn-read">
                    <p class="podcast-cards-btn-read-txt">Watch</p>
                    <img class="press-cards-img-read" src="public/podcast_arrow.svg">
                  </button>
                </div>
              </div>
              <div class="press-card">
                <div style="height: auto;">
                  <img class="podcast-img" src="public/podcast3.svg">
                  <p class="podcast-txt">Yury Lifshits - Superdao: The “Shopify” for DAOs</p>
                  <p class="podcast-txt-comment">Zima Red by Andrew Stainwold</p>
                  <button class="press-cards-btn-read">
                    <p class="podcast-cards-btn-read-txt">Listen</p>
                    <img class="podcast-cards-img-read" src="public/podcast_arrow.svg">
                  </button>
                </div>
              </div>
              <buton class="press-btn-xs">
                <p class="press-btn-txt">See all</p>
                <img class="press_arrow" src="public/press_arrow.svg">
              </buton>
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
      windowWidth: window.innerWidth,
      buttons: [
        { label: 'NFT membership', isActive: true },
        { label: 'Member directory', isActive: false },
        { label: 'Treasury', isActive: false },
        { label: 'Feed', isActive: false },
        { label: 'Governance', isActive: false },
        { label: 'App store', isActive: false }
      ],
      logos: [
        '/alliance.jpeg',
        '/digital.jpeg',
        '/oneblock.jpeg',
        '/fika.jpeg',
        '/pear.jpeg',
        '/shima.jpeg',
      ],
      logosTwo: [
        '/great.jpeg',
        '/norwest.jpeg',
        '/50.jpeg',
        '/circle.jpeg',
        '/protocol.jpeg',
        '/venturesouq.jpeg',
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
    },
    infiniteLogos() {
      return [...this.logos,...this.logos,...this.logos,...this.logos,...this.logos,...this.logos];
    },
    infiniteLogosTwo() {
      return [...this.logosTwo,...this.logosTwo,...this.logosTwo,...this.logosTwo,...this.logosTwo,...this.logosTwo,,...this.logosTwo,];
    },
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

.tools-block {
  height: 900px;
}

.video-img {
  width: 32px;
  height: 32px;
}

.video-txt {
  color: rgb(255, 207, 1);
  font-family: 'Montserrat';
  font-size: 20px;
  font-weight: 700;
  line-height: 36px;
  letter-spacing: 0px;
  text-align: left;
  height: auto;
  margin: 0px 0px 0px 12px;
}

.video-btn {
  width: 280px;
  height: 68px;
  border-radius: 16px;
  background: rgba(255, 207, 1, 0.15);
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 44px 0px 0px 0px;
}

.video-btn-navigation {
  display: flex;
  justify-content: center;
}

.works-txt {
  color: rgb(229, 229, 229);
  font-family: 'Russo One';
  font-size: 54px;
  font-weight: 400;
  line-height: 80px;
  letter-spacing: 0px;
  text-align: center;
  width: 315px;
  height: 80px;
  float: left;
  margin: 9px 32px 0px 64px;
}

.works-star-img {
  width: 55px;
  height: 43px;
  float: left;
}

.works-txt-navigation {
  margin: 190px 0px 0px 0px;
  height: auto;
  display: flex;
  justify-content: center;
}

.blockchain-blocks {
  box-sizing: border-box;
  border: 2px solid rgb(42, 55, 68);
  border-radius: 40px;
  background: rgb(18, 30, 40);
  width: 160px;
  height: 160px;
}

.blockchain-img {
  width: 160px;
  height: 160px;
}

.blockchain-txt {
  color: rgb(229, 229, 229);
  font-family: 'Montserrat';
  font-size: 22px;
  font-weight: 600;
  line-height: 40px;
  letter-spacing: 0px;
  text-align: center;
  height: 40px;
  margin: 16px 0px 0px 0px;
}

.blockchain-blocks-navigation {
  float: left;
  width: auto;
  height: auto;
}

.blockchain-blocks-display {
  display: flex;
  gap: 36px;
  margin: 44px 0px 0px 0px;
}

.container-works {
  display: flex;
  flex-direction: column;
  align-items: center;
  height: 528px;
}

.devs-img {
  width: 160px;
  height: 160px;
  border-radius: 42px;
}

.devs-nav-one {
  height: auto;
  float: left;
  display: flex;
  gap: 25px;
  margin: 0px 25px 0px 0px;
}

.devs-nav-two {
  height: auto;
  float: left;
  display: flex;
  gap: 25px;
}

.devs-txt {
  color: rgb(229, 229, 229);
  font-family: 'Russo One';
  font-size: 54px;
  font-weight: 400;
  line-height: 80px;
  letter-spacing: 0px;
  text-align: center;
  width: 501px;
  height: 80px;
}

.container-devs {
  display: flex;
  flex-direction: column;
  align-items: center;
  height: 80px;
  margin: 200px 0px 0px 0px;
}

.container-devs-two {
  height: 160px;
  margin: 44px 0px 0px 0px;
  display: flex;
  justify-content: center;
}

.devs-roles {
  color: rgb(255, 255, 255);
  font-family: 'Russo One';
  font-size: 40px;
  font-weight: 700;
  line-height: 50px;
  letter-spacing: 0px;
  text-align: left;
  height: 50px;
  width: auto;
  float: left;
}

.dev-stars-roles {
  width: 30px;
  height: 30px;
  float: left;
}

.devs-roles-block-navigation {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 28px;
  align-items: center;
  height: auto;
  margin: 48px 0px 0px 0px;
}

.devs-roles-block {
  height: auto;
  width: 900px;
}

.roles-navigation {
  display: flex;
  height: auto;
  justify-content: center;
}

.form {
  height: auto;
  display: flex;
  justify-content: center;
  margin: 214px 0px 0px 0px;
}

.form-block {
  background-image: url(form.png);
  width: 1140px;
  height: 390px;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}

.form-txt {
  color: rgb(255, 255, 255);
  font-family: 'Russo One';
  font-size: 54px;
  font-weight: 700;
  line-height: 80px;
  letter-spacing: 0px;
  text-align: left;
  width: 412px;
  height: 80px;
}

.form-txt-comment {
  color: rgb(154, 175, 196);
  font-family: 'Montserrat';
  font-size: 36px;
  font-weight: 600;
  line-height: 44px;
  letter-spacing: 0px;
  text-align: left;
  width: 580px;
  height: 44px;
  margin: 26px 0px 68px 0px;
}

.form-style {
  width: 506px;
  height: 68px;
  border: 2px solid rgb(42, 55, 68);
  border-radius: 16px;
  background: rgb(18, 30, 40);
  outline: none;
  color: rgb(255, 255, 255);
  font-family: 'Montserrat';
  font-size: 20px;
  font-weight: 600;
  line-height: 24px;
  letter-spacing: 0%;
  text-align: left;
  padding: 0px 0px 0px 28px;
}

::placeholder {
  color: rgb(61, 76, 91);
}

.form-btn {
  color: rgb(16, 21, 26);
  font-family: 'Montserrat';
  font-size: 20px;
  font-weight: 600;
  line-height: 36px;
  letter-spacing: 0px;
  text-align: center;
  border-radius: 16px;
  width: 175px;
  height: 68px;
  background: rgb(206, 170, 255);
  margin: 0px 0px 0px 24px;
}

.form-setting {
  display: block;
  height: auto;
  width: auto;
}

.logos-img {
  height: 132px;
  width: auto;
  margin: 0 20px;
  border-radius: 30px;
}


.sponsors {
  width: 100%;
  overflow: hidden;
  height: auto;
}

.sponsors-block {
  width: 100%;
  height: 132px;
  overflow: hidden;
  position: relative;
  margin: 56px 0px 0px 0px;
}

.sponsors-blockTwo {
  width: 100%;
  height: 132px;
  overflow: hidden;
  position: relative;
  margin: 40px 0px 0px 0px;
}

.logos-slide {
  display: inline-block;
  animation: slide 100s linear infinite;
}

.logos-slideTwo {
  display: inline-block;
  animation: slide 115s linear infinite;
}

.logo {
  display: inline-block;
  height: 100%;
  width: auto;
  vertical-align: middle;
  margin-right: 10px; /* Добавлено для небольшого отступа между логотипами */
}

@keyframes slide {
  from {
    transform: translateX(0);
  }
  to {
    transform: translateX(-100%);
  }
}

.logos {
  overflow: hidden;
  height: 212px;
  background: none;
  white-space: nowrap;
  position: relative;
}

.logos:before,
.logos:after {
  position: absolute;
  top: 0;
  width: 250px;
  height: 132px;
  content: "";
  z-index: 2;
}

.logos:before {
  left: 0;
  background: linear-gradient(90.00deg, rgb(16, 21, 26),rgba(16, 21, 26, 0) 100%);
}

.logos:after {
  right: 0;
  background: linear-gradient(270.00deg, rgb(16, 21, 26) 0%,rgba(16, 21, 26, 0) 100%);;
}

.sponsors-txt {
  color: rgb(229, 229, 229);
  font-family: 'Russo One';
  font-size: 54px;
  font-weight: 400;
  line-height: 80px;
  letter-spacing: 0px;
  text-align: center;
  width: 279px;
  height: 80px;
  float: left;
  margin: 34px 47px 0px 94px;
}

.sponsors-txt-block {
  width: auto;
  height: 114px;
  display: flex;
  justify-content: center;
  margin: 166px 0px 0px 0px;
  
}

.sponsor-star-img {
  width: 65px;
  height: 50px;
  float: left;
}

.press-block {
  height: auto;
  display: flex;
  justify-content: center;
  margin: 163px 0px 0px 0px;
}

.press-block-settings {
  width: 1139px;
  height: 117px;
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
}

.press-txt {
  color: rgb(229, 229, 229);
  font-family: 'Russo One';
  font-size: 54px;
  font-weight: 400;
  line-height: 80px;
  letter-spacing: 0px;
  text-align: left;
  width: 158px;
  height: 80px;
  float: left;
  margin: 37px 35px 0px 0px;
}

.press-txt-block-settings {
  height: 117px;
}

.press-img {
  width: 58px;
  height: 59px;
  float: left;
}

.press-btn-txt {
  color: rgb(131, 149, 167);
  font-family: 'Montserrat';
  font-size: 22px;
  font-weight: 700;
  line-height: 40px;
  letter-spacing: 0px;
  width: 75px;
  height: 40px;
}

.press_arrow {
  width: 15px;
  height: 11.67px;
  margin: 0px 0px 0px 10px;
}

.press-btn {
  width: 100px;
  height: 40px;
  display: flex;
  align-items: center;
  transition: 1s;
  position: relative; /* Для позиционирования псевдоэлемента */
}


.press-btn:hover::after {
  width: 100%; /* Полная ширина при наведении */
}

.press-btn::after {
  content: '';
  position: absolute;
  left: 0; /* Начинаем с левого края */
  bottom: 5px; /* Отступ как в text-underline-offset */
  width: 0; /* Начальная ширина */
  height: 2px; /* Толщина линии */
  background: rgb(131, 149, 167); /* Цвет линии */
  transition: width 0.3s ease; /* Анимация расширения */
}

.press-cads-block {
  display: flex;
  justify-content: center;
  margin: 32px 0px 0px 0px;
  height: auto;
  gap: 28px;
}

.press-card-blue {
  width: 361px;
  height: 382px;
  border-radius: 20px;
  background: rgb(119, 230, 255);
  float: left;
  display: flex;
  justify-content: center;
  align-items: center;
}

.press-card-viol {
  width: 361px;
  height: 382px;
  border-radius: 20px;
  background: #E2C1F9;
  float: left;
  display: flex;
  justify-content: center;
  align-items: center;
}

.press-card-yellow {
  width: 361px;
  height: 382px;
  border-radius: 20px;
  background: #DBE268;
  float: left;
  display: flex;
  justify-content: center;
  align-items: center;
}

.logo-img {
  width: 120px;
  height: 39.92px;
}

.card-txt {
  color: rgb(16, 21, 26);
  font-family: 'Montserrat';
  font-size: 22px;
  font-weight: 700;
  line-height: 30px;
  letter-spacing: 0px;
  text-align: left;
  width: 305px;
  height: 90px;
  margin: 20px 0px 12px 0px;
}

.card-txt-comment {
  color: rgb(16, 21, 26);
  font-family: 'Montserrat';
  font-size: 17px;
  font-weight: 600;
  line-height: 29px;
  letter-spacing: 0px;
  text-align: left;
  width: 305px;
  height: 116px;
  margin: 0px 0px 20px 0px;
}

.press-cards-btn-read {
  display: flex;
  height: auto;
  align-items: center;
  padding: 0px;
}

.press-cards-btn-read-txt {
  width: 43px;
  height: 20px;
  color: rgb(16, 21, 26);
  font-family: 'Montserrat';
  font-size: 16px;
  font-weight: 700;
  line-height: 20px;
  letter-spacing: 0%;
  text-align: left;
  float: left;
}

.press-cards-img-read {
  width: 13px;
  height: 12px;
  float: left;
  margin: 0px 0px 0px 8px;
}

.press-btn-xs {
  display: none;
}

.podcast-star-img {
  width: 61px;
  height: 54.17px;
}

.podcast-star {
  float: left;
  height: auto;
  margin: 0px 32px 0px 0px;
}

.press-card {
  box-sizing: border-box;
  border: 2px solid rgb(42, 55, 68);
  border-radius: 20px;
  backdrop-filter: blur(4px);
  background: rgb(18, 30, 40);
  width: 361px;
  height: 334px;
  display: flex;
  justify-content: center;
  align-items: center;

}

.podcast-img {
  width: 50px;
  height: 50px;
}

.podcast-txt {
  color: rgb(255, 255, 255);
  font-family: 'Montserrat';
  font-size: 20px;
  font-weight: 700;
  line-height: 28px;
  letter-spacing: 0px;
  text-align: left;
  width: 301px;
  height: 84px;
  margin: 21px 0px 18px 0px;
}

.podcast-txt-comment {
  color: rgb(226, 226, 226);
  font-family: 'Montserrat';
  font-size: 17px;
  font-weight: 600;
  line-height: 21px;
  letter-spacing: 0px;
  text-align: left;
  opacity: 0.8;
  height: 47px;
  width: 301px;
  margin: 0px 0px 34px 0px;
}

.podcast-cards-btn-read-txt {
  color: rgb(255, 255, 255);
  font-family: 'Montserrat';
  font-size: 16px;
  font-weight: 700;
  line-height: 20px;
  letter-spacing: 0px;
  text-align: left;
  width: 55px;
  height: 19px;
}

.podcast-cards-img-read {
  width: 13px;
  height: 10px;
}

.podcasts-block {
  display: flex;
  height: 484px;
  margin: 168px 100px 0px 0px;
  justify-content: center;
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

  .tools-block {
    height: 600px;
  }

  .video-img {
    width: 28px;
    height: 28px;
  }

  .video-txt {
    color: rgb(255, 207, 1);
    font-family: 'Montserrat';
    font-size: 17px;
    font-weight: 700;
    line-height: 36px;
    letter-spacing: 0px;
    text-align: left;
    height: auto;
    margin: 0px 0px 0px 12px;
  }

  .video-btn {
    width: 240px;
    height: 56px;
    border-radius: 12px;
    background: rgba(255, 207, 1, 0.15);
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 32px 0px 0px 0px;
  }

  .video-btn-navigation {
    display: flex;
    justify-content: center;
  }

  .works-txt {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 36px;
    font-weight: 400;
    line-height: 43px;
    letter-spacing: 0px;
    text-align: center;
    width: 210px;
    height: 43px;
    float: left;
    margin: 10px 23px 0px 46px;
  }

  .works-star-img {
    width: 35px;
    height: 27.36px;
    float: left;
  }

  .works-txt-navigation {
    margin: 100px 0px 0px 0px;
    height: auto;
    display: flex;
    justify-content: center;
  }

  .blockchain-blocks {
    box-sizing: border-box;
    border: 2px solid rgb(42, 55, 68);
    border-radius: 24px;
    background: rgb(18, 30, 40);
    width: 100px;
    height: 100px;
  }

  .blockchain-img {
    width: 100px;
    height: 100px;
  }

  .blockchain-txt {
    color: rgb(229, 229, 229);
    font-family: 'Montserrat';
    font-size: 14px;
    font-weight: 600;
    line-height: 24px;
    letter-spacing: 0px;
    text-align: center;
    height: 24px;
    margin: 12px 0px 0px 0px;
  }

  .blockchain-blocks-navigation {
    float: left;
    width: auto;
    height: auto;
  }

  .blockchain-blocks-display {
    display: flex;
    gap: 27px;
    margin: 34px 0px 0px 0px;
  }

  .container-works {
    display: flex;
    flex-direction: column;
    align-items: center;
    height: 325px;

  }

  .devs-img {
    width: 112px;
    height: 112px;
    border-radius: 30px;
  }

  .devs-nav-one {
    height: auto;
    float: left;
    display: flex;
    gap: 27px;
    margin: 0px 27px 0px 0px;
  }

  .devs-nav-two {
    height: auto;
    float: left;
    display: flex;
    gap: 27px;
  }

  .devs-txt {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 36px;
    font-weight: 400;
    line-height: 43px;
    letter-spacing: 0px;
    text-align: center;
    width: 334px;
    height: 43px;
  }

  .container-devs {
    display: flex;
    flex-direction: column;
    align-items: center;
    height: 80px;
    margin: 100px 0px 0px 0px;
  }

  .container-devs-two {
    height: 112px;
    margin: 0px 0px 0px 0px;
    display: flex;
    justify-content: center;
  }

  .devs-roles {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 32px;
    font-weight: 700;
    line-height: 40px;
    letter-spacing: 0px;
    text-align: left;
    height: 40px;
    width: auto;
    float: left;
  }

  .dev-stars-roles {
    width: 25px;
    height: 25px;
    float: left;
  }

  .devs-roles-block-navigation {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 16px;
    align-items: center;
    height: auto;
    margin: 37px 0px 0px 0px;
  }

  .devs-roles-block {
    height: auto;
    width: 738px;
  }

  .roles-navigation {
    display: flex;
    height: auto;
    justify-content: center;
  }

  .form {
    height: auto;
    display: flex;
    justify-content: center;
    margin: 100px 0px 0px 0px;
  }

  .form-block {
    background-image: url(formS.png);
    width: 736px;
    height: 293px;
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
  }

  .form-txt {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 36px;
    font-weight: 700;
    line-height: 45px;
    letter-spacing: 0px;
    text-align: center;
    width: 258px;
    height: 43px;
  }

  .form-txt-comment {
    color: rgb(154, 175, 196);
    font-family: 'Montserrat';
    font-size: 28px;
    font-weight: 600;
    line-height: 40px;
    letter-spacing: 0px;
    text-align: left;
    width: 451px;
    height: 40px;
    margin: 18px 0px 48px 0px;
  }

  .form-style {
    width: 324px;
    height: 60px;
    border: 2px solid rgb(42, 55, 68);
    border-radius: 16px;
    background: rgb(18, 30, 40);
    outline: none;
    color: rgb(255, 255, 255);
    color: rgb(61, 76, 91);
    font-family: 'Montserrat';
    font-size: 20px;
    font-weight: 600;
    line-height: 24px;
    letter-spacing: 0%;
    text-align: left;
    padding: 0px 0px 0px 24px;
  }

  ::placeholder {
    color: rgb(61, 76, 91);
  }

  .form-btn {
    color: rgb(16, 21, 26);
    font-family: 'Montserrat';
    font-size: 20px;
    font-weight: 600;
    line-height: 36px;
    letter-spacing: 0px;
    text-align: center;
    border-radius: 16px;
    width: 167px;
    height: 60px;
    background: rgb(206, 170, 255);
    margin: 0px 0px 0px 24px;
  }
  
  .form-setting {
    display: block;
    height: auto;
    width: auto;
  }

  .logos-img {
    height: 88px;
    width: auto;
    margin: 0 12px;
    border-radius: 20px;
  }


  .sponsors {
    width: 100%;
    overflow: hidden;
    height: auto;
  }

  .sponsors-block {
    width: 100%;
    height: 88px;
    overflow: hidden;
    position: relative;
    margin: 38px 0px 0px 0px;
  }

  .sponsors-blockTwo {
    width: 100%;
    height: 88px;
    overflow: hidden;
    position: relative;
    margin: 24px 0px 0px 0px;
  }

  .logos-slide {
    display: inline-block;
    animation: slide 100s linear infinite;
  }

  .logo {
    display: inline-block;
    height: 100%;
    width: auto;
    vertical-align: middle;
    margin-right: 10px; /* Добавлено для небольшого отступа между логотипами */
  }

  @keyframes slide {
    from {
      transform: translateX(0);
    }
    to {
      transform: translateX(-100%);
    }
  }

  .logos {
    overflow: hidden;
    height: 88px;
    background: none;
    white-space: nowrap;
    position: relative;
  }

  .logos:before,
  .logos:after {
    position: absolute;
    top: 0;
    width: 250px;
    height: 88px;
    content: "";
    z-index: 2;
  }

  .logos:before {
    left: 0;
    background: linear-gradient(90.00deg, rgb(16, 21, 26),rgba(16, 21, 26, 0) 100%);
  }

  .logos:after {
    right: 0;
    background: linear-gradient(270.00deg, rgb(16, 21, 26) 0%,rgba(16, 21, 26, 0) 100%);;
  }

  .sponsors-txt {
    color: rgb(255, 255, 255);
    font-family:'Russo One';
    font-size: 36px;
    font-weight: 400;
    line-height: 43px;
    letter-spacing: 0px;
    text-align: center;
    width: 186px;
    height: 43px;
    float: left;
    margin: 20px 30px 0px 60px;
  }

  .sponsors-txt-block {
    width: auto;
    height: 63px;
    display: flex;
    justify-content: center;
    margin: 79px 0px 0px 0px;
    
  }

  .sponsor-star-img {
    width: 53px;
    height: 40.77px;
    float: left;
  }

  .logos-slideTwo {
    display: inline-block;
    animation: slide 115s linear infinite;
  }

  .press-block {
    height: auto;
    display: flex;
    justify-content: center;
    margin: 69px 0px 0px 0px;
  }

  .press-block-settings {
    width: 735px;
    height: 75px;
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
  }

  .press-txt {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 36px;
    font-weight: 400;
    line-height: 43px;
    letter-spacing: 0px;
    text-align: left;
    width: 105px;
    height: 43px;
    float: left;
    margin: 30px 21px 0px 0px;
  }

  .press-txt-block-settings {
    height: 73px;
  }

  .press-img {
    width: 45px;
    height: 45.78px;
    float: left;
  }

  .press-btn-txt {
    color: rgb(131, 149, 167);
    font-family: 'Montserrat';
    font-size: 18px;
    font-weight: 700;
    line-height: 32px;
    letter-spacing: 0px;
    width: 62px;
    height: 32px;
  }

  .press_arrow {
    width: 13px;
    height: 10px;
    margin: 0px 0px 0px 8px;
  }

  .press-btn {
    width: 83px;
    height: 32px;
    display: flex;
    align-items: center;
    transition: 1s;
    position: relative; /* Для позиционирования псевдоэлемента */
  }


  .press-btn:hover::after {
    width: 100%; /* Полная ширина при наведении */
  }

  .press-btn::after {
    content: '';
    position: absolute;
    left: 0; /* Начинаем с левого края */
    bottom: 2px; /* Отступ как в text-underline-offset */
    width: 0; /* Начальная ширина */
    height: 2px; /* Толщина линии */
    background: rgb(131, 149, 167); /* Цвет линии */
    transition: width 0.3s ease; /* Анимация расширения */
  }

  .press-cads-block {
    display: flex;
    justify-content: center;
    margin: 30px 0px 0px 0px;
    height: auto;
    gap: 20px;
  }

  .press-card-blue {
    width: 232px;
    height: 335px;
    border-radius: 20px;
    background: rgb(119, 230, 255);
    float: left;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .press-card-viol {
    width: 232px;
    height: 335px;
    border-radius: 20px;
    background: #E2C1F9;
    float: left;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .press-card-yellow {
    width: 232px;
    height: 335px;
    border-radius: 20px;
    background: #DBE268;
    float: left;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .logo-img {
    width: 91px;
    height: 30.28px;
  }

  .card-txt {
    color: rgb(16, 21, 26);
    font-family: 'Montserrat';
    font-size: 18px;
    font-weight: 700;
    line-height: 24px;
    letter-spacing: 0px;
    text-align: left;
    width: 192px;
    height: 96px;
    margin: 12px 0px 8px 0px;
  }

  .card-txt-comment {
    color: rgb(16, 21, 26);
    font-family: 'Montserrat';
    font-size: 13px;
    font-weight: 600;
    line-height: 22px;
    letter-spacing: 0px;
    text-align: left;
    width: 192px;
    height: 110px;
    margin: 0px 0px 16px 0px;
  }

  .press-cards-btn-read {
    display: flex;
    height: auto;
    align-items: center;
    padding: 0px;
  }

  .press-cards-btn-read-txt {
    width: 33px;
    height: 15px;
    color: rgb(16, 21, 26);
    font-family: 'Montserrat';
    font-size: 12px;
    font-weight: 700;
    line-height: 15px;
    letter-spacing: 0%;
    text-align: left;
    float: left;
  }

  .press-cards-img-read {
    width: 10px;
    height: 7.5px;
    float: left;
    margin: 0px 0px 0px 6px;
  }

  .press-btn-xs {
    display: none;
  }

  .podcast-star-img {
    width: 44px;
    height: 39.07px;
  }

  .podcast-star {
    float: left;
    height: auto;
    margin: 0px 29px 0px 0px;
  }

  .press-card {
    box-sizing: border-box;
    border: 2px solid rgb(42, 55, 68);
    border-radius: 20px;
    backdrop-filter: blur(4px);
    background: rgb(18, 30, 40);
    width: 232px;
    height: 284px;
    display: flex;
    justify-content: center;
    align-items: center;

  }

  .podcast-img {
    width: 40px;
    height: 40px;
  }

  .podcast-txt {
    color: rgb(255, 255, 255);
    font-family: 'Montserrat';
    font-size: 17px;
    font-weight: 700;
    line-height: 24px;
    letter-spacing: 0px;
    text-align: left;
    width: 192px;
    height: 96px;
    margin: 16px 0px 12px 0px;
  }

  .podcast-txt-comment {
    color: rgb(226, 226, 226);
    font-family: 'Montserrat';
    font-size: 14px;
    font-weight: 600;
    line-height: 24px;
    letter-spacing: 0px;
    text-align: left;
    opacity: 0.8;
    height: 44px;
    width: 192px;
    margin: 0px 0px 17px 0px;
  }

  .podcast-cards-btn-read-txt {
    color: rgb(255, 255, 255);
    font-family: 'Montserrat';
    font-size: 12px;
    font-weight: 700;
    line-height: 15px;
    letter-spacing: 0px;
    text-align: left;
    width: 42px;
    height: 15px;
  }

  .podcast-cards-img-read {
    width: 10px;
    height: 7.5px;
  }

  .podcasts-block {
    display: flex;
    height: 368px;
    margin: 88px 70px 0px 0px;
    justify-content: center;
  }
}

@media (min-width: 360px) and (max-width: 768px) {
  * {
    margin: 0px;
    height: 0px;
  }

  .show-burder-logos {
    width: 140px;
    height: 23.24px;
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
    height: auto;
    width: 100%;
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
    margin: 65px 0px 0px 0px;
    height: 75px;
  }

  .tools-block {
    height: 300px;
  }

  .video-img {
    width: 24px;
    height: 24px;
  }

  .video-txt {
    color: rgb(255, 207, 1);
    font-family: 'Montserrat';
    font-size: 15px;
    font-weight: 700;
    line-height: 36px;
    letter-spacing: 0px;
    text-align: left;
    height: auto;
    margin: 0px 0px 0px 8px;
  }

  .video-btn {
    width: 190px;
    height: 44px;
    border-radius: 8px;
    background: rgba(255, 207, 1, 0.15);
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 24px 0px 0px 0px;
  }

  .video-btn-navigation {
    display: flex;
    justify-content: center;
  }

  .works-txt {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 28px;
    font-weight: 400;
    line-height: 36px;
    letter-spacing: 0px;
    text-align: center;
    width: 163px;
    height: 36px;
    float: left;
    margin: 13px 5px 0px 10px;
  }

  .works-star-img {
    width: 26px;
    height: 20.33px;
    float: left;
  }

  .works-txt-navigation {
    margin: 135px 0px 0px 0px;
    height: auto;
    display: flex;
    justify-content: center;
  }

  .blockchain-blocks {
    box-sizing: border-box;
    border: 2px solid rgb(42, 55, 68);
    border-radius: 24px;
    background: rgb(18, 30, 40);
    width: 100px;
    height: 100px;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .blockchain-img {
    width: 100px;
    height: 100px;
  }

  .blockchain-txt {
    color: rgb(229, 229, 229);
    font-family: 'Montserrat';
    font-size: 14px;
    font-weight: 600;
    line-height: 24px;
    letter-spacing: 0px;
    text-align: center;
    height: 24px;
    margin: 12px 0px 0px 0px;
  }

  .blockchain-blocks-navigation {
    float: left;
    width: auto;
    height: auto;
  }

  .blockchain-blocks-display {
    display: flex;
    gap: 20px;
    margin: 24px 0px 0px 0px;
    flex-direction: column;
  }

  .container-works {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .blockchain-blocks-display-navigation {
    height: auto;
    display: flex;
    gap: 20px;
    margin: 0px 0px 0px 0px;
  }

  .blockchain-blocks-display-navigation-first {
    height: auto;
    display: flex;
    gap: 20px;
    margin: 20px 0px 0px 0px;
  }

  .devs-img {
    width: 112px;
    height: 112px;
    border-radius: 33px;
  }

  .devs-nav-one {
    height: auto;
    float: left;
    display: flex;
    gap: 10px;
    margin: 33px 10px 10px 0px;
  }

  .devs-nav-two {
    height: auto;
    float: left;
    display: flex;
    gap: 10px;
  }

  .devs-txt {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 28px;
    font-weight: 400;
    line-height: 36px;
    letter-spacing: 0px;
    text-align: center;
    width: 260px;
    height: 36px;
  }

  .container-devs {
    display: flex;
    flex-direction: column;
    align-items: center;
    height: 70px;
    margin: 80px 0px 0px 0px;
  }

  .container-devs-two {
    height: 175px;
    margin: 0px 0px 0px 0px;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
  }

  .devs-roles {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 18px;
    font-weight: 700;
    line-height: 23px;
    letter-spacing: 0px;
    text-align: left;
    height: 23px;
    width: auto;
    float: left;
  }

  .dev-stars-roles {
    width: 13px;
    height: 13px;
    float: left;
  }

  .devs-roles-block-navigation {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px;
    align-items: center;
    height: auto;
    margin: 73px 0px 0px 0px;
  }

  .devs-roles-block {
    height: auto;
    width: 362px;
  }

  .roles-navigation {
    display: flex;
    height: auto;
    justify-content: center;
  } 

  .form {
    height: auto;
    display: flex;
    justify-content: center;
    margin: 80px 0px 0px 0px;
  }

  .form-block {
    box-sizing: border-box;
    border: 1px solid rgb(42, 55, 68);
    border-radius: 22px;
    background: rgb(20, 33, 45);
    width: 328px;
    height: 280px;
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
  }

  .form-txt {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 28px;
    font-weight: 400;
    line-height: 36px;
    letter-spacing: 0px;
    text-align: center;
    width: 200px;
    height: 36px;
  }

  .form-txt-comment {
    color: rgb(154, 175, 196);
    font-family: 'Montserrat';
    font-size: 19px;
    font-weight: 600;
    line-height: 28px;
    letter-spacing: 0px;
    text-align: center;
    width: 280px;
    height: 56px;
    margin: 8px 0px 24px 0px;
  }

  .form-style {
    width: 279px;
    height: 44px;
    border: 1px solid rgb(42, 55, 68);
    border-radius: 10px;
    background: rgb(18, 30, 40);
    outline: none;
    color: rgb(61, 76, 91);
    font-family: 'Montserrat';
    font-size: 14px;
    font-weight: 600;
    line-height: 18px;
    letter-spacing: 0%;
    text-align: left;
    padding: 0px 0px 0px 18px;
  }

  ::placeholder {
    color: rgb(61, 76, 91);
  }

  .form-btn {
    color: rgb(16, 21, 26);
    font-family: 'Montserrat';
    font-size: 14px;
    font-weight: 600;
    line-height: 24px;
    letter-spacing: 0px;
    text-align: center;
    border-radius: 10px;
    background: rgb(226, 193, 249);
    margin: 16px 0px 0px 0px;
    width: 280px;
    height: 44px;
  }

  .form-setting {
    display: flex;
    flex-direction: column;
    align-items: center;
    height: auto;
    width: auto;
  }

  .logos-img {
    height: 58px;
    width: auto;
    margin: 0 16px;
    border-radius: 12px;
  }


  .sponsors {
    width: 100%;
    overflow: hidden;
    height: auto;
  }

  .sponsors-block {
    width: 100%;
    height: 58px;
    overflow: hidden;
    position: relative;
    margin: 24px 0px 0px 0px;
  }

  .sponsors-blockTwo {
    width: 100%;
    height: 58px;
    overflow: hidden;
    position: relative;
    margin: 24px 0px 0px 0px;
  }

  .logos-slide {
    display: inline-block;
    animation: slide 100s linear infinite;
  }

  .logo {
    display: inline-block;
    height: 100%;
    width: auto;
    vertical-align: middle;
    margin-right: 10px; /* Добавлено для небольшого отступа между логотипами */
  }

  @keyframes slide {
    from {
      transform: translateX(0);
    }
    to {
      transform: translateX(-100%);
    }
  }

  .logos {
    overflow: hidden;
    height: 58px;
    background: none;
    white-space: nowrap;
    position: relative;
  }

  .logos:before,
  .logos:after {
    position: absolute;
    top: 0;
    width: 85px;
    height: 58px;
    content: "";
    z-index: 2;
  }

  .logos:before {
    left: 0;
    background: linear-gradient(90.00deg, rgb(16, 21, 26),rgba(16, 21, 26, 0) 100%);
  }

  .logos:after {
    right: 0;
    background: linear-gradient(270.00deg, rgb(16, 21, 26) 0%,rgba(16, 21, 26, 0) 100%);;
  }

  .sponsors-txt {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 28px;
    font-weight: 400;
    line-height: 36px;
    letter-spacing: 0px;
    text-align: center;
    width: 145px;
    height: 36px;
    float: left;
    margin: 15px 20px 0px 40px;
  }

  .sponsors-txt-block {
    width: auto;
    height: 63px;
    display: flex;
    justify-content: center;
    margin: 65px 0px 0px 0px;
    
  }

  .sponsor-star-img {
    width: 33px;
    height: 25.38px;
    float: left;
  }

  .logos-slideTwo {
    display: inline-block;
    animation: slide 115s linear infinite;
  }

  .press-block {
    height: auto;
    display: flex;
    justify-content: center;
    margin: 64px 0px 0px 0px;
  }

  .press-block-settings {
    width: 100%;
    height: 52px;
    display: flex;
    justify-content: center;
    align-items: flex-start;
  }

  .press-txt {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 28px;
    font-weight: 400;
    line-height: 36px;
    letter-spacing: 0px;
    text-align: center;
    width: 82px;
    height: 36px;
    float: left;
    margin: 16px 8px 0px 16px;
  }

  .press-txt-block-settings {
    height: 52px;
  }

  .press-img {
    width: 31.84px;
    height: 32.39px;
    float: left;
  }

  .press-btn-txt {
    color: rgb(131, 149, 167);
    font-family: 'Montserrat';
    font-size: 18px;
    font-weight: 700;
    line-height: 32px;
    letter-spacing: 0px;
    width: 62px;
    height: 32px;
  }

  .press_arrow {
    width: 13px;
    height: 10px;
    margin: 0px 0px 0px 8px;
  }

  .press-btn {
    width: 83px;
    height: 32px;
    display: none;
    align-items: center;
    transition: 1s;
    position: relative; /* Для позиционирования псевдоэлемента */
  }


  .press-btn:hover::after {
    width: 100%; /* Полная ширина при наведении */
  }

  .press-btn::after {
    content: '';
    position: absolute;
    left: 0; /* Начинаем с левого края */
    bottom: 2px; /* Отступ как в text-underline-offset */
    width: 0; /* Начальная ширина */
    height: 2px; /* Толщина линии */
    background: rgb(131, 149, 167); /* Цвет линии */
    transition: width 0.3s ease; /* Анимация расширения */
  }

  .press-cads-block {
    display: flex;
    margin: 24px 0px 0px 0px;
    height: auto;
    gap: 16px;
    flex-direction: column;
    align-items: center;
  }

  .press-card-blue {
    width: 328px;
    height: 262px;
    border-radius: 20px;
    background: rgb(119, 230, 255);
    float: none;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .press-card-viol {
    width: 328px;
    height: 262px;
    border-radius: 20px;
    background: #E2C1F9;
    float: none;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .press-card-yellow {
    width: 328px;
    height: 262px;
    border-radius: 20px;
    background: #DBE268;
    float: none;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .logo-img {
    width: 105px;
    height: 34.93px;
  }

  .card-txt {
    color: rgb(16, 21, 26);
    font-family: 'Montserrat';
    font-size: 18px;
    font-weight: 700;
    line-height: 24px;
    letter-spacing: 0px;
    text-align: left;
    width: 288px;
    height: 72px;
    margin: 12px 0px 8px 0px;
  }

  .card-txt-comment {
    color: rgb(16, 21, 26);
    font-family: 'Montserrat';
    font-size: 13px;
    font-weight: 600;
    line-height: 22px;
    letter-spacing: 0px;
    text-align: left;
    width: 288px;
    height: 66px;
    margin: 0px 0px 19px 0px;
  }

  .press-cards-btn-read {
    display: flex;
    height: auto;
    align-items: center;
    padding: 0px;
  }

  .press-cards-btn-read-txt {
    width: 38px;
    color: rgb(16, 21, 26);
    font-family: 'Montserrat';
    font-size: 14px;
    font-weight: 700;
    line-height: 17px;
    letter-spacing: 0%;
    text-align: left;
    float: left;
  }

  .press-cards-img-read {
    width: 11.05px;
    height: 8.5px;
    float: left;
    margin: 0px 0px 0px 6px;
  }

  .press-btn-xs {
    display: flex;
    align-items: center;
    margin: 40px 0px 0px 0px;
  }

  .podcast-star-img {
    width: 32px;
    height: 28.42px;
  }

  .podcast-star {
    float: left;
    height: auto;
    margin: 0px 20px 0px 0px;
  }

  .press-card {
    box-sizing: border-box;
    border: 2px solid rgb(42, 55, 68);
    border-radius: 20px;
    backdrop-filter: blur(4px);
    background: rgb(18, 30, 40);
    width: 328px;
    height: 260px;
    display: flex;
    justify-content: center;
    align-items: center;

  }

  .podcast-img {
    width: 40px;
    height: 40px;
  }

  .podcast-txt {
    color: rgb(255, 255, 255);
    font-family: 'Montserrat';
    font-size: 17px;
    font-weight: 700;
    line-height: 24px;
    letter-spacing: 0px;
    text-align: left;
    width: 288px;
    height: 72px;
    margin: 16px 0px 12px 0px;
  }

  .podcast-txt-comment {
    color: rgb(226, 226, 226);
    font-family: 'Montserrat';
    font-size: 14px;
    font-weight: 600;
    line-height: 24px;
    letter-spacing: 0px;
    text-align: left;
    opacity: 0.8;
    height: 44px;
    width: 288px;
    margin: 0px 0px 17px 0px;
  }

  .podcast-cards-btn-read-txt {
    color: rgb(255, 255, 255);
    font-family: 'Montserrat';
    font-size: 12px;
    font-weight: 700;
    line-height: 15px;
    letter-spacing: 0px;
    text-align: left;
    width: 42px;
    height: 15px;
  }

  .podcast-cards-img-read {
    width: 10px;
    height: 7.5px;
  }

  .podcasts-block {
    display: flex;
    height: 390px;
    width: 100%;
    margin: 88px 70px 0px 0px;
    justify-content: center;
  }

  .podc-txt {
    color: rgb(255, 255, 255);
    font-family: 'Russo One';
    font-size: 28px;
    font-weight: 400;
    line-height: 36px;
    letter-spacing: 0px;
    text-align: center;
    width: 133px;
    height: 36px;
    float: left;
    margin: 9px 40px 0px 0px;
  }
}
</style>