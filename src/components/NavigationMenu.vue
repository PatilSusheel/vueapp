<template>
  <nav class="navbar navbar-expand-lg navbar-light custom-bg-color fixed-top p-2">
    <a class="navbar-brand text-white" href="/">

      <img src="../assets/logo.png" alt="Salesine Logo" class="navbar-logo">
      <span class="navbar-title">Salesine</span>
    </a>

    <div class="mx-auto">
      <a class="navbar-brand text-white" href="/home">HOME</a>
      <a class="navbar-brand text-white" href="/calls">CALLS</a>
      <a class="navbar-brand text-white" href="/deals">DEALS</a>
      <a class="navbar-brand text-white" href="/individual">INDIVIDUAL</a>
      <a class="navbar-brand text-white" href="/library">LIBRARY</a>
    </div>

    <form class="form-inline mx-3">
      <input
        class="form-control mr-sm-2"
        type="search"
        placeholder="Search"
        aria-label="Search"
      />
    </form>

    <button class="btn btn-outline-light ml-2" @click="login">LOGIN/REGISTER</button>
  </nav>
</template>

<script>
export default {
  name: 'NavigationMenu',
};
</script>

<style scoped>

.custom-bg-color {
  background-color: #3f51b5;
}

.navbar-logo {
  margin-left: 70%;
  width: auto;
  height: auto;
}


.navbar-title {
  margin-left: 5px;
  align-content: center;
  color: white;
  font-size: 24px;
  font-weight: bold; 
}

.navbar-brand {
  padding: 0.25rem 0.5rem; 
  font-size: 14px;
}


.form-control {
  padding: 0.25rem 0.5rem;
}
</style>
