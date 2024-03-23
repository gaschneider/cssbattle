# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/67f8279f-ad1c-4e4f-8abc-62144797ec81)

```
<div o><p l><p l r><p l b></div><p c>
<style>
  body{
    background: #161616;
    display: grid;
    place-items: center;
  }
  p{
    position: absolute;
    border-radius: 50%;
  }
  [o]{
    background: #A22015;
    width: 190px;
    height: 190px;
    border: 5px solid #000000;
    overflow: hidden;
    border-radius: 50%;
    display: grid;
    place-items: center;
    position: relative;
  }
  [c]{
    width: 50px;
    height: 50px;
    background: #000000;
    box-shadow: 0 0 0 10px #E96A23, 0 0 0 25px #000000;
  }
  [l]{
    border: 15px solid #000000;
    width: 70px;
    height: 70px;
    translate: -73.8px -42.5px;
  }
  [b]{
    translate: 0 84.8px;
  }
  [r]{
    translate: 73.8px -42.5px;
  }
</style>
```

