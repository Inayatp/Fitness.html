let members = document.getElementById("members");
let programs = document.getElementById("programs");
let abouts = document.getElementById("abouts");

members.addEventListener("click",function(){
    members.style.color="rgb(2, 253, 2);";
    programs.style.color="white";
    connects.style,color="white";
    abouts.style.color="white";
})

programs.addEventListener("click",function(){
    members.style.color="white";
    programs.style.color="rgb(2, 253, 2);";
    connects.style,color="white";  
})

connects.addEventListener("click",function(){
    members.style.color="white";
    programs.style.color="white";
    abouts.style,color="rgb(2, 253, 2);";
})

    
    







