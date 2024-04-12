# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/9fb44196-f674-432b-a376-f48bc3cf925a)

```
<p r><p r><p s>
<style>
  body{
    background: #F3AC3C;
    display: grid;
    place-items: center;
    
  }
  [r],[r]:after{position: absolute; background: #1A4341}
  [r]{
    width: 100;
    height: 100;
    translate: -85px -35px;
    border-radius: 10px 0 10px 10px;
    z-index: -1;
  }
  [r]:after{
    content: '';
    width: 50;
    height: 50;
    right: -50px;
    border-radius: 0 10px 10px 0;
    box-shadow: -40px 10px #1A4341;
  }
  [r]+[r]{
    rotate: 180deg;
    translate: 85px 35px;
  }
  [s]{
    width: 70;
    height: 70;
    background: #F3AC3C;
    border-radius: 10px;
  }
</style>
```
