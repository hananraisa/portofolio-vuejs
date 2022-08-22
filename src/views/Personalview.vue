<script setup>
import Personal from '@/components/Personal.vue'
</script>

<template>
  <div class="container">
    <h1>Personal</h1>
    <div class="box">
        <div class="foto"></div>
        <div class="konten">
            <h2>About Me</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nisi nemo cumque repellat repellendus atque facere dolorem dolore quis eveniet quam voluptatem fugiat hic nihil sequi, dignissimos quae, eum inventore laboriosam.</p>
            <h2>About Me</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nisi nemo cumque repellat repellendus atque facere dolorem dolore quis eveniet quam voluptatem fugiat hic nihil sequi, dignissimos quae, eum inventore laboriosam.</p>
            <h2>About Me</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nisi nemo cumque repellat repellendus atque facere dolorem dolore quis eveniet quam voluptatem fugiat hic nihil sequi, dignissimos quae, eum inventore laboriosam.</p>
        </div>
        
    </div>
  </div>
</template>
<style scoped>
.container{
background-color: cornflowerblue;
color: white;
height: 500px;
border-radius: 10px;
}
.container h1{
margin-left: 20px;
text-align: center;
font-size: 50px;
margin-top: 10px;
}
.container h2{
margin-left: 30px;
margin-top: 30px;
}
.container p{
margin-left: 30px;
}
.box{
width: 1000px;
justify-content: space-evenly;
}
</style>