# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/876545ab-a9a1-4d1c-9035-e01222395913)

```
<a c><a c l><a c r><a d l><a d r>
<style>
  body{
    background:#F5D6B4;
    display:grid;
    place-items:center;
  }
  a{
    position:absolute;
    width:60;
    aspect-ratio:1;
    border-radius:50%;
  }
  [c]{
    border:20px solid#D86F45;
    clip-path:polygon(0 0,100% 0,100% 50%,0 50%)
  }
  [l],[r]{rotate:180deg}
  [l]{left:70}
  [r]{right:70}
  [d]{
    width:20;
    border-radius:50%;
    background:#D86F45;
  }
</style>
```
