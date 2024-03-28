# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/df79987b-f17e-466a-9913-41c8f746a543)

```
<p y a><p y e><p h><p m><p y b><p y c><p y d>
<style>
  *{margin: 0}
  body{
    background: #161616;
    display: grid;
    place-items: center;
  }
  p{position: absolute}
  [h]{
    width: 80px;
    height: 60px;
    background: linear-gradient(90deg, #FFFFFF 50%, #FFDEB9 50%);
    translate: 0 36px;
    border-radius: 0 0 50px 50px;
  }
  [m]{
    width: 20px;
    height: 20px;
    background: #161616;
    translate: 0 46px;
    border-radius: 50%;
    clip-path: polygon(0 50%, 100% 50%, 100% 100%, 0 100%);
  }
  [y]{
    width: 60px;
    height: 60px;
    border-radius: 50%;
    background: #EBAE11;
    clip-path: polygon(0 50%, 100% 50%, 100% 100%, 0 100%);
  }
  [a]{
    translate: -29px 10px;
    rotate: 15deg;
  }
  [b]{
    translate: -15px -8px;
    rotate: 60deg;
  }
  [c]{
    height: 58;
    width: 58;
    border-radius: 0 100px 0 100px;
    clip-path: unset;
    rotate: 45deg;
    translate: 0 -25px;
  }
  [d]{
    translate: 15px -8px;
    rotate: -60deg;
  }
  [e]{
    translate: 29px 10px;
    rotate: -15deg;
  }
</style>
```
