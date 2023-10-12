<template>
  <div>
    <header class="header center">
      <div class="logo">
        <img
          src="@/assets/img/Main/Logo.svg"
          alt="Logo icon"
          class="logo__icon"
        />
        <p class="logo__text">Interno</p>
      </div>
      <nav class="nav">
        <ul class="nav__ul">
          <li class="nav__li"><a href="#" class="nav__link">Home</a></li>
          <li class="nav__li"><a href="#" class="nav__link">Project</a></li>
          <li class="nav__li"><a href="#" class="nav__link">Blog</a></li>
        </ul>
      </nav>
    </header>
    <div class="top-blog center-wide">
      <div class="top-blog__box">
        <div class="top-blog__content">
          <h2 class="top-blog__title">Articles & News</h2>
          <p class="top-blog__links">
            <a href="#" class="top-blog__link">Home</a>
            <a href="#" class="top-blog__link">Blog</a>
          </p>
        </div>
      </div>
    </div>
    <section class="post center">
      <h2 class="post__title">Latest Post</h2>
      <div class="post__content">
        <div class="post__double-box">
          <div class="post__img-box">
            <img
              src="@/assets/img/Blog/post_img.jpg"
              alt="card img"
              class="post__img"
            />
          </div>
        </div>
        <div class="post__desc">
          <h3 class="post__subtitle">
            Low Cost Latest Invented Interior <br />
            Designing Ideas
          </h3>
          <p class="post__text">
            Lorem ipsum dolor sit amet, adipiscing Aliquam eu sem vitae turpis
            dignissim maximus.posuere in.Contrary to popular belief.
          </p>
          <p class="post__text post__text_mb">
            Lorem Ipsum is not simply random text. It has roots in a piece of
            classica.
          </p>
          <div class="post__date">
            <p class="post__date-text">26 December,2022</p>

            <button class="button-round button-round_margin-bottom">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="70"
                height="70"
                viewBox="0 0 70 70"
                fill="none"
              >
                <circle cx="35" cy="35" r="35" fill="#F4F0EC" />
                <path
                  d="M32 44L40 35L32 26"
                  stroke="#292F36"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </button>
          </div>
        </div>
      </div>
    </section>
    <section class="blog center">
      <h2 class="blog__title blog__title_align-left">Articles & News</h2>

      <div class="blog__cards">
        <div v-for="card in cards" :key="card.id" class="blog__card-box">
          <p class="blog__card-desc">
            {{ card.desc }}
          </p>
          <div class="card">
            <div class="card__img-box card__img-box-radius_double">
              <img :src="card.img" alt="card img" class="card" />
            </div>
            <h3 class="card__title card__title_margin">
              {{ card.title }} <br />
              {{ card.title_end }}
            </h3>
            <div class="card__content">
              <div class="card__desc">
                <p class="card__text">{{ card.date }}</p>
              </div>
              <button class="button-round">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="70"
                  height="70"
                  viewBox="0 0 70 70"
                  fill="none"
                >
                  <circle cx="35" cy="35" r="35" fill="#F4F0EC" />
                  <path
                    d="M32 44L40 35L32 26"
                    stroke="#292F36"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                  />
                </svg>
              </button>
            </div>
          </div>
        </div>
      </div>
      <div class="menu">
        <button class="menu__button">01</button>
        <button class="menu__button">02</button>
        <button class="menu__button">03</button>
        <button class="menu__button">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="1em"
            viewBox="0 0 320 512"
          >
            <!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
            <path
              d="M278.6 233.4c12.5 12.5 12.5 32.8 0 45.3l-160 160c-12.5 12.5-32.8 12.5-45.3 0s-12.5-32.8 0-45.3L210.7 256 73.4 118.6c-12.5-12.5-12.5-32.8 0-45.3s32.8-12.5 45.3 0l160 160z"
            />
          </svg>
        </button>
      </div>
    </section>
    <footer class="footer center">
      <div class="footer__left">
        <div class="logo">
          <img
            src="@/assets/img/Main/Logo.svg"
            alt="Logo icon"
            class="logo__icon"
          />
          <p class="logo__text">Interno</p>
        </div>
        <p class="footer__text">
          It is a long established fact that a reader will be distracted
          lookings.
        </p>
        <a href="#" class="footer__link footer__link_margin"
          ><img src="@/assets/img/Main/footer_icon_1.svg" alt="Footer icon"
        /></a>
        <a href="#" class="footer__link"
          ><img src="@/assets/img/Main/footer_icon_2.svg" alt="Footer icon"
        /></a>
      </div>
      <div class="footer__center">
        <h3 class="footer__title">Pages</h3>
        <nav class="nav">
          <ul class="nav__ul footer__nav_flex">
            <li class="nav__li">
              <a href="#" class="nav__link footer__nav__link_font">Home</a>
            </li>
            <li class="nav__li">
              <a href="#" class="nav__link footer__nav__link_font">Project</a>
            </li>
            <li class="nav__li">
              <a href="#" class="nav__link footer__nav__link_font">Blog</a>
            </li>
          </ul>
        </nav>
      </div>
      <div class="footer__right">
        <h3 class="footer__title">Contact</h3>
        <p class="footer__text">
          55 East Birchwood Ave. Brooklyn, New York 11201
        </p>
        <p class="footer__text footer__text_lign-height">contact@interno.com</p>
        <p class="footer__text footer__text_lign-height">(123) 456 - 7890</p>
      </div>
    </footer>
  </div>
</template>

<script>
import img1 from "@/assets/img/Blog/blog_img1.jpg";
import img2 from "@/assets/img/Blog/blog_img2.jpg";
import img3 from "@/assets/img/Blog/blog_img3.jpg";
import img4 from "@/assets/img/Blog/blog_img4.jpg";
import img5 from "@/assets/img/Blog/blog_img5.jpg";
import img6 from "@/assets/img/Blog/blog_img6.jpg";

export default {
  data() {
    return {
      product: {
        title: "",
        date: "",
        img: "",
      },
      flag: false,

      cards: [
        {
          id: 1,
          img: img1,
          desc: "Kitchan Design",
          title: "Let’s Get Solution For Building Construction",
          title_end: "Work",
          date: "26 December, 2022 ",
        },
        {
          id: 2,
          img: img2,
          desc: "Living Design",
          title: "Let’s Get Solution For Building Construction",
          title_end: "Work",
          date: "22 December, 2023 ",
        },
        {
          id: 3,
          img: img3,
          desc: "Interior Design",
          title: "Best For Any Office & Business Interior",
          title_end: "Solution",
          date: "25 December, 2022 ",
        },
        {
          id: 4,
          img: img4,
          desc: "Kitchan Design",
          title: "Let’s Get Solution For Building Construction",
          title_end: "Work",
          date: "26 December, 2022 ",
        },
        {
          id: 5,
          img: img5,
          desc: "Living Design",
          title: "Low Cost Latest Invented Interior Designing",
          title_end: "Ideas.",
          date: "22 December, 2022 ",
        },
        {
          id: 6,
          img: img6,
          desc: "Interior Design",
          title: "Best For Any Office & Business Interior",
          title_end: "Solution.",
          date: "25 December, 2022 ",
        },
      ],
    };
  },
  methods: {
    addData() {
      this.title = this.card.title;
      this.date = this.card.date;
    },
  },
};
</script>

<style scoped></style>
