<template>
    <div class="main">
      <RouterLink class="item" to="/editoras">Editoras</RouterLink>
      <RouterLink class="item" to="/categorias">Categorias</RouterLink>    
      <RouterLink class="item" to="/autores">Autores</RouterLink>    
      <RouterLink class="item" to="/livros">Livros</RouterLink>
    </div>
</template>
<style scoped>
.main{
    background: #ff009f;
    border-radius: 10px;
    min-width: 20px;
    height: 300px ;
    border-radius: 20px;
    margin-left: 20%;
    margin-right:20% ;
    margin-top: 10%;
    text-align: center;

}          

.item {
    background-color: bisque;
    margin: 20px;
    
}
</style>