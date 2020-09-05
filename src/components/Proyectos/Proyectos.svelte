<script>
  import Icon from "svelte-awesome/components/Icon.svelte";
  import { archive } from "svelte-awesome/icons";
  import Carousel1 from "./Carousel1.svelte";
  import Carousel2 from "./Carousel2.svelte";
  import Carousel3 from "./Carousel3.svelte";
  import Carousel4 from "./Carousel4.svelte";
  import Pie from "../Pie.svelte";
</script>

<style>
.color {
  background-color: rgb(222, 222, 222);
}
</style>

<section class="color hero  mb-2">
  <div class="hero-body">
    <div class="container">
      <h2 class="title is-2 has-text-centered mt-4">
        <Icon data={archive} scale="2" /> Algunos de Nuestros Proyectos
      </h2>
    </div>
  </div>
</section>

<Carousel1 />
<Carousel2 />
<Carousel3 />
<Carousel4 />
<Pie />
