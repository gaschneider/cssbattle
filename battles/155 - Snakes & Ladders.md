# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/568836ca-7956-49fe-864b-f12dc371eacd)


```
<p c><p c><div><p s><p s><p s></div>
<style>
  body{
    display: grid;
    place-content: center;
    background: #6592CF;
    grid-template-columns: 30px 30px;
    gap: 100px;
  }
  p {
    background: #060F55;
  }
  [c] {
    height: 240px;
    width: 30px;
    transform: translateY(30px);
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
  }
  div {
    position: absolute;
    display: grid;
    grid-template-rows: 30px 30px 30px;
    translate: 142px 96px;
    gap: 30px;
  }
  [s] {
    width: 100px;
    height: 30px;
  }
</style>
```
