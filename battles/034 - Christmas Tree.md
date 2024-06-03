# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/83c43c26-2981-4a23-9e19-b02e5b6ef900)

```
<p><p s><p t>
<style>
  body{
    display:grid;
    place-content:center;
    place-items:center;
    grid-template-rows:50px 50px 50px;
    background:#007065;
  }
  p{
    width:250;
    height:100;
    background:#FFEECF;
    clip-path:polygon(50% 0, 100% 100%, 0 100%)
  }
  [s]{background:#F5C181;z-index:-1}
  [t]{background:#00A79D;z-index:-2}
</style>
```
