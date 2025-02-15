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
                <input type="checkbox" id="burger-checkbox" class="burger-checkbox">
                <label for="burger-checkbox" class="burger">
                  <span></span>
                </label>
                <ul class="menu-list">
                  <li><a href="" class="menu-item">Главная</a></li>
                  <li><a href="" class="menu-item">О нас</a></li>
                  <li><a href="" class="menu-item">Команда</a></li>
                  <li><a href="" class="menu-item">Контакты</a></li>
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
    display: grid;
    gap: 12px;
    padding: 42px 0;
    margin: 0;
    background: orange;
    list-style-type: none;
    transform: translateX(-100%);
    transition: .3s;
    width: 100%;
    height: 100%;
  }
  .menu-item {
    display: block;
    padding: 8px;
    color: white;
    font-size: 18px;
    text-align: center;
    text-decoration: none;
  }
  .menu-item:hover {
    background: rgba(255,255,255,.2)
  }
  .burger-checkbox:checked ~ .menu-list {
    transform: translateX(0);
  }

  .show-burger {
    display: flex;
  }
}
</style>