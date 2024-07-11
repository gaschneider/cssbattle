# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/a5169156-031d-40ca-a729-e2ceb85d9cfd)

```
<a s b><a m><a s c><a m><a s t>
<style>
  body{
    display:grid;
    place-items:center;
    grid-template-columns:50px 100px 100px 100px 50px;
    background:#6867D4;
    margin:0
  }
  a{width:100%;height:100}
  [s]{background:#7BAFDE;transform:skewY(26.5deg)}
  [b]{translate:0 12.5px}
  [s][t]{translate:0 -12.5px}
  [m]{background:#000039;transform:skewY(-26.5deg)}
  [c]{height:200}
</style>
```
