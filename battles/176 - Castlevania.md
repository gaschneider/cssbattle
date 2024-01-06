# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/7add83f5-512a-44f4-afdb-1a494047f7b4)


```
<div class="top">
  <div class="triangle"></div>
  <div class="triangle"></div>
</div>
<div class="castle"></div>
<div class="windows">
    <div class="window"></div>
    <div class="window"></div>
</div>
<div class="door"></div>
<style>
  body {
    background: #A6D6AE;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-top: 60px;
  }

  .top {
    display: flex;
    gap: 70px;
    
    .triangle {
      width: 0px;
      height: 0px;
      border: 40px solid transparent;
      border-top: 0px;
      border-bottom: 60px solid #3A0F09;    
    }
  }

  .windows {
    position: absolute;
    display: flex;
    gap: 130px;
    margin-top: -68px;
  }
  
  .window{
    background: #BB9213;
    height: 25px;
    width: 20px;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
  }

  .door {
    position: absolute;
    background: #BB9213;
    height: 50px;
    width: 60px;
    border-top-left-radius: 30px;
    border-top-right-radius: 30px;
    margin-top: 77px;
  }
  
  .castle {
    width: 200px;
    height: 120px;
    background: #3A0F09;
    clip-path: polygon(0 0, 25% 0, 25% 29.2%, 50% 0, 75% 29.2%, 75% 0, 100% 0, 100% 100%, 0 100%)
  }
</style>
```
