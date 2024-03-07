# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/854ce3bb-dd83-4857-a2ce-15c514407596)

```
<div><p c><p y><p y><p y><p y><p y><p y s><p y s><p y s><p y><p y><p y><p y><p y><p y><p y><p y><p y></div>
<style>
  body,div{
    display: grid;
    place-items: center;
    background: #C74E4E;
  }
  div {
    width: 220px;
    height: 120px;
    grid-template: repeat(5, 20px) / repeat(9, 20px);
    gap: 5px;
  }
  [s]{
    grid-column: span 9;
    justify-self: end;
  }
  p{
    width: 20px;
    height: 20px;
  }
  [y]{
    background: #E0E246;
    border-radius: 5px;
  }
  [c]{
    background: #FFFFFF;
    border-radius: 50%;
    grid-column: span 4;
    justify-self: start;
  }
</style>
```
