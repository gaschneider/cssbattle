# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/bbeabafe-a491-460c-943f-1220c0d2c5ed)

```
<p p><p t><p w><p r><p s><p s><p s>
<style>
  body{
    background: #000000;
    display: grid;
    place-items: center;
  }
  p{position: absolute;}
  [p]{
    border: 30px solid #E0E246;
    width: 0px;
    border-radius: 50%;
    translate: -110px;
  }
  [t]{
    width: 35px;
    height: 70px;
    clip-path: polygon(0 50%, 100% 0, 100% 100%);
    background: #000000;
    translate: -95px;
  }
  [w]{
    width: 10px;
    height: 10px;
    border-radius: 50%;
    background: #FFFFFF;
    box-shadow: -30px 0 #FFFFFF, 30px 0 #FFFFFF;
  }
  [r]{
    width: 60px;
    height: 60px;
    border-radius: 50px 50px 0 0;
    background: #C74E4E;
    translate: 110px;
  }
  [s]{
    translate: 90px 25px;
    border: 15px solid transparent;
    border-top: unset;
    border-bottom: 15px solid #000000;
  }
  [s]+[s]{
    translate: 110px 25px;
  }
  [s]+[s]+[s]{
    translate: 130px 25px;
  }
</style>
```
