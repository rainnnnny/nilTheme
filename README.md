# nilTheme
Color Scheme of Sublime Text .

#### usage:<br>
(My ST version is build 3143)<br>
1.Create a folder named "Nil" under the "Cache" folder of Sublime Text. (usually like "C:\Users\xxxx\AppData\Local\Sublime Text 3\Cache" on Windows, where lies lots of plug-in folders) <br>
2.Put the .tmTheme file in the folder <br>

Recommand to use the default adaptive Theme of ST - "Adaptive.sublime-theme".

<br>

#### example:<br>
![](https://github.com/rainnnnny/nilTheme/blob/master/example.png)
<br>

#### about:<br>
Self maded theme, with the help of http://tmtheme-editor.herokuapp.com/#!/editor/theme. This website is convenient to create your own theme, just sometimes the preview effect is not actually the same as the real effect on ST.

In fact it's a xml file, so after you get familiar with the common args, you can directly modify the file to change the effect.

Something about the effect in Python: (didn't test in other language)<br>
Using the website editor I couldn't find where to modify the color of formal parameters and explicit arguments, after referring to the Monokai's code, I found this may help:<br>
```
<key>name</key>
<string>Function argument</string>
```
you can only find ```<string>Functions</string>```key in the website generated file, which by default will make the function call and the arguments same color.
