# TARGEt

![image](https://github.com/gaschneider/cssbattle/assets/16023844/65cbeb96-b917-46ea-8880-4bc3b8b65807)

```
<div c><p h><p h g m><p h c><p h g s></div>
<div l><p h><p h g m><p h c><p h g s></div>
<div r><p h><p h g m><p h c><p h g s></div>
<p b>
<style>
  *{margin: 0}
  body{
    background: #4FA07B;
  }
  div{
    position: absolute;
  }
  [b]{
    height: 70px; 
    width: 20px; 
    background: #0D1335;
    translate: 190px 235px;
    box-shadow: -40px -25px #0D1335, 40px -25px #0D1335;
  }
  div[c]{translate: 130px 20px}
  div[l]{translate: 70px 120px}
  div[r]{translate: 190px 120px}
  [h] {
    --color: #0D1335;
    position: absolute;
    width: 140px;
    height: 117px;
    background: var(--color);
    border-radius: 150px 150px 0 0;
  }
  [g]{--color: #4FA07B}
  p[m]{
    width: 100px;
    height: 97px;
    top: 20px;
    left: 20px;
  }
  p[c]{
    width: 60px;
    height: 100px;
    top: 40px;
    left: 40px;
  }
  [s]{
    width: 20px;
    height: 80px;
    top: 60px;
    left: 60px;
  }
</style>
```
