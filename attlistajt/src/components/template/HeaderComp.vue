<template>
  <header>
    <div class="menu-esquerdo">
      <span> <RouterLink to="/">Home</RouterLink> </span>
      <span>|</span>
      <span> <RouterLink to="/times">Times</RouterLink> </span>
      <span>|</span>
      <span> <RouterLink to="/jogadores">Jogadores</RouterLink> </span>
      <span>|</span>
      <span> <RouterLink to="/estadios">Estádios</RouterLink> </span>
      <span>|</span>
      <span> <RouterLink to="/musicas">Músicas</RouterLink> </span>
    </div>
    <div class="menu-direito">
      <span>Sair</span>
    </div>
  </header>
</template>

<style>
header span {
  padding: 0 20px;
}

header {
  background-color: cornflowerblue;
  height: 15%;
  font-size: 1.3rem;
  padding-left: 2rem;
  color: white;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
</style>