<template>
    <nav class="navbar bg-gray-600 flex items-center h-[72px] relative">
      <section class="container m-auto flex">
        <h1 class="site-logo m-auto">
          <a class="navbar-item text-3xl text-white font-bold" href="/">
            Gameboxd
          </a>
        </h1>
        <div class="navbar-menu text-gray-400 font-bold flex items-center">
          <ul class="navbar-start flex ">
            <a class="navbar-item px-2 hover:text-gray-200" href="/PROFILE">PERFIL</a>
            <a class="navbar-item px-4 hover:text-gray-200" href="/GAME-de">GAMES</a>
            <a class="navbar-item px-4 hover:text-gray-200" href="/LISTS">LISTS</a>
            <a class="navbar-item px-2 hover:text-gray-200" href="/MEMBERS">MEMBERS</a>
          </ul>    
        </div>
        <div class="navbar-end mx-auto text-gray-300 font-bold flex items-center">
            <a class="navbar-item" href="/iniciar-sesion">
              <button class="bg-green-400 hover:bg-green-500 rounded-lg px-2">Iniciar sesión</button>
            </a>
          </div>
      </section>
    </nav>
  </template>

<script>
export default {
    name: 'NavBar'
}
</script>

<style>

</style>