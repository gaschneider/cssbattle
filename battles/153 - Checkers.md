# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/7f9bee7f-ddce-4057-ba2b-f85c2fb9c418)

```
<div><p r t c><p r t c><p l t c><p c><p r t c><p r t><p r t><p l t c><p c><p r t c><p r t c><p r t c></div>
<style>
  body {
    background: #E3516E;
    display: grid;
    place-items: center;
  }
  div {
    width: 200px;
    height: 200px;
    background: #FADE8B;
    display: grid;
    place-items: center;
    grid-template: repeat(5, 40px) / repeat(5, 40px);
  }

  p {
    width: 40px;
    height: 40px;
    background: #E3516E;
    position: relative;
  }
  [r]{
    margin-left: auto;
  }
  [l] {
    margin-right: auto;
  }
  [c]::before{
    position: absolute;
    top: 10px;
    left: 10px;
    width: 20px;
    height: 20px;
    border-radius: 50%;
    content: '';
    background: #FADE8B;
  }
  [t] {
    grid-column: span 2;
  }
</style>
```
