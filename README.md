# Tablearray
Data of all recognized pinball tables


<table>
  <tr><th>name</th><th>display</th><th>manufactor</th><th>needed</th><th>forbidden</th><th>highscore</th></tr>
  <tr><td>1-2-3</td><td>1-2-3...</td><td>Talleres de Llobregat 1973</td><td>"1-2-3,1973"</td><td></td><td>TlD_123.txt</td></tr>
  <tr><td>2 in 1</td><td>2 in 1</td><td>Bally 1964</td><td>"2,in,Bally,1964"</td><td></td><td></td></tr>
  <tr><td>3-in-line</td><td>3 in Line</td><td>Bally 1963</td><td></td><td></td><td></td></tr>
  <tr><td>2001</td><td>2001</td><td>Gottlieb 1971</td><td>"2001,Gottlieb,1971"</td><td></td><td>2001_71VPX.txt</td></tr>
  <tr><td>...</td><td>...</td><td>...</td><td></td><td></td><td></td></tr>
</table>


> [!NOTE]
> If "needed" is empty all strings of "name" are needed in filename to match this entry.

> [!NOTE]
> "forbidden" overrules "needed".

> [!TIP]
> Highscore is only used for pinball-tables saving highscores in POST-IT files.



CSV Data:
```
name,display,manufactor,needed,forbidden,highscore
1-2-3,1-2-3...,Talleres de Llobregat 1973,"1-2-3,1973",,TlD_123.txt
2 in 1,2 in 1,Bally 1964,"2,in,Bally,1964",,
3-in-line,3 in Line,Bally 1963,,,
2001,2001,Gottlieb 1971,"2001,Gottlieb,1971",,2001_71VPX.txt
...

```

> [!CAUTION]
> If you have "," in your values(strings) you must escape string with doublequotes: "1-2-3,1973".
