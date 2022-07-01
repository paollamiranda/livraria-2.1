<template>
  <header>
    <div>
      <span> <RouterLink to="/">Home</RouterLink> </span>
    </div>
    <div>
      <span> <RouterLink to="/home">Home</RouterLink> </span>
    </div>
  </header>
</template>

<style>
header span {
  padding: 0 20px;
}


header {
  background-color: #000000;
  height: 15%;
  font-size: 1.3rem;
  padding-left: 2rem;
  color: #ffffff;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
</style>
