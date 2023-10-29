<template>
<center>

  <br><br>

  <p class="title">Gallery</p>

    <p>Gooey's things and projects</p>

  <br>

  <div class="project-box">

    <div class="row">

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

    <div class="nes-container with-title project-card">
      <!--<img src="/pictures/QuickNoter-Screenshot.png" alt="" class="nes-container card-pic">-->
      <a target="_blank" rel="noopener noreferrer" href="https://qr-genr.vercel.app/"><p>QR Code Generatore</p></a>
      <img src="../assets/QRCodeGeneratore-Screenshot.png" alt="" class="nes-container "/>
      <br><br>
      <p>Generate QR code faster than the speed of dark!</p>
    </div>

    </div>

    <br><br><br><br>

    <div class="row">

    <div class="nes-container with-title project-card">
      <!--<img src="/pictures/QuickNoter-Screenshot.png" alt="" class="nes-container card-pic">-->
      <a target="_blank" rel="noopener noreferrer" href="https://gooey12.itch.io/a-game-name"><p>A Game: Name</p></a>
      <img src="../assets/TrashyGame-Screenshot.png" alt="" class="nes-container "/>
      <br><br>
      <p>Most trashy game in the Universe.</p>
    </div>

    <div class="nes-container with-title project-card">
      <!--<img src="/pictures/QuickNoter-Screenshot.png" alt="" class="nes-container card-pic">-->
      <a target="_blank" rel="noopener noreferrer" href="https://gooey12.itch.io/name"><p>[Name]</p></a>
      <img src="../assets/Name-Screenshot.png" alt="" class="nes-container "/>
      <br><br>
      <p>Recreation of A Game: Name.</p>
    </div>

    <div class="nes-container with-title project-card">
      <!--<img src="/pictures/QuickNoter-Screenshot.png" alt="" class="nes-container card-pic">-->
      <a target="_blank" rel="noopener noreferrer" href="https://gooey12.itch.io/jam-rush"><p>Game Jam Rush</p></a>
      <img src="../assets/GameJamRush-Screenshot.png" alt="" class="nes-container "/>
      <br><br>
      <p>Game made for the <a target="_blank" rel="noopener noreferrer" href="https://itch.io/jam/jame-gam-33"><p>Jame Gam #33.</p></a></p>
    </div>          

  </div>

  </div>

  <br><br><br>  

  <footer><p class="copyright">&copy; Copyright 2023 - Gooey.</p></footer>
</center>
</template>

<style scoped>
a:hover {
    color: #212529;
  }
  
a {
    color: #212529;
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
}

.row {
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
