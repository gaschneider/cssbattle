# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/b75cf064-2473-4ce0-9ad8-c2670f09c739)

```
<p s><p c l><p c r><p c t>
<style>
  body{
    background: #4F77FF;
    display: grid;
    place-items: center;
  }
  [s] {
    position: absolute;
    width: 100px;
    height: 80px;
    background: #1038BF;
    transform: translateY(60px);
  }
  [c] {
    position: absolute;
    width: 100px;
    height: 100px;
    background: #1038BF;
    border-radius: 50%;
  }

  [l] {
    transform: translate(-45px, 20px);
    box-shadow: -10px 40px #4F77FF;
  }

  [r] {
    transform: translate(45px, 20px);
    box-shadow: 10px 40px #4F77FF;
  }

  [t] {
    transform: translateY(-50px)
  }
</style>
```
