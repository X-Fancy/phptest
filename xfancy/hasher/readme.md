# this is a test for laravel package

### 用法
```
composer require xfancy/hasher
```
或者在你的composer.json 的require部分中添加：
```json
 "xfancy/hasher": "~1.0"
```
下载完毕之后，直接配置 `app/config`的 `providers`:
```php
//Illuminate\Hashing\HashServiceProvider::class,
\Xfancy\Hasher\MD5HasherProvider::class,
```


