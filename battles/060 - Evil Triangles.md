# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/a99234b0-35e8-4d4e-9734-9838cedeea1b)

```
<div><p><p></div>
<style>
  *{margin:0}
  body,div{
    display:grid;
    place-items:center;
    background:#191919;
  }
  p,div{position:absolute}
  div {
    width: 200px;
    height: 150px;
    overflow: hidden;
  }
  p{
    width:100%;
    height:100;
    bottom:0;
    clip-path:polygon(0 0, 25% 50%, 50% 0, 75% 50%, 100% 0, 100% 50%, 75% 100%, 50% 50%, 25% 100%, 0 50%);
    background:#4F77FF;
  }
  p+p{
    top:-50
  }
</style>
```
