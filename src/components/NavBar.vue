<template>

    <div class="navbar nes-container with-title is-centered">
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

</template>

<style scoped>
/* @media (max-width: 320px) {
    .navbar {
  float: left;
  font-size: 16px;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

    .dropdown {
  float: left;
  overflow: hidden;
}

    .dropdown .dropbtn {
  font-size: 16px;
  border: none;
  outline: none;
  padding: 14px 16px;
  background-color: inherit;
  font-family: inherit;
  margin: 0;
} 

.dropdown-content {
  display: none;
  position: absolute;
  min-width: 160px; 
  z-index: 1;
}
} */

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