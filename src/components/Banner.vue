<template>
  <div class="container-fluid px-0">
    <div class="banner-box">
      <img src="../assets/banner.png" alt="banner image" class="img-banner" />
      <div class="banner-content">
        <h1>imagine a place...</h1>
        <p class="text-center">
          ...where you can belong to a school club, a gaming group, or a
          worldwide art community. <br />
          Where just you and a handful of friends can spend time together. A
          place that makes it easy <br />
          to talk every day and hang out more often.
        </p>
        <div class="d-flex w-100 justify-content-center flex-wrap">
          <button class="btn-setting btn-download">
            <i class="fa-solid fa-download pe-2"></i>
            Download for Windows
          </button>
          <button class="btn-setting btn-open mt-3 mt-lg-0">
            Open Discord in your browser
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Banner",
};
</script>

<style scoped>
.banner-box {
  height: 630px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}
.img-banner {
  height: 710px;
  object-fit: cover;
  width: 100%;
  position: absolute;
  top: 0;
  left: 0;
  z-index: -10;
}
.banner-content {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}
.banner-content h1 {
  text-transform: uppercase;
  color: var(--whiteColor);
  font-size: 32px;
  font-weight: bold;
}
.banner-content p {
  color: var(--whiteColor);
  font-size: 14px;
  margin: 30px 0;
}
.btn-setting {
  padding: 15px 25px;
  margin: 0 10px;
  border-radius: 50px;
  border: none;
  transition: all 0.25s ease-in;
}
.btn-setting:hover {
  box-shadow: var(--shadowColor);
}
.btn-download {
  color: var(--darkerColor);
  background-color: var(--whiteColor);
}
.btn-download:hover {
  color: var(--blueColor);
}
.btn-open {
  color: var(--whiteColor);
  background-color: var(--darkerColor);
}
.btn-open:hover {
  color: var(--whiteColor);
  background-color: rgba(49, 51, 56, 0.9);
}
@media (min-width: 576px) {
  .banner-content h1 {
    font-size: 92px;
  }
  .banner-content p {
    font-size: 20px;
  }
}
</style>
