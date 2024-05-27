# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/230faa3e-914f-45dc-9a9d-b1dc5f9a81f3)

```
<p><p>
<style>
  body{
    display:grid;
    place-items:center;
    background:#293462;
  }
  p{
    position:absolute;
    width:50;
    height:135;
    background:#FE5F55;
    translate:-25px -3px;
    border-radius:0 40px;
  }
  p:before,p:after{
    content:'';
    position:absolute;
    background:#293462;
    border-radius:50%;
    aspect-ratio:1;
  }
  p:before{
    width:30;
    right:5;
    top:60;
  }
  p:after{
    width:80;
    bottom:-45;
    left:-30;
    border-radius:0 50% 0 0;
  }
  p+p{
    transform:scaleX(-1);
    translate:25px -3px;
  }
</style>
```
