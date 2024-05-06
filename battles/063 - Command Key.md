# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/9cf940e7-5fa4-4543-bd9b-aec5c4ab6ac8)

```
<p s><p d><p d r><p d l><p d b>
<style>
  body{
    display:grid;
    place-items:center;
    background:#191919
  }
  p{
    position:absolute;
    width:50;
    height:50;
    background:#191919;
    border:10px solid #5DBCF9;
  }
  [s]{translate:1px -1px}
  [d]{
    translate:-59px -61px;
    border-radius:50% 50% 0;
  }
  [r]{
    rotate:90deg;
    translate: 61px -61px;
  }
  [l]{
    rotate:-90deg;
    translate:-59px 59px;
  }
  [b]{
    rotate:180deg;
    translate:61px 59px;
  }
</style>
```
