# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/a90b937d-b2f4-46ec-978b-ce5db6ef53bc)

```
<a b><a b><a b><a c>
<style>
  body{
    background:#5F133F;
    display:grid;
    place-items:center;
  }
  [c]{
    position:absolute;
    width:50;
    height:50;
    background:#F7BED9;
    border-radius:50%;
  }
  [b]{
    width:220;
    height:50;
    rotate:30deg;
    background:linear-gradient(90deg,#F7BED9 30px,#F075B0 0 190px, #F7BED9 0);
    position:absolute;
    clip-path:polygon(0 50%,30px 0,190px 0,100% 50%,190px 100%, 30px 100%)
  }
  [b]+[b]{rotate:90deg}
  [b]+[b]+[b]{rotate:150deg}
</style>
```
