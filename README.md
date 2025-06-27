# This is a text file

Completed two simple project on javascript

## 1. Color changer JS code
```javascript
let box1 = document.querySelector("#box1")
let box2 = document.getElementById("box2")
let box3 = document.getElementById("box3")
let box4 = document.getElementById("box4")
let btn = document.getElementById("btn")

box1.addEventListener("click", function(e){
    document.body.style.backgroundColor = "gray"
})

box2.addEventListener("click", function(){
    document.body.style.backgroundColor = "blue"
})

box3.addEventListener("click", function(){
    document.body.style.backgroundColor = "brown"
})

box4.addEventListener("click", function(){
    document.body.style.backgroundColor = "yellow"
})

btn.addEventListener("click", function(){
    document.body.style.backgroundColor = "white"
})
