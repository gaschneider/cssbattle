# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/4e4b1e1c-80d4-4b7f-835e-76b8d6d77cc0)

```
<p w><p w><p b><p e>
<style>
  body{
    display:grid;
    place-items:center;
    place-content:center;
    grid-template: 75px 75px / 75px 75px;
    background:#998235;
  }
  p{width:100%;height:100%}
  [w]{
    background:#FFF;
    border-radius: 50% 50% 0 50%;
  }
  [w]+[w]{transform:scaleX(-1)}
  [b]{
    background:linear-gradient(90deg, #191919 25px,#EFF33C 25px 35px,#191919 35px 60px,#EFF33C 60px 70px,#191919 70px 95px,#EFF33C 95px 0);
    border-radius:50px;
    grid-column: span 2;
  }
  [e]{
    width:15;
    height:15;
    border-radius:50%;
    background:#191919;
    position:absolute;
    translate: 47px 27px;
  }
</style>
```
