Class FileUploaderCore
=====================





* Class name: FileUploaderCore
* Source: [classes/FileUploader.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/FileUploader.php#L28)


Contents
--------


### Properties

* [$allowedExtensions](#property-$allowedExtensions)
* [$file](#property-$file)
* [$sizeLimit](#property-$sizeLimit)

### Methods

* [__construct](#method-__construct)
* [handleUpload](#method-handleUpload)
* [toBytes](#method-toBytes)




Properties
----------


### <a name="property-$allowedExtensions"></a>$allowedExtensions

```php
protected mixed $allowedExtensions = array()
```





* Visibility: **protected**
* Source: [classes/FileUploader.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/FileUploader.php#L30).


### <a name="property-$file"></a>$file

```php
protected mixed $file
```





* Visibility: **protected**
* Source: [classes/FileUploader.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/FileUploader.php#L31).


### <a name="property-$sizeLimit"></a>$sizeLimit

```php
protected mixed $sizeLimit
```





* Visibility: **protected**
* Source: [classes/FileUploader.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/FileUploader.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed FileUploaderCore::__construct(array $allowedExtensions, $sizeLimit)
```





* Visibility: **public**
* Source: [classes/FileUploader.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/FileUploader.php#L34)


#### Arguments
* $allowedExtensions **array**
* $sizeLimit **mixed**



### <a name="method-handleUpload"></a>handleUpload

```php
mixed FileUploaderCore::handleUpload()
```

Returns array('success'=>true) or array('error'=>'error message')



* Visibility: **public**
* Source: [classes/FileUploader.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/FileUploader.php#L65)




### <a name="method-toBytes"></a>toBytes

```php
mixed FileUploaderCore::toBytes($str)
```





* Visibility: **protected**
* Source: [classes/FileUploader.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/FileUploader.php#L49)


#### Arguments
* $str **mixed**


