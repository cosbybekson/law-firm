<template>
    <nav class="navbar navbar-expand-lg text-white p-0">
      <div class="container-fluid">
        <div class="navbar-brand justify-content-start ">
          <img class="img-fluid me-2" src="@/assets/logo.jpeg" alt="" />
          <h3 class="navbar-brand-text my-auto">Warner & Co law Consultants</h3>
        </div>
        <div class="d-flex justify-content-end" id="navbarSupportedContent">
          <ul class="navbar-nav my-auto me-5">
            <li class="nav-item">
              <a class="nav-link active text-white" aria-current="page" href="#"
                >Home</a
              >
            </li>
            <li class="nav-item dropdown text-white">
              <a
                class="nav-link dropdown-toggle text-white"
                href="#"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                Services
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Criminal Defense</a></li>
                <li><a class="dropdown-item" href="#">Family Law</a></li>
                <li><a class="dropdown-item" href="#">Corporate Law</a></li>
                <li><a class="dropdown-item" href="#">Real Estate Law</a></li>
              </ul>
            </li>
            <li class="nav-item text-white">
              <a class="nav-link text-white" href="#">About</a>
            </li>
          </ul>
          <button class="btn" type="submit">Contact</button>
        </div>
      </div>
    </nav>
  </template>
  
  <script>
  export default {
    name: "Nav-bar",
  };
  </script>
  
  <style scoped>
  .navbar {
    background: rgba(8, 8, 8, 0.95);
  }
  
  .navbar-brand {
    display: flex;
    padding: 0px;
  }
  
  .nav-item {
    color: #fff;
    font-family: "Bebas Neue", sans-serif;
    font-size: 24px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    text-transform: capitalize;
  }
  
  .navbar-brand-text {
    color: #fff;
    font-family: "Bebas Neue", sans-serif;
    font-size: 28px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    text-transform: capitalize;
  }
  
  .brand-img {
    margin-right: 1px;
  }
  
  img {
    width: 58px;
    height: 61px;
  }
  
  .btn {
    border-radius: 0px;
    padding: 14px 32px;
    background: #49e4e4;
    color: white;
    font-family: "Bebas Neue", sans-serif;
    font-size: 24px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    text-transform: capitalize;
  }
  </style>