# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/c70c750b-26e8-4ecd-923a-51a20460ba1e)


```
<div class="ears">
  <div class="left"></div>
  <div class="right"></div>
</div>
<div class="head"></div>
<div class="eyes">
  <div></div>
  <div></div>
</div>

<style>
  body {
    background: #ED6A9D;
    display: grid;
    place-items: center;
  }

  .ears {
    position: absolute;
    display: flex;
    gap: 70px;
    top: 60px;
    
    > * {
      width: 0;
      height: 0;
      border: 30px solid transparent;
      border-top: 0px;
      border-bottom: 60px solid #050044;
    }

    .left {
      rotate: -30deg;
    }
    .right {
      rotate: 30deg;
    }
  }
  
  .head {
    background: #050044;
    margin-top: 30px;
    width: 180px;
    height: 150px;
    border-radius: 50%;
    display: grid;
    place-items: center;

    &:before{
      content: "";
      width: 0;
      height: 0;
      border: 15px solid transparent;
      border-top: 0px;
      border-bottom: 15px solid #ED6A9D;
      rotate: 180deg;
      margin-top: 55px;
    }
  }
  
  .eyes {
    position: absolute;
    display: flex;
    gap: 30px;
    > * {
      width: 40px;
      aspect-ratio: 1;
      background: #FFC100;
      border-radius: 50% 0;
      rotate: 45deg;
      display: grid;
      place-items: center;

      &:before {
         content: "";
        width: 10px;
        height: 30px;
        background: #050044;
        rotate: -45deg;
        border-radius: 100%;
      }
    }
  }
</style>
```
