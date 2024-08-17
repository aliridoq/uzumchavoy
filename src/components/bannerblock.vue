<template>
  <div class="banner-block">
    <div class="banner-wrapper">
      <!-- Navigation Buttons -->
      <div class="navigation">
        <div @click="prevSlide" class="slider-button prev">
          <svg
            class="oldin"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="#1f2026"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M15.8106 20.4983C16.0857 20.1887 16.0579 19.7146 15.7483 19.4394L7.8789 12L15.7483 4.56055C16.0579 4.28536 16.0857 3.81131 15.8106 3.50172C15.5354 3.19213 15.0613 3.16425 14.7517 3.43944L6.25173 11.4394C6.09161 11.5818 6 11.7858 6 12C6 12.2142 6.09161 12.4182 6.25173 12.5605L14.7517 20.5605C15.0613 20.8357 15.5354 20.8079 15.8106 20.4983Z"
              fill="black"
            ></path>
          </svg>
        </div>
        <div @click="nextSlide" class="slider-button next">
          <svg
            class="keyin"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="#1f2026"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M8.18945 20.4983C7.91426 20.1887 7.94215 19.7146 8.25174 19.4394L16.1211 12L8.25173 4.56055C7.94215 4.28536 7.91426 3.81131 8.18945 3.50172C8.46464 3.19213 8.93869 3.16425 9.24828 3.43944L17.7483 11.4394C17.9084 11.5818 18 11.7858 18 12C18 12.2142 17.9084 12.4182 17.7483 12.5605L9.24828 20.5605C8.93869 20.8357 8.46464 20.8079 8.18945 20.4983Z"
              fill="black"
            ></path>
          </svg>
        </div>
      </div>

      <!-- Swiper Container -->
      <div class="swiper-container">
        <!-- Slide 1 -->
        <div
          v-for="(slide, index) in slides"
          :key="index"
          :class="['swiper-slide', { active: index === currentIndex }]"
        >
          <a :href="slide.link" class="slide">
            <img class="slide-img" :src="slide.image" :alt="slide.alt" />
          </a>
        </div>
      </div>

      <!-- Pagination -->
      <div class="pagination">
        <span
          v-for="(slide, index) in slides"
          :key="index"
          @click="goToSlide(index)"
          :class="{ active: index === currentIndex }"
        ></span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      slides: [
        {
          link: "https://uzum.uz/uz/category/shkolnyj-bazar--512",
          image:
            "https://i.ibb.co/LNPPrV7/maktab.jpg",
          alt: "Uzum aksiyalari, mahsulotlar termasi va xabarlari",
        },
        {
          link: "https://uzum.uz/promo/pepsi",
          image:
            "https://i.ibb.co/x8NZVrd/pepsi.jpg",
          alt: "Uzum aksiyalari, mahsulotlar termasi va xabarlari",
        },
        // Add more slides here as needed
      ],
      currentIndex: 0,
    };
  },
  methods: {
    prevSlide() {
      this.currentIndex =
        this.currentIndex === 0
          ? this.slides.length - 1
          : this.currentIndex - 1;
    },
    nextSlide() {
      this.currentIndex =
        this.currentIndex === this.slides.length - 1
          ? 0
          : this.currentIndex + 1;
    },
    goToSlide(index) {
      this.currentIndex = index;
    },
  },
};
</script>

<style scoped>
.banner-block {
  line-height: 1;
  box-sizing: border-box;
  border-radius: 10px;
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  vertical-align: baseline;
  outline: none;
  font-style: inherit;
}
.banner-wrapper {
  line-height: 1;
  box-sizing: border-box;
  padding: 0;
  border: 0;
  font-size: 100%;
  vertical-align: baseline;
  outline: none;
  font-style: inherit;
  margin: 0 auto;
  border-radius: 10px !important;
  max-width: 1300px;
  position: relative;
  transform: translateZ(0);
  width: 100%;
}
.navigation {
  line-height: 1;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  vertical-align: baseline;
  outline: none;
  font-style: inherit;
  position: absolute;
  top: calc(50% - 20px);
  width: 100%;
  z-index: 2;
}
.slider-button.prev {
  line-height: 1;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-size: 100%;
  vertical-align: baseline;
  outline: none;
  font-style: inherit;
  align-items: center;
  background: hsla(0, 0%, 100%, 0.7);
  border: 1px solid rgba(54, 55, 64, 0.25);
  border-radius: 20px;
  cursor: pointer;
  display: flex;
  height: 40px;
  justify-content: center;
  opacity: 0.5;
  position: absolute;
  text-decoration: none;
  transition: all 0.3s ease-in-out;
  width: 40px;
  z-index: 1;
  left: 16px;
}
.oldin {
  line-height: 1;
  font-size: 100%;
  font-style: inherit;
  cursor: pointer;
  width: 24;
  height: 24;
  fill: rgb(31, 32, 38);
  box-sizing: border-box;
  outline: 0;
  border: 0;
}
.slider-button.next {
  border-radius: 20px;
  cursor: pointer;
  display: flex;
  height: 40px;
  justify-content: center;
  opacity: 0.5;
  position: absolute;
  text-decoration: none;
  transition: all 0.3s ease-in-out;
  width: 40px;
  z-index: 1;
  right: -30px;
  background: hsla(0, 0%, 100%, 0.7);
  border: 1px solid rgba(54, 55, 64, 0.25);
  line-height: 1;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-size: 100%;
  vertical-align: baseline;
  outline: none;
  font-style: inherit;
  align-items: center;
}
.keyin {
  cursor: pointer;
  width: 24;
  height: 24;
  fill: rgb(31, 32, 38);
  box-sizing: border-box;
  line-height: 1;
  font-size: 100%;
  font-style: inherit;
  outline: 0;
  border: 0;
}
.swiper-container {
  line-height: 1;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  vertical-align: baseline;
  outline: none;
  font-style: inherit;
  cursor: pointer;
}
.swiper-slide {
  line-height: 1;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  vertical-align: baseline;
  outline: none;
  font-style: inherit;
  display: none;
}
.swiper-slide.active {
  display: block;
}
.pagination {
  line-height: 1;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  vertical-align: baseline;
  outline: none;
  font-style: inherit;
  position: absolute;
  bottom: 20px;
  left: 50%;
  transform: translateX(-50%);
  display: flex;
  justify-content: center;
}
.pagination span {
  line-height: 1;
  box-sizing: border-box;
  margin: 0 5px;
  padding: 0;
  border: 0;
  font-size: 100%;
  vertical-align: baseline;
  outline: none;
  font-style: inherit;
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background: rgba(255, 255, 255, 0.5);
  cursor: pointer;
  transition: all 0.3s ease-in-out;
}
.pagination .active {
  background: rgba(255, 255, 255, 1);
}
.slide-img{
  border-radius: 10px;
}
</style>
