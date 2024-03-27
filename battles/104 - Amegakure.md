# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/0a730e81-8f52-4de9-b9c6-5ab09ec9c06a)

```
<p b><p p><p d><p d l><p v><p v><p v><p v>
<style>
  body{
    background: #000;
    display: grid;
    place-items: center;
  }
  p{position: absolute; background: #000}
  [p]{
    width: 200;
    height: 80;
    background: linear-gradient(105deg, #9897AE 82px, #C0C3DB 82px 132px, #9897AE 132px);
    border-radius: 10px;
  }
  [b]{
    width: 240;
    height: 120;
    background: #37385A;
    border-radius: 20px;
  }
  [v]{
    width: 10;
    height: 50;
    border-radius: 5px;
    translate: -30px 0;
    box-shadow: 20px 0, 40px 0, 60px 0;
  }
  [d]{
    width: 10px;
    height: 10px;
    border-radius: 50%;
    translate: -80px 0;
    box-shadow: 0 -20px, 0 20px;
  }
  [d][l]{
    translate: 80px 0;
  }
</style>
```
