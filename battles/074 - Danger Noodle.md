# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/2ca287a0-2f67-405d-b121-f702775fe9d9)

```
<p h a><p h b><p h c><p h d><p h e><p h f><p l><p l a><p l b><p l c><p l d><p l e><p w>
<style>
  body{
    background:#191919;
    display:grid;
    place-items:center;
  }
  p{position:absolute; background:#191919}
  [h]{
    width:30;
    height:30;
    border-radius:50%;
    box-shadow:0 0 0 5px#E08027,0 0 0 15px#191919,0 0 0 20px#E08027;
    clip-path:polygon(-20px -50px, 90px -50px, 90px 50%,-20px 50%);
  }
  [h][a],[h][c],[h][e]{rotate:180deg}
  [b],[d]{top:44}
  [c],[e]{bottom:44}
  [a]{
    left:-15;
    top:94;
  }
  [b]{left:35}
  [c]{left:85}
  [d]{left:135}
  [e]{left:185}
  [f]{
    clip-path:polygon(-20px -50px, 50% -50px, 50% 50%,-20px 50%);
    translate: 50px 25px;
  }
  [l]{
    width:20;
    height:55;
    background:linear-gradient(90deg, #E08027 5px, #191919 5px 15px,#E08027 15px 20px);
    left:15;
    top:55;
  }
  [l][a]{
    height: 155;
    left: 65;
  }
  [l][b]{
    height: 155;
    left: 115;
  }
  [l][c]{
    height: 155;
    left: 165;
  }
  [l][d]{
    left: 215;
    top: 155;
  }
  [l][e]{
    rotate:90deg;
    width:19.5;
    left: 266;
    top:106;
  }
  [w]{
    width:50;
    height:30;
    background:#E08027;
    translate: 90px;
    border-radius:10px 15px 15px 10px;
  }
  [w]:after{
    content:'';
    position:absolute;
    width:10;
    height:10;
    background:#191919;
    border-radius: 50%;
    right:10;
    top:2;
    box-shadow: 0 16px#191919;
  }
</style>
```
