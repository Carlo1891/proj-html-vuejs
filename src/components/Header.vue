<template>
  <header>
    <div class="top-bar d-flex justify-content-around">

      <div class="pick-language">
        English
      </div>

      <nav class="d-flex">
        <ul class="d-flex">

          <li>Home</li>
          <li>Pages</li>
          <li>Course Formats</li>
          <li>Courses</li>
          <li>Demos</li>
            
        </ul>

        <ul class="d-flex">

          <li><i class="fa-brands fa-facebook-f"></i></li>
          <li><i class="fa-brands fa-twitter"></i></li>
          <li><i class="fa-brands fa-instagram"></i></li> 
          <li><i class="fa-brands fa-linkedin"></i></li> 
          <li><i class="fa-brands fa-google-plus"></i></li> 
          <li><i class="fa-brands fa-youtube"></i></li>

        </ul>
      </nav>

    </div>
  </header>
</template>

<script>

  export default {
    name: 'Header',
    data() {
      return {
        navLinks: [
          {
              name: "Home",
              url: "#",
              id: 1,
          },
        ],
      };
    }
  }
  
</script>


<style scoped lang="scss">
  .top-bar {
    border-bottom: 1px solid lightgrey;
  }

  nav ul {
    list-style: none;
    border-spacing: 5px;
  }

</style>
