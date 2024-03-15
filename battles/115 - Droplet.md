# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/b9465aa6-8461-4119-b56c-b4805092d61d)

```
<p b><p r b><p c><p c y>
<style>
  *{margin: 0}
  body{
    background: linear-gradient(#C36271 50%, #F2E09F 50%);
    display:grid;
    place-items: center;
  }
  p{position: absolute}
  [b]{
    width: 380px;
    bottom: 0;
    left: 20px;
    height: 150px;
    background: #C36271;
    border-radius: 100px 0 0 0;
  }
  [r]{
    rotate: 180deg;
  }
  [r][b]{
    bottom: unset;
    left: unset;
    top: 0;
    right: 20;
    background: #F2E09F;
  }
  [c]{
    width: 100px;
    height: 100px;
    border-radius: 50%;
    background: #C36271;
  }
  [y]{
    background: #F2E09F;
    clip-path: polygon(0 50%, 100% 50%, 100% 100%, 0 100%);
  }
</style>
```

