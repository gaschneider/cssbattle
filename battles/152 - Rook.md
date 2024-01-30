# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/4b0e8cdd-a4f4-4cb1-8565-073ee202bbc8)

```
<div><div c><p><p p><p><p p><p></div><p f></div><p b l><p j><p m><p j r><p b w><p class="base">
<style>
  body {
    background: #62306D;
    display: grid;
    place-content: center;
    grid-template-rows: 60px 10px 65px 10px 25px;
    gap: 5px;
  }
  div{
    display: flex;
    justify-self: center;
    flex-direction: column;
    position: relative;
  }
  [c] {
    height: 45px;
    flex-direction: row;
    > p {
      width: 10px;
      border-radius: 5px 5px 0px 0px;
    }
    > [p] {
      z-index: 1;
      width: 30px;
      background: #62306D;
      rotate: 180deg;
    }
  }
  p {
    margin: 0;
    height: 100%;
    background: #F7EC7D;
    width: 90px;
  }
  p:not([j]){
    justify-self: center;
  }
  [f]{
    position: absolute;
    height: 18px;
    bottom: 0;
    border-radius: 0px 0px 10px 10px;
  }
  [m] {
    z-index: -2;
    width: 90px;
  }
  [b] {
    border-radius: 5px;
  }
  [j]{
    z-index: -1;
    position: absolute;
    width: 150px;
    height: 150px;
    border-radius: 50%;
    background: #62306D;
    translate: 22px 62px;
  }
  [r]{
    translate: 212px 62px;
  }
  [l] {
    width: 60px;
  }
  [w] {
    width: 110px;
  }
  
  .base {
    width: 140px;
    border-radius: 16px 16px 8px 8px;
  }
</style>
```
