# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/32adbf87-7c2a-41bb-bdd9-49fb766ebd83)


```
<div class="circle"></div>
<div class="line"></div>
<div class="line left"></div>
<div class="line right"></div>

<style>
  body {
    background: linear-gradient(#F19E4B 100px, #FFFFFF 100px 200px, #3F8627 0);
    display: grid;
    place-items: center;
  }
  
  .circle {
    width: 80px;
    aspect-ratio: 1;
    background: radial-gradient(#00007B 10px, #FFFFFF 10px 30px, #00007B 0);
    border-radius: 100%;
  }

  .line {
    position: absolute;
    height: 70px;
    width: 4px;
    background: #00007B;
  }

  .left {
    rotate: 60deg;
  }

  .right {
    rotate: -60deg;
  }
  
</style>
```
