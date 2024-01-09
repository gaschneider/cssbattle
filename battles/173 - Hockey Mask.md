# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/a2e5e80c-3d55-474d-8029-54a45add5031)

```
<div c></div>
<div class="forehead">
  <div c s class="left"></div>
  <div c s class="right"></div>
  <div c s class="center"></div>
</div>
<div class="eyes">
  <div c></div>
  <div c></div>
</div>
<div class="mouth">
  <div c s></div>
  <div c s></div>
  <div c s></div>
  <div c s></div>
  <div c s></div>
  <div c s></div>
</div>

<style>
  body {
    background: #A5B5B4;
    display: grid;
    place-items: center;
  }
  [c] {
    position: absolute;
    width: 150px;
    height: 180px;
    background: #FFFFFF;
    border-radius: 50%;
  }

  .forehead {
    width: 60px;
    height: 40px;
    transform: translateY(-55px);
    display: grid; 
    place-items: center;
    grid-template-columns: 1fr 1fr; 
    grid-template-rows: 1fr 1fr; 
    grid-template-areas: 
      "left right"
      "center center"; 
  }

  .center { grid-area: center; }
  .left { grid-area: left; }
  .right { grid-area: right; }

  .eyes {
    position: absolute;
    display: flex;
    gap: 40px;
    transform: translate(0px, -25px);
    align-items: center;
    justify-content: center;
    > div {
      position: relative;
      width: 30px;
      height: 30px;
      background: #000000;
    }
  }

  .mouth {
    position: absolute;
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-auto-rows: 20px;
    width: 60px;
    height: 60px;
    transform: translate(10px, 40px);

    > [c] {
      position: relative;
    }
  }
  
  [s] {
    width: 10px;
    height: 10px;
    background: #000000;
  }
</style>
```
