<template functional>
  <div
    class='popup'
    id="popup"
  >
    <div class='popup__content'>
      <div class='popup__left'>
        <img
          src='../assets/img/nat-8.jpg'
          alt='Tour photo'
          class="popup__img"
        >
        <img
          src='../assets/img/nat-9.jpg'
          alt='Tour photo'
          class="popup__img"
        >
      </div>
      <div class='popup__right'>
        <a
          href='#section-tours'
          class='popup__close'
        >&times;</a>
        <h2 class='heading-secondary u-margin-bottom-small'>Start booking now</h2>
        <h3 class='heading-tertiary u-margin-bottom-small'>Important &ndash; Please read these terms before booking</h3>
        <p class='popup__text'>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Corporis ipsum sit odit officia facere delectus incidunt perferendis temporibus voluptates quaerat itaque eum, reiciendis, maiores et neque, laudantium sunt repellat suscipit! Corporis ipsum sit odit officia facere delectus incidunt perferendis temporibus voluptates quaerat itaque eum. Corporis ipsum sit odit officia facere delectus incidunt perferendis temporibus voluptates quaerat itaque eum, reiciendis, maiores et neque, laudantium sunt repellat suscipit! Corporis ipsum sit odit officia facere delectus incidunt perferendis temporibus voluptates quaerat itaque eum, reiciendis, maiores et neque, laudantium sunt repellat suscipit! maiores et neque, laudantium sunt repellat suscipit! maiores et neque, laudantium sunt repellat suscipit!</p>
        <a
          href='#'
          class='btn btn--green'
        >Book now</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PopUp"
};
</script>
