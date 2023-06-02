<template>
  <div>
    <nav class="navbar fixed-top navbar-expand-lg" style="background-color: #e3f2fd;">
      <div class="container-fluid">
        <NuxtLink class="navbar-brand" to="/">HOME</NuxtLink>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <NuxtLink class="nav-link" to="/">HOME</NuxtLink>
            </li>
            <li class="nav-item">
              <NuxtLink class="nav-link" aria-current="page" to="/test">test</NuxtLink>
            </li>
            <li class="nav-item">
              <NuxtLink class="nav-link" aria-current="page" to="/test">Proyek</NuxtLink>
            </li>
            <li class="nav-item">
              <NuxtLink class="nav-link" aria-current="page" to="/test">test</NuxtLink>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!--- render page -->
    <slot />
  </div>
</template>

<style>
body {
  background-color: rgb(221, 221, 221);
  font-family: "Quicksand", sans-serif;
}
</style>