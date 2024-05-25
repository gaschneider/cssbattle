# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/ce2751e9-3ef4-437f-a447-8e3d2a13b105)

```
<p s>
<style>
  body{
    display:grid;
    place-items:center;
    background:#1A4341;
  }
  [s]{
    width:160;
    height:180;
    background: repeating-linear-gradient(#F3AC3C 0px 20px, #1A4341 20px 40px);
  }
  [s]:before, [s]:after {
    content:'';
    position:absolute;
    width:250;
    height:280;
    border-radius:50%;
    background:#1A4341;
  }
  [s]:before {
    translate: -220.5px -50px;
  }
  [s]:after {
    translate: 130.5px -50px;
  }
  
</style>
```
