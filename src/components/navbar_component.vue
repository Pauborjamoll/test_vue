<template>
    <nav class="navbar navbar-expand-md navbar-light bg-header pb-2 pt-0">
        <div class="container">
            <div class="navbar-brand p-0 ">
            <img src="@/assets/images/logo.jpg"  alt="" />
            </div>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#main-nav"
            aria-controls="main-nav"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
         
          <div
            class=" collapse navbar-collapse justify-content-center align-center"
            id="main-nav"
          >
            <ul class="navbar-nav ">
              <li class="nav-item px-3">
                <router-link to="/">Home</router-link>
              </li>
              <li class="nav-item px-3">
                <router-link to="/shop">Shop</router-link>
              </li>
              <li class="nav-item px-3">
                <router-link to="/blog">Blog</router-link>
              </li>
            </ul>
          </div>
        </div>
      </nav>
</template>
<script>
export default {
  name: 'navComponent',
}
</script>