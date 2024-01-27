# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/5bb84eb6-6b2e-4a5c-ad67-1a0068bd7905)

```
<p t><p r><p m><p l><p c>
<style>
  body{
    display: grid;
    place-content: center;
    background: radial-gradient(circle, #0B2429 80px, #FCBE5C 80px 95px, #0B2429 95px 105px, #998235 100px);
  }
  [c] {
    border-radius: 50%;
    z-index: 1;
    width: 120;
    height: 120;
    border: 10px solid #FCBE5C;
  }

  p:not([c]){
    position: absolute;
    height: 208;
    width: 30;
    background: #0B2429;
    translate: 177px 22px;
  }
  [r]{
    rotate: 45deg;
  }
  [m]{
    rotate: 90deg;
  }
  [l]{
    rotate: -45deg;
  }
</style>
```
