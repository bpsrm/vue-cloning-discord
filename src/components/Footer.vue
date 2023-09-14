<template>
  <div class="container-fluid p-3">
    <div class="container">
      <div class="row mt-5">
        <div class="col-4 d-flex flex-column align-items-start">
          <div class="dropdown mb-4">
            <button
              class="btn-dropdown"
              type="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              English, USA <i class="fa-solid fa-angle-down ps-2"></i>
            </button>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="">ไทย</a></li>
              <li><a class="dropdown-item" href="">Dansk</a></li>
              <li><a class="dropdown-item" href="">Deutsch</a></li>
            </ul>
          </div>
          <SocialRow />
        </div>
        <div class="col-8 d-flex justify-content-between">
          <div class="product-box">
            <p>Product</p>
            <ul>
              <li>Download</li>
              <li>Nitro</li>
              <li>Status</li>
              <li>App Directory</li>
            </ul>
          </div>
          <div class="company-box">
            <p>Company</p>
            <ul>
              <li>Download</li>
              <li>Nitro</li>
              <li>Status</li>
              <li>App Directory</li>
            </ul>
          </div>
          <div class="resource-box">
            <p>Resource</p>
            <ul>
              <li>College</li>
              <li>Support</li>
              <li>Safety</li>
              <li>Blog</li>
              <li>Feedback</li>
              <li>Developers</li>
              <li>StreamKit</li>
              <li>Creators</li>
              <li>Community</li>
              <li>Official 3rd Party Merch</li>
            </ul>
          </div>
          <div class="policies-box">
            <p>Policies</p>
            <ul>
              <li>Terms</li>
              <li>Privacy</li>
              <li>Cookie Settings</li>
              <li>Guidelines</li>
              <li>Acknowledgements</li>
              <li>Licenses</li>
              <li>Company Information</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="line-footer"></div>
      <div class="row mb-4">
        <div class="col-6 mt-4">
          <a class="navbar-brand" href="">
            <img src="../assets//discord-logo.svg" alt="Discord Logo" />
            Discord
          </a>
        </div>
        <div class="col-6 mt-4 d-flex justify-content-end">
          <button class="btn-signUp">Sign Up</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import SocialRow from "./SocialRow.vue";

export default {
  name: "Footer",
  components: {
    SocialRow,
  },
};
</script>

<style scoped>
.container-fluid {
  color: var(--whiteColor);
  background-color: var(--bgDarkerColor);
}
.product-box li,
.company-box li,
.resource-box li,
.policies-box li {
  list-style: none;
  margin: 10px 0;
  font-weight: normal;
}
.product-box ul,
.company-box ul,
.resource-box ul,
.policies-box ul {
  padding-left: 0 !important;
}
.product-box p,
.company-box p,
.resource-box p,
.policies-box p {
  color: var(--blueColor);
}
.btn-dropdown {
  padding: 10px 20px;
  background: transparent;
  border: none;
  color: var(--whiteColor);
}
.line-footer {
  margin-top: 30px;
  border-top: 1px solid var(--blueColor);
}
.btn-signUp {
  padding: 7px 16px;
  border-radius: 50px;
  border: none;
  font-size: 14px;
  color: var(--whiteColor);
  background-color: var(--bgColor);
  transition: all 0.25s ease-in;
}
.btn-signUp:hover {
  background-color: var(--blueColor);
}
</style>
