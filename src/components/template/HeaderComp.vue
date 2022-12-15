<template>
  <header class="menu-superior">
    <div class="cl">
      <RouterLink to="/">Home</RouterLink>
      <span>|</span>
      <RouterLink to="/Livros">Livros</RouterLink>
      <span>|</span>
      <RouterLink to="/Ed">Editoras</RouterLink>
      <span>|</span>
      <RouterLink to="/Cate">Categorias</RouterLink>
      <span>|</span>
      <RouterLink to="/Au">Autores</RouterLink>
    </div>
    <div>
      <input class="pesquisar" type="text" placeholder="Pesquisar" />
      <button class="pesquisa">Pesquisar</button>
    </div>
    <div class="Perfil">
      <RouterLink to="/Perfil"
        ><img src="https://cdn-icons-png.flaticon.com/512/1361/1361728.png"
      /></RouterLink>
    </div>
  </header>
</template>

<style scooped>
header .menu-superior {
  justify-content: space-between;
  display: flex;
  align-items: center;
  float: left;
}
a {
  transition: 1s;
    color: black;
    text-decoration: none;
}

a:hover {
  transform: scale(1.2) rotate(360deg); 
}
.cl {
  display: flex;
  align-items: center;
  float: left;
}

header span {
  padding: 0 20px;
}
.Perfil img {
  height: 50px;
  width: 50px;
}
.Perfil {
  margin-left: 640px;
}
.pesquisar {
  padding-right: 90px;
  margin-left: 2rem;
  font-weight: bold;
  border: 1px solid;
  border-radius: 0.8rem;
}
.pesquisa {
  margin-left: 10px;
  font-weight: bold;
  border: 1px solid;
  border-radius: 0.8rem;
}
</style>
