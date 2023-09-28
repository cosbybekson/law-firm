<template>
  <div class="container-fliud">
    <div class="hero-img">
      <div class="container">
        <div class="row">
          <div class="col-6 hero-badge mt-5">
            <p class="hero-badge-text text-start mt-5">
              Help to reclaim your life and freedom.
            </p>
            <div class="text-start">
              <button type="button" class="btn mt-4">About Us</button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="hero-content">
      <div class="row">
        <div class="col-3 mt-5">
          <h1 class="hero-title mt-5">
            MISSION <br />
            & <br />
            VISION
          </h1>
        </div>
        <div class="col">
          <div class="vr mt-5"></div>
        </div>
        <div class="col-8 text-start">
          <p class="hero-text mt-5">
            At Warner & Co law Consultants, our mission is to provide
            exceptional legal services to our clients...
          </p>
          <p class="hero-text mt-2">
            Our vision is to be a trusted partner for our clients, guiding them
            through legal challenges with integrity and empathy
          </p>
          <button type="button" class="btn mb-5">Get Involve</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
};
</script>

<style scoped>
.hero-img {
  background-image: url("/src/assets/image1.jpg");
  background-size: cover;
  height: 700px;
  background-color: rgba(0, 0, 0, 0.5);
  background-blend-mode: darken;
}

.hero-badge-text {
  color: #fff;
  font-family: "Open Sans", sans-serif;
  font-size: 40px;
  font-style: normal;
  font-weight: 600;
  letter-spacing: 0.2px;
}

.hero-badge {
  padding: 80px 0 70px 0;
}

.hero-text {
  color: black;
  font-family: Open Sans;
  font-size: 20px;
  font-style: normal;
  font-weight: 300;
  letter-spacing: 0.2px;
}

.hero-content {
  background-color: #f4f3f3;
}

.vr {
  width: 3px;
  height: 250px;
  background-color: #797878;
}

.hero-title {
  color: #726a6a;
  font-family: Open Sans;
  font-size: 40px;
  font-style: normal;
  font-weight: 700;
  line-height: 20px; /* 50% */
  letter-spacing: 0.2px;
}

.btn {
  border-radius: 5px;
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
