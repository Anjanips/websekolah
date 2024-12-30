<template>
  <nav class="navbar navbar-expand-lg bg-secondary bg-body-tertiary sticky-top">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <div class="align-items-center">
          <img src="assets/img/logo smk(1).png" alt="Logo" width="50" height="50"
            class="d-inline-block align-text-bootom">
          <span>
            SMK NEGERI 4
          </span>
          TASIKMALAYA
        </div>

      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown"
        aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNavDropdown">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="/">HOME</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link active dropdown-toggle " href="#" role="button" data-bs-toggle="dropdown"
              aria-expanded="false">
              PROFIL
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="/profil/sejarah/">SEJARAH</a></li>
              <li><a class="dropdown-item" href="/profil/visi/">VISI & MISI</a></li>
              <li><a class="dropdown-item" href="/profil/kk/">KOMPETENSI KEAHLIAN</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="/eskul">EKSTRAKURIKULER</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="/album">GALERI</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

</template>
<style scoped></style>