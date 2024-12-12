<h1 align="center">php生成条形码或者二维码</h1>
<p align="center">
<a href="https://scrutinizer-ci.com/g/majiameng/QrCode-php/?branch=master"><img src="https://scrutinizer-ci.com/g/majiameng/QrCode-php/badges/quality-score.png?b=master" alt="Scrutinizer Code Quality"></a>
<a href="https://scrutinizer-ci.com/g/majiameng/QrCode-php/build-status/master"><img src="https://scrutinizer-ci.com/g/majiameng/QrCode-php/badges/build.png?b=master" alt="Build Status"></a>
<a href="https://packagist.org/packages/tinymeng/code"><img src="https://poser.pugx.org/tinymeng/code/v/stable" alt="Latest Stable Version"></a>
<a href="https://github.com/majiameng/QrCode-php/tags"><img src="https://poser.pugx.org/tinymeng/code/downloads" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/tinymeng/code"><img src="https://poser.pugx.org/tinymeng/code/v/unstable" alt="Latest Unstable Version"></a>
<a href="https://github.com/majiameng/QrCode-php/blob/master/LICENSE"><img src="https://poser.pugx.org/tinymeng/code/license" alt="License"></a>
</p>



### Install

```
composer require tinymeng/code v1.0 -vvv
```

> 类库使用的命名空间为`\\tinymeng\\code`

### 一维码(条形码)
```
use tinymeng\code\Generate;
$generate = Generate::bar();

/** 直接输出图片 */
$generate->create("123456789");

/** 直接输出图片下面显示数字 */
//$generate->create("123456789",true);

/** 条形码存入本地并输出存储路径 */
//$file_path = $generate->create("123456789",true);
//var_dump($file_path);
```


```php
```

### 二维码生成
```
use tinymeng\code\Generate;
$generate = Generate::qr();

/** 直接输出图片 */
$generate->create("123456789");


/** 二维码存入本地并输出存储路径 */
//$file_path = $generate->create("123456789",true);
//var_dump($file_path);

```
