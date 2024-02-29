# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/d0749bd5-eab0-46ac-b5ec-c086a6d1effc)

```
<p r><p l><p r s><p l s>
<style>
  *{margin: 0}
  body{
    display: grid;
    place-items: center;
    background: #62306D;
  }
  p{
    position: absolute;
    height: 140px;
    width: 42px;
  }
  [r]{
    background: #C5B732;
    transform: skewX(20deg);
    translate: 30px;
  }
  [l]{
    background: #FEF9CA;
    transform: skewX(-20deg);
    translate: -30px;
  }
  [s]{
    height: 50px;
    width: 52px;
  }
  [s][r]{
    background: #AA445F;
    translate: 25px 45px;
    transform: skewX(40deg);
  }
  [s][l]{
    background: #E38F66;
    translate: -25px 45px;
    transform: skewX(-40deg);
  }
</style>
```
