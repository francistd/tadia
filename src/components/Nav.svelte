<script>
  let isOpen = false;
  export let segment;
  function toggleNav() {
    isOpen = !isOpen;
  }
</script>

<style>
  ul {
    margin: 0;
    padding: 0;
  }

  /* clearfix */
  ul::after {
    content: "";
    display: block;
    clear: both;
  }

  li {
    display: block;
    float: left;
  }

  [aria-current] {
    position: relative;
    display: inline-block;
  }

  [aria-current]::after {
    position: absolute;
    content: "";
    width: calc(100% - 1em);
    height: 2px;
    background-color: rgb(255, 62, 0);
    display: block;
    bottom: -1px;
  }

  a {
    text-decoration: none;
    padding: 1em 0.5em;
    display: block;
  }

  nav {
    border-bottom: solid gray 1px;
  }
</style>

<nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a href="/" class="navbar-item">
      <img src="logo.png" alt="Tadia" />
    </a>

    <span
      class="navbar-burger"
      on:click={toggleNav}
      class:is-active={isOpen}
      aria-label="menu"
      aria-expanded="false">
      <span aria-hidden="true" />
      <span aria-hidden="true" />
      <span aria-hidden="true" />
    </span>
  </div>
  <div class="navbar-menu" class:is-active={isOpen}>
    <div class="navbar-start">
    
      <a href="/" class="navbar-item" 
      aria-current={segment === undefined ? 'page' : undefined}
      class:is-active={segment === undefined}>
        Inicio
      </a>

      <a
        href="/proyectos"
        class="navbar-item"
        aria-current={segment === 'proyectos' ? 'page' : undefined}
        class:is-active={segment === 'proyectos'}>
        Proyectos
      </a>

      <a
        href="/nosotros"
        class="navbar-item"
        aria-current={segment === 'nosotros' ? 'page' : undefined}
        class:is-active={segment === 'nosotros'}>
        Nosotros
      </a>


    </div>
  </div>
</nav>
