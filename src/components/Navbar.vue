<!-- markup -->
<template>
  <nav class="navbar">
    <div class="navbar__logo">
        <a href="#">Title and logo</a>
    </div>

    <div class="navbar__menu">
        Put navbar menu here
    </div>
    <div class="navbar__search">
        <a href="#">Search</a>
    </div>
</nav>
</template>

<!-- Script -->
<script>
    export default {
        name: 'Navbar',
        props: {
            msg: String
        }
    }
</script>

<!-- Styles -->
<style lang="scss" scoped>
    .navbar {
        background-color: lightgray;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        padding: 20px;
    }
</style>