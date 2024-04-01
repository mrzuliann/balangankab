<template>
  <div>
      <nav class="navbar navbar-expand-lg bg-dark" data-bs-theme="dark">
          <div class="container">
            <NuxtLink class="navbar-brand" to="/">
              <img src="/portal.png" alt="Logo" width="200px">
            </NuxtLink>
          
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                  data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                  aria-label="Toggle navigation">
                  <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarSupportedContent" style="color: aquamarine;">
                  <ul class="navbar-nav me-auto mb-2 mb-lg-0"> 
                      <li class="nav-item">
                      <NuxtLink class="navbar-brand" style="font-size: 80%; stroke: aquamarine 20px;" to="/">
                       Home
                      </NuxtLink>
                       </li>
                      <NuxtLink class="navbar-brand" style="font-size: 80%;" to="/berita">
                      Berita
                      </NuxtLink>
                      <NuxtLink class="navbar-brand"  style="font-size: 80%;" to="/layanan">
                      PPID
                      </NuxtLink>
                      <NuxtLink class="navbar-brand"  style="font-size: 80%;" to="/renstra">
                      Renstra
                      </NuxtLink>
                      <NuxtLink class="navbar-brand"  style="font-size: 80%;" to="/renja">
                      Renja
                      </NuxtLink>
                      <NuxtLink class="navbar-brand"  style="font-size: 80%;" to="/sakip">
                      112
                      </NuxtLink>
                  </ul>
                  <ul class="navbar-nav ms-auto mb-2 mb-lg-0" role="search">
                      <a href="https://santrikoding.com" target="_blank" class="btn btn-success">balangankab.go.id</a>
                  </ul>
              </div>
          </div>
      </nav>

      <!--- render page -->
      <slot />
      <footer class="bg-dark text-light text-center p-3">
        <div class="container">
            <p>&copy; 2024 Balangankab. All rights reserved.</p>
            <p>Designed by <a href="https://diskominfo.balangankab.go.id" class="text-light">balangankab.go.id</a></p>
        </div>
      </footer>


      

  </div>
  
</template>


<style>
body { background-color: rgb(217, 255, 229); font-family: 'Quicksand', sans-serif }

.page-enter-active,
.page-leave-active {
  transition: all 0.4s;
}
.page-enter-from,
.page-leave-to {
  opacity: 0;
  filter: blur(1rem);
}
</style>