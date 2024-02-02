# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/056e7770-8744-4d0f-a332-50b10228d010)

```
<p p v><p p h><p o><p o><p o>
<style>
  * {margin: 0}
  body{
    background: #E38F66;
  }
  p{
    position: absolute;
  }
  [p] {
    margin: 0;
    width: 40px;
    height: 120px;
    background: #FFFBDA;
    border-radius: 50px; 
  }
  [v]{
    bottom: 80px;
    box-shadow: 80px 80px #FFFBDA;
  }
  [h]{
    rotate: 90deg;
    bottom: 40px;
    left: 40;
    box-shadow: 80px -80px #FFFBDA;
  }
  [o] {
    width: 80px;
    height: 80px;
    background: #E38F66;
    bottom: 0;
    border-top-right-radius: 10px;
    box-shadow: 20px -20px 0px 0px #FFFBDA;
  }
  [o]+[o] {
    rotate: 180deg;
    left: 120px;
    bottom: 40px;
  }
  [o]+[o]+[o] {
    left: 40px;
    bottom: 120px;
  }
</style>
```
