<template>
  <div>
    <div class="backround">
      <div class="header">
        <ul>
          <li>
            <img class="logo" src="public/logo.svg">
          </li>
        </ul>
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
}

ul li {
  float: left;
  list-style: none;
}

@media (min-width: 769px) and (max-width: 1200px) {
  * {
    margin: 0px;
    height: 0px;
  } 

  .logo {
    width: 140px;
    height: 23.24px;
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
  
}

@media (min-width: 360px) and (max-width: 768px) {
  * {
    margin: 0px;
    height: 0px;
  }

  .logo {
    width: 140px;
    height: 23.24px;
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
}
</style>