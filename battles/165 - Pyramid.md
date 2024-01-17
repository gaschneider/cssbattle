# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/b4218fda-a043-4de6-9f97-4604fbee554a)

```
<p class="bl">
<p class="tc">
<p class="br">
<div></div>
  <div p>
<style>
  body {
    display: grid; 
    place-items: center;
    grid-template-columns: 100px 100px 100px; 
    grid-template-rows: 100px 100px; 
    gap: 40px 0;
    margin: 0;
    padding: 30px 50px;
    background: #F0CD48;
  }
  p {
    width: 100px;
    height: 100px;
    background: #66284A;
    border-radius: 50%;
  }

  div {
    position: absolute;
    border-left: 100px solid transparent;
    border-right: 100px solid transparent;
    border-bottom: 140px solid #F0CD48;
  }

  [p] {
    margin-top: 10px;
    border-left-width: 70px;
    border-right-width: 70px;
    border-bottom: 100px solid #66284A;
  }
  
  .bl {
    grid-area: 2 / 1;
  }

  .tc {
    grid-area: 1 / 2;
  }

  .br {
    grid-area: 2 / 3;
  }
</style>
```
