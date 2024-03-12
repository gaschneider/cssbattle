# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/06836ca4-a865-4b00-8e28-65592842e691)

```
<p w><p b><p b r><p b>
<style>
  *{margin:0}
  body{
    background:#000;
    display:grid;
    place-content:center;
    grid-template-rows:20px 20px 20px;
    grid-gap:30px
  }
  [b]{
    width:300px;
    height:20px;
    background:#af067c;
    border-radius:15px
  }
  [r]{
    rotate:-4deg
  }
  [w]{
    position:absolute;
    background:#fff;
    height:60px;
    width:20px;
    translate:80px 90px;
    z-index:-1;
    box-shadow:220px 20px #fff,220px 40px #fff,110px 52px #fff
  }
</style>
```
