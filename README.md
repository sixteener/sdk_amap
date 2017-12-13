> 高德web服务api封装修改

## 安装

```shell
composer require sixteener/sdk_amap
```

## 使用

```php
<?php
use \Amap\Amap;

$options = [
    'sign'=>false, //是否进行数字签名，默认不签名
    'private_key'=>'', //数字签名私钥，sign=true时必填
    'key'=>''//api调用key，必填
];

$map = new Amap($options);
```

文档查看Amap.php

## 相关文档
* 在lvzhao1995/amap-sdk的包的基础上修改
* 高德web服务API: http://lbs.amap.com/api/webservice/summary/
* 高德云图服务API: http://lbs.amap.com/api/yuntu/summary

> 建议先查看高德相关文档

## License

MIT

