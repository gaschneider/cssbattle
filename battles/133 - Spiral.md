# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/967f51ec-7b6d-44f7-b330-53b151874b9a)

```
<p g o b><p m b><p m o t><p m t><p c o b><p c b><p o t c><p><p s o><p s o>
<style>
  *{background: #F5D6B4}
  body{
    display: grid;
    place-items: center;
  }
  p {
    position: absolute;
    width: 40;
    aspect-ratio: 1;
    border-radius: 50%;
  }
  [t]{clip-path: polygon(0 0, 100% 0, 100% 50%, 0 50%)}
  [b]{clip-path: polygon(0 100%, 0 50%, 100% 50%, 100% 100%)}
  [o]{background: #D86F45}
  [c]{width: 80}
  [c][o][b]{width: 120;translate: -20px}
  [c][b]{translate: -20px}
  [m]{width: 120}
  [m][o]{width: 160}
  [m][b], [g]{width: 160; translate: -20px}
  [g][o]{width: 200}
  [s]{width: 20; translate: -30px}
  [s]+[s]{translate: -110px}
</style>
```
