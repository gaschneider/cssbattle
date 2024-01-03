# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/7c284b79-7120-463a-a8a1-32a150986291)


```
<div class="square"></div>
<div class="square"></div>
<div class="square"></div>
<div class="square"></div>
<div class="line"></div>
<div class="line horiz"></div>
<div class="triangle"></div>
<div class="triangle top"></div>
<div class="triangle left"></div>
<div class="triangle right"></div>
<style>
  body {
    display: flex;
    flex-wrap: wrap;
    background: #E8112D;
    gap: 80px;
    margin: 0px;
    justify-content: center;
    align-items: center;
  }
  
  .square {
    width: 160px;
    height: 110px;
    background: #FFFFFF;
  }

  .line {
    position: absolute;
    width: 20px;
    height: 200px;
    background: #F9DD16;
  }

  .horiz {
    rotate: 90deg;
  }

  .triangle {
    position: absolute;
    width: 0;
    height: 0;
    border: 20px solid transparent;
    border-top: 0;
    border-bottom: 30px solid #F9DD16;
    top: 235px;
  }

  .top {
    top: 35px;
    rotate: 180deg;
  }

  .left {
    top: 135px;
    left: 80px;
    rotate: 90deg;
  }

  .right {
    top: 135px;
    left: 280px;
    rotate: -90deg;
  }
</style>

```
