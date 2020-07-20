<template functional>
  <section class='section-stories'>
    <div class='bg-video'>
      <video
        class='bg-video__content'
        autoplay
        muted
        loop
      >
        <source
          src="../assets/img/video.mp4"
          type="video/mp4"
        >
        <source
          src="../assets/img/video.webm"
          type="video/webm"
        >
        Your browser is not supported!
      </video>
    </div>
    <div class='u-center-text u-margin-bottom-big'>
      <h2 class='heading-secondary'>
        We make people genuinely happy
      </h2>
    </div>
    <div class='row'>
      <div class='story'>
        <figure class='story__shape'>
          <img
            srcset="../assets/img/nat-8-small.jpg 500w, ../assets/img/nat-8.jpg 2000w"
            sizes="(max-width: 900px) 30vw, (max-width: 600px) 40vw, 285px"
            alt='Person on a tour'
            class="story__image"
            src='../assets/img/nat-8.jpg'
          >
          <figcaption class='story__caption'>Mary Smith</figcaption>
        </figure>
        <div class='story__text'>
          <h3 class='heading-tertiary u-margin-bottom-small'>I had the best week ever with my family</h3>
          <p>
            eius, deleniti nam eum nihil voluptate esse dicta unde atque. eius, deleniti nam eum nihil voluptate esse dicta unde atque. eius, deleniti nam eum nihil voluptate esse dicta unde atque deleniti nam eum nihil voluptate esse dicta unde atque l voluptate esse dicta unde atque l voluptate esse dicta unde atque
          </p>
        </div>
      </div>
    </div>
    <div class='row'>
      <div class='story'>
        <figure class='story__shape'>
          <img
            srcset="../assets/img/nat-9-small.jpg 500w, ../assets/img/nat-9.jpg 2000w"
            sizes="(max-width: 900px) 30vw, (max-width: 600px) 40vw, 285px"
            alt='Person on a tour'
            class="story__image"
            src='../assets/img/nat-9.jpg'
          >
          <figcaption class='story__caption'>Jack Wilson</figcaption>
        </figure>
        <div class='story__text'>
          <h3 class='heading-tertiary u-margin-bottom-small'>WOW! My life is completely different now</h3>
          <p>
            eius, deleniti nam eum nihil voluptate esse dicta unde atque. eius, deleniti nam eum nihil voluptate esse dicta unde atque. eius, deleniti nam eum nihil voluptate esse dicta unde atque deleniti nam eum nihil voluptate esse dicta unde atque l voluptate esse dicta unde atque l voluptate esse dicta unde atque
          </p>
        </div>
      </div>
    </div>
    <div class='u-center-text u-margin-top-huge'>
      <a
        href='#'
        class='btn-text'
      >Read all stories &rarr;</a>
    </div>
  </section>
</template>

<script>
export default {
  name: "Stories"
};
</script>