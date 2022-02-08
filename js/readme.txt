
document.querySelector(".fade-layer").addEventListener("click", showMenu)

document.querySelector(".menu-botton").addEventListener("click", showMenu)


function showMenu(){
    console.log("hej");
let menu = document.querySelector("nav.menu"); 
menu.classList.toggle("show");

let layer = document.querySelector(".fade-layer"); 
layer.classList.toggle("visible");
}

