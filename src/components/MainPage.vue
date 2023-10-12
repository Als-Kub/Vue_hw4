<template>
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
  <section class="top center">
    <div class="top__box">
      <h1 class="top__title">Let Your Home Be Unique</h1>
      <p class="top__text">
        There are many variations of the passages of lorem Ipsum fromavailable,
        majority.
      </p>
      <button class="button">
        <span class="button__text">Get Started</span
        ><svg
          xmlns="http://www.w3.org/2000/svg"
          width="19"
          height="17"
          viewBox="0 0 19 17"
          fill="none"
        >
          <path
            d="M2 8.43542L15.7232 8.29857M10.6182 1.91138L17.1412 8.43436L10.4868 15.0887"
            stroke="#CDA274"
            stroke-width="2"
            stroke-linecap="square"
            stroke-linejoin="round"
          />
        </svg>
      </button>
    </div>
  </section>
  <section class="projects center">
    <h2 class="projects__title">Follow Our Projects</h2>
    <p class="projects__text">
      It is a long established fact that a reader will be distracted by the of
      readable content of page lookings at its layouts points.
    </p>
    <div class="projects__cards">
      <div class="card">
        <div class="card__img-box card__img-box_radius-tr">
          <img
            src="@/assets/img/Main/project_img1.jpg"
            alt="card img"
            class="card"
          />
        </div>
        <div class="card__content">
          <div class="card__desc">
            <h3 class="card__title">Modern Kitchan</h3>
            <p class="card__text">Decor / Artchitecture</p>
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
      <div class="card">
        <div class="card__img-box card__img-box_radius-tl">
          <img
            src="@/assets/img/Main/project_img3.jpg"
            alt="card img"
            class="card"
          />
        </div>
        <div class="card__content">
          <div class="card__desc">
            <h3 class="card__title">Modern Kitchan</h3>
            <p class="card__text">Decor / Artchitecture</p>
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
      <div class="card">
        <div class="card__img-box card__img-box_radius-br">
          <img
            src="@/assets/img/Main/project_img4.jpg"
            alt="card img"
            class="card"
          />
        </div>
        <div class="card__content">
          <div class="card__desc">
            <h3 class="card__title">Modern Kitchan</h3>
            <p class="card__text">Decor / Artchitecture</p>
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
      <div class="card">
        <div class="card__img-box card__img-box_radius-bl">
          <img
            src="@/assets/img/Main/project_img1.jpg"
            alt="card img"
            class="card"
          />
        </div>
        <div class="card__content">
          <div class="card__desc">
            <h3 class="card__title">Modern Kitchan</h3>
            <p class="card__text">Decor / Artchitecture</p>
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
  </section>
  <div class="results center">
    <div class="results__box">
      <div class="results__content results__content_border-left">
        <p class="results__digit">12</p>
        <p class="results__text">Years Of Experiance</p>
      </div>
      <div class="results__content">
        <p class="results__digit">85</p>
        <p class="results__text">Success Project</p>
      </div>
      <div class="results__content">
        <p class="results__digit">15</p>
        <p class="results__text">Active Project</p>
      </div>
      <div class="results__content results__content_border-right">
        <p class="results__digit">95</p>
        <p class="results__text">Happy Customers</p>
      </div>
    </div>
  </div>
  <section class="blog center">
    <h2 class="blog__title">Articles & News</h2>
    <p class="blog__text">
      It is a long established fact that a reader will be distracted by the of
      readable content of a page when lookings at its layouts the points of
      using.
    </p>
    <div class="blog__cards">
      <div class="blog__card-box">
        <div class="card card_desc_1">
          <div class="card__img-box card__img-box-radius_double">
            <img
              src="@/assets/img/Main/blog_img1.jpg"
              alt="card img"
              class="card"
            />
          </div>
          <h3 class="card__title card__title_margin">
            Let’s Get Solution For Building Construction <br />
            Work
          </h3>
          <div class="card__content">
            <div class="card__desc">
              <p class="card__text">26 December,2022</p>
            </div>
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
      <div class="blog__card-box">
        <div class="card card_desc_2">
          <div class="card__img-box card__img-box-radius_double">
            <img
              src="@/assets/img/Main/blog_img2.jpg"
              alt="card img"
              class="card"
            />
          </div>
          <h3 class="card__title card__title_margin">
            Let’s Get Solution For Building Construction <br />
            Work
          </h3>
          <div class="card__content">
            <div class="card__desc">
              <p class="card__text">26 December,2022</p>
            </div>
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
      <div class="blog__card-box">
        <div class="card card_desc_3">
          <div class="card__img-box card__img-box-radius_double">
            <img
              src="@/assets/img/Main/blog_img3.jpg"
              alt="card img"
              class="card"
            />
          </div>
          <h3 class="card__title card__title_margin">
            Let’s Get Solution For Building Construction <br />
            Work
          </h3>
          <div class="card__content">
            <div class="card__desc">
              <p class="card__text">26 December,2022</p>
            </div>
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
        It is a long established fact that a reader will be distracted lookings.
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
</template>

<script>
export default {};
</script>

<style scoped></style>
