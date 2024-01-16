# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/cc143d46-81c7-4e01-a0ec-91aefc08d395)

```
<div></div>
<p class="bar left">
<p class="circle left">
<p class="circle orange left">
<p class="bar center">
<p class="circle big">
<p class="circle orange right">
<p class="circle right">
<p class="bar right">

<style>
  body {
    background: #D86F45;
  }

  p {
    position: absolute;
    background: #FDFBF8;
  }

  .circle {
    width: 30px;
    aspect-ratio: 1;
    border-radius: 50%;
  }

  .orange {
    background: #D86F45;
  }

  .left {
    transform: translate(92px, 131px);
  }

  .right {
    transform: translate(262px, 131px);
  }

  .orange.left {
    transform: translate(122px, 131px);
  }

  .orange.right {
    transform: translate(232px, 131px);
  }

  .big {
    width: 80px;
    transform: translate(152px, 106px);
  }

  .bar {
    height: 200px;
    width: 30px;
    border-radius: 50px;
  }

  .bar.left {
    transform: translate(92px, -99px);
  }

  .bar.right {
    transform: translate(262px, -99px);
  }

  .bar.center {
    width: 80px;
    transform: translate(152px, -124px);
  }

  div {
    position: absolute;
    width: 200px;
    height: 100px;
    background: #FDFBF8;
    transform: translate(92px, 162px);
    border-bottom-left-radius: 100px;
    border-bottom-right-radius: 100px;
  }
</style>
```
