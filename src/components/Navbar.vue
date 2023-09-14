<template>
  <nav class="navbar navbar-expand-lg">
    <div class="container-fluid">
      <a class="navbar-brand" href="">
        <img src="../assets//discord-logo.svg" alt="Discord Logo" />
        Discord
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navigationLink"
        aria-controls="navigationLink"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <i class="fa-solid fa-bars"></i>
      </button>
      <div class="collapse navbar-collapse" id="navigationLink">
        <ul class="navbar-nav justify-content-center w-100">
          <li class="nav-item">
            <a class="nav-link" href="">Download</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="">Nitro</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="">discover</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="">safety</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="">support</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="">blog</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="">careers</a>
          </li>
        </ul>
        <div class="box-btn">
          <button class="btn-login">Login</button>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
.navbar-expand-lg {
  background-color: transparent;
}
.navbar-toggler {
  border: none !important;
}
.navbar-toggler:focus {
  box-shadow: none;
}
.fa-bars {
  color: var(--whiteColor);
  font-size: 36px;
}
.navbar-brand,
.navbar-brand:hover {
  color: var(--whiteColor);
  font-weight: bold;
  letter-spacing: 1.2px;
}
.nav-item {
  margin: 0 20px;
}
.nav-link {
  color: var(--whiteColor);
  text-transform: capitalize;
  font-weight: 500;
}
.nav-link:hover {
  text-decoration: underline;
  color: var(--whiteColor);
}
.btn-login {
  padding: 8px 15px;
  border-radius: 20px;
  border: 1px solid var(--blueColor);
  color: var(--darkerColor);
  transition: all 0.25s ease-in;
  margin: 10px 20px;
}
.btn-login:hover {
  box-shadow: var(--shadowColor);
  color: var(--blueColor);
}
@media (min-width: 576px) {
  .btn-login {
    margin: 0;
  }
}
</style>
