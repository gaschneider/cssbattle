# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/fa950c33-ac9e-470c-8c46-b206767d2eb3)

<details>
<summary>
  99% match using repeating linear gradient
</summary>
  
```
<p>
<style>
  body{
    background: #40234B;
    display: grid;
    place-items: center;
  }
  p {
    width: 230px;
    height: 200px;
    background: repeating-linear-gradient(120deg, #A94EA4, #A94EA4 15px, #40234B 15px, #40234B 26px);
    clip-path: polygon(0 0, 100% 0, 50% 100%);
  }
</style>
```
</details>
  
<details>
<summary>
  100% using linear gradient without repeating
</summary>
  
```
<p>
<style>
  body{
    background: #40234B;
    display: grid;
    place-items: center;
  }
  p {
    width: 230px;
    height: 200px;
    background: linear-gradient(120deg, 
                                #A94EA4 14px, 
                                #40234B 15px 24.5px, 
                                #A94EA4 25px 40px, 
                                #40234B 41px 50.5px, 
                                #A94EA4 51px 66px, 
                                #40234B 67px 76.5px, 
                                #A94EA4 77px 92px, 
                                #40234B 93px 102px, 
                                #A94EA4 103px 118px, 
                                #40234B 119px 128px, 
                                #A94EA4 129px 144px, 
                                #40234B 145px 154.5px, 
                                #A94EA4 155px 170.5px, 
                                #40234B 171px 180.5px, 
                                #A94EA4 181px 201px
                               );
    clip-path: polygon(0 0, 100% 0, 50% 100%);
  }
</style>
```
</details>
