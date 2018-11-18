<template>
    <div>
        <nav class="navbar position-absolute">
            <span class="navbar-brand h1 ">Navbar</span>
        </nav>
        <nav class="navbar justify-content-end navbar-expand-lg navbar-light">
            <ul class="navbar-nav ">
                <NavLink name="Home" link="/"/>
                <NavLink name="About" link="/about"/>
                <NavLink name="Test" link="/test"/>
            </ul>
        </nav>
    </div>
</template>

<script>
import NavLink from './nav_utils/NavLink.vue'

export default {
  name: 'Navigation',
  components: { NavLink }
}
</script>

<style scoped>

</style>
