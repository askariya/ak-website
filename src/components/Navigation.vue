<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <!-- <router-link tag="li" to="/" exact><a>Home</a></router-link>
          <router-link tag="li" to="/projects" exact><a>Projects</a></router-link> -->
          <router-link tag="li" class="nav-item" v-for="route in links" v-bind:key="route.id" :to="`${route.page}`" exact>
            <a class="nav-link">{{route.text}}</a>
          </router-link>
        </ul>
      </div>
    </nav>

  </div>
</template>

<script>
export default {
  name: 'Navigation',
  data () {
    return {
      links: [
        {
          id: 0,
          text: 'Home',
          page: '/'
        },
        {
          id: 1,
          text: 'Projects',
          page: '/projects'
        },
        {
          id: 2,
          text: 'Contact',
          page: '/contact'
        }
      ]
    }
  }
}
</script>

<style>

.router-link-active {
  background-color: #8e9cac;
  /* color: red !important; */
}

/* li{
  border: 1px solid yellow;
  background-color: green;
} */

</style>
