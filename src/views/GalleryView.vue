<template>
<center>

  <br><br>

  <p class="title">Gallery</p>

    <p>Gooey's things and projects</p>

  <br>

  <div class="project-box">

    <div class="nes-container with-title project-card">
      <!--<img src="/pictures/QuickNoter-Screenshot.png" alt="" class="nes-container card-pic">-->
      <a target="_blank" rel="noopener noreferrer" href="https://captgooey12.github.io/QuickNoter"><p>QuickNoter</p></a>
      <img src="../assets/QuickNoter-Screenshot.png" alt="" class="nes-container" />
      <br><br>
      <p>A simple and easy-to-use web-based note app.</p>
    </div>

    <div class="nes-container with-title project-card">
      <!--<img src="/pictures/QuickNoter-Screenshot.png" alt="" class="nes-container card-pic">-->
      <a target="_blank" rel="noopener noreferrer" href="https://captgooey12.github.io/funomizer"><p>Funomizer</p></a>
      <img src="../assets/Funomizer-Screenshot.png" alt="" class="nes-container "/>
      <br><br>
      <p>Cure your boredom with Cats, and Jokes!</p>
    </div>

  </div>

  <br><br><br>  

  <footer><p class="copyright">&copy; Copyright 2023 - Gooey.</p></footer>
</center>
</template>

<style scoped>
a:hover {
  color: black;
}

a {
  color: black;
}

img {
  width: 230px;
  height: 140px;
}

.nes-container {
  padding: 0px;
}

.project-box {
  width: 1000px;
  border: 4px;
  border-style: solid;
  border-color: black;
  padding: 20px;
  display: flex;
}

.project-card {
  width: 300px;
  height: fit-content;
  max-width: 100%;
  max-height: 100%;
  display: block;
  margin-left: 20px;
  padding: 8px;
}

.card-pic {
  width: 300px;
  height: 200px; 
}
</style>
