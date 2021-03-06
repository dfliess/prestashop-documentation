Class StockAvailableCore
=====================

Represents quantities available
It is either synchronized with Stock or manualy set by the seller



* Class name: StockAvailableCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/stock/StockAvailable.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L34)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$depends_on_stock](#property-$depends_on_stock)
* [$id_group_shop](#property-$id_group_shop)
* [$id_product](#property-$id_product)
* [$id_product_attribute](#property-$id_product_attribute)
* [$id_shop](#property-$id_shop)
* [$out_of_stock](#property-$out_of_stock)
* [$quantity](#property-$quantity)
* [$webserviceParameters](#property-$webserviceParameters)
* [$def](#property-$def)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$id](#property-$id)
* [$id_lang](#property-$id_lang)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$table](#property-$table)
* [$tables](#property-$tables)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [addSqlShopParams](#method-addSqlShopParams)
* [addSqlShopRestriction](#method-addSqlShopRestriction)
* [associateTo](#method-associateTo)
* [clearCache](#method-clearCache)
* [copyStockAvailableFromShopToShop](#method-copyStockAvailableFromShopToShop)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [dependsOnStock](#method-dependsOnStock)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getDefinition](#method-getDefinition)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getQuantityAvailableByProduct](#method-getQuantityAvailableByProduct)
* [getStockAvailableIdByProductId](#method-getStockAvailableIdByProductId)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isLangMultishop](#method-isLangMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [outOfStock](#method-outOfStock)
* [postSave](#method-postSave)
* [removeProductFromStockAvailable](#method-removeProductFromStockAvailable)
* [resetProductFromStockAvailableByGroupShop](#method-resetProductFromStockAvailableByGroupShop)
* [save](#method-save)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [setProductDependsOnStock](#method-setProductDependsOnStock)
* [setProductOutOfStock](#method-setProductOutOfStock)
* [setQuantity](#method-setQuantity)
* [synchronize](#method-synchronize)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateQuantity](#method-updateQuantity)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'stock_available', 'primary' => 'id_stock_available', 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_group_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'quantity' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'depends_on_stock' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'out_of_stock' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/stock/StockAvailable.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L60).


### <a name="property-$depends_on_stock"></a>$depends_on_stock

```php
public boolean $depends_on_stock
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L52).


### <a name="property-$id_group_shop"></a>$id_group_shop

```php
public integer $id_group_shop
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L46).


### <a name="property-$id_product"></a>$id_product

```php
public integer $id_product
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L37).


### <a name="property-$id_product_attribute"></a>$id_product_attribute

```php
public integer $id_product_attribute
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L40).


### <a name="property-$id_shop"></a>$id_shop

```php
public integer $id_shop
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L43).


### <a name="property-$out_of_stock"></a>$out_of_stock

```php
public boolean $out_of_stock
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L55).


### <a name="property-$quantity"></a>$quantity

```php
public integer $quantity
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L49).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_product' => array('xlink_resource' => 'products'), 'id_product_attribute' => array('xlink_resource' => 'combinations'), 'id_shop' => array('xlink_resource' => 'shops'), 'id_group_shop' => array('xlink_resource' => 'shop_groups')), 'hidden_fields' => array())
```





* Visibility: **protected**
* Source: [classes/stock/StockAvailable.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L77).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L122).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L72).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L57).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L87).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L77).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L92).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L82).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L97).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L48).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L51).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L67).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L108).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L111).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L62).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L102).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ObjectModelCore::__construct(integer $id, integer $id_lang, integer $id_shop)
```

Build object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L150)


#### Arguments
* $id **integer** - Existing object id in order to load object (optional)
* $id_lang **integer** - Required if object is multilingual (optional)
* $id_shop **integer** - ID shop for objects with multishop on langs



### <a name="method-add"></a>add

```php
mixed StockAvailableCore::add($autodate, $null_values)
```

Upgrades total_quantity_available after having saved



* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 297](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L297)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 925](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L925)


#### Arguments
* $fields **mixed**



### <a name="method-addSqlShopParams"></a>addSqlShopParams

```php
mixed StockAvailableCore::addSqlShopParams(array $params, integer $id_shop)
```

Add sql params for shops fields - specific to StockAvailable



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 608](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L608)


#### Arguments
* $params **array** - Reference to the params array
* $id_shop **integer** - Optional : The shop ID



### <a name="method-addSqlShopRestriction"></a>addSqlShopRestriction

```php
mixed StockAvailableCore::addSqlShopRestriction(\DbQuery $sql, integer $id_shop, string $alias)
```

Add an sql restriction for shops fields - specific to StockAvailable



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 553](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L553)


#### Arguments
* $sql **[DbQuery](class.DbQueryCore.md)**
* $id_shop **integer** - Optional : The shop ID
* $alias **string** - Optional : The current table alias



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops, string $type)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 973](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L973)


#### Arguments
* $id_shops **integer|array**
* $type **string**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 939](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L939)


#### Arguments
* $all **mixed**



### <a name="method-copyStockAvailableFromShopToShop"></a>copyStockAvailableFromShopToShop

```php
boolean StockAvailableCore::copyStockAvailableFromShopToShop(integer $src_shop_id, integer $dst_shop_id)
```

Copies stock available content table



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 642](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L642)


#### Arguments
* $src_shop_id **integer**
* $dst_shop_id **integer**



### <a name="method-delete"></a>delete

```php
boolean ObjectModelCore::delete()
```

Delete current object from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 521](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L521)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage()
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1047](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1047)




### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 559](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L559)


#### Arguments
* $selection **array**



### <a name="method-dependsOnStock"></a>dependsOnStock

```php
boolean StockAvailableCore::dependsOnStock(integer $id_product, integer $id_shop)
```

For a given product, tells if it depends on the physical (usable) stock



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 505](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L505)


#### Arguments
* $id_product **integer**
* $id_shop **integer** - Optional : gets context if null @see Context::getContext()



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 757](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L757)


#### Arguments
* $field **mixed**
* $class **mixed**
* $htmlentities **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1017](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1017)


#### Arguments
* $id **mixed**



### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Specify if an ObjectModel is already in database



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1081](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1081)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L272)


#### Arguments
* $id_lang **integer** - If this parameter is given, only take lang fields



### <a name="method-formatValue"></a>formatValue

```php
mixed ObjectModelCore::formatValue(mixed $value, integer $type, $with_quotes)
```

Format a data



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L319)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string $field)
```

Get object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1184](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1184)


#### Arguments
* $class **string** - Name of object
* $field **string** - Name of field if we want the definition of one field only



### <a name="method-getFieldByLang"></a>getFieldByLang

```php
mixed ObjectModelCore::getFieldByLang($field_name, null $id_lang)
```

Return the field value for the specified language if the field is multilang, else the field value.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1261](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1261)


#### Arguments
* $field_name **mixed**
* $id_lang **null**



### <a name="method-getFields"></a>getFields

```php
array ObjectModelCore::getFields()
```

Prepare fields for ObjectModel class (add, update)
All fields are verified (pSQL, intval.

..)

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L234)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L249)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 917](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L917)


