# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/060e5994-625d-4340-8f80-e595a3af0c0b)

```
<p b><p c><p s r><p z r><p d><p s><p z>
<style>
  body{
    background: #14313E;
    display: grid;
    place-items: center;
  }
  p{position: absolute}
  [b] {
    width: 274px;
    height: 150px;
    border-radius: 20px;
    background: #FFDF00;
  }
  [b]:before,[b]:after{
    content: '';
    position: absolute;
    width: 10px;
    height: 40px;
    background: #FFDF00;
    left: -10;
    top: calc(50% - 20px);
    border-radius: 5px 0 0 5px;
  }
  [b]:after{
    right: -10;
    left: unset;
    border-radius: 0 5px 5px 0;
  }
  [c]{
    width: 194px;
    height: 150px;
    background: #14313E;
  }
  [c]:before,[c]:after{
    content: '';
    position: absolute;
    width: 15px;
    height: 100px;
    background: #14313E;
    left: -15;
    top: calc(50% - 50px);
    border-radius: 10px 0 0 10px;
  }
  [c]:after{
    right: -15;
    left: unset;
    border-radius: 0 10px 10px 0;
  }
  [s]{
    background: #FFDF00;
    width: 80px;
    height: 200px;
    clip-path: polygon(50% 0, 55px 15px, 55px 150px, 100% 150px, 100% 170px, 50px 170px, 50px 100%, 30px 100%, 30px 170px, 0 170px, 0 150px, 25px 150px, 25px 15px);
    rotate: -45deg;
    translate: -3px -8px;
  }
  [z]{
    width: 15px;
    height: 20px;
    background: #FFDF00;
    translate: 69px 64px;
    rotate: 45deg;
    border-radius: 15px;
  }
  [s][r]{
    rotate: 45deg;
    translate: 2px -8px;
  }
  [z][r]{
    rotate: -45deg;
    translate: -70px 64px
  }
  [d]{
    width: 50px;
    height: 50px;
    background: #14313E;
    rotate: -45deg;
    translate: 5px;
  }
</style>
```
