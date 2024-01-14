# #4 - Ups n Downs

## 💥 Challenge
![Ups n Downs](img/4_UpsnDowns.png)

## 🔎 Link
[Try it too and go to battle!](https://cssbattle.dev/play/4)

## 💡 Solution
```
<div class="box">
  <div class="portion"></div>
  <div class="portion""></div>
  <div class="portion"></div>
  <div class="portion"></div>
  <div class="portion""></div>
  <div class="portion"></div>
</div>

<style>
  body {
    margin: 0px;
    background: #62306D;
    display: grid;
    place-content: center
  }
  
  .box {
    display: flex;
    width: 300px;
    flex-wrap: wrap;
  }

  .portion{
    width: 100px;
    height: 100px;
    border-top-left-radius: 50px;
    border-top-right-radius: 50px;
    background-color: #F7EC7D;
  }

  .portion:nth-child(n+4){
    transform: rotate(180deg)
  }

  .portion:nth-child(odd){
    background: #62306D;
  }
</style>
```
