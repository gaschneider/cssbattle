# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/c3b2d9bd-a558-4f2e-a347-1ab35e1a9715)

```
<p s><p b><p s><p t><p><p><p>
<style>
  body{
    display:grid;
    place-items:center;
    grid-template-columns: repeat(3, 45px) 30px repeat(4, 45px);
    margin:0 45;
    padding-top:30;
    background:#6592CF;
  }
  p{
    width:10;
    height:50;
    background:#243D83;
    justify-self:start;
    position:relative;
  }
  p:after,[s]:before,[b]:before{
    content:'';
    width:20;
    aspect-ratio:1;
    border-radius:50%;
    position:absolute;
    background:#243D83;
    left:-5;
    top:-10
  }
  [s]:before,[b]:before{
    width:40;
    background:#EEB850;
    left:-15;
    top:-20;
    z-index:-1;
  }
  [b]:before{width:60;left:-25;top:-40}
  [t]{grid-column:span 2; translate:30px}
</style>
```
