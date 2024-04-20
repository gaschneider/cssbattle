# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/e2bf1e03-4a89-4c46-9f82-18deabef554d)

```
<p c><p b><p x><p r><p r><p r><p r><p r>
<style>
  *{margin: 0;background:#6592CF}
  body{
    display:grid;
    place-items: center;
  }
  p{position: absolute;aspect-ratio: 1;border-radius: 50%}
  [c],[r]{border: 10px solid #243D83}
  [c]{
    width: 150;
    margin-top:19
  }
  [b],[x]{
    border-radius: 10px 70px;
    width: 70;
    translate: 0 74px;
    rotate: 135deg;
    background: #243D83;
  }
  [x]{
    border-radius: 10px 50px;
    width: 65;
    translate: 0 85px;
    background: #6592CF
  }
  [r]{
    width: 30;
    translate: -70px 40px;
  }
  [r]+[r]{translate: 70px 40px}
  [r]+[r]+[r]{translate: -70px -30px}
  [r]+[r]+[r]+[r]{translate: 70px -30px}
  [r]+[r]+[r]+[r]+[r]{translate: 0px -70px}
  [r]:after{
    content: '';
    width: 10;
    height:10;
    background:#243D83;
    position: absolute;
    border-radius: 50%;
    left: calc(50% - 5px);
    top: calc(50% - 5px);
  }
</style>
```
