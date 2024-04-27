# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/0618eb27-e996-44f0-bd02-dc98dc50e329)

```
<p z><p b e><p h><p b><p b c><p b d>
<style>
  body{
    background:#243D83;
    display:grid;
    place-items:center;
  }    
  p{
    position:absolute;
    width:60;
    height:50;
    border-radius:50%;
    background:#6592CF;
  }
  [z]{
    width:140;
    height:140;
    border-radius:50%;
    background:#6592CF;
  }
  [a]{translate: -55px;box-shadow:18px 37px#6592CF,55px 55px#6592CF,92px 37px#6592CF,110px 0#6592CF}
  [b],[e]{box-shadow:0px 120px#6592CF}
  [b]{translate:0 -60px}
  [c],[d]{box-shadow:0px 113px#6592CF}
  [c]{rotate: 45deg;translate: 40px -40px}
  [d]{rotate: -45deg;translate: -40px -40px}
  [e]{rotate:90deg;translate:60px}
  [h]{
    background:#243D83;
    translate:0 -7px;
    height: 65px;
    border-radius:0 0 50% 50%;
  }
  [h]:after{
    content:'';
    position:absolute;
    background:#6592CF;
    width:10;
    height:10;
    border-radius:50%;
    left:15;
    top:19;
    box-shadow:20px 0#6592CF;
  }
</style>
```
