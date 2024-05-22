# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/24ea36e2-c73e-46e9-9d8f-e70b66b052a6)

```
<p m><p l><p l r><p l b><p c><p c><p c>
<style>
  body{
    display:grid;
    place-items:center;
    background:#1A4341
  }
  p{position:absolute;background:#F3AC3C}
  [m]{
    width:100;
    height:100;
    border-radius:50%;
  }
  [l]{
    width:10;
    height:180;
    top:34;
    border-radius:10px;
    transform-origin:0 50%;
  }
  [r]{
    rotate: 60deg;
    translate:11px 1px;
  }
  [b]{
    rotate: -60deg;
    translate:11px 19px;
  }
  [c]{
    width:10;
    aspect-ratio:1;
    background:#998235;
    border-radius:50%;
    translate:25px -25px
  }
  [c]+[c]{
    width:20;
    translate:0 25px
  }
  [c]+[c]+[c]{
    width:30;
    translate:-15px -15px;
  }
</style>
```
