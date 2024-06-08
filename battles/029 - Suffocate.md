# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/2fddb809-fa83-4a72-a3c4-e435f6e6e985)

```
<p><p a><p b><p c>
<style>
  *{margin:0}
  body{
    display:grid;
    grid-template:150px 150px / 200px 200px;
    background:#1A4341;
  }
  p{
    width:100%;
    height:100%;
    background:#F3AC3C;
    border-radius:0 0 100px;
  }
  [a]{border-radius:0 0 0 100px}
  [b]{border-radius:0 100px 0 0}
  [c]{border-radius:100px 0 0 0}
</style>
```
