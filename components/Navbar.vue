<template>
  <nav class="navbar navbar-expand-lg bg-tranparent py-3">
    <div class="container-fluid">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="mx-auto navbar-nav">
          <li class="nav-item mx-5">
            <a class="nav-link  fw-bold text-dark" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item mx-5">
            <a class="nav-link fw-bold text-dark" href="#">Contact</a>
          </li>
          <li class="nav-item mx-5">
            <a class="nav-link fw-bold text-dark" href="#">Affiliate</a>
          </li>
          <li class="nav-item mx-5">
            <a class="nav-link fw-bold text-dark">About</a>
          </li>
          <li class="nav-item mx-5">
            <a class="nav-link fw-bold text-dark">FAQ</a>
          </li>
        </ul>
      </div>
    </div>
</nav>
</template>

<script>
export default {
  name:"header"
}
</script>

<style>
li.nav-item a.nav-link{
  font-size: 25px;
}
</style>
