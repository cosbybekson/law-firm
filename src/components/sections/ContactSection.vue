<template>
  <div class="contact-section">
    <div class="container p-5">
      <div class="row">
        <div class="col">
          <h1 class="contact-title text-start">Contact Us!</h1>
          <p class="contact-text">
            <i class="bi bi-envelope"></i>
            <a href="mailto:warner.joseph607@gmail.com"
              >warner.joseph607@gmail.com</a
            >
          </p>
          <p class="contact-text">+233 50 900 2404</p>
          <p class="contact-text">
            215 South Liberation Link. Airport City, Accra. Ghana.
          </p>
        </div>
        <div class="col">
          <h1 class="contact-title text-start">Send us a message</h1>
          <p class="contact-text">
            We would love to hear from you. Please get in touch with us if you
            have any legal related issues."
          </p>
          <form>
            <div class="mb-3 text-start">
              <label for="text" class="form-label">Your Name</label>
              <input
                type="text"
                class="form-control"
                id="exampleFormControlInput1"
              />
            </div>
            <div class="mb-3 text-start">
              <label for="email" class="form-label">Your Email</label>
              <input
                type="email"
                class="form-control"
                id="exampleFormControlInput1"
              />
            </div>
            <div class="mb-3 text-start">
              <label for="phoneInput" class="form-label">Your Number</label>
              <input
                type="tel"
                class="form-control"
                id="exampleFormControlInput1"
              />
            </div>
            <div class="mb-3 text-start">
              <label for="text" class="form-label">Example textarea</label>
              <textarea
                class="form-control"
                id="exampleFormControlTextarea1"
                rows="3"
              ></textarea>
            </div>
          </form>
          <div class="submit text-start">
            <button type="button" class="btn">Submit</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContactSection",
};
</script>

<style scoped>
.contact-section {
  background: #dedada;
}

.contact-title {
  color: #0a142f;
  text-align: center;
  font-family: Open Sans;
  font-size: 30px;
  font-style: normal;
  font-weight: 700;
}

.contact-text {
  color: #000;
  text-align: center;
  font-family: Open Sans;
  font-size: 20px;
  font-style: normal;
  font-weight: 400;
  text-align: start;
}

.contact-text a {
  text-decoration: none;
  color: #000;
}
button {
  border-radius: 5px;
  background: #49e4e4;
  color: white;
}
</style>