#### Arguments
* $all **mixed**



### <a name="method-getQuantityAvailableByProduct"></a>getQuantityAvailableByProduct

```php
integer StockAvailableCore::getQuantityAvailableByProduct(integer $id_product, integer $id_product_attribute, integer $id_shop)
```

For a given id_product and id_product_attribute, gets its stock available



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L269)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - Optional
* $id_shop **integer** - Optional : gets context by default



### <a name="method-getStockAvailableIdByProductId"></a>getStockAvailableIdByProductId

```php
integer StockAvailableCore::getStockAvailableIdByProductId(integer $id_product, integer $id_product_attribute, integer $id_shop)
```

For a given {id_product, id_product_attribute and id_shop}, gets the stock available id associated



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L96)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - Optional
* $id_shop **integer** - Optional



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 595](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L595)


#### Arguments
* $fields_array **mixed**



### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $class)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L130)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 890](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L890)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-getWebserviceParameters"></a>getWebserviceParameters

```php
mixed ObjectModelCore::getWebserviceParameters($ws_params_attribute_name)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 816](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L816)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1116](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1116)


#### Arguments
* $data **array**
* $id_lang **integer**



### <a name="method-hydrateCollection"></a>hydrateCollection

```php
array ObjectModelCore::hydrateCollection(string $class, array $datas, integer $id_lang)
```

Fill (hydrate) a list of objects in order to get a collection of these objects



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1135](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1135)


#### Arguments
* $class **string** - Class of objects to hydrate
* $datas **array** - List of data (multi-dimensional array)
* $id_lang **integer**



### <a name="method-isAssociatedToGroupShop"></a>isAssociatedToGroupShop

```php
boolean ObjectModelCore::isAssociatedToGroupShop(integer $id_group_shop)
```

Check if current object is associated to a group shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1003](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1003)


#### Arguments
* $id_group_shop **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 954](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L954)


#### Arguments
* $id_shop **integer**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean ObjectModelCore::isCurrentlyUsed(string $table, boolean $has_active_column)
```

