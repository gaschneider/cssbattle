# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/10366411-f604-440f-aac7-fa90e407e888)

```
<p><p l><p c><p q><p q>
<style>
  body{
    background: #F3AC3C;
    display: grid;
    place-items: center;
  }
  p{
    position: absolute;
    background: #998235;
    width: 160;
    height: 160;
    translate: -2px;
    rotate: 45deg
  }
  [l]{
    background: #F3AC3C;
    width: 100;
    height: 100;
  }
  [c]{
    background: #1A4341;
    width: 30;
    height: 30;
  }
  [q]{
    background: #F3AC3C;
    width: 30;
    height: 100;
    translate: 60px -61.5px;
  }
  [q]+[q]{
    rotate: -45deg;
    translate: -61.5px -60px;
  }
</style>
```
