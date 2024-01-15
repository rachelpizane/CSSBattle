# #7 - Leafy Trail

## 💥 Challenge
![Leafy Trail](img/07_Leafy_Trail.png)

## 🔎 Link
[Try it too and go to battle!](https://cssbattle.dev/play/7)

## 💡 Solution
```
<div></div>
<style>
  body {
    margin: 0px;
    display: grid;
    background: #0B2429;
  }
  div {
    margin: auto;
    width: 150px;
    height: 150px;
    border-top-left-radius: 67%;
    border-bottom-right-radius: 67%;
    background: #998235;
    position: relative;
  }
  div::before {
    content: "";
    display: block;
    width: 150px;
    height: 150px;
    border-top-left-radius: 67%;
    border-bottom-right-radius: 67%;
    background: #1A4341;
    position: absolute;
    z-index: -1;
    left: -50px;
  }
  div::after {
    content: "";
    display: block;
    width: 150px;
    height: 150px;
    border-top-left-radius: 67%;
    border-bottom-right-radius: 67%;
    background: #F3AC3C;
    position: absolute;
    left: 50px;
  }
</style>
```
