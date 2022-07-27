<template>
  <main>
    <div class="pre-jumbo d-flex justify-content-around">

      <div>
        <ul>

          <li>
            <i class="fa-solid fa-city"></i>
            Business
          </li>

          <li>
            <i class="fa-solid fa-palette"></i>
            Design
          </li>
        
          <li>
            <i class="fa-solid fa-gear"></i>
            Development
          </li>
        
          <li>
            <i class="fa-solid fa-face-smile"></i>
            Lifestyle
          </li>
        
          <li>
            <i class="fa-solid fa-folder-open"></i>
            Office Productivity
          </li>
        </ul>

      </div>
    </div>

    <div>
      <figure class="jumbotron d-flex">
        <h1 class="text-white">
          Udemy Affiliate Sales
        </h1>

        <img src="../../../public/img/slide-1.jpg" alt="slide-1" class="img-fluid">
      </figure>
    </div>
  </main>
</template>

<script>

  export default {
    name: 'Main',
  }

</script>


<style scoped lang="scss">

  @import "../../assets/styles/variables.scss";

  .pre-jumbo {
    margin: 0 auto;
    width: 70%;
  }

  div>ul {
    list-style: none;
  }

  ul>li {
    display: inline-block;
  }
  .jumbotron{
    background-color: $bgJumbotron;
  }
</style>
