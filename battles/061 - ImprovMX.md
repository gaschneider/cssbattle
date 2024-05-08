# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/deb9a1d7-c130-49cc-8751-cd419639622e)

```
<p s><p s><p t><p t><p l><p b>
<style>
  body{background:#191919}
  p{position:absolute}
  [l]{
    background:#5DBCF9;
    width:200;
    height:10;
    left:100;
    bottom:70;
    box-shadow:0 0 0 10px#191919;
  }
  [b]{
    background:#5DBCF9;
    width:110;
    height:10;
    left:145;
    bottom:50;
  }
  [t]{
    width:80;
    height:90;
    background:#5DBCF9;
    left:122;
    top:109;
    clip-path:polygon(0 46px, 100% 0,100% 100%, 25px 100%);
  }
  [t]:after{
    content:'';
    width:80;
    height:90;
    position:absolute;
    background:#191919;
    left:14;
    top:4;
    clip-path:polygon(0 46px, 59px 11px,59px 100%, 25px 100%);
  }
  [t]+[t]{
    transform:scaleX(-1);
    left:198
  }
  [s]{
    width:30;
    height:30;
    border:10px solid#5DBCF9;
    left:175;
    top:50;
  }
  [s]+[s]{
    width:80;
    height:60;
    left:150;
    top:80;
    background:#191919
  }
  
</style>
```
