# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/1b275bce-7430-4299-9c5e-f30c9639da83)

```
<p s><p c><p c r><p c l><p c b>
<style>
  body{
    background:#191919;
    display:grid;
    place-items:center;
  }
  p{position:absolute}
  [s]{
    width:110;
    height:110;
    background:#4F77FF;
  }
  [c]{
    width:45;
    height:45;
    border-radius:50%;
    background: #F9E492;
    translate:-53px -53px;
    box-shadow: 7.5px 7.5px 0px 7.5px #191919;
  }
  [c]:after{
    content:'';
    width:30;
    height:30;
    border-radius:50%;
    background:#4F77FF;
    position:absolute;
  }
  [r]{
    translate:52px -53px;
    rotate: 90deg;
  }
  [b]{
    translate:52px 52px;
    rotate: 180deg;
  }
  [l]{
    translate:-53px 52px;
    rotate: -90deg;
  }
</style>
```
