<template>
  <div class="container">
    <h1 class="gallery-title mt-5 mb-5">Practice Advice</h1>
    <p class="gallery-text"></p>
    <div class="row mb-5">
      <div class="col">
        <div class="card">
          <img
            src="@/assets/image6.jpg"
            class="card-img-top fluid img h-25"
            alt="..."
          />

          <div class="card-body">
            <h5 class="card-title">Fraud and Misleading Information</h5>
            <div class="card-text text-start">
              <p>
                At Warner & Co law Consultants, we take fraud and misleading
                information seriously. We are dedicated to Adhering to the
                highest ethical standards in all our legal practices.
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img
            src="@/assets/image3.jpg"
            class="card-img-top fluid img h-25"
            alt="..."
          />

          <div class="card-body">
            <h5 class="card-title">Bails and Warrants</h5>
            <div class="card-text text-start">
              <p>
                We assist clients by navigating bail bond processes to secure
                pretrial release and address warrants, providing legal expertise
                and representation throughout the legal proceedings.
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img
            src="@/assets/image4.jpg"
            class="card-img-top fluid img h-25"
            alt="..."
          />

          <div class="card-body">
            <h5 class="card-title">Drug Crimes</h5>
            <div class="card-text text-start">
              <p>
                Defending individuals facing drug-related
                charges, offering expert legal counsel and representation to
                navigate complex drug crime cases and seek the best possible
                outcomes for our clients.
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img
            src="@/assets/image5.jpg"
            class="card-img-top fluid img h-25"
            alt="..."
          />

          <div class="card-body">
            <h5 class="card-title">Traffic Crimes</h5>
            <div class="card-text text-start">
              <p>
                We provides comprehensive legal support for
                individuals dealing with traffic-related offenses, leveraging our
                expertise to protect our clients' rights and minimize legal
                consequences.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "GallerySection",
};
</script>

<style scoped>
.gallery-title {
  color: #090909;
  text-align: center;
  font-family: Bebas Neue;
  font-size: 60px;
  font-style: normal;
  font-weight: 400;
  line-height: 30px;
}

.gallery-text {
  color: #090909;
  text-align: center;
  font-family: Bebas Neue;
  font-size: 25px;
  font-style: normal;
  font-weight: 400;
  line-height: 30px;
}
.card {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.card-title {
  font-size: 20px;
  font-weight: bold;
  margin-bottom: 10px;
  color: #333; /* Text color */
}

.card-text {
  font-size: 16px;
  line-height: 1.5; /* Adjust line height for readability */
  color: #666; /* Text color */
}
</style>
