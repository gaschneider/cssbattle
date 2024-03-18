# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/14101ce4-9eba-4e99-8776-ce70a73bf632)

```
<p><p r><p><p r><p><p r>
<style>
  *{margin: 0}
  body{
    display: grid;
    place-content: center;
    place-items: center;
    grid-template-columns: 125px 125px;
    grid-template-rows: 50px 50px 50px;
    background: #6592CF;
  }
  p{
    width: 125px;
    height: 120px;
    background: #293D7E;
    clip-path: polygon(0 10px, 40px 10px, 100% 80px, 100% 110px);
  }
  [r]{
    clip-path: polygon(100% 10px, 85px 10px, 0 80px, 0 110px);
  }
</style>
```
