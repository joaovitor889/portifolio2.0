<template>

  <nav id="barra" class="navbar" role="navigation" aria-label="main navigation">
    <div class="navbar-brand" id="barra_interna">
      <a class="navbar-item" href="/">
        <img id='logo' src="../assets/logo.png">
      </a>

      <div id="links_buttons">
        <a href="">Sobre</a>
        <a href="">Abilidades</a>
        <a href="">Projetos</a>
        <a>
          <img src="../assets/Vector.png" alt="sol">
        </a>
      </div>
    </div>
  </nav>
</template>

<script>
export default {

}
</script>

<style>
  #logo{
    height: 5rem;
  }
  #barra{
    background: #ffff;
    display: flex;
    align-items: center;
    justify-content: center;
    border-bottom: 0.2rem black solid;
    
  }
  #barra_interna{
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 90%;
  }
  #links_buttons {
    display: flex;
    align-items: center;
  }
  #links_buttons a{
    color: black;
    margin: 0.5rem;
    display: flex;
  }
  #links_buttons a img{
    height: 1.2rem;
  }
  
</style>