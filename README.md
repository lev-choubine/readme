# MyFirstReadme
Making a README 


Repo explaining Repo
```javascript
const handleWin = (letter) => {
  gameIsLive = false;
  if (letter === "x") {
    statusDiv.innerHTML = `${letterToSymbol(letter)} has won!`;
  } else {
    statusDiv.innerHTML = `<span>${letterToSymbol(letter)} has won!</span>`;
  }
};
```

## Steps to Install on local computer
1. Go to repo on Github profile

2. `fork` and `clone` repo
3. Clone to local machine
```text
git clone https://github.com/SEI-ALT/tic-tac-toe.git
```
4. Go to `tic-tac-toe` directory
5. Open index.html

```css
.grid {
    background-color: salmon;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(3, 1fr);
    gap: 15px;
    margin-top: 50px;
}
```

```html
<div class="grid">
        <div class="box" id="box-1"></div>
        <div class="box" id="box-2"></div>
        <div class="box" id="box-3"></div>
        <div class="box" id="box-4"></div>
        <div class="box" id="box-5"></div>
        <div class="box" id="box-6"></div>
        <div class="box" id="box-7"></div>
        <div class="box" id="box-8"></div>
        <div class="box" id="box-9"></div>
    </div>
```
| Function | Description |
| ----------- | ----------- |
| 'handleWin()| Handle Win of the game |
| (`checkGameStatus()` | Checks the status of the game |