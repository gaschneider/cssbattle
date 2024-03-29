# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/0f585035-7714-4541-a287-8f821fcc7599)

```
<p h><p t l><p t><p t r><p t b><p t b><p t b><p t b><p n><p n>
<style>
  *{margin: 0}
  body{
    background: #000000;
    display: grid;
    place-items: center;
  }
  p{position: absolute}
  [h]{
    width: 150px;
    height: 100px;
    background: #FFFFFF;
    translate: 0 10px;
    border-radius: 50px;
  }
  [t]{
    width: 15px;
    height: 20px;
    background: #FFFFFF;
    translate: 0 80px;
  }
  [l]{
    translate: -20px 80px;
  }
  [r]{
    translate: 20px 80px;
  }
  [b]{
    translate: -75px -35px;
    rotate: 45deg;
  }
  [b]:after,[b]:before{
    position: absolute;
    content: '';
    width: 25px;
    height: 25px;
    background: #FFF;
    border-radius: 50%;
  }
  [b]:before{
    left: -23;
    bottom: -10;
  }
  [b]:after{
    left: -23;
    top: -10;
  }
  [b]+[b]{
    translate: -75px 55px;
    rotate: -45deg;
  }
  [b]+[b]+[b]{
    translate: 75px -35px;
    rotate: 135deg;
  }
  [b]+[b]+[b]+[b]{
    translate: 75px 55px;
    rotate: -135deg;
  }
  [n]{
    width: 40px;
    height: 50px;
    background: #000;
    border-radius: 50%;
    rotate: 55deg;
    translate: -30px 10px;
  }
  [n]+[n]{
    rotate: -55deg;
    translate: 30px 10px;
  }
</style>
```
