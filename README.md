#Js

// For Fullscreen sidebar
function openNav() {
    $("#myNav").css({ "width": "40%"});
    var windowSize = window.matchMedia("(max-width: 600px)")
    if(windowSize.matches){
    $("#myNav").css({ "width": "100%"});
    }
// document.getElementById("myNav").style.width = "100%";
}

function closeNav() {
    $("#myNav").css({ "width": "0%" });
// document.getElementById("myNav").style.width = "0%";
}
#css
ul
{
    padding: 0 !important;
    margin: 0;
}
ul li
{
    list-style: none;
}
a
{
    text-decoration: none !important;
    cursor: pointer;
}
hr {
    background: #E7E8EA !important;
    opacity: 1;
}
:focus-visible 
{
    outline: none;
}
.dropdown-toggle::after
{
    display: none !important;
}
ul
{
    padding: 0 !important;
    margin: 0;
}
ul li
{
    list-style: none;
}
a
{
    text-decoration: none !important;
    cursor: pointer;
}
hr {
    background: #E7E8EA !important;
    opacity: 1;
}
:focus-visible 
{
    outline: none;
}
.dropdown-toggle::after
{
    display: none !important;
}
