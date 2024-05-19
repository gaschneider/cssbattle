# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/efc9a242-4005-4be7-b15a-0d61fad90a84)

```
<p r><p h>
<style>
  *{margin:0}
  body {
    background: #6592CF;
    display:grid;
    place-content:center;
    place-items:center;
    grid-template-rows:100px 100px
  }
  p{background:#243D83}
  [r]{
    width:200;
    height:100;
    clip-path:polygon(0 100%, 50% 0, 100% 100%)
  }
  [h]{
    width:150;
    height:100;
    border-radius:0 0 10px 10px;
    position:relative;
  }
  [h]:before,[h]:after{
    content:'';
    position:absolute;
    background:#EEB850;
  }
  [h]:before{
    width:100;
    height:10;
    top:-5;
    left:25;
    border-radius:5px;
  }
  [h]:after{
    width:50;
    height:50;
    bottom:0;
    left:50;
    border-radius:10px 10px 0 0;
  }
</style>
```
