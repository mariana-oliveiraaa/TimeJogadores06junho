<template>
 <header class="menu-superior">
    <div class="menu-esquerdo">
      <span> <RouterLink to="/">Home</RouterLink> </span>
      <span>|</span>
      <span> <RouterLink to="/Times">Times</RouterLink> </span>
      <span>|</span>
      <span> <RouterLink to="/Jogadores">Jogadores</RouterLink></span>
      <span>|</span>
    </div>
    <div class="menu-direito">
      <span>sair</span>
    </div>
 </header>
</template>

<style>
   
header span {
  padding: 0 20px;
}

.menu-superior {
  justify-content: space-between;
}
</style>

  
  
  
  
  
  
  