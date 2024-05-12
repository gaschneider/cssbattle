# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/71e98bdd-2f7f-4d73-ac12-f1c113fa8b81)

```
<p h><p m>
<style>
  body{
    display:grid;
    place-items:center;
    place-content:center;
    grid-template-rows: 100px 30px;
    background:#191919;
  }
  p{background:#4F77FF}
  [h]{
    width:120;
    height:100;
    border-radius: 100px 100px 16px 16px;
    position:relative;
  }
  [h]:after,[h]:before,[m]:after{
    content:'';
    aspect-ratio:1;
    border-radius:50%;
    position:absolute;
    background:#191919;
  }
  [h]:before{
    width:40;
    left:15;
    top:53;
    box-shadow:50px 0 #191919;
  }
  [h]:after{
    width:20;
    left:50;
    top:91;
  }
  [m]{
    width:80;
    height:30;
    border-radius:0 0 20px 20px;
    position:relative;
    z-index:-1
  }
  [m]:after{
    width:10;
    border-radius:50% 50% 0 0;
    left:20;
    top:20;
    box-shadow:15px 0#191919, 30px 0 #191919
  }
</style>
```
