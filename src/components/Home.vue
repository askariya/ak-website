<template>
  <div class="Home">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col">
          <div class="row justify-content-center">
            <div class="col text-center">
              <img id="intro_pic" src="../assets/arunalu.jpg" alt="arunalu"/>
            </div>
            <div class="w-100"></div>
          <div class="row justify-content-center">
            <div class="col">
              <ul>
                <li> <b>Name:</b> Arunalu Kariyawasam</li>
                <li> <b>Location:</b> Calgary, AB</li>
                <li> <b>Phone:</b> 587-707-4129</li>
                <li> <b>Email:</b> askariya@ucalgary.ca</li>
              </ul>
            </div>
          </div>
          </div>
        </div>
        <div class="col-8" border="1px solid black">
          <h1>{{ msg }}</h1>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  /* padding: 0; */
}
a {
  color: #42b983;
}

img{
    /* border: 0.2em solid #3D5A80; */
    /* margin-bottom: 1em; */
}

#intro_pic{
    /* border-radius: 15em; */
    max-height: 20em;
    width: auto;
}

/*debugging*/
.col{
  border: 1px solid black
}
.col-8{
  border: 1px solid black
}

</style>
