# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/9301ea67-1541-45e0-84d0-d2f23a07ab7e)

```
<p><p o>
<style>
  body{
    display:grid;
    place-items:center;
    place-content:center;
    grid-template-columns:100px 100px;
    background:#62306D;
    column-gap:40px
  }
  p{
    width:100;
    height:100;
    background:#F7EC7D;
    border-radius:50%;
    position:relative;
  }
  p:before{
    position:absolute;
    content:'';
    width:100;
    height:100;
    background:#AA445F;
    top:-50;
    z-index:-1;
    border-radius:50% 50% 0 0;
  }
  [o]:before{background:#E38F66;rotate:180deg;top:50}
</style>
```
