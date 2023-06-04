<h1 align='center'> ИГОРЬ FUCKING SLAVE </h1>
<p align="center">
  <img src="https://github.com/romper008/bg3timer/blob/main/van.jpg?raw=true" />
</p>
<h1 align='center'> До выхода Baldur's Gate 3: </h1>
<script src="//megatimer.ru/get/5468ba46a5cab785debfba427e087ac5.js"></script>
//<audio ref='themeSong' src="https://github.com/romper008/bg3timer/blob/main/bg3.mp3?raw=true" autoPlay loop></audio>
<input type="range" id="volume-control">
let audio = new Audio("https://github.com/romper008/bg3timer/blob/main/bg3.mp3?raw=true");
let volume = document.querySelector("#volume-control");
volume.addEventListener("change", function(e) {
audio.volume = e.currentTarget.value / 100;
})

