# php生成条形码或者二维码

### Install

```
composer require tinymeng/QRcode dev-master -vvv
```

> 类库使用的命名空间为`\\tinymeng\\QRcode`

```
//一维码
common\lib\phpcode\QRcode::getBarCode($number);
```

```
//二维码
common\lib\phpcode\QRcode::getQrCode($number);
```
