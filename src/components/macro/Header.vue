<template>
  <header>
    <div class="top-bar d-flex justify-content-between px-5">

      <div>
        <p>English <i class="fa-solid fa-angle-down"></i></p>
      </div>

      <nav>
        <ul>
          <li>Home</li>
          <li>Pages</li>
          <li>Course Formats</li>
          <li>Course</li>
          <li>Demos</li>
        </ul>

        <ul>
          <li><i class="fa-brands fa-facebook-f"></i></li>
          <li><i class="fa-brands fa-twitter"></i></li>
          <li><i class="fa-brands fa-instagram"></i></li> 
          <li><i class="fa-brands fa-linkedin"></i></li> 
          <li><i class="fa-brands fa-google-plus"></i></li> 
          <li><i class="fa-brands fa-youtube"></i></li>
        </ul>
      </nav>

    </div>
    <div class="d-flex px-5">
      <figure class="img-fluid">
        <img src="../../../public/img/MasterStudy.svg" alt="master study">
      </figure>

      <div>
        <input type="text" placeholder="Search Courses">
        <a href="#" role="button"><i class="fa-solid fa-magnifying-glass p-2"></i></a>
      </div>

      <div>
        
        <a href="#">Become an Istructor</a>
        <a href="#">For Enterprise</a>
        
      </div>

      <div>
        <a href="#">Log in</a>
        <a class="btn btn-danger rounded" href="#" role="button">Sign In</a>
      </div>

      <div>
        <i class="fa-solid fa-bookmark"></i>
      </div>
    </div>
  </header>
</template>

<script>

  export default {
    name: 'Header',
  }
  
</script>


<style scoped lang="scss">

  .top-bar {
    border-bottom: 1px solid lightgray;
    padding-top: 15px;
  }

  nav {
    display: flex;
  }

  nav>ul {
    display: flex;
    list-style: none;
  }

</style>
