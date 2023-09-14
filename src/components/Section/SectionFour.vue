<template>
  <div class="container-fluid mt-5 p-5 text-center">
    <h1 class="pt-5 fw-bold">RELIABLE TECH FOR STAYING CLOSE</h1>
    <p>
      Low-latency voice and video feels like you’re in the same room. Wave hello
      over video, watch friends stream their <br />
      games, or gather up and have a drawing session with screen share.
    </p>
    <img
      src="/src/assets/section-four.svg"
      alt=""
      class="img-fluid my-3 py-5"
    />
    <h3 class="fw-bold">Ready to start your journey?</h3>
    <button class="btn-download-window mb-5">
      <i class="fa-solid fa-download pe-2"></i> Download for Window
    </button>
  </div>
</template>

<script>
export default {
  name: "SectionFour",
};
</script>

<style scoped>
.container-fluid {
  background-color: #f6f6f6;
}
.btn-download-window {
  margin-top: 30px;
  padding: 15px 30px;
  border-radius: 50px;
  background-color: var(--bgColor);
  color: var(--whiteColor);
  border: none;
  font-size: 18px;
  transition: all 0.25s ease-in;
}
.btn-download-window:hover {
  background-color: rgba(64, 78, 237, 0.8);
  box-shadow: var(--shadowColor);
}
</style>
