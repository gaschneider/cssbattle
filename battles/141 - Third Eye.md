# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/1f114eb9-7c21-4fe1-9a98-e45a3ce8dc8a)

```
<p c t><p m><p c b>
<style>
  *{margin: 0;}
  body{
    display: grid;
    place-items: center;
    background: #E3516E;
  }
  [c]{
    border-radius: 0 0 75px; 
    width: 75px;
    height: 75px;
  }
  [t]{top: 0; left: 0;}
  [b]{bottom: 0; right: 0; rotate: 180deg;}
  p {
    position: absolute;
    background: #D9D9D9;
  }
  [m] {
    width: 100px;
    height: 100px;
    border-radius: 0 100px;
    rotate: -45deg;
  }
</style>
```
