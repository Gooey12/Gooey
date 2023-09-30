<template>

    <div class="navbar nes-container with-title is-centered fixed-top">
            <div class="logo">
            <a target="_blank" rel="noopener noreferrer" href="https://github.com/captgooey12" class="nes-btn is-success">Gooey</a>
            </div>
            <div class="pages">
            <ul>
                <li></li>
                <li><RouterLink to="/" class="nes-btn is-success">Home</RouterLink></li>
                <li><RouterLink to="/gallery" class="nes-btn is-success">Gallery</RouterLink></li>
                <li><RouterLink to="/aboutme" class="nes-btn is-success">About Me</RouterLink></li>
            </ul>
            </div>
    </div>

    <br>
    <br>
    <br>

</template>

<style scoped>
.fixed-top {
  position: fixed;
  width: 100%;
  z-index: 999;
}

.navbar {
    background-color: #92CC41;
    height: 78px;
    padding: 10px;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

ul li {
    display: inline;
    margin-left: 15px;
}

.logo {
    float: left;
}

.pages {
    float: right;
}

</style>