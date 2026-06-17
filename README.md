<div align="left">

# 🚀 SHD1
### *Modern, CSS UI Framework*

[![npm version](https://img.shields.io/npm/v/@ghanmidev2012/shd1?color=blue&style=flat-square)](https://www.npmjs.com/package/@ghanmidev2012/shd1)
[![license](https://img.shields.io/npm/l/@ghanmidev2012/shd1?color=green&style=flat-square)](https://x.org)

**SHD1** is make card better with smooth animation.

```bash
npm i @ghanmidev2012/shd1
```
# How use 
 * this code for how we use this package:

 ```html
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@ghanmidev2012/shd1/sd1.css">
    <title>test</title>
    <link rel="stylesheet" href="sd1.css">
</head>
<body>
    <div class="sd1-box">
        <h2>welcome to sd1</h2>
    </div>
</body>
</html>
```

* and css code:
```css
.sd1-box {
  background-color: #059669; /* تم استبدال المتغير باللون الحقيقي */
  color: #ffffff;
  padding: 30px;
  text-align: center;
  border-radius: 12px;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease; /* الحركة الناعمة */
}

/* تأثير التمرير تم فصله في كود مستقل يفهمه المتصفح */
.sd1-box:hover {
  background-color: #047857;
  transform: translateY(-5px); /* يرتفع للأعلى */
  box-shadow: 0 10px 25px rgba(5, 150, 105, 0.3); /* توهج أخضر */
}
```
