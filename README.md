# psr15

psr15的实现

## 安装

``` bash
composer require diggphp/psr15
```

## 用例

``` php
$request_handler = new \DiggPHP\Psr15\RequestHandler();
$request_handler->setHandler(function(){
    return 'hello world~';
});
$response = $request_handler->handle('一个实现了 Psr\Http\Message\ServerRequestInterface 的实例');
```
