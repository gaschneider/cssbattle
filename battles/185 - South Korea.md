# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/cf3e1d95-be11-48b3-9f2b-2b7f4e1719c6)

<details>
  <summary>Solution - Using divs for the circle: 99.9% match</summary>
  
```
<div class="circle"></div>
<div class="circle red-left smaller"></div>
<div class="circle blue-right smaller"></div>

<div class="lines tl">
  <div class="line"></div>
  <div class="line"></div>
  <div class="line"></div>
</div>

<div class="lines tr">
  <div class="line spaced"></div>
  <div class="line"></div>
  <div class="line spaced"></div>
</div>

<div class="lines bl">
  <div class="line"></div>
  <div class="line spaced"></div>
  <div class="line"></div>
</div>

<div class="lines br">
  <div class="line spaced"></div>
  <div class="line spaced"></div>
  <div class="line spaced"></div>
</div>

<style>
  body {
    display: grid;
    place-items: center;
  }
  
  .circle {
    position: absolute;
    width: 120px;
    aspect-ratio: 1;
    background: linear-gradient(#CD2E3A 0 50%,  #0047A0 50%);
    border-radius: 50%;
  }

  .red-left {
    background: #CD2E3A;
    top: 40%;
    left: 35%;
  }

  .blue-right {
    background: #0047A0;
    top: 40%;
    left: 50%;
  }

  .smaller {
    width: 60px;
    aspect-ratio: 1;
  }

  
  .lines {
    position: absolute;
    width: 60px;

    .line {
      width: 100%;
      height: 10.4px;
      background: #000000;
      margin-bottom: 5.5px;
    }

    .spaced {
      background: linear-gradient(90deg, #000000 45%, #FFFFFF 0 55%, #000000 0);
    }
  }

  .tl {
    rotate: -60deg;
    top: 72.5px;
    left: 78px;
    width: 60.4px;
  }

  .tr {
    rotate: 60deg;
    top: 73px;
    left: 262;
  }

  .bl {
    rotate: -120deg;
    top: 178.5;
    left: 77.5px;
  }

  .br {
    rotate: 120deg;
    top: 179;
    left: 262;
  }
</style>
```
</details>

<details>
  <summary>Solution - Using body background radial gradient solution: 100% match</summary>

  ```
<div class="lines tl">
  <div class="line"></div>
  <div class="line"></div>
  <div class="line"></div>
</div>

<div class="lines tr">
  <div class="line spaced"></div>
  <div class="line"></div>
  <div class="line spaced"></div>
</div>

<div class="lines bl">
  <div class="line"></div>
  <div class="line spaced"></div>
  <div class="line"></div>
</div>

<div class="lines br">
  <div class="line spaced"></div>
  <div class="line spaced"></div>
  <div class="line spaced"></div>
</div>

<style>
  body {
    background: radial-gradient(1q, #0000, 64q, #fff),
      radial-gradient(1q, #CD2E3A, 30px, #0000)-32q,
      radial-gradient(1q, #0047A0, 32q, #0000)32q,
      linear-gradient(#CD2E3A 50%, #0047A0 0);
    
    display: grid;
    place-items: center;
  }
  
  .lines {
    position: absolute;
    width: 60px;

    .line {
      width: 100%;
      height: 10.4px;
      background: #000000;
      margin-bottom: 5.5px;
    }

    .spaced {
      background: linear-gradient(90deg, #000000 45%, #FFFFFF 0 55%, #000000 0);
    }
  }

  .tl {
    rotate: -60deg;
    top: 72.5px;
    left: 78px;
    width: 60.4px;
  }

  .tr {
    rotate: 60deg;
    top: 73px;
    left: 262;
  }

  .bl {
    rotate: -120deg;
    top: 178.5;
    left: 77.5px;
  }

  .br {
    rotate: 120deg;
    top: 179;
    left: 262;
  }
</style>
```
</details>
