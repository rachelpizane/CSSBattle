# #8 - Forking Crazy

## 💥 Challenge
![Forking Crazy](img/08_Forking_Crazy.png)

## 🔎 Link
[Try it too and go to battle!](https://cssbattle.dev/play/8)

## 💡 Solution
```
<div class="box">
  <div class="claw"></div>
  <div class="claw"></div>
  <div class="claw"></div>
  <div class="claw"></div>
  <div class="claw"></div>
  <div class="claw"></div>
  <div class="claw"></div>
</div>
<div class="circle"></div>

<style>
  body {
    margin: 0px;
    display: grid;
    place-content: center;
    background: #6592CF;
  }
  .box {
    margin: auto;
    display:flex;
    width: 140px;
    position: relative;
    bottom: -30px;
  }
  .claw{
    width: 20px;
    height: 110px;
    border-top-left-radius: 15px;
    border-top-right-radius: 15px;
    background: #060F55;
  }
  .claw:nth-child(even){
    background: #6592CF;
    transform: rotate(180deg);
  }
  .circle {
    top:-30;
    background: #060F55;
    width: 140px;
    height: 150px;
    border-bottom-left-radius: 70px;
    border-bottom-right-radius: 70px;
    position: relative;
    z-index: -1
  }
  .circle::after{
    content:"";
    display: block;
    position: absolute;
    width: 20px;
    height: 100px;
    left: 60px;
    bottom: -70;
    background: #060F55;
  }
</style>
```
