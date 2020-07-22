#### 本文件为PAYJS官方PHP版本SDK，单文件引用

使用方法：
```php
<?php
include("payjs.class.php");

$mchid = '123456';
$key = 'xxxxxx';

$data = [
    "mchid" => $mchid,
    "total_fee" => 1,
    "out_trade_no" => '123123123',
];

$payjs = new Payjs();
$result = $payjs->native($data);

print_r($result);

```
