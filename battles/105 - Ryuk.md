# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/98725662-9715-4b4d-aab1-6d3abc962702)

```
<p t><p e><p e r><div l><p a><p b></div><div l r><p a><p b></div>
<style>
  *{margin: 0}
  body{
    background: #BAC7CE;
  }
  p{position: absolute}
  [t]{
    background: #475862;
    width: 180;
    height: 90;
    left: 110;
    clip-path: polygon(0 0, 100% 0, 50% 100%)
  }
  [e]{
    width: 120;
    height: 120;
    background: #000;
    border-radius: 0 50%;
    bottom: 50;
    left: 30;
    rotate: -15deg;
  }
  [e][r]{
    rotate: 105deg;
    right: 30;
    left: unset;
  }
  [l]{
    position: absolute;
    background: #5A6042;
    width: 100;
    height: 100;
    border-radius: 50%;
    bottom: 60;
    left: 40;
    overflow: hidden;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  [l][r]{
    right: 40;
    left: unset;
  }
  [a]{
    background: #868A64;
    width: 100%;
    height: 100%;
    translate: 0 15px;
    border-radius: 50%;
  }
  [b]{
    width: 30;
    height: 30;
    border-radius: 50%;
    background: #4E2B24;
    box-shadow: 0 0 0 5px #000000;
  }
</style>
```
