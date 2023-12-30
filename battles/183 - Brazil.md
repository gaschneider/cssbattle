# TARGET
![image](https://github.com/gaschneider/cssbattle/assets/16023844/d929ba75-bd67-4c4f-a3fc-9232dbf1c2ac)


```
<div class="yellow">
  <div class="blue">
    <div class="white"></div>
  </div>
</div>

<style>
  body {
    background: #009B3A;  
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .yellow {
    width: 300px;
    height: 200px;
    background: #FEDF00;
    clip-path: polygon(50% 0%, 100% 50%, 50% 100%, 0% 50%);
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .blue {
    width: 120px;
    aspect-ratio: 1;
    background: #002776;
    border-radius: 100%;
    overflow: hidden;
    position: relative;
  }

  .white {
    position: absolute;
    width: 200px;
    aspect-ratio: 1;
    border-radius: 100%;
    box-shadow: 0px 0px 0px 10px rgba(255,255,255,1);
    top: 40px;
    left: -70px;
  }
</style>
```
