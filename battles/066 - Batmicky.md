# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/c821cfbd-e3af-442b-be38-24d5b04233a3)

```
<p b><p s><p e><p c><p c>
<style>
  body{
    background:#191919;
    display:grid;
    place-items:center;
  }
  p{position:absolute}
  [b]{
    width:250;
    height:100;
    background:#F2AD43;
  }
  [s]{
    width:80;
    height:80;
    background:#191919;
    border-radius:10px;
    translate: 0 -60px;
  }
  [e]{
    width:20;
    height:20;
    background:#F2AD43;
    translate:0 -30px;
  }
  [e]:before{
    position:absolute;
    content:'';
    width:10;
    height:10;
    border-radius:50%;
    background:#F2AD43;
    left:-5;
    top:-5;
    box-shadow:20px 0#F2AD43;
  }
  [c]{
    width:100;
    height:100;
    border-radius:50%;
    background:#191919;
    translate:-125px;
    box-shadow: 250px 0#191919;
  }
  [c]+[c]{
    width:150;
    translate:-60px 60px;
    box-shadow:120px 0#191919;
  }
</style>
```
