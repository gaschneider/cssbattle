# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/64d539b0-0633-4057-9f5a-5d01fd69a4a8)


```
<div class="white"></div>
<div class="red"></div>
<div class="black"></div>
<style>
  body {
      background: #13AA4B;
  }

  div {
    position: absolute;
    width: 100%;
    height: 100%;
  }
  
  .white {
    top: 100px;
    left: 0;
    background: #FFFFFF;
  }

  .red {
    top: 200px;
    left: 0;
    background: #EC1E25;
  }

  .black {
    top: 0;
    left: 0;
    background: #000000;
    clip-path: polygon(0 0, 30% 100px, 30% 200px, 0% 100%);
  }
</style>
```
