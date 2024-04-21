# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/cb652238-2329-413b-bf66-58521809c72c)

```
<p n r><p n r><p n b><p n r><p l r>
<style>
  body{
    display:grid;
    place-items:center;
    place-content:center;
    grid-template-columns:repeat(4, 50px);
    background:#191919;
    gap:20px;
  }
  p{translate: 5px -10px}
  [r]{--color:#FE5F55;background:var(--color)}
  [b]{--color:#A64942;background:var(--color)}
  [n]{
    position:relative;
    width:10;
    height:100;
  }
  [n]:after{
    position:absolute;
    content:'';
    width: 50;
    height:40;
    background:var(--color);
    bottom:-20;
    left:-40;
    border-radius:50%;
  }
  [l]{
    position: absolute;
    width:40;
    height:10;
    translate: -83px -55px;
    box-shadow: 35px 0#FE5F55, 138px 0#A64942, 208px 0#FE5F55, 208px 20px#FE5F55;
  }
</style>
```
