<template>
  <div>
    <ul class="d-flex px-0">
      <li class="list-social">
        <a href="">
          <i class="fa-brands fa-twitter"></i>
        </a>
      </li>
      <li class="list-social">
        <a href="">
          <i class="fa-brands fa-instagram"></i>
        </a>
      </li>
      <li class="list-social">
        <a href="">
          <i class="fa-brands fa-facebook"></i>
        </a>
      </li>
      <li class="list-social">
        <a href="">
          <i class="fa-brands fa-youtube"></i>
        </a>
      </li>
      <li class="list-social">
        <a href="">
          <i class="fa-brands fa-tiktok"></i>
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "SocialRow",
};
</script>

<style scoped>
.list-social {
  list-style: none;
  margin: 0 15px;
}
.list-social a i {
  font-size: 24px;
  color: var(--whiteColor);
}
</style>
