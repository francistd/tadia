<script>
  import Pie from "../Pie.svelte";
</script>

<style>
.color {
  background-color: rgb(222, 222, 222);
}
</style>

<section class="color hero mb-2">
  <div class="hero-body">
    <div class="container">
      <h2 class="title is-2 has-text-centered mt-4">
        Nosotros
      </h2>
    </div>
  </div>
</section>

<div class="container">
  <figure class="image is-128x128 container mt-4">
    <img
      class="is-rounded"
      alt="img"
      src="https://bulma.io/images/placeholders/128x128.png" />
  </figure>
  <div class="container">
  <p class="has-text-centered mt-5 mb-3">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat, dolores
      quam? Quaerat officia laboriosam odio cumque rerum eligendi iure sunt
      odit? Doloremque nam error dolorum velit reiciendis voluptatibus
      voluptatem sunt!
    </p>
  </div>
</div>

<div class="container ">
  <div class="hero-body">

    <div class="tile is-ancestor">
      <div class="tile mr-3 mb-2">
        <article class="message is-light ">
          <div class="message-body">
            <figure class="image is-128x128 container">
              <img
                class="is-rounded"
                alt="img"
                src="https://bulma.io/images/placeholders/128x128.png" />
            </figure>
            <p class="has-text-centered">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid
              distinctio obcaecati, cupiditate sit eaque sint enim? Nobis modi
              dolore ratione earum? Dolorem laboriosam facere et iste labore
              temporibus molestiae numquam.
            </p>
          </div>
        </article>
      </div>

      <div class="tile mr-3 mb-2">
        <article class="message is-primary">
          <div class="message-body">
            <figure class="image is-128x128 container">
              <img
                class="is-rounded"
                alt="img"
                src="https://bulma.io/images/placeholders/128x128.png" />
            </figure>
            <p class="has-text-centered">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid
              distinctio obcaecati, cupiditate sit eaque sint enim? Nobis modi
              dolore ratione earum? Dolorem laboriosam facere et iste labore
              temporibus molestiae numquam.
            </p>
          </div>
        </article>
      </div>

      <div class="tile mr-3 mb-2">
        <article class="message is-primary ">
          <div class="message-body">
            <figure class="image is-128x128 container">
              <img
                class="is-rounded"
                alt="img"
                src="https://bulma.io/images/placeholders/128x128.png" />
            </figure>
            <p class="has-text-centered">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid
              distinctio obcaecati, cupiditate sit eaque sint enim? Nobis modi
              dolore ratione earum? Dolorem laboriosam facere et iste labore
              temporibus molestiae numquam.
            </p>
          </div>
        </article>
      </div>

    </div>
  </div>
</div>

<section class="color hero">
  <div class="hero-body">
    <div class="container">
      <h1 class="title is-2 has-text-centered mt-4">Personal</h1>
    </div>
  </div>
</section>

<div class="container">
  <figure class="image is-128x128 container mt-4">
    <img
      class="is-rounded"
      alt="img"
      src="https://bulma.io/images/placeholders/128x128.png" />
  </figure>
  <div class="container">
  <p class="has-text-centered mt-3 mb-3">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat, dolores
      quam? Quaerat officia laboriosam odio cumque rerum eligendi iure sunt
      odit? Doloremque nam error dolorum velit reiciendis voluptatibus
      voluptatem sunt!
    </p>
  </div>
</div>

<section class="color hero">
  <div class="hero-body">
    <div class="container">
      <h1 class="title is-2 has-text-centered mt-4">Contacto</h1>
    </div>
  </div>
</section>


<nav class="level">
  <div class="level-item has-text-centered">
   
<div class="container">
<figure class="image is-128x128 container mt-4">
    <img
      class="is-rounded"
      alt="img"
      src="https://bulma.io/images/placeholders/128x128.png" />
  </figure>
  <!-- <p class="has-text-centered">tadia.arquitectura@gmail.com</p> -->
  <p class="has-text-centered">@tadia.arquitectura</p>
</div>
  </div>

  <div class="level-item has-text-centered">
    <div class="container">
<figure class="image is-128x128 container mt-4">
    <img
      class="is-rounded"
      alt="img"
      src="https://bulma.io/images/placeholders/128x128.png" />
  </figure>
  <!-- <p class="has-text-centered">@tadia.arquitectura</p> -->
  <p class="has-text-centered">tadia.arquitectura@gmail.com</p>
</div>
  </div>

  <div class="level-item has-text-centered">
    <div class="container">
<figure class="image is-128x128 container mt-4">
    <img
      class="is-rounded"
      alt="img"
      src="https://bulma.io/images/placeholders/128x128.png" />
  </figure>
  <p class="has-text-centered">809-407-2332</p>
</div>
  </div>

</nav>


<Pie />
