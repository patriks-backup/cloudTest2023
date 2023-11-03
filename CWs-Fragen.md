Christian Wiedemann11:22 AM
wie mache ich einen text farbig
kann ich relative bildpfade verwenden
kann ich inline images verwenden
gabs da nicht auch eine andere möglichkeit für headlines?
kann ich das link target definieren
Christian Wiedemann11:23 AM
wenn ich ih einem kursiven text ein wort fett machen will, geht das auch.
welche zeichen sind für aufzählungen erlaubt
welche zeichen sind für horizontale linien erlabt.


Text farbig in markdown?
Nein, markdown an sich unterstützt keine farben. Einige Interpreter können das aber darstellen.

in github beispielsweise über code snippets:

```diff
-This is red
```


<p style="color : blue">text</p>

```html
<p> Text </p>
```



 <h1 style="color:purple;">Hello World</h1>

$${\color{green}Green}$$

  <p align="center">
    Show ❤️ by starring this fork! 
    <br />
    Thank you for reading
  </p>

  <div style="color: skyblue">this</div>
