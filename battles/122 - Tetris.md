# TARGET

![image](https://github.com/gaschneider/cssbattle/assets/16023844/515e8bc5-3f03-4367-b08c-b38b20d69954)

```
<p q e r><p w e r><p t r><p y><p y><p r u c><p b><p y><p y><p r><p p c u><p r><p r><p r><p a><p p><p p><p y><p a><p a><p a><p p><p a>
<style>
  body{
    margin: 0 50px;
    display: grid;
    grid-template: repeat(6, 45px) / repeat(6, 45px);
    gap: 6px;
    background: #173889;
  }
  p {
    width: 45px;
    height: 45px;
    margin: 0;
  }
  [r]{background: #EE4F63}
  [a]{background: #2CE1EA}
  [y]{background: #F8DA37}
  [p]{background: #B069F7}
  [b]{background: #173889}
  [e]{justify-self: end}
  [c]{justify-self: center}
  [q]{grid-column: span 5}
  [w]{grid-column: span 4}
  [u]{grid-column: span 3}
  [t]{grid-column: span 2}
</style>
```
