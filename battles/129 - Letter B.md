# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/1128c494-1fef-4c27-a42b-821e0363fc50)

```
<div r><p s><p c t><p c b></div><div m><p s><p c t><p c b></div><div l><p s><p c t><p c b>
<style>
  body{background: #6592CF;}
  *{margin: 0}
  [l]>*{ background: #060F55;}
  [m]>*{ background: #2E3B9F;}
  [r]>*{ background: #515DBD;}
  [s]{
    width: 55px;
    height: 140px;
    translate: -63px 0;
  }
  [c]{
    width: 80px;
    height: 80px;
    border-radius: 50%;
  }
  [t]{translate: -30px -30px}
  [b]{translate: -30px 30px}
  body,div{
    display: grid;
    place-items: center;
  }
  div,p{position:absolute}
  [m]{translate: 40px 0}
  [r]{translate: 80px 0}
</style>
```
