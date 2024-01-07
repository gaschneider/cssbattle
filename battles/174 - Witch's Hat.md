# TARGET
![image](https://github.com/gaschneider/cssbattle/assets/16023844/350217c3-de7d-4f11-a576-52f16b5abaa9)

```
<div class="cone"></div>
<div class="base">
  <div></div>
</div>

<div class="brooch"></div>


<style>
  body {
    background: #F4DCBF;
    display: grid;
    place-items: center;
    place-content: center;
    grid-template-rows: 140px 50px;
  }

  .cone {
    width: 0;
    height: 0;
    border: 44px solid transparent;
    border-top: 0;
    border-bottom: 150px solid #30383F;
  }
  
  .base {
    width: 150px;
    height: 60px;
    background: #30383F;
    border-radius: 50%;
    overflow: hidden;
    
    > div {
      width: 160px;
      height: 70px;
      border: 10px solid #556D7F;
      border-radius: 50%;
      transform: translate(-15px, -55px)
    }
  }

    .brooch {
      position: absolute;
      width: 30px;
      height: 20px;
      border-radius: 5px;
      background: #FBD038;
      transform: translate(0px, 70px)
    }
</style>
```
