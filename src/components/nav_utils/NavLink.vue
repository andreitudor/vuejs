<template>
    <div>
        <li class="nav-item">
            <router-link v-on:click="active++" class="nav-link" :to=link>{{ name }}</router-link>
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
      active: 0
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
