<template>
  <div class="Projects">
    <body>
      <div class="container">
        <div class="row justify-content-center">
          <div class="col center-block">
            <center>
            <img id="intro_pic" src="../assets/arunalu.jpg" alt="arunalu"/>
            <div class="information">
              <h4><b>Information</b></h4>
              <ul>
                <li> <b>Name:</b> Arunalu Kariyawasam</li>
                <li> <b>Location:</b> Calgary, AB</li>
                <li> <b>Phone:</b> 587-707-4129</li>
                <li> <b>Email:</b> askariya@ucalgary.ca</li>
              </ul>
            </div>
            </center>
          </div>
          <div class="col-8" border="1px solid black">
            <h2>Description</h2>
            <p>
              Hello, and welcome to my page! <br> My name is Arunalu Kariyawasam and I am a student that has just completed my final
              year in the Software Engineering (BSc. of Science) program at University of Calgary.
              As a Software Engineering student, I’ve had the opportunity to collaborate and complete many software projects and
              software-related activities (both extracurricular and in-class). You can view details about these projects by clicking
              the Projects tab above.
            </p>
            <p>
              ...heyyyy that's pretty good.
            </p>
          </div>
        </div>
      </div>
    </body>
  </div>
</template>

<script>
export default {
  name: 'Projects',
  data () {
    return {
      msg: 'Summary'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

body{
  padding-top: 2em;
}

h1, h2 {
  font-weight: normal;
}

.information{
  display: inline-block;
  /* text-align: center; */
}
ul {
  list-style-type: none;
  display: inline-block;
  text-align: left;
  /* padding: 0; */
}
a {
  color: #42b983;
}

img{
    /* border: 0.2em solid #3D5A80; */
    margin-bottom: 1em;
}

#intro_pic{
    /* border-radius: 15em; */
    max-height: 15em;
    width: auto;
}

/*debugging*/
.col{
  /* border: 1px solid black; */
}
.col-8{
  /* border: 1px solid black; */
}
.container{
  /* border: 1px solid red; */
  /* padding: 1em; */
}

</style>
