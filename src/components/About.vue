<template functional>
  <section class='section-about'>
    <div class='u-center-text u-margin-bottom-big'>
      <h2 class='heading-secondary'>
        Exciting tours for adventurous people
      </h2>
    </div>
    <div class='row'>
      <div class='col-1-of-2'>
        <h3 class='heading-tertiary u-margin-bottom-small'>You're going to fall in love with nature</h3>
        <p class='paragraph'>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ut eius, deleniti nam eum nihil voluptate esse dicta unde atque, illo quisquam quidem voluptatem incidunt consequatur laboriosam nemo. Inventore, eos dicta?</p>
        <h3 class='heading-tertiary u-margin-bottom-small'>Live adventures like you never have before</h3>
        <p class='paragraph'> unde atque, illo quisquam quidem voluptatem incidunt consequatur laboriosam nemo. Inventore, eos dicta?</p>

        <a
          href='#'
          class='btn-text'
        >Learn more &rarr;</a>
      </div>
      <div class='col-1-of-2'>
        <div class='composition'>
          <img
            srcset="../assets/img/nat-1.jpg 300w, ../assets/img/nat-1-large.jpg 1000w"
            sizes="(max-width: 56.25em) 20vw, (max-width: 37.5em) 30vw, 300px"
            alt='Photo 1'
            class='composition__photo composition__photo--p1'
            src='../assets/img/nat-1-large.jpg'
          >
          <img
            srcset="../assets/img/nat-2.jpg 300w, ../assets/img/nat-2-large.jpg 1000w"
            sizes="(max-width: 56.25em) 20vw, (max-width: 37.5em) 30vw, 300px"
            alt='Photo 2'
            class='composition__photo composition__photo--p2'
            src='../assets/img/nat-2-large.jpg'
          >
          <img
            srcset="../assets/img/nat-3.jpg 300w, ../assets/img/nat-3-large.jpg 1000w"
            sizes="(max-width: 56.25em) 20vw, (max-width: 37.5em) 30vw, 300px"
            alt='Photo 3'
            class='composition__photo composition__photo--p3'
            src='../assets/img/nat-3-large.jpg'
          >
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "About"
};
</script>
