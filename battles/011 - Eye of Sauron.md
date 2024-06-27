# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/f1732dfc-8325-427b-815f-aa8798a89b6a)

```
<a c><a c h l><a c h r><a d>
<style>
  body{
    background:#191210;
    display:grid;
    place-items:center;
  }
  a{
    position:absolute;
    width:100;
    aspect-ratio:1;
    border-radius:50%
  }
  [c]{
    
    border:20px solid#ECA03D;
  }
  [h]{
    width:60;
    clip-path:polygon(0 0,100% 0,100% 50%,0 50%)
  }
  [l]{rotate:180deg;left:50}
  [r]{right:50}
  [d]{
    width:50;
    background:#84271C;
  }
</style>
```
