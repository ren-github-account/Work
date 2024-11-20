**HTML**
```
<!DOCTYPE html>
<html>

<head>
 <link rel="stylesheet" href="sample.css">
 <title>シンプルな雑談掲示板</title>
</head>

<body>
<h2>シンプルな雑談掲示板</h2>
<div class="text">
1.<span class ="name">名無し</span><br>
なんやこれ<br><br>
<div class="reply"><a href ="#comment-2">※2</a></div> <a href="#comment-4">※4</a>
</div>

<div class="text">
 <div id="comment-2">2.<span class ="name">名無し</span></div><br>
>>1<br>
草<br><br>
</div>

<div class="text">
3.<span class ="name">名無し</span><br>
>>1<br>
草ァ!<br><br>
</div>

<div class="text">
<div id="comment-4">4.<span class ="name">名無し</span></div><br>
>>1<br>
草<br><br>
</div>

</body>

</html>
```

**CSS**
```
body {
 background:#ffffe0;
}
.text {
 border:solid 1px #d3d3d3;
 display:block;
 padding:20px;
 background:#ffffff;
}

.name {
 color:#006400;
}

.reply:hover {
}
```
