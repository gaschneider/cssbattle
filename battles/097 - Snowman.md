# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/4a1b0510-d6a3-4773-b5ec-46547c9b8e63)

```
<p h><p b><p n><p n><p e><p t>
<style>
  *{margin: 0}
  body{
    display: grid;
    place-items: center;
    place-content: center;
    background: #AC474B;
    grid-template-rows: 30px 110px;
    margin-top: 60;
  }  
  [h]{
    width: 60;
    height: 60;
    background: #FFF;
    border-radius: 50%;
  }
  [n]{
    width: 80;
    height: 18;
    position: absolute;
    background: #AC474B;
    translate: 0 -32px;
  }
  [n]+[n]{
    border-radius: 5px;
    background: #FFA63F;
    height: 10;
    width: 60;
  }
  [e]{
    position: absolute;
    width: 10;
    height: 10;
    border-radius: 50%;
    background: #0E1F2B;
    translate: -10px -62px;
    box-shadow: 20px 0 #0E1F2B;
  }
  [t]{
    position: absolute;
    width: 40;
    height: 15;
    background: #0E1F2B;
    translate: 0 -93px;
    box-shadow: 0 -25px #0E1F2B, 0 -15px #FFFFFF;
  }
  [t]:after{
    position: absolute;
    content: '';
    width: 60;
    height: 5;
    background: #0E1F2B;
    bottom: -5px;
    left: -10px;
  }
  [b]{
    width: 100;
    height: 100;
    background: #FFF;
    border-radius: 50%;
  }
</style>
```
