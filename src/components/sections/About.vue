<script>
export default {
  name: "About",
};
</script>

<template>
  <div class="content">
    <section class="section-about">
      <div class="about-box">
        <h1>About Us</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor
          quaerat, blanditiis explicabo id quae nostrum at eius dolorem neque
          accusantium quibusdam itaque doloribus ullam enim necessitatibus
          eligendi vel dicta excepturi.
        </p>
        <button class="btn-home">Learn More</button>
      </div>
      <div class="about-box2">
        <h1>Our Histoty</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor
          quaerat, blanditiis explicabo id quae nostrum at eius dolorem neque
          accusantium quibusdam itaque doloribus ullam enim necessitatibus
          eligendi vel dicta excepturi.
        </p>
        <button class="btn-home">Learn More</button>
      </div>
    </section>
  </div>
</template>

<style scoped>
.section-about {
  display: flex;
  height: 100vh;
  width: 100%;
  background-image: url("https://images.pexels.com/photos/695644/pexels-photo-695644.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940");
  background-position: center;
  background-size: cover;
  background-attachment: fixed;
  justify-content: space-between;
  align-items: center;
  padding: 0 2rem;
}

.about-box {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  width: 45%;
  color: #fff;
}

.about-box2 {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  width: 45%;
  color: #fff;
}

.about-box h1,
.about-box2 h1 {
  font-size: 3em;
  color: #ffa500;
  font-family: "Dancing Script", cursive;
}

.about-box p,
.about-box2 p {
  margin: 1rem 0;
}

@media (max-width: 680px) {
  .section-about {
    padding: 2rem 0;
    flex-direction: column;
    justify-content: space-evenly;
    height: auto !important;
  }

  .about-box,
  .about-box2 {
    width: 100%;
    align-items: center;
    justify-content: center;
    text-align: center;
    margin: 1rem 0;
  }

  .about-box p,
  .about-box2 p {
    padding: 0 2rem;
  }
}
</style>