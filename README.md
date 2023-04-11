<p align="center">
    <a href="https://www.linkedin.com/in/evansemet/" target="_blank"><img src="linkedinlogo.png" width="40" height="40"></a>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    <a href="mailto:evancsemet@gmail.com"><img src="gmaillogo.webp" width="40" height="40"></a>
</p>

<p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=evansemet&show_icons=true&theme=tokyonight" alt="GitHub Stats" />
</p>

<p align="center">
    <img src="https://profile-counter.glitch.me/evansemet/count.svg" /> 
</p>

<div id="matrix"></div>

<style>
#matrix {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    font-size: 16px;
    color: green;
    background-color: black;
}
</style>

<script>
function generateMatrix() {
    const matrix = document.getElementById("matrix");
    const chars = "01";
    const codeLength = 50;
    let code = "";

    for (let i = 0; i < codeLength; i++) {
        code += chars.charAt(Math.floor(Math.random() * chars.length));
    }

    matrix.innerHTML += code + "<br>";
}

setInterval(generateMatrix, 100);
</script>
