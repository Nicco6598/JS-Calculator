# JSCounter

JSCounter is a JavaScript calculator that increases/resets/decreases the value displayed on the screen.

## Installation

Use the Git Bash terminal to clone the repository locally.

```gitbash
git clone https://github.com/Nicco6598/JS-CalculatorProject.git
```

## Index.html buttons and counter

```html
<label id="countLabel">0</label><br>
    <div class="container">
        <div class="vertical-center"></div>
            <button id="decreaseBtn">decrease</button>
            <button id="resetBtn">reset</button>
            <button id="increaseBtn">increase</button>
            <script src="js/index.js"></script>
        </div>
    </div>
```

## Index.js functions

```js
let count = 0;

document.getElementById("decreaseBtn").onclick = function(){
    count-=1;
    document.getElementById("countLabel").innerHTML = count;
}

document.getElementById("resetBtn").onclick = function(){
    count=0;
    document.getElementById("countLabel").innerHTML = count;
}

document.getElementById("increaseBtn").onclick = function(){
    count+=1;
    document.getElementById("countLabel").innerHTML = count;
}
```

## License

[MIT](https://github.com/Nicco6598/JS-CalculatorProject/blob/main/license.txt)