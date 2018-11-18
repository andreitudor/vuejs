<template>
    <div>
        <li class="nav-item">
            <router-link v-on:click="active_link++" class="nav-link { active: active_link == 1 }" :to=link>{{ name }}</router-link>
        </li>
    </div>
</template>

<script>
export default {
  name: 'NavLink',
  props: {
    link: String,
    name: String
  },
  data: function () {
    return {
      active_link: 0
    }
  },
  methods: {
    activate: function () {
    }
  }
}
</script>

<style scoped>

</style>
