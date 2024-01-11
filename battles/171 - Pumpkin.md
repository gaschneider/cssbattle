# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/05d13876-8d80-48c1-80e5-0c17194f20c5)

```
<div class="core fl"></div>
<div class="core l"></div>
<div class="core fr"></div>
<div class="core r"></div>
<div class="core"></div>
<div class="tip"></div>
<style>
  body {
    background: #784972;
    display: grid;
    place-items: center;
  }
  
  .core {
    position: absolute;
    width: 100px;
    height: 150px;
    background: #F7FFCF;
    transform: translateY(25px);
    border-radius: 50%;
    box-shadow: 0px 0px 0px 10px #784972;
  }

  .tip {
    position: absolute;
    width: 22px;
    height: 80px;
    background: #F7FFCF;
    border-radius: 11px;
    transform: translateY(-60px);
  }

  .l {
    margin-left: -80px;
  }

  .fl {
    margin-left: -160px;
  }

  .r {
    margin-left: 80px;
  }

  .fr {
    margin-left: 160px;
  }

</style>
```
