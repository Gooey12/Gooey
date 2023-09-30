<template>
<center>

    <br><br>

    <div class="nes-container titlesub">

        <p class="title">About Me</p>

    <p>Gooey - An alive <a target="_blank" rel="noopener noreferrer" href="https://en.wikipedia.org/wiki/Human">human being</a></p>

    </div>

    <br><br>

    <div class="body">

        <div class="sub-container left nes-container">
            <p class="sub-subtitle">Gooey</p>

            <p class="text">I'm Gooey, and right now, I'm on an exciting journey of learning HTML, CSS and JavaScript.
               I'm diving deep into the world of coding, eager to create amazing website, things and applications.
               When I'm not coding, you'll find me immersed in the world of gaming, battling foes and exploring virtual realms.
               Music is my other love; it adds rhythm to my life.
               I'm a human being, passionate about technology, gaming and other cool things, ready to explore the endless possibilities that lies ahead in this digital age.</p>
        </div>

        <div class="sub-container nes-container">
            <p class="sub-subtitle">Skills</p>
            <p class="small-txt">Here's some tools, programming languages, frameworks and other things that I uses:</p><br>

            <div class="icons">
            <a href="https://code.visualstudio.com" class="icon"><img src="https://raw.githubusercontent.com/nthnn/nthnn/main/assets/ic-visual-studio-code.png" width="48" /></a>
            <a href="https://github.com/" class="icon"><img src="https://raw.githubusercontent.com/nthnn/nthnn/main/assets/ic-github.png" width="48" /></a>
            <a href="https://markdownguide.org/" class="icon"><img src="https://raw.githubusercontent.com/nthnn/nthnn/main/assets/ic-markdown.png" width="48" /></a>
            <a href="https://html5.org" class="icon"><img src="https://raw.githubusercontent.com/nthnn/nthnn/main/assets/ic-html5.png" width="48" /></a>
            <a href="https://www.css3.com" class="icon"><img src="https://raw.githubusercontent.com/nthnn/nthnn/main/assets/ic-css3.png" width="48" /></a>
            <a href="https://www.javascript.com" class="icon"><img src="https://raw.githubusercontent.com/nthnn/nthnn/main/assets/ic-js.png" width="48" /></a>
            <a href="https://vuejs.org/" class="icon"><img src="https://raw.githubusercontent.com/nthnn/nthnn/main/assets/ic-vue.png" width="48" /></a>
            <a href="https://vercel.com/" class="icon"><img src="https://raw.githubusercontent.com/nthnn/nthnn/main/assets/ic-vercel.png" width="48" /></a>
            </div>
        </div>

    </div>

    <br><br><br>

    <footer><p class="copyright">&copy; Copyright 2023 - Gooey.</p></footer>

</center> 
</template>

<style scoped>
.icon {
    margin-left: 3px;
}

.text {
    font-size: 15px;
}

.sub-subtitle {
    font-size: 38px;
}

.sub-container {
    width: fit-content;
    display: block;
    width: 600px;
    margin-left: 15px;
}

.body {
    display: flex;
    padding-left: 60px;
}

.titlesub {
    width: fit-content;
}

a:hover {
    color: #212529;
  }
  
a {
    color: #212529;
}
</style>