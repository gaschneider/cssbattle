# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/0c628841-0724-4db3-8468-b323f12b60ab)

```
<p e l><p e r><p h><p m><p t>
<style>
    body{
      background:#998235;
      display:grid;
      place-items:center;      
    }
  p{position:absolute}
  [e]{
    width: 80px;
    height: 180px;
    background: radial-gradient(80px 180px at 56px,#0B2429 50%,#1A4341 50%);
    border-radius: 50%;
  }
  [l]{left:50}
  [r]{right:50;transform:scaleX(-1)}
  [h]{width:180;height:180;border-radius:50%;background:#1A4341}
  [h]:before,[h]:after{
    content:'';
    position:absolute;
    width:20;
    height:20;
    background:#0B2429;
    border-radius:50%;
    left:50;
    top:80;
    box-shadow:0 0 0 10px#998235;
    clip-path:polygon(-10px 50%, 30px 50%,30px 50px, -10px 50px);
  }
  [h]:after{left:110}
  [m]{
    width:80;
    height:80;
    border-radius:50%;
    border: 20px solid #FFF;
    bottom: -26;
    clip-path:polygon(0 0, 100% 0,100% 50%, 0 50%);
  }
  [t]{
    width:40;
    height:120;
    background:#0B2429;
    bottom:-16;
    border-radius:20px 20px 0 0;
  }
</style>
```
