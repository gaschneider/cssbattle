# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/8ef0f132-3614-4b40-ac28-57af535a8c07)

```
<p e><p e><p f><p m><p n><p n><p l>
<style>
  body{
    background:#F3AC3C;
    display:grid;
    place-items:center;
  }
  p{position:absolute}
  [f]{
    width:150;
    height: 150;
    background:#998235;
    border-radius:75px 75px 60px 60px;
  }
  [f]:after,[f]:before{
    content:'';
    position:absolute;
  }
  [f]:after{
    width:20;
    height:20;
    border-radius:50%;
    background:#1A4341;
    left:25;
    top:60;
    box-shadow: 80px 0 #1A4341;
  }
  [f]:before{
    border: 26px solid transparent;
    border-top:26px solid #1A4341;
    border-bottom: unset;
    border-radius:45%;
    top:0;
    left: calc(50% - 26px)
  }
  [e]{
    width:40;
    height:40;
    background:#1A4341;
    border-radius:50%;
    translate: -55px -55px;
    box-shadow:0 0 0 10px#998235;
  }
  [e]+[e]{
    translate: 55px -55px;
  }
  [m]{
    width:100;
    height:40;
    background:#FFF;
    translate:0 40px;
    border-radius:12px 12px 30px 30px;
  }
  [n]{
    width:20;
    height:20;
    border-radius:50%;
    background:#FFF;
    translate: -15px 30px;
    box-shadow:0 0 0 10px#1A4341;
    clip-path:polygon(-10px 50%,-10px 50px, 60px 50px, 60px 50%);
  }
  [n]+[n]{
    translate: 15px 30px;
  }
  [l]{
    width:10;
    height:20;
    background:#1A4341;
    translate: 0 20px;
  }
</style>
```
