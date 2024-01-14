# #5 - Acid Rain

## 💥 Challenge
![Acid Rain](img/05_Acid_Rain.png)

## 🔎 Link
[Try it too and go to battle!](https://cssbattle.dev/play/5)

## 💡 Solution
```
<div></div>

<style>
  body {
    margin: 0px;
    background: #0B2429;
    display:grid;
    place-content:center
  }

  div{
    position: relative;
    width:120px;
    height:120px;
    border-bottom-left-radius:50%;
    border-bottom-right-radius:50%;
    border-top-left-radius:50%;
    background:#998235;
  }
  
  div::before{ 
    content:"";
    display: block;
    position: absolute;
    bottom: -60px;
    left: -60px;
    width: 120px;
    height: 120px;
    border-bottom-left-radius: 50%;
    border-bottom-right-radius: 50%;
    border-top-left-radius: 50%;
    background: #F3AC3C;
  }

  div::after{ 
    content:"";
    display: block;
    position: absolute;
    top: -60px;
    right: -60px;
    z-index:-1;
    width: 120px;
    height: 120px;
    border-radius: 50%;
    background: #F3AC3C;
  }
</style>
```
