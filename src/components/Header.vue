<template>
  <header
    class="flex items-center w-full p-4 space-x-10 text-white bg-slate-800"
  >
    <h1 class="text-2xl">Book</h1>
    <nav class="flex space-x-4">
      <div class="">
        <router-link to="/">Home</router-link>
      </div>
      <div class="">
        <a href="/">Books</a>
      </div>
      <div class="">
        <router-link to="/login">Login</router-link>
      </div>
    </nav>
  </header>
</template>
