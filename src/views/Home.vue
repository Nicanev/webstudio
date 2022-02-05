<template>
  <main class="main">
    <div class="fullscrean-block">
      <div class="preview">
        <div class="preview__container">
          <div class="preview__text">
            <h1>
              Высоко-качественная веб-студия создающая крутые сайты на новейших
              технологиях и фреймворках.
            </h1>
            <h2>
              Нам доверяют крупные компании, государства и многие заказчики и вы
              также можете убедиться в качестве наших работ.
            </h2>
            <div class="preview__buttons">
              <button class="button button_large">Заказать</button>
              <button class="button button_light button_large">
                Посмотреть
              </button>
            </div>
          </div>
          <div class="preview__img">
            <picture
              ><source
                srcset="../assets/img/background.webp"
                type="image/webp" />
              <img src="../assets/img/background.png" alt="preview background"
            /></picture>
          </div>
        </div>
      </div>
      <div class="preview-about">
        <div class="preview-about__container">
          <div class="preview-about__item">
            <div class="preview-about__title">Направление</div>
            <div class="preview-about__text">Full-Stack</div>
          </div>
          <div class="preview-about__item">
            <div class="preview-about__title">Количество сайтов</div>
            <div class="preview-about__text">100+</div>
          </div>
          <div class="preview-about__item">
            <div class="preview-about__title">Количество сотрудников</div>
            <div class="preview-about__text">20+</div>
          </div>
        </div>
      </div>
    </div>
    <div class="about">
      <div class="about__container">
        <div class="about__subtitle">закажите сайт для своего дела</div>
        <div class="about__title">
          <h1>Чем мы лучше остальных?</h1>
        </div>
        <div class="about__text">
          Мы используем только самые современные фреймворки последней версий.
          Поэтому все наши сайты получаются передовыми, обеспечивая отличный
          отлик и современный дизайн. Не важно что вам нужно: интернет-магазин,
          лендинг пейдж, сайт для бизнеса или редакторский спецпроект - с Web
          Studio вы получите качественный результат.
        </div>
        <div class="about__about-block about-block">
          <div class="about-block__item">
            <div class="about-block__img">
              <picture
                ><source
                  srcset="../assets/img/Modern_Design.webp"
                  type="image/webp" />
                <img src="../assets/img/Modern_Design.png" alt=""
              /></picture>
            </div>
            <div class="about-block__text">
              <div class="about-block__title">
                <h1>Современный дизайн</h1>
              </div>
              <div class="about-block__subtitle">
                <h2>Интуитивно понятный mobile first современный дизайн</h2>
              </div>
              <div class="about-block__des">
                Доверьтесь нашим дизайнерам. Наша команда дизайнеров внимательно
                следит за трендами в сфере дизайна, поэтому ваши сайты будут
                выглядить красиво и современно
              </div>
            </div>
          </div>
          <div class="about-block__item">
            <div class="about-block__text">
              <div class="about-block__title">
                <h1>Качественная верстка</h1>
              </div>
              <div class="about-block__subtitle">
                <h2>Анимации, адаптивность, слайдеры и многое другое.</h2>
              </div>
              <div class="about-block__des">
                Наши верстальщики сверстают вам сайт любой сложности, будь то на
                нём анимации для привлечения внимания, до форм обратной связи
              </div>
            </div>
            <div class="about-block__img">
              <picture
                ><source srcset="../assets/img/layout.webp" type="image/webp" />
                <img src="../assets/img/layout.png" alt=""
              /></picture>
            </div>
          </div>
          <div class="about-block__item">
            <div class="about-block__img">
              <picture
                ><source srcset="../assets/img/tech.webp" type="image/webp" />
                <img src="../assets/img/tech.png" alt=""
              /></picture>
            </div>
            <div class="about-block__text">
              <div class="about-block__title">
                <h1>Передовые технологии</h1>
              </div>
              <div class="about-block__subtitle">
                <h2>Мощные инструменты последней версии</h2>
              </div>
              <div class="about-block__des">
                Наша команда использует множество технологий для создания
                современного и качественного конечного продукта. <br /><br />
                Говоря о наших навыках, в работе мы используем:
                <ul>
                  <li>Вёрстка - адаптивность, SASS</li>
                  <li>Frontend - Vue 3, WebAPI</li>
                  <li>PHP - Laravel, Symfony</li>
                  <li>CMS - WordPress, Shopify</li>
                  <li>Инфраструктура - Google Cloud, AWS</li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="feedback">
      <div class="feedback__container">
        <div class="feedback__subtitle"></div>
        <h1 class="header__title">Напишите нам</h1>
        <form action="" class="feedback__form">
          <div class="feedback__inputs">
            <input type="text" placeholder="Кто вы?" />
            <input type="email" placeholder="Ваш email" />
            <textarea
              placeholder="Сообщение"
              name=""
              id=""
              cols="30"
              rows="10"
            ></textarea>
          </div>
          <button class="header__button button">Отправить</button>
        </form>
      </div>
    </div>
    <div class="news">
      <div class="news__container">
        <h1 class="news__title">Новости</h1>
        <div class="news__slider">
          <div class="slider-block">
            <swiper
              :spaceBetween="10"
              :slidesPerGroup="1"
              :pagination="true"
              :breakpoints="{
                310: {
                  slidesPerView: 1
                },
                650: {
                  slidesPerView: 2
                  
                },
                970: {
                  slidesPerView: 3
                }
              }"
              class="mySwiper"
            >
              <swiper-slide class="slide" v-for="(item, index) in 5" :key="index">
                <div class="news__block">
                  <div class="news__img">
                    <img src="../assets/img/Man.png" alt="" />
                  </div>
                  <div class="news__title">Набор людей в студию!</div>
                  <div class="news__date">Загружено 22.12.22</div>
                  <div class="news__des">Мы объявляем набор в нашу студию</div>
                </div>
              </swiper-slide>
            </swiper>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<style>
.news__slider{
margin-top: 50px;
}
</style>
<script>
// @ is an alias to /src
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// swiper bundle styles
import "swiper/swiper-bundle.min.css";

// swiper core styles
import "swiper/swiper.min.css";

// modules styles
import "swiper/components/navigation/navigation.min.css";
import "swiper/components/pagination/pagination.min.css";

// import Swiper core and required modules
import SwiperCore, { Pagination, Navigation } from "swiper";
SwiperCore.use([Pagination, Navigation]);
export default {
  name: "Home",
  components: {
    Swiper,
    SwiperSlide,
  },
};
</script>
