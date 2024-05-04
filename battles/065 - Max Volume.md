# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/ffe0010b-324e-4508-aeb2-1c8e850ddf06)

```
<p c><p t><p s>
<style>
  body{
    background:#191919;
    display:grid;
    place-items:center;
  }
  p{position:absolute}
  [c]{
    width:80;
    height:80;
    border-radius:50%;
    box-shadow:0 0 0 10px#5DBCF9,0 0 0 25px#191919,0 0 0 35px#5DBCF9,0 0 0 50px#191919,0 0 0 60px#5DBCF9;
    translate:25px;
    clip-path:polygon(50% -60px, 200px -60px, 200px 200px, 50% 200px)
  }
  [t],[s]{background:#5DBCF9}
  [t]{
    width:100;
    height:200;
    translate: -50px;
    clip-path:polygon(0 50%,100% 0, 100% 100%)
  }
  [s]{
    width:100;
    height:50;
    translate:-75px;
    border-radius:10px;
  }
</style>
```
