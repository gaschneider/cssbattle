# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/2d0d01eb-c84d-48cd-bbd0-3110ce0adf66)

```
<a c><a c b><a l><a r><a s l><a s r>
<style>
  body{
    background:#90D3A6;
    display:grid;
    place-items:center;
    place-content:center;
    grid-template-rows:160px 20px;
  }
  a{background:#024817;width:20;}
  [c]{
    height:160;
    border-radius:10px 10px 0 0;
  }
  [b]{
    rotate:90deg;
    height:200;
    border-radius:10px;
  }
  [l],[r]{
    position:absolute;
    height:60;
    top:85;
    border-radius:10px
  }
  [l]{
    left:164;
    rotate:-60deg;
  }
  [r]{
    right:164;
    rotate:60deg;
  }
  [s]{
    top:135
  }
</style>
```
