<template>
  <div class="wrapper">
    <header class="header">
      <div class="header__container">
        <div class="header__burger">
          <img src="../assets/img/Burger.svg" alt="" />
        </div>
        <div class="header__logo">
          <a href="#"><img src="../assets/img/Logo.svg" alt="" /></a>
        </div>
        <div class="header__person">
          <img src="../assets/img/person.svg" alt="" />
        </div>
        <div class="header__menu menu">
          <ul class="menu__list">
            <li class="menu__item">
              <a href="#" class="menu__link">О нас</a>
            </li>
            <li class="menu__item">
              <a href="#" class="menu__link">Новости</a>
            </li>
            <li class="menu__item">
              <a href="#" class="menu__link">Услуги</a>
            </li>
            <li class="menu__item">
              <a href="#" class="menu__link">Контакты</a>
            </li>
          </ul>
        </div>
        <div class="header__buttons">
          <a href="#">Войти</a>
          <button class="button">Регистрация</button>
        </div>
      </div>
    </header>
    
    <router-view />

    <footer class="footer">
      <div class="footer__container">
        <div class="footer__menu menu">
          <ul class="menu__list">
            <li class="menu__item">
              <a href="#" class="menu__link">О нас</a>
            </li>
            <li class="menu__item">
              <a href="#" class="menu__link">Новости</a>
            </li>
            <li class="menu__item">
              <a href="#" class="menu__link">Услуги</a>
            </li>
            <li class="menu__item">
              <a href="#" class="menu__link">Контакты</a>
            </li>
          </ul>
        </div>
        <div class="footer__logo">
          <img src="../assets/img/Logo.svg" alt="" />
        </div>
        <div class="footer__title">Оптимизируйте свой бизнес</div>
        <div class="footer__social">
          <a href="#"><img src="../assets/img/tg.svg" alt="" /></a>
          <a href="#"><img src="../assets/img/vk.svg" alt="" /></a>
          <a href="#"><img src="../assets/img/youtube.svg" alt="" /></a>
        </div>
        <div class="footer__copyright">WebStudio LLC</div>
      </div>
    </footer>
  </div>
</template>
