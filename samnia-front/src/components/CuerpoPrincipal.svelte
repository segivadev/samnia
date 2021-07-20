<script>
  import Icon from '@iconify/svelte';
  import magnifyingGlass from '@iconify/icons-foundation/magnifying-glass';
</script>

<div class="container has-text-centered">
  <p class="title">
    Lo que sientes es real
  </p>
  <p class="subtitle">
    Tenemos a los mejores
    <br>
    psicólogos dispuestos a
    <br>
    brindarte ayuda,
    <br>
    recíbela a un solo click
  </p>

  <button>
    Encuentra el tuyo
    <Icon icon={magnifyingGlass}/>
  </button>
</div>

<style>
  .title{
    color: white;
    font-size: 60px;
  }

  .subtitle{
    color: white;
    font-size: 40px;
  }
  button{
    /* /* position: absolute; */
    border: none;
    width: 290px;
    height: 47px;
    left: 260px;
    top: 605px; 

    background: rgba(0, 135, 129, 0.7);
    box-shadow: 6px 4px 4px rgba(0, 0, 0, 0.25);
    border-radius: 12px;

    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 29px;
    color: white;
  }

</style>