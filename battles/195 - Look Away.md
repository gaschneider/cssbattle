# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/dcc022e2-862e-453a-a021-15dac4845274)

99.9%

```
<div><p c></div><p e><p e><p d>
<style>
  body{
    display:grid;
    place-items:center;
    background: #131313
  }
  div{
    width:240;
    height:190;
    rotate: -15deg;
    border-radius: 110px 110px 200px 200px;
    overflow:hidden;
  }
  [c]{
    width:400;
    height:342;
    background:#F459E3;
    border-radius: 50%;
    position: absolute;
    left: -230;
    top: -82;
    box-shadow: 40px 10px #E89A52, 90px 10px#F9C96C;
    z-index:-1
  }
  [e]{
    position: absolute;
    width:50;
    height:50;
    border:15px solid #131313;
    translate: -60px 10px;
    border-radius: 50%;
    clip-path:polygon(0 50%, 100% 50%, 100% 100%, 0 100%);
  }
  [e]+[e]{
    translate: 35px 10px;
  }
  [d]{
    position:absolute;
    width:15;
    height:15;
    background: #131313;
    border-radius:50%;
    translate: -93px 9px;
    box-shadow: 65px 0#131313,95px 0 #131313, 160px 0#131313
  }

</style>
```
