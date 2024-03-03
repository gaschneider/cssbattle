# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/0430e2e4-6842-45ba-a320-ce2913be58f7)

```
<p c><p t><p t><p t><p t>
<style>
  *{margin: 0}
  body{
    background: radial-gradient(circle, #8B0051 20px, 0, #F180B6 35px, 0, #8B0051 50px, 0, #FCDDEB 65px, 0, #8B0051 80px, 0, #FCDDEB);
  }
  p{position: absolute}
  [c]{
    width: 30px;
    height: 30px;
    border-radius: 50%;
    background: #8B0051;
    translate: 85px 135px;
    box-shadow: 200px 0px #8B0051, 100px -100px #8B0051, 100px 100px #8B0051;
  }
  [t]{
    width: 52px;
    height: 30px;
    background: #8B0051;
    translate: 100px 135px;
    clip-path: polygon(0 0, 100% 26%, 100% 74%, 0 100%);
  }
  [t]+[t]{
    rotate: 90deg;
    translate: 174px 60px;
  }
  [t]+[t]+[t]{
    rotate: 180deg;
    translate: 248px 135px;
  }
  [t]+[t]+[t]+[t]{
    rotate: -90deg;
    translate: 174px 207px;
  }
</style>
```
