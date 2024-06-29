# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/951a8de8-c8ed-4d73-835f-244daebcf530)

```
<a v><a v b><a v><a v b><a v><a v b><a v><a f><a m>
<style>
  body{
    display:grid;
    place-items:center;
    place-content:center;
    grid-template:100px 100px / repeat(7,20px);
    background:#6592CF;
  }
  a{background:#060F55}
  [v]{
    width:20;
    height:110;
    translate:0 5px;
    border-radius:10px;
  }
  [b]{background:#6592CF}
  [f]{
    grid-column:span 7;
    width:100%;
    height:100;
    border-radius:0 0 100px 100px
  }
  [m]{
    position:absolute;
    width:20;
    height:100;
    bottom:0;
  }
</style>
```
