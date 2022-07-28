<template>
  <header>
    <div class="top-bar d-flex justify-content-between px-5">

      <div>
        <p class="head-text">English <i class="fa-solid fa-angle-down"></i></p>
      </div>

      <nav class="d-flex">
        <ul>

          <a href="#">
            <li class="mx-1">Home</li>
          </a>

          <a href="#">
            <li class="mx-1">Pages</li>
          </a>

          <a href="#">
           <li class="mx-1">Course Formats</li>
          </a>

          <a href="#">
            <li class="mx-1">Course</li>
          </a>

          <a href="#">
            <li class="mx-1">Demos</li>
          </a>
        </ul>

        <ul>
          <a href="#">
            <li><i class="fa-brands fa-facebook-f mx-1"></i></li>
          </a>

          <a href="#">
           <li><i class="fa-brands fa-twitter mx-1"></i></li>
          </a>

          <a href="#">
            <li><i class="fa-brands fa-instagram mx-1"></i></li> 
          </a>

          <a href="#">
            <li><i class="fa-brands fa-linkedin mx-1"></i></li>
          </a>

          <a href="#">
            <li><i class="fa-brands fa-google-plus mx-1"></i></li> 
          </a>

          <a href="#">
            <li><i class="fa-brands fa-youtube mx-1"></i></li>
          </a>

        </ul>
      </nav>

    </div>

    <div class="bottom-bar d-flex justify-content-between px-5 py-3">
      <figure class="img-fluid">
        <img src="../../../public/img/MasterStudy.svg" alt="master study">
      </figure>

      <div>
        <i class="fa-solid fa-bars"></i>
        Category
        <input type="text" placeholder="Search Courses" class="searchbar">
        <a href="#" role="button" class="search"><i class="fa-solid fa-magnifying-glass p-2 mx-1"></i></a>
      </div>

      <div>
        
        <a href="#" class="mx-2">
          <i class="fa-solid fa-volume-high"></i>Become an Istructor
        </a>

        <a href="#" class="mx-2">
          <i class="fa-solid fa-briefcase"></i>For Enterprise
        </a>
        
      </div>

      <div>
        <a href="#" class="mx-2">
          <i class="fa-solid fa-user"></i>Log in
        </a>

        <a class="btn btn-danger rounded" href="#" role="button">SIGN UP</a>
        <i class="fa-solid fa-bookmark mx-3"></i>
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

  @import "../../assets/styles/variables.scss";


  .top-bar {
    border-bottom: 1px solid lightgray;
    padding-top: 15px;
  }

  .head-text {
    color: $textHeader;
  }

  nav ul {
    display: flex;
    list-style: none;
    & a{
      text-decoration: none;
      color: $textHeader;
    }
  }

  .searchbar{
    width: 300px;
  }
  .search {
    background-color: cornflowerblue;
    padding: 0.4rem;
  }

  .bottom-bar a {
      text-decoration: none;
  }

</style>
