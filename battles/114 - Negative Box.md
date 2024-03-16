# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/041fc5b7-17f7-4c34-a97b-8ecdbcfa2d25)

```
<p b><p t>
<style>
  body{
    background: #172D2C;
    display:grid;
    place-items: center;
  }
  p{position: absolute; background: #E9AF53}
  [b]{
    width: 180px;
    height: 130px;
    transform: skewY(20deg);
    translate: -90px 32.5px;
  }
  [t]{
    width: 180px;
    height: 130px;
    translate: 90px -65px;
    clip-path: polygon(0 0, 100% 50%, 0 100%)
  }
</style>
```
