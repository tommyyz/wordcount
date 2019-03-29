### wordcount
word count in: js, golang, python... Idealy support all modern languages

不同开发语言版本的字数统计小工具，理论上支持中文，英文，日文等流行语言

### Quick Start
```
node wordcount.go
# [ 'This', 'is', 'Tom', 'Zhu', '这', '是', '汤', '姆', '猪' ]
# 9
```

```
go run wordcount.go
# [This is Tom Zhu 这 是 汤 姆 猪] 9
```

### Thank To
JS code is taken from [`Tinymce v4`](https://github.com/tinymce/tinymce/tree/4.5.x/js/tinymce/plugins/wordcount/src/main/js/tinymce/wordcount)

Golang code is simply a translation from JS code
