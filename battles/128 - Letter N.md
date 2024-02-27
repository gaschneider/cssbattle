# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/65811ad7-3241-459d-a834-342166441ad8)

```
<p l><p m><p r>
<style>
  body{
    background: #998235;
    display: grid;
    place-items: center;
  }
  p{
    position: absolute;
    height: 160px;
    width: 42px;
    background: #0B2429;
  }
  [r],[l]{height: 230px; width: 40px;}
  [r]{translate: -45px 35px}
  [l]{translate: 45px -35px}
  [m]{
    background: #FCBE5C;
    transform: skewX(20deg);
  }
</style>
```
