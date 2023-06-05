<script setup lang="ts">

//meta title
useHead({
  title: 'Welcome',
});

const resume = {
  firstname: 'Muhamad',
  lastname: 'Rizki',
  Job: 'Fullstack Developer',
  city: 'Bogor',
  country: 'Indonesia',
  postalCode: '16962',
  phone: '+62 521-600-0521',
  email: 'muhamadrizki1a@gmail.com',
  language: [
    {
      name: 'Indonesia',
      level: 'Native',
    },
    {
      name: 'English',
      level: 'Beginner',
    },
  ],
  aboutme: 'Saya adalah seorang Fullstack Developer yang berfokus pada pengembangan aplikasi berbasis web. Saya memiliki pengalaman dalam pengembangan aplikasi web menggunakan Laravel dan VueJS. Saya memiliki kemampuan untuk bekerja secara mandiri maupun dalam tim. Saya juga memiliki kemampuan untuk memecahkan masalah dan belajar hal baru dengan cepat.'
}

const education = [
  {
    school: 'SMK Muhammadiyah 2 Cileungsi',
    major: 'Teknik Komputer Jaringan',
    year: '2017 - 2020',
  }
]

const links = [
  {
    label: 'Linkedin',
    link: 'https://www.linkedin.com/in/muhamad-rizki-9ba8551b1/',
  },
  {
    label: 'Github',
    link: 'https://github.com/rizkiarch'
  },
]

</script>

<template>
  <div class="p-5 mb-4 bg-light rounded-3">
    <div class="container-fluid py-5">
      <div class="col-12">
        <div class="row">
          <div class="col-2"></div>
          <div class="col-10">
            <h1 class="display-5 fw-bold">{{ resume.firstname }} {{ resume.lastname }}</h1>
            <p class="col-md-8 fs-4">{{ resume.Job }}</p>
          </div>
        </div>
      </div>
      <div class="border border-primary border-2 opacity-50 d-flex justify-content-center" style="width: 200px; "></div>
      <div class="col-8">
        <div class="d-flex justify-content-center">
          <div class="d-flex flex-column mt-2">
            <h1 class="display-6 fw-bold text-uppercase">Tentang Saya </h1>
            <p class="blockqoute text-justify ">
              {{ resume.aboutme }}
            </p>

          </div>


        </div>
      </div>
      <div class="border border-primary border-2 opacity-50 position-relative" style="width: 200px; "></div>
      <div class="col-12">
        <div class="d-flex justify-content-center">
          <h1 class="display-6 fw-bold text-uppercase">Proyek</h1>
        </div>
      </div>
      <div class="border border-primary border-2 opacity-50 position-relative" style="width: 200px; "></div>
      <div class="col-12">
        <div class="d-flex justify-content-center">
          <h1 class="display-6 fw-bold text-uppercase">Proyek</h1>
        </div>
      </div>
    </div>
  </div>
</template>