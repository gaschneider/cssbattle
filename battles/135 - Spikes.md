# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/18dfdad6-be05-4729-8314-1d3e95ba1043)

```
<p><p t><p l><p r>
<style>
  *{margin: 0}
  body{
    display: grid;
    place-content: center;
    grid-template: 40px 40px / 40px 40px;
    gap: 20px 10px;
    background: #E3516E;
    margin-left: -10px;
  }
  p {
    width: 30px;
    height: 40px;
    background: #D9D9D9;
    border-radius: 0 40px 40px 0;
    justify-self: end;
    position: relative;
  }
  p:after{
    position: absolute;
    content: '';
    border: 29px solid transparent;
    border-top: 0px;
    border-bottom: 29px solid #D9D9D9;
    rotate: 45deg;
    left: -39px;
    top: -4px;
  }
  [t] {
    transform: scaleX(-1);
  }
  [l]{
    transform: scaleY(-1);
  }
  [r]{
    transform: scale(-1);
  }
</style>
```
