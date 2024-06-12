# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/921541be-d6e4-4ba4-895e-64e962df7100)

```
<p g f><p><p g><p f>
<style>
  body{
    display:grid;
    place-items:center;
    grid-template:60px 60px 60px / 85px 85px;
    place-content:center;
    background:#998235;
    column-gap:15px
  }
  p{
    width:80;
    height:60;
    background:#F3AC3C;
    border-radius:50px 0 50px 0
  }
  [g]{
    height:100;
    background:#1A4341;
    grid-row:span 2;
    margin-top:36px
  }
  [f]{transform:scaleX(-1)}
  [g][f]{margin-bottom:56px}
</style>
```
