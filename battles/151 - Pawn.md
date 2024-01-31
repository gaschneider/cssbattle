# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/6fa6cad9-eb36-4f5a-8587-2d50297ad6b3)

```
<p c><p b><p j><p m><p j r><p class="base">
<style>
  body {
    background: #F5D6B4;
    display: grid;
    place-content: center;
    grid-template-rows: 50px 20px 65px 40px;
    gap: 5px;
  }
  div{
    display: flex;
    justify-self: center;
    flex-direction: column;
    position: relative;
  }
  [c] {
    width: 50px;
    border-radius: 50%;
  }
  p {
    margin: 0;
    height: 100%;
    background: #D86F45;
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
  }
  [b] {
    width: 80px;
    border-radius: 10px 10px 20px 20px;
  }
  [j]{
    z-index: -1;
    position: absolute;
    width: 150px;
    height: 150px;
    border-radius: 50%;
    background: #F5D6B4;
    translate: 22px 62px;
  }
  [r]{
    translate: 212px 62px;
  }
  
  .base {
    width: 140px;
    border-radius: 20px 20px 10px 10px;
  }
</style>
```
