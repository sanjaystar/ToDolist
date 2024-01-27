<script setup>

</script>

<template>
  <div class="forms">
    <h1 class="login">Login Form</h1>
    <h3 class="text">
    <input type="text" placeholder="Your username or email">
    <br>
    <input type="password" placeholder="Password">
    </h3>
    <h2>
      <button>sign in</button>
    </h2>
      <h6><router-link to="/forget">Forget password?</router-link></h6>
  </div>
</template>

<style scoped>

.forms{
  margin: auto;
  height: 300px;
  width: 300px;
  border-radius: 15px;

}
.login{
  padding-top: 1px;
  text-align: center;
  font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  font-size: xx-large;
}
input[type=text]{
  font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  opacity: 55%;
  margin: 20px ;  
  width: 86%;
  padding: 5px;
}
input[type=password]{
  font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  opacity: 55%;
  margin: 0px 20px;  
  width: 86%;
  padding: 5px;
}
h2{
  text-align: center;
  font-size: x-large; 
}

button{
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  font-weight: bold;
  width: 86%;
  padding: 5px;
  margin: 30px 20px 0px;
  color: white;
  font-size: medium;
  background-color: black;
  border: 1px solid;
  
}

button:hover{
  background-color:rgb(10, 207, 233);
}
h6{
  margin-top: 10px;
  text-align: center;
  width: 100%;
  font-size: small;
  text-decoration: underline;
}
</style>