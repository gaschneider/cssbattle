# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/9a747257-40e3-4718-8735-bbba23251825)

<details>
  <summary>Using triangles</summary>

  ```
<p><p l><p r><p t>
<style>
  body{
    background: #E3516E;
  }
  p {
    position: absolute;
    border: 70px solid transparent;
    border-top: 0;
    border-bottom: 70px solid #FADE8B;
    transform: translate(122px, 148px);
  }
  [t] {
    transform: translate(122px, 34.5px) rotate(180deg);
  }
  [l] {
    transform: translate(65px, 91px) rotate(90deg);
  }
  [r] {
    transform: translate(178px, 91px) rotate(-90deg);
  }
</style>
```
</details>

<details>
  <summary>Using square and cross</summary>

  ```
<p><div><div>
<style>
  body{
    background: #E3516E;
    display: grid;
    place-items: center;
  }
  p {
    width: 184.5px;
    aspect-ratio: 1;
    background: #FADE8B;
  }

  div {
    position: absolute;
    background: #E3516E;
    width: 30px;
    height: 100%;
    rotate: 45deg;
    > div {
      rotate: -90deg;
    }
  }
</style>
```
</details>
