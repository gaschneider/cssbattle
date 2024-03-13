# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/b4997744-021a-4d6c-885a-1d84c410463b)

```
<p a l><p a r><p c><p v><p w k l><p w k r><p k l><p k r><p v>
<style>
  body{
    display: grid;
    place-items: center;
  }
  p{position: absolute}
  [a]{
    width: 44px;
    height: 180px;
    background: #2E2926;
  }
  [a][l]{
    transform: skewX(-25deg);
    translate: -44px;
  }
  [a][r]{
    transform: skewX(25deg);
    translate: 44px;
  }
  [c]{
    width: 22px;
    height: 22px;
    border-radius: 50%;
    background: #0088CA;
  }
  [v]{
    height: 24px;
    width: 5px;
    background: #0088CA;
    translate: 0 51px;
  }
  [k]{
    width: 20px;
    background: #0088CA;
  }
  [k][l]{
    height: 113px;
    transform: skewY(-45deg);
    rotate: -45deg;
    translate: -40px 13px
  }
  [k][r]{
    height: 170px;
    transform: skewY(45deg);
    rotate: 45deg;
    translate: 60px -6.5px
  }
  [w]{
    width: 36px;
    background: #FFFFFF;
  }
</style>
```
