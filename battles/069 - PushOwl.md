# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/74e9d6a2-f348-42af-bd0e-1be092429c01)

```
<p e><p s><p e r><p c><p c r>
<style>
  body{
    display:grid;
    place-items:center;
    background:#191919;
  }
  p{position:absolute}
  [e]{
    width: 114px;
    height: 114px;
    background:#E08027;
    border-radius:0 50% 50%;
    translate:-54px -16px;
  }
  [e][r]{
    transform:scaleX(-1);
    translate:54px -16px;
    box-shadow:0 0 0 10px#191919;
  }
  [c]:before{
    position:absolute;
    content:'';
    width: 12px;
    height: 6px;
    border-radius: 30px 30px 0px 0px;
    margin-top: -3px;
    border: 9px solid #E08027;
    border-bottom: none;
    left:30;
    top:39;
  }
  [c]{
    width:90;
    height:90;
    border-radius:50%;
    background:#191919;
    translate: -54px -16px;
  }
  [c][r]{
    translate: 54px -16px;
  }
  [s]{
    width: 50px;
    height: 40px;
    background: #E08027;
    rotate: 45deg;
    translate: -3.5px 41px;
  }
</style>
```
