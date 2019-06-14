# CSS 基礎 #

### 基本構文 ###

        body {
            display: grid;
            margin: 0;
            min-height: 100vh;
            grid-template-rows: 100px 1fr 100px;
            grid-template-columns: 200px 1fr;
        }
        p {
            color : "red";
            font-weight : "bold";
        }

### セレクタ ###
#### タグ ####
```
p {
    color : "red";
    font-weight : "bold";
}
```
```html:sample.html
<p>Pタグに適用される</p>
```
### id ###
```
#mytext {
    color : "skyblue";
    font-style : "italic";
}
```
```
<span id="mytext">idが"mytext"のタグに適用される</span>
```
### class ###
```
.anytext {
    color : "skyblue";
    font-style : "italic";
}
```
```
<span class="anytext">classが"anytext"のタグに適用される</span>
```
