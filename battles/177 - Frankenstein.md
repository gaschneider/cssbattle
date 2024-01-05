# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/e13a91e6-ecee-44da-90b5-e3894f7ca035)

```
<div class="head">
  <div class="hair"></div>
  <div class="eye eyeLeft"></div>
  <div class="eye eyeRight"></div>
  <div class="mouth"></div>
</div>

<div class="screw screwLeft"></div>
<div class="screw screwRight"></div>
<div class="line"></div>


<style>
  body {
    background: #3C8D3F;
    display: grid;
    place-items: center;
  }
  
  .head {
    width: 150px;
    aspect-ratio: 1;
    background: #14F078;
    border-radius: 10px 10px 50% 50%;
    position: relative;
    overflow: hidden;
    display: grid;
    place-items: center;
  }

  .eye {
    position: absolute;
    width: 30px;
    aspect-ratio: 1;
    border-radius: 50%;
    background: radial-gradient(#FFFFFF 22.5%, #1A1D2F 22.5% 100%);
    margin-top: 20px;
  }

  .eyeLeft {
    margin-left: -60px;
  }

  .eyeRight {
    margin-right: -60px;
  }

  .mouth {
    position: absolute;
    width: 40px;
    height: 20px;
    margin-top: 90px;
    background: #1A1D2F;
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 20px;
  }

  .screw {
    position: absolute;
    width: 10px;
    height: 30px;
    background: #1A1D2F;
    border-radius: 5px;
    margin-top: 20px;
  }

  .screwLeft {
    margin-left: -190px;
  }

  .screwRight {
    margin-right: -190px;
  }

  .line {
    position: absolute;
    width: 200px;
    height: 10px;
    background: #1A1D2F;
    margin-top: 20px;
    z-index: -1;
  }

  .hair {
    position: absolute;
    width: 100%;
    height: 45px;
    background:  #1A1D2F;
    top: 0;
    clip-path: polygon(0 0, 100% 0%, 100% 67.5%, 90% 100%, 80% 67.5%, 70% 100%, 60% 67.5%, 50% 100%, 40% 67.5%, 30% 100%, 20% 67.5%, 10% 100%, 0 67.5%);
  }
</style>
```
