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
    <main>
      <section>
        <div class="d-flex flex-column align-items-center mb-5">
        <h1>Learn At Your Own Pace!</h1>
        <h6>Get teamed up with peaple of the same will.</h6>
        <button type="button" class="btn btn-green">Success</button>
        </div>
        <div>
          <img src="./images/home-6-hero-left-person-244x300.png" alt="">
          <img src="./images/home-6-hero-poster-final.jpg" alt="">
          <!-- remeber to add playbutton and shift the img -->
          <img src="./images/home-6-hero-right-person-195x300.png" alt="">
        </div>
        <aside>

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
section{
  background-color:$portGore;
  color:white;
  display: flex;
  flex-direction: column;
  align-items: center;
  position: relative;
  .btn-green{
    background-color:$mountainMeadow;
    color:white;
  }
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
</style>
