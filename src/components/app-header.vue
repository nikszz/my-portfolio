<template>
  <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-global py-4">
    <div class="container-fluid">
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarsExample08"
        aria-controls="navbarsExample08"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div
        class="collapse navbar-collapse justify-content-md-center"
        id="navbarsExample08"
      >
        <ul class="navbar-nav ls-header">
          <li class="nav-item" v-for="item in nav" :key="item.id">
            <a class="nav-link active mx-4" aria-current="page" href="#">{{
              item.name
            }}</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "AppHeader",
  methods: {},
  data() {
    return {
      nav: [
        {
          id: "1",
          name: "Intro",
        },

        {
          id: "2",
          name: "About",
        },

        {
          id: "3",
          name: "Works",
        },

        {
          id: "4",
          name: "Connect",
        },
      ],
    };
  },
};
</script>
