<template>
    <div>
        <li class="nav-item">
            <router-link class="nav-link navLinkColor" :to=link>{{ name }}</router-link>
        </li>
    </div>
</template>

<script>
export default {
  name: 'NavLink',
  props: {
    link: String,
    name: String
  }
}
</script>

<style scoped lang="scss">
    a.nav-link.navLinkColor {
        color: black;
        font-weight: 600;
        &:hover {
            text-decoration: underline;
            color: black;
        }
    }
    a.nav-link.navLinkColor.router-link-exact-active {
        color: black;
        text-decoration: underline;
    }
</style>
