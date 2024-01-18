# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/e63e6ae0-ac3b-46fb-8380-91f87189d73d)

```
<p><p p><p y><p o>
<style>
  body{
    display: grid;
    place-items: center;
    background: #66284A;
  }
  p {
    position: absolute;
    border-radius: 50%;
    width: 60px;
    aspect-ratio: 1;
    border: 20px solid #FDFBF8;
    border-top-color: transparent;
    transform: translateY(60px) rotate(45deg);
  }

  [p] {
    border-color: #D669EC;
    border-top-color: transparent;
    transform: translateX(60px) rotate(-45deg);
  }

  [y] {
    border-color: #F0CD48;
    border-top-color: transparent;
    transform: translateY(-60px) rotate(-135deg);
  }

  [o] {
    border-color: #D86F45;
    border-top-color: transparent;
    transform: translateX(-60px) rotate(135deg);
  }
</style>
```
