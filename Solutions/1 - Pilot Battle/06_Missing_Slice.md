# #6 - Missing Slice

## 💥 Challenge
![Missing Slice](img/06_Missing_Slice.png)

## 🔎 Link
[Try it too and go to battle!](https://cssbattle.dev/play/6)

## 💡 Solution
```
<div class="box">
  <div class="side"></div>
  <div class="side"></div>
  <div class="side"></div>
</div>

<style>
  body {
    margin: 0px;
    background: #E3516E;
    display: grid;
    place-content: center
  }
  .box {
    display: flex;
    max-width: 200px;
    flex-wrap: wrap;
  }
  .side{
    width: 100px;
    height: 100px;
    border-top-left-radius: 100%;
    background: #51B5A9;
  }
  .side:nth-child(2){
    transform: rotate(90deg);
    background: #FADE8B;
  }
  .side:nth-child(3){
    transform: rotate(270deg);
    background: #F7F3D7;
  }
</style>
```
