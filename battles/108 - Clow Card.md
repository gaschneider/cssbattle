# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/559f95f7-977a-4272-a5ba-9421759de8e7)

```
<div><p b><p b l><p b><p o><p o><p c></div>
<style>
  body{
    background: #000000;
    margin: 75px 50px;
  }
  div{
    background: linear-gradient(105deg, #E96A23 36.65%, #EBAE11 36.65% 52%, #E96A23 52% 56%, #EBAE11 56% 63.7%, #E96A23 63%);
    display: grid;
    place-items: center;
    place-content: center;
    width: 100%;
    height: 100%;
    grid-template-rows: 15px 90px 15px;
  }
  [b]{
    width: 240px;
    height: 100%;
    border-radius: 13px 13px 0 0;
    background: #000000;
  }
  [l]{
    width: 270px;
    border-radius: 13px;
  }
  [l]+[b]{
    border-radius: 0 0 13px 13px ;
  }
  [o]{
    position: absolute;
    width: 200px;
    height: 80px;
    border: 5px solid #EBAE11;
    border-radius: 50%;
  }
  [o]+[o]{
    width: 120px;
    height: 60px;
  }
  [c]{
    position: absolute;
    width: 50px;
    height: 50px;
    background: #EBAE11;
    border-radius: 50%;
  }
</style>
```
