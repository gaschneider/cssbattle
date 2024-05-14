# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/ba6b3c25-aa08-4bf1-a870-0c4bd01cb354)

```
<p><p><p><p>
<style>
  body{
    display:grid;
    place-items:center;
    background:#191919
  }
  p{
    width:100;
    height:100;
    border-radius:50%;
    background:#F9E492;
    clip-path:polygon(0 0, 0 50%, 100% 50%, 100% 0);
    position:absolute;
    translate:-50px;
    transform-origin: 100% 50%;
  }
  p+p{rotate:180deg}
  p+p+p{rotate:90deg;background:#4F77FF}
  p+p+p+p{rotate:-90deg}
</style>
```
