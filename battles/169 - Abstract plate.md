# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/5a8e4576-24cf-45b4-a87b-bbdc0335953e)


```
<div class="container">
  <p></p>
  <p r></p>
</div>


<style>
  * {
    background: radial-gradient(circle, #4FA07B 55px, 0, #0D1335 65px, 0, #4FA07B 85px, 0, #0D1335 95px, 0, #4FA07B 115px, 0, #0D1335 125px, 0, #4FA07B);
  }
  body {
    display: grid;
    place-items: center;
  }
  
  .container {
    width: 310px;
    height: 236px;
    background: #FBFAE2;
    clip-path: polygon(0 0, 0 100%, 50% 139px, 100% 100%, 100% 0, 50% 97px);
  }
  
  p {
    position: absolute;
    inset: 0;
    clip-path: polygon(55px 34px, 55px 234px, 190px 150px, 166px 134px, 190px 118px);
  }
  
  [r] {
    rotate: 180deg;
  }
</style>
```
