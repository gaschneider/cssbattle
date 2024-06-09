# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/b0fe6897-d61e-4ba0-b408-c1b557e1e866)

```
<p><p y b><p b><p y><p y t><p><p y><p t>
<style>
  body{
    display:grid;
    place-items:center;
    place-content:center;
    grid-template: 50px 50px / repeat(4, 50px);
    gap:20px;
    background:#1A4341
  }
  p{
    width:50;
    height:50;
    border-radius:50%;
    background:#998235;
  }
  [y]{background:#F3AC3C}
  [b]{border-radius:50% 50% 0 0}
  [t]{border-radius:0 0 50% 50%}
</style>
```
