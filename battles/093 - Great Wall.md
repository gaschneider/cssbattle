# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/75818d7f-4e32-4da3-980d-1fb05e7ea2dd)

```
<div><p l><p r></div><p c><p m>
<style>
  body{
    display: grid;
    place-items: center;
    background: #4F77FF;
  }
  div {
    width: 200px;
    height: 200px;
    background: #191919;
    border-radius: 50%;
    position: relative;
    overflow: hidden;
  }
  p{position: absolute}
  [l],[r]{
    width: 100;
    height: 16;
    background: #F9E492;
    box-shadow: 0 26px #F9E492, 0 52px #F9E492;
  }
  [l]{translate: 0 106px}
  [r]{translate: 120px 93px}
  [c]{
    width: 20;
    height: 16;
    transform: skewY(-33deg);
    background: #D6B73F;
    translate: 10px 23.3px;
    box-shadow: 0 26px #D6B73F, 0 52px #D6B73F;
  }
  [m]{
    width: 40;
    height: 40;
    background: #F9E492;
    border-radius: 50%;
    translate: -40px -40px;
  }
</style>
```
