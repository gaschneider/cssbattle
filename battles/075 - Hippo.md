# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/69ee19f6-59ee-4716-aaca-caaa66627d3a)

```
<p e><p e><p h><p n><p y>
<style>
  body{
    background:#191919;
    display:grid;
    place-items:center;
  }
  p{position:absolute}
  [n]{
    width:150;
    height:100;
    background:#A64942;
    translate:0 45px;
    border-radius: 55px 55px 45px 45px;
  }
  [n]:before,[n]:after{
    content:'';
    width:30;
    height:20;
    background:#000;
    position:absolute;
    border-radius: 50%;
    left:20;
    top:25;
    rotate:-45deg;
  }
  [n]:after{
    rotate:45deg;
    left:unset;
    right:20;
  }
  [h]{
    width:130;
    height:150;
    background:#FE5F55;
    border-radius:60px 60px 0 0;
  }
  [y]{
    width:10;
    height:10;
    background:#000;
    border-radius:50%;
    translate: -35px -20px;
    box-shadow: 70px 0#000;
  }
  [e]{
    width:20;
    height:10;
    background:#000;
    border-radius: 50%;
    rotate:-45deg;
    translate: 40px -65px;
    box-shadow:0 0 0 5px#FE5F55;
  }
  [e]+[e]{
    rotate:45deg;
    translate: -40px -65px;
    box-shadow:0 0 0 5px#FE5F55;
  }
</style>
```
