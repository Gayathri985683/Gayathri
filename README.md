<!DOCTYPE html>
<html>
    <head>
        <title>selector with color change</title>
    </head>
    <body>
        <h1 id="title"> Hello SVPCET students</h1>
        <h1></h1>
        <h1><p class="message"> This is dept of CAI</p></h1>
        <h1><p>This is 3rd year 5th sem</p></h1>
        <button onclick="selectElements()">click me</button>
        <script src="script2.js"></script>
    </body>
</html>
function selectElements()
{
    let titlejs=document.getElementById("title");
    titlejs.style.color="blue";
    let messagejs=document.getElementsByClassName("message")[0];
    messagejs.style.color="green";
    let paragraphs=document.getElementsByTagName("p");
    paragraphs[1].style.backgroundcolor="yellow";
}
