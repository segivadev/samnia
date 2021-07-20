<script>
  const secciones =[ { id: 1, label: '¿Quienes somos?', href: "#" },
                     { id: 2, label: 'Servicios',       href: "#" },
                     { id: 3, label: 'Contacto',        href: "#" },
  ]; 
  
  let logo = 'assets/img/logo.png';
</script>

<nav class="navbar" role="navigation" aria-label="main navigation">
  <!-- Logo -->
  <div class="navbar-brand">
    <a class="navbar-item" href="https://bulma.io">
      <img src={logo} alt="Samnia">
      <h1>S A M N I A</h1>
    </a>
    <span class="navbar-burger" data-target="navbarMenuHeroC">
      <span></span>
      <span></span>
      <span></span>
    </span>
  </div>

  <!--Secciones -->
  <div class="navbar-menu">
    <div class="navbar-end">
        <div class="buttons">
          {#each secciones as seccion}
            <a class="navbar-item" href={seccion.href}>{seccion.label}</a>
          {/each}
          <button>Iniciar sesión</button>
        </div>
    </div>
  </div>
</nav>

<style>
  a{
    color: #4CB275;
    font-size: 20px;
  }

  button{
    background: #008781CC;
    border: none;
    border-radius: 12px;
    box-shadow: 24px 4px 6px rgba(0, 0, 0, 0.25);
    color: white;
    font-size: 20px;
    height: 45px;
    left: 1242px;
    margin-right: 20px;
    top: 40px;
    width: 148px;
  }

  h1{
    color: #4CB275; 
    font-size: 28px;   
    margin-left: 15px;
    margin-top: 10px;
  }

  img{
    height: 56px;
    left: 61px;
    margin-left: 61px; 
    top: 13px;
  }
</style>