This method is allow to know if a entity is currently used



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1099](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1099)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1037](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1037)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 611](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L611)


#### Arguments
* $fields **mixed**
* $fields_array **mixed**
* $id_language **mixed**



### <a name="method-outOfStock"></a>outOfStock

```php
boolean StockAvailableCore::outOfStock(integer $id_product, integer $id_shop)
```

For a given product, get its "out of stock" flag



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 528](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L528)


#### Arguments
* $id_product **integer**
* $id_shop **integer** - Optional : gets context if null @see Context::getContext()



### <a name="method-postSave"></a>postSave

```php
mixed StockAvailableCore::postSave()
```

Upgrades total_quantity_available after having saved



* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 320](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L320)




### <a name="method-removeProductFromStockAvailable"></a>removeProductFromStockAvailable

```php
mixed StockAvailableCore::removeProductFromStockAvailable(integer $id_product, integer $id_product_attribute, integer $id_shop)
```

Removes a given product from the stock available



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 456](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L456)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - Optional
* $id_shop **integer** - Optional



### <a name="method-resetProductFromStockAvailableByGroupShop"></a>resetProductFromStockAvailableByGroupShop

```php
mixed StockAvailableCore::resetProductFromStockAvailableByGroupShop(\GroupShop $group_shop)
```

Removes all product quantities from all a group of shops
If stocks are shared, remoe all old available quantities for all shops of the group
Else remove all available quantities for the current group



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 473](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L473)


#### Arguments
* $group_shop **[GroupShop](class.GroupShopCore.md)** - the GroupShop object



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L360)


#### Arguments
* $null_values **boolean**
* $autodate **boolean**



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static
Remove this in 1.6 !



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1207](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1207)




### <a name="method-setProductDependsOnStock"></a>setProductDependsOnStock

```php
mixed StockAvailableCore::setProductDependsOnStock(integer $id_product, integer $depends_on_stock, integer $id_shop)
```

For a given id_product, sets if stock available depends on stock



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L190)


#### Arguments
* $id_product **integer**
* $depends_on_stock **integer** - Optional : true by default
* $id_shop **integer** - Optional : gets context by default



### <a name="method-setProductOutOfStock"></a>setProductOutOfStock

```php
mixed StockAvailableCore::setProductOutOfStock(integer $id_product, integer $out_of_stock, integer $id_shop)
```

For a given id_product, sets if product is available out of stocks



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L231)


#### Arguments
* $id_product **integer**
* $out_of_stock **integer** - Optional false by default
* $id_shop **integer** - Optional gets context by default



### <a name="method-setQuantity"></a>setQuantity

```php
mixed StockAvailableCore::setQuantity(integer $id_product, integer $id_product_attribute, $quantity, integer $id_shop)
```

For a given id_product and id_product_attribute sets the quantity available



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 386](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L386)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - Optional
* $quantity **mixed**
* $id_shop **integer** - Optional



### <a name="method-synchronize"></a>synchronize

```php
mixed StockAvailableCore::synchronize(integer $id_product)
```

For a given id_product, synchronizes StockAvailable::quantity with Stock::usable_quantity



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L115)


#### Arguments
* $id_product **integer**



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 575](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L575)




### <a name="method-update"></a>update

```php
mixed StockAvailableCore::update($null_values)
```

Upgrades total_quantity_available after having update



* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 308](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L308)


#### Arguments
* $null_values **mixed**



### <a name="method-updateQuantity"></a>updateQuantity

```php
mixed StockAvailableCore::updateQuantity(integer $id_product, integer $id_product_attribute, integer $delta_quantity, integer $id_shop)
```

For a given id_product and id_product_attribute updates the quantity available



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 346](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/stock/StockAvailable.php#L346)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - Optional
* $delta_quantity **integer** - The delta quantity to update
* $id_shop **integer** - Optional



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 772](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L772)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 778](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L778)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 710](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L710)


#### Arguments
* $field **string** - Field name
* $value **mixed** - Field value
* $id_lang **integer**



### <a name="method-validateFields"></a>validateFields

```php
boolean|string ObjectModelCore::validateFields(boolean $die, boolean $error_return)
```

Check for fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 649](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L649)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsLang"></a>validateFieldsLang

```php
boolean|string ObjectModelCore::validateFieldsLang(boolean $die, boolean $error_return)
```

Check for multilingual fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 675](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L675)


#### Arguments
* $die **boolean**
* $error_return **boolean**


