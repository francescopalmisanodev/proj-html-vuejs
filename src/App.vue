<template>
  <div>
    <header class="pb-5">
      <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Navbar</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Dropdown
                </a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Dropdown
                </a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Dropdown
                </a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Dropdown
                </a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Dropdown
                </a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Dropdown
                </a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Dropdown
                </a>
              </li>   
              <li>
                <form class="d-flex">
                <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-success" type="submit">Search</button>
                </form>
              </li>       
            </ul>
          </div>
        </div>
      </nav>
    </header>
    <main class="d-flex flex-column align-items-center">
      <section class="hero mb-5 w-100">
        <div class="d-flex flex-column align-items-center mb-5">
        <h1>Learn At Your Own Pace!</h1>
        <h6>Get teamed up with peaple of the same will.</h6>
        <button type="button" class="btn btn-green">Success</button>
        </div>
        <div class="heroImg">
          <img src="./images/home-6-hero-left-person-244x300.png" alt="">
          <img src="./images/home-6-hero-poster-final.jpg" alt="">
          <!-- remeber to add playbutton and shift the img -->
          <img src="./images/home-6-hero-right-person-195x300.png" alt="">
        </div>
        <aside>
          <!-- add icons (fontawesome is already installed) -->
        </aside>
      </section>
      <section class="d-flex flex-column align-items-center w-75 p-5 text-center"> 
        <h2 class="mb-5 w-50">Let passion and determination be the guide along the way and develop at your own pace that's confortable</h2>
        <h6 class="mb-2">FANNIE MORENO</h6>
        <span class="fw-light mb-5">/Founder and CEO</span>
        <div class="stats d-flex w-75 justify-content-between mt-5">
          <div class="d-flex flex-column align-items-center">
            <h1 class="greenTxt fw-bold">1.926</h1>
            FINISHED SESSION
          </div>
          <div class="d-flex flex-column align-items-center">
            <h1 class="greenTxt fw-bold">3.092+</h1>
            ENROLLED LEARNERS
          </div>
          <div class="d-flex flex-column align-items-center">
            <h1 class="greenTxt fw-bold">200</h1>
            ONLINE INSTRUCTOR
          </div>
          <div class="d-flex flex-column align-items-center">
            <h1 class="greenTxt fw-bold">100%</h1>
            SATISFACTION RATE
          </div>
        </div>
      </section>
      <section class="d-flex justify-content-center align-items-center">
        <div class="cards w-50">

        </div>
        <aside class="d-flex flex-column align-items-start w-50 p-5">
          <span>TOGETHER WE CAN CREATE</span>
          <h1 class="fw-bold">Services We <span class="fw-normal greenTxt">Can Provide</span> For My Clients.</h1>
          <ul class="list-unstyled">
            <!-- add icons -->
            <li>Slect e customize courses to your preferences</li>
            <li>Change the tutor and make arrangements</li>
            <li>Participate in events to join others</li>
            <li>Get the desired certificate delivered at your house</li>
          </ul>
          <button type="button" class="btn btn-green py-2 px-4">Get started for free</button>
        </aside>
      </section>
    </main>
    <footer>

    </footer>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style lang="scss">
@import "./scss/variables.scss";
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
header{
  background-color:$portGore;
  color:white;
  display: flex;
  justify-content: center;
}
.hero{
  background-color:$portGore;
  color:white;
  display: flex;
  flex-direction: column;
  align-items: center;
  position: relative;
  
  // .heroImg{
  //   transform: translate(0 ,+30%);
  //   overflow: hidden;
  // }
  aside{
    position: absolute;
    top:30%;
    right:0;
    background-color:white;
    width: 40px;
    height: 150px;
    border-top-left-radius:8px;
    border-bottom-left-radius:8px;
    transform: translate(0, -50%);
  }
}
.greenTxt{
  color:$mountainMeadow;
}
.btn.btn-green{
    background-color:$mountainMeadow;
    color:white;
}
</style>
