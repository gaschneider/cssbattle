# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/8dffc340-8114-4954-8c28-21141eef8e68)

```
<p h><p m>
<style>
  body{
    display:grid;
    place-items:center;
    background:#293462;
  }
  p{position:absolute}
  [h]{
    width:250;
    height:40;
    border:10px solid#FFF1C1;
    border-radius:50px;
    translate:0 -20px;
  }
  [m]{
    width:150;
    height:100;
    background:#FFF1C1;
    border-radius:0 0 50px 50px
  }
  [m]:before,[m]:after{
    content:'';
    position:absolute;
    background:#FE5F55;
    width:40;
  }
  [m]:before{
    height:10;
    left:20;
    top:20;
    border-radius:5px;
    box-shadow:0 20px#FE5F55
  }
  [m]:after{
    height:40;
    right:20;
    top:40;
    border-radius:50%;
  }
</style>
```
