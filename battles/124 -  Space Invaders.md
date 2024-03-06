# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/65c4ca3a-d967-424c-88f6-26462bd11ff1)

```
<p a b t><p a m b s><div a l><div c p><p s h><p s><p s></div><div c p><p s h><p s><p s></div><div c p><p s h><p s><p s></div><div c p><p s h><p s><p s></div><div c y><p s h><p s><p s></div><div></div><div c y><p s h><p s><p s></div><div c y><p s h><p s><p s></div></div>
<style>
  *{margin: 0}
  [a]{position: absolute}
  body{
    background: #071945;
    display: grid;
    place-items: center;
  }
  [c]{
    display: grid;
    grid-template: 10px 10px / 10px 50px 10px;
  }
  [l]{
   display: grid;
   grid-template-columns: repeat(4, 70px);
   grid-template-rows: 20px 20px;
    grid-gap: 30px 20px;
    translate: 0 -75px;
  }
  [p]>*{--color: #B069F7}
  [b]{--color: #2CE1EA}
  [y]>*{--color: #F8DA37}
  [s]{
    width: 10px;
    height: 10px;
    background: var(--color);
  }
  [s]+[s]+[s]{
    grid-column: span 2;
    justify-self: end;
  }
  [h]{
    width: 50px;
    grid-column: span 3;
    justify-self: center;
  }
  [m]{
    translate: 0 130px;
    box-shadow: 0 -5px #2CE1EA, 0 -35px #2CE1EA, 0 -65px #2CE1EA;
  }
  [t]{
    position: absolute;
    width: 42px;
    height: 21px;
    bottom: 0;
    clip-path:polygon(0 100%, 50% 0, 100% 100%);
    background: var(--color)
  }
</style>
```
