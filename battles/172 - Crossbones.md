# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/a0c6908b-6555-4101-9551-46428d00416c)


```
<div class="bone">
  <div class="circle tl"></div>
  <div class="circle tr"></div>
  <div class="circle bl"></div>
  <div class="circle br"></div>
</div>
<div class="bone x">
  <div class="circle tl"></div>
  <div class="circle tr"></div>
  <div class="circle bl"></div>
  <div class="circle br"></div>
</div>
<style>
  body {
    background: #EFEB99;
    display: grid;
    place-items: center;
  }
  
  .bone {
    position: absolute;
    width: 190px;
    height: 30px;
    background: #8647E6;
    rotate: 45deg;

    .circle {
      position: absolute;
      width: 30px;
      aspect-ratio: 1;
      border-radius: 50%;
      background: #8647E6;
    }

    .tr {
      transform: translate(-15px, -15px);
    }

    .tl {
      transform: translate(-15px, 15px);
    }

    .bl {
      transform: translate(175px, -15px);
    }

    .br {
      transform: translate(175px, 15px);
    }
  }

  .x{
    rotate: -45deg;
  }

</style>
```
