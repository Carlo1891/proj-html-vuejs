<template>
  <main>
    <div class="pre-jumbo d-flex justify-content-around p-2 my-3">

      <div>
        <ul>

          <li class="mx-4">
            <i class="fa-solid fa-city"></i>
            Business
          </li>

          <li class="mx-4">
            <i class="fa-solid fa-palette"></i>
            Design
          </li>
        
          <li class="mx-4">
            <i class="fa-solid fa-gear"></i>
            Development
          </li>
        
          <li class="mx-4">
            <i class="fa-solid fa-face-smile"></i>
            Lifestyle
          </li>
        
          <li class="mx-4">
            <i class="fa-solid fa-folder-open"></i>
            Office Productivity
          </li>
        </ul>

      </div>
    </div>

    <div>
      <figure class="jumbotron d-flex">

        <div class="jumbo-text">
          <h2>
            Udemy Affiliate Sales
          </h2>
          <p>
            Monetize your audience and attract new costumers with Udemy!
          </p>
        </div>
       

        <img src="../../../public/img/slide-1.jpg" alt="slide-1" class="img-fluid">
      </figure>
    </div>

    <h4>
      Popular Development Courses
    </h4>

    <p>
      Development >
    </p>

    <p>
      The Complete iOS 10 & Swift 3 Developer Courses
      $199.99
      $100
    </p>

    <p>
      Web Design for Beginners: Real World Coding in HTML & CSS
      $129.99
      $65
    </p>

    <p>
      GitHub Ultimate: Master Git and GitHub - Beginner to Expert
      $99.99
      $50
    </p>

    <p>
      The Complete iOS 11 & Swift Developer Courses - Build 20 Apps
      $199.99
      $100
    </p>

    <p>
      Android Java Masterclass - Become an App Developer
      $99.99
      $50
    </p>

    <p>
      Xamarin Forms: Build Native Cross-platform Apps with C#
      $189.99
      $95
    </p>

    <h2>Limitless learning, more possibilities</h2>
    <p>Online courses open the opportunity for learning to almost anyone,
      regardless of their scheduling commitments.
    </p>
    <a class="btn btn-danger rounded" href="#" role="button">READ MORE</a>

    <h2>Recent courses</h2>

    <a href="#">All Categories</a>
    <a href="#">Business</a>
    <a href="#">Design</a>
    <a href="#">Development</a>
    <a href="#">IT & Software</a>
    <a href="#">Lifestyle</a>
    <a href="#">Marketing</a>
    <a href="#">Office Productivity</a>

    <!-- elenco -->
    <p>
      The Complete iOS 10 & Swift 3 Developer Courses
      $199.99
      $100
    </p>

    

    <a class="btn btn-danger rounded" href="#" role="button">SHOW ALL</a>

    <h4>Subscribe our newsletter</h4>
    <p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words</p>

    <h2>Become an Istructor</h2>
    <p>Teach what you love, Masterstudy gives you the tools to create a course.</p>
    <a class="btn btn-danger rounded" href="#" role="button">START TEACHING</a>

    <h2>Access For Business</h2>
    <p>Get unlimited acess to 2.500 of top courses for your team.</p>
    <a class="btn btn-danger rounded" href="#" role="button">DOING BUSINESS</a>

    <!-- testimonial -->

    <h2>Investing for Your Future</h2>
    <p>It is no exaggeration to say this MasterStudy experience was transformative-both professionally and personally. This workshop will long remain a high point of my life. Thanks again... I am feeling energized and eafer to start teaching my class next week, I can't wait to use all of my new teaching tools. I will absolutely recommend this workshop to other educators!</p>
    <p>Linda Green</p>
    <p>Product Manager, Apple Inc.</p>












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
    width: 100%;
    background-color: $bgTopBarMain;
    color: $bgMainColor;
  }
  .jumbo-text{
    color: white;
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
