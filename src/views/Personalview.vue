<script setup>
import Personal from '@/components/Personal.vue'
</script>

<template>
  <div class="container">
    <h1>HANAN RAISA PUTRI</h1>
    <h3>Front-End Developer</h3>
    <hr>
    <div class="box">
        <div class="foto">
          <img alt="Vue logo" class="logo" src="@/assets/hanan.jfif" width="200" height="300" />
        </div>
        <div class="konten">
          <div class="p1">
            <h2>About Me</h2>
            <p>I am a novice web developer who is studied at SMK Taruna Bhakti Depok. experienced in making several websites and web design to fulfill school assignments.</p>
          </div>
          <div class="p2">
            <h2>Contact</h2>
            <div class="con">
            <div class="con1">
              <span class="material-symbols-outlined">mail</span>
              <h4>Email</h4>
              <p>hananhar09@gmail.com</p>
            </div>
            <div class="con2">
              <span class="material-symbols-outlined">phone_iphone</span>
              <h4>No.Telp</h4>
              <p>0856-9246-5493</p>
            </div>
            <div class="con3">
              <span class="material-symbols-outlined">home</span>
              <h4>Alamat</h4>
              <p>Jl Flamboyan VII No.65, Depok, Jawa Barat</p>
            </div> 
            </div>
          </div>           
        </div>
    </div>
  </div>
</template>
<style scoped>
.container{
  background-color: cornflowerblue;
  color: white;
  height: 600px;
  border-radius: 10px;
}
.container h1{
  margin-left: 20px;
  text-align: center;
  font-size: 60px;
  margin-top: 10px;
  font-weight: 900;
  color: lightskyblue;
  
}
.container h3{
  text-align: center;
  margin-top: 10px;
  margin-bottom: 10px;
  font-weight: 500;
  font-size: 20px;
  color: black;
}
.box{
  width: 1200px;
  justify-content: center;
  display: flex;
}

.foto{
  margin-left: 30px;
  margin-top: 50px;
}
.p1 h2{
  font-size: 30px;
  margin-left: 50px;
  margin-bottom: 10px;
  margin-top: 50px;
  font-weight: 700;
  color: lightskyblue;
}
.p1 p{
  margin-left: 50px;
  width: 90%;
  margin-bottom: 40px;
  color: black;
  font-weight: 500;
}
.p2 h2{
  font-size: 30px;
  margin-left: 50px;
  margin-bottom: 10px;
  font-weight: 700;
  color: lightskyblue;
}
.p2 h4{
  margin-left: 90px;
  margin-top: -30px;
  font-size: 15px;
  font-weight: 800;
  color: black;
}
.p2 p{
  margin-left: 50px;
  margin-top: 5px;
  width: 100%;
  color: black;
  font-weight: 500;
}.con{
  display: flex;
}
.con span{
  margin-left: 50px;
}
</style>