# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/b51a47af-4171-4646-8134-84429d8b4678)

```
<a><a t><a>
<style>
  body{
    display:grid;
    margin:50;
    background:#62306D;
    grid-template-columns:1fr 1fr 1fr;
  }
  a{
    width:100%;
    height:100%;
    background:#F7EC7D;
    border-radius:50px;
    clip-path:polygon(0 50%,100% 50%,100% 100%,0 100%)
  }
  [t]{clip-path:polygon(0 0,100% 0,100% 50%,0 50%)}
</style>
```
