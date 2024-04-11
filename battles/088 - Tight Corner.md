# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/d472810b-75a1-4496-abc1-93628bc7270d)

```
<p b><p c><p s><p s>
<style>
  *{margin: 0}
  body{
    display: grid;
    place-items: center;
    background: #F7F3DA;
  }
  p{position: absolute}
  [b]{
    width: 300;
    height: 40;
    background: #D25B70;
    border-radius: 10px;
    translate: -150px -20px;
    box-shadow: 300px 40px #D25B70;
  }
  [c]{
    width: 40;
    height: 40;
    background: #D25B70;
    border-radius: 50%;
  }
  [s]{
    width: 200;
    height: 150;
    background: #F7F3DA;
    right: 0;
    top: 0;
    border-radius: 0 0 0 20px;
  }
  [s]+[s]{
    bottom: 0;
    left: 0;
    top: unset;
    right: unset;
    border-radius: 0 20px 0 0;
  }

</style>
```
