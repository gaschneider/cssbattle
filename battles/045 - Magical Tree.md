# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/fd5a01b7-ae0c-4c5b-a187-b00532817068)

```
<p s><p s m><p l><p l>
<style>
  body{
    display:grid;
    place-items:center;
    background:#1A4341;
  }
  p{position:absolute}
  [s]{
    width:90;
    height:120;
    border:30px solid #998235;
    top:-46
  }
  [m]{
    width:210;
    height:180;
    border-color:#F3AC3C;
  }
  [l]{
    width:270;
    height:30;
    background:#998235;
    bottom:14
  }
  [l]+[l]{
    rotate:90deg;
    width:700;
    background:#F3AC3C;
  }
</style>
```
