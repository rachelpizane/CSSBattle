# #3 - Push Button

## 💥 Challenge
![Push Button](img/03_Push_Button.png)

## 🔎 Link
[Try it too and go to battle!](https://cssbattle.dev/play/3)

## 💡 Solution
```
<div class="rectangle">
  <div class="circle">
    <div class="circle-yellow"></div> 
  </div>
</div>

<style>
  body {
    margin: 0px;
    background: #6592CF;
    display: grid;
  }
  
 .rectangle{
   display: grid;
   place-content:center;
   margin: auto;
   width: 300px;
   height: 150px;
   background: #243D83;
  }

  .circle {
    width: 150px;
    height: 150px;
    border: 50px solid #6592CF;
    border-radius: 50%;
    display: grid;
  }

  .circle-yellow {
    margin: auto;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background-color: #EEB850
  }
</style>
```
