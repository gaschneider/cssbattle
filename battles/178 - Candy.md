# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/90198268-b19c-4f09-bddb-8d880f10923b)


```
<div class="triangle"></div>
<div class="rectangle"></div>
<div class="triangle right"></div>
<div class="wrapper">
  <div class="line"></div>
  <div class="line"></div>
  <div class="line"></div>
  <div class="line"></div>
  <div class="line"></div>
</div>
<style>
  body {
    background: #CBE8DD;
    display: grid;
    place-items: center;
  }

  .triangle {
    position: absolute;
    width: 30px;
    height: 80px;
    background: #007192;
    left: 70px;
    clip-path: polygon(0 0, 100% 30px, 100% 50px, 0 100%)
  }

  .right {
    rotate: 180deg;
    left: 300px;
  }
  
  .rectangle {
    width: 180px;
    height: 100px;
    background: #007192;
    border-radius: 10px;
  }

  .wrapper {
    position: absolute;
    display: flex;
    gap: 10px;
  }
  .line {
    background: #CBE8DD;
    width: 10px;
    height: 150px;
    rotate: 20deg;
  }
</style>
```
