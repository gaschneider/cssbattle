# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/6a756f78-b5f1-4ae2-9c5e-727747a41436)

```
<p g t w r><p m t w l><p s t l><p b w><p b>
<style>
  *{background: #D669EC}
  body{
    display:grid;
    place-items: center;
  }
  p  {position: absolute;}
  [w]{background: #FDFBF8;}
  
  [g]{width: 180;height: 180;}
  [m]{width: 80; height: 80;}
  [s]{width: 50; height: 50;}
  
  [t]{clip-path: polygon(0 0, 100% 50%, 0 100%);}
  
  [r]{translate: 55px;}
  [l]{rotate: 180deg; translate: -105px}
  [s][l]{translate: -90px}

  [b]{width: 150; height: 20; rotate: 90deg; translate: 85px}
  [b][w]{translate: -40px; rotate: unset;}
</style>
```
