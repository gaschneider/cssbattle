# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/238c0838-26b3-49b1-8be4-be59e5db1930)

```
<p f><p m>
<style>
  body{background:#293462;display:grid;place-items:center}
  [f]{
    width:200;
    height:200;
    background:#FE5F55;
    border-radius:50% 50% 50px 50px;
    overflow:hidden;
    position:relative;
  }
  [f]:before,[f]:after{
    content:'';
    position:absolute;
    width:60;
    aspect-ratio:1;
    background:#FFF1C1;
    border-radius:50%;
    left:20;
    top:90;
    box-shadow:100px 0#FFF1C1;
  }
  [f]:before{
    width:100;
    top:-50;
    left:0
  }
  [m]{
    position:absolute;
    width:40;
    height:10;
    background:#FFF1C1;
    border-radius:10px;
    translate:0 75px
  }
</style>
```
