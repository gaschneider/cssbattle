# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/7dc48ae0-fcc0-4fa7-842a-644b5f127899)

```
<a><a b>
<style>
  body{
    margin:60 125;
    background:#222;
  }
  a{
    position:absolute;
    width:100;
    height:30;
    background:#F2994A;
    rotate:-45deg;
    translate:-5px 33px;
    border-radius:10px 0 0;
  }
  a:after{
    content:'';
    position:absolute;
    width:51;
    height:30;
    background:#F2994A;
    rotate:-90deg;
    left:-10;
    top:39;
    border-radius:0 0 0 5px;
  }
  [b],[b]:after{
    background:#2D9CDB;
  }
  [b]{
    rotate:135deg;
    top:143;
    left:183
  }
</style>
```
