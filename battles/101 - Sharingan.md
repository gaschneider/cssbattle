# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/67f8279f-ad1c-4e4f-8abc-62144797ec81)

```
<div><p l><p l r><p l b></div>
<style>
  body{
    background: #161616;
    display: grid;
    place-items: center;
  }
  div {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    background: radial-gradient(#000000 25px, #E96A23 25px 35px, #000000 35px 50px, #A22015 50px 95px, #000000 95px);
    position: relative;
    display: grid;
    place-items: center;
    overflow: hidden;
  }
  p{position: absolute; border-radius: 50%}
  [l]{
    border: 15px solid #000000;
    width: 70px;
    height: 70px;
    translate: -73.5px -42.5px;
  }
  [b]{
    translate: 0 85px;
  }
  [r]{
    translate: 73.5px -42.5px;
  }
</style>
```

