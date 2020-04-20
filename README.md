# change-background-color-javascript
Change random background color using javascript.

var button = document.getElementById('changeBG');

button.addEventListener('click', changeBG);

var color = ['blue', 'green', 'yellow', 'red', 'pink', 'brown', 'golden']

function changeBG(){
    const colorIndex = parseInt(Math.random()*color.length);
    document.body.style.backgroundColor = color[colorIndex];
}
