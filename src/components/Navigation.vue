<template>
  <div>
    <!-- <nav>
        <router-link v-for="route in links" 
          v-bind:key="route.id" 
          :to="`${route.page}`">{{route.text}}
        </router-link>
    </nav> -->
    <nav class="navbar navbar-inverse">
      <div class="container-fluid">
        <ul class="nav navbar-nav">
          <li v-for="route in links" v-bind:key="route.id">
            <router-link :to="`${route.page}`">{{route.text}}</router-link>
          </li>
        </ul>
      </div>
    </nav>

  </div>
</template>

<script>
export default {
  name: 'Navigation',
  data() { 
  return { 
    links: [ 
      { 
         id: 0,
         text: 'Home', 
         page: '/' 
      },
      { 
         id: 0,
         text: 'Projects', 
         page: '/projects' 
      },
      { 
         id: 0,
         text: 'Contact', 
         page: '/contact' 
      }   
    ] 
  } 
}
}
</script>

<style>
</style>
