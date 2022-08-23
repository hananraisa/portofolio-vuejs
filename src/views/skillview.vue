<template>
  <div class="container">
    <h1>MY SKILL</h1>
    <hr>
    <div class="skill-1">
      <img alt="Vue logo" class="logo" src="@/assets/html.png" width="50" height="50" />
      <h2>HTML</h2>
        <div class="progress">
          <div class="progress-bar" role="progressbar" style="width: 80%;"  aria-valuemin="0" aria-valuemax="100">80%</div>
        </div>
    </div>
    <div class="skill-2">
      <img alt="Vue logo" class="logo" src="@/assets/css.png" width="30" height="40" />
      <h2>CSS / BOOTSTRAP</h2>
        <div class="progress">
          <div class="progress-bar" role="progressbar" style="width: 60%;" aria-valuemin="0" aria-valuemax="100">60%</div>
        </div>
    </div>
    <div class="skill-3">
      <img alt="Vue logo" class="logo" src="@/assets/figma.png" width="100" height="50" />
      <h2>FIGMA DESIGN</h2>
        <div class="progress">
          <div class="progress-bar" role="progressbar" style="width: 75%;" aria-valuemin="0" aria-valuemax="100">75%</div>
        </div>
    </div>
    <div class="skill-4">
      <img alt="Vue logo" class="logo" src="@/assets/laravel.png" width="70" height="60" />
      <h2>LARAVEL</h2>
        <div class="progress">
          <div class="progress-bar" role="progressbar" style="width: 40%;" aria-valuemin="0" aria-valuemax="100">25%</div>
        </div>
    </div>
  </div>
</template>
<style scoped>
.skill-1 .logo{
  margin-left: 60px;
  margin-bottom: -110px;
}
.skill-2 .logo{
  margin-left: 70px;
  margin-bottom: -110px;
}
.skill-3 .logo{
  margin-left: 35px;
  margin-bottom: -110px;
}
.skill-4 .logo{
  margin-left: 50px;
  margin-bottom: -110px;
}
.container{
background-color: cornflowerblue;
color: white;
height: 600px;
width: 1220px;
border-radius: 10px;
justify-content: space-evenly;
}
.container h1{
font-size: 60px;
text-align: center;
margin-top: 10px;
margin-bottom: 10px;
font-weight: 900;
color: lightskyblue;
}
.container h2{
  margin-top: 40px;
  margin-left: 120px;
  color: black;
  font-weight: 700;
  font-size: 20px;
}
.container p{
margin-left: 30px;
}
.progress{
  width: 90%;
  margin-left: 50px;
}

</style>