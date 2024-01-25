# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/0a22cebe-19ee-4ed6-acac-71fcc6318092)

```
<div class="hat">
  <p h>
  <p b>
</div>
<div class="eyes">
  <p>
  <p>
</div>
<div class="moustache">
  <p>
  <p>
</div>
<style>
  body {
    background: #E38F66;
    display: grid;
    place-content: center;
    grid-template-rows: 110px 60px 60px;
  }
  .hat {
    display: grid;
    grid-template-rows: 90px 20px;
    place-items: center;
    margin-top: 5px;
    
    > [h] {
      width: 120px;
      height: 90px;
      background: #FFFBDA;
      border-top-left-radius: 100px;
      border-top-right-radius: 100px;
    }
    > [b] {
      width: 180px;
      height: 20px;
      background: #FFFBDA;
      border-radius: 50px;
    }
  }

  .eyes {
    display: flex;
    width: 180px;
    justify-content: center;
    align-items: center;
    gap: 20px;
    height: 100%;
    padding-top: 7px;

    > p {
      width: 20px;
      aspect-ratio: 1;
      border-radius: 50%;
      background: #FFFBDA;
      border: 10px solid #E38F66;
    }

    > p+p {
      background: #E38F66;
      border: 10px solid #FFFBDA;
    }
  }

  .moustache {
    display: flex;
    width: 180px;
    justify-content: center;
    align-items: center;
    gap: 10px;
    height: 100%;
    padding-top: 5px;
    
    > p {
      width: 40px;
      aspect-ratio: 1;
      border-radius: 50% 50% 50% 0;
      background: #FFFBDA;
      transform: rotate(45deg);
    }
    > p+p {
      transform: rotate(-135deg);
    }
  }
</style>
```
