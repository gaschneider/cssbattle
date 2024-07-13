# TARGET

![image](https://github.com/user-attachments/assets/2743cc06-56a8-4c1a-a99b-4b20aee91ebb)

```
<a v><a h s><a h m><a h b><a l><a r>
<style>
  body{
    margin:0;
    display:grid;
    place-items:center;
    background:#F48B26;
  }
  a{position:absolute}
  [v]{background:#FEFF58;width:20;height:100%}
  [h]{background:#FEFF58;height:20;border-radius:10px;}
  [s]{width:160;top:30}
  [m]{width:240;top:80}
  [b]{width:320;top:130}
  [l],[r]{
    width:140;
    height:100;
    border:20px solid#FEFF58;
    bottom:-20;
  }
  [l]{
    border-radius:0 60px 0 0;
    left:-20
  }
  [r]{
    border-radius:60px 0 0 0;
    right:-20
  }
  [l]:after,[r]:after{
    content:'';
    width:110;
    height:70;
    background:#FEFF58;
    position:absolute;
    top:30;
    border-radius:0 10px 0 0;
  }
  [r]:after{
    right:0;
    transform:scaleX(-1);
  }
</style>
```
