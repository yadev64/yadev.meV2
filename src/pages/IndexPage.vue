<template>
  <div class="about-area" style="height: 100vh; width: 100vw">
    <div style="width: 100vw">
      <!-- <section class="updated-banner-area">
        <div class="container"> -->
      <div class="row flex flex-center">
        <div
          class="banner-content col-lg-12 col-md-12 justify-content-center flex flex-center"
          style="height: 100vh"
        >
          <div class="row">
            <div class="col-12">
              <div
                class="me wow fadeInDown"
                data-wow-duration="1s"
                data-wow-delay="0.7s"
              >
                Hi, I'm
              </div>
              <h1
                class="wow fadeInUp h1-cover"
                data-wow-duration="1s"
                data-wow-delay="1.0s"
              >
                Yadev Jayachandran
              </h1>
              <h6
                class="designation mb-50 wow fadeInUp q-px-md"
                style="max-width: 800px; margin: auto"
                data-wow-duration="1s"
                data-wow-delay="1.3s"
              >
                A technologist, designer &amp; educator who loves to experiment
                on the edge of
                <span class="designer">Design</span>
                and
                <span class="developer">Technology</span>
              </h6>
            </div>

            <div class="col-12 q-mt-xl">
              <div
                class="footer-social wow fadeInUp"
                data-wow-duration="1s"
                data-wow-delay="1.8s"
              >
                <a
                  href="https://www.linkedin.com/in/yadev-jayachandran/"
                  target="_blank"
                  ><i class="fa fa-linkedin"></i
                ></a>
                <a href="https://www.behance.net/yadev64" target="_blank"
                  ><i class="fa fa-behance"></i
                ></a>
                <a href="https://github.com/yadev64" target="_blank"
                  ><i class="fa fa-github"></i
                ></a>
                <a
                  href="https://www.facebook.com/yadev.jayachandran"
                  target="_blank"
                  ><i class="fa fa-facebook"></i
                ></a>
                <a href="https://twitter.com/yadev64" target="_blank"
                  ><i class="fa fa-twitter"></i
                ></a>
                <a href="https://www.instagram.com/yadev64/" target="_blank"
                  ><i class="fa fa-instagram"></i
                ></a>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- </div>
      </section> -->
    </div>
  </div>

  <q-page class="flex flex-center">
    <!-- <img
      alt="Quasar logo"
      src="~assets/quasar-logo-vertical.svg"
      style="width: 200px; height: 200px"
    /> -->
    <q-card style="height: 100px; width: 100px">sdg</q-card>
    <q-card style="height: 100px; width: 100px">sdg</q-card>
  </q-page>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "IndexPage",
});
</script>

<style scoped>
.about-area {
  background: linear-gradient(
    -45deg,
    #00ff6a,
    #006eff,
    #002fff,
    #8400ff,
    #ae00ff
  );
  background-size: 400% 400%;
  animation: gradient 13s ease infinite;
}
.about-area p,
.about-area h2 {
  text-align: justify;
  text-justify: inter-word;
  color: #fff;
}
@media (max-width: 600px) {
  .about-area {
    background: linear-gradient(
      -45deg,
      #00ff6a,
      #00aeff,
      #006eff,
      #002fff,
      #8400ff,
      #ae00ff,
      #9900ff
    );
    background-size: 300% 300%;
    animation: gradient 10s ease infinite;
  }
}
@keyframes gradient {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}
.about-area .section-title {
  margin-bottom: 0;
}
@media (max-width: 1024px) {
  .about-area .section-title {
    padding-bottom: 0px;
  }
}
@media (max-width: 991px) {
  .about-area .about-left {
    display: block;
    padding-top: 30px;
  }
}
.about-area .primary-btn.white {
  margin-right: 10px;
}
@media (max-width: 1199px) {
  .about-area .primary-btn.white {
    margin-right: 0;
    margin-bottom: 15px;
  }
}
@media (max-width: 991px) {
  .about-area .primary-btn.white {
    margin-bottom: 0px;
  }
}
@media (max-width: 380px) {
  .about-area .primary-btn.white {
    margin-right: 0;
    margin-bottom: 15px;
  }
}
</style>
