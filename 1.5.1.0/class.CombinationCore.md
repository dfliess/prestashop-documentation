Class CombinationCore
=====================





* Class name: CombinationCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Combination.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L28)


Contents
--------


### Properties

* [$available_date](#property-$available_date)
* [$default_on](#property-$default_on)
* [$definition](#property-$definition)
* [$ean13](#property-$ean13)
* [$ecotax](#property-$ecotax)
* [$id_product](#property-$id_product)
* [$location](#property-$location)
* [$minimal_quantity](#property-$minimal_quantity)
* [$price](#property-$price)
* [$quantity](#property-$quantity)
* [$reference](#property-$reference)
* [$supplier_reference](#property-$supplier_reference)
* [$unit_price_impact](#property-$unit_price_impact)
* [$upc](#property-$upc)
* [$webserviceParameters](#property-$webserviceParameters)
* [$weight](#property-$weight)
* [$wholesale_price](#property-$wholesale_price)
* [$db](#property-$db)
* [$def](#property-$def)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$get_shop_from_context](#property-$get_shop_from_context)
* [$id](#property-$id)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$id_shop_list](#property-$id_shop_list)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$table](#property-$table)
* [$tables](#property-$tables)
* [$update_fields](#property-$update_fields)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteAssociations](#method-deleteAssociations)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getAssociatedShops](#method-getAssociatedShops)
* [getAttributesName](#method-getAttributesName)
* [getDefinition](#method-getDefinition)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsShop](#method-getFieldsShop)
* [getIdByReference](#method-getIdByReference)
* [getPrice](#method-getPrice)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [getWsImages](#method-getWsImages)
* [getWsProductOptionValues](#method-getWsProductOptionValues)
* [hasMultishopEntries](#method-hasMultishopEntries)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isFeatureActive](#method-isFeatureActive)
* [isLangMultishop](#method-isLangMultishop)
* [isMultishop](#method-isMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [save](#method-save)
* [setAttributes](#method-setAttributes)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [setFieldsToUpdate](#method-setFieldsToUpdate)
* [setImages](#method-setImages)
* [setWsImages](#method-setWsImages)
* [setWsProductOptionValues](#method-setWsProductOptionValues)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateMultishopTable](#method-updateMultishopTable)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)
* [validateFieldsRequiredDatabase](#method-validateFieldsRequiredDatabase)




Properties
----------


### <a name="property-$available_date"></a>$available_date

```php
public mixed $available_date = '0000-00-00'
```





* Visibility: **public**
* Source: [classes/Combination.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L58).


### <a name="property-$default_on"></a>$default_on

```php
public mixed $default_on
```





* Visibility: **public**
* Source: [classes/Combination.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L56).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'product_attribute', 'primary' => 'id_product_attribute', 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'location' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 64), 'ean13' => array('type' => self::TYPE_STRING, 'validate' => 'isEan13', 'size' => 13), 'upc' => array('type' => self::TYPE_STRING, 'validate' => 'isUpc', 'size' => 12), 'quantity' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'size' => 10), 'reference' => array('type' => self::TYPE_STRING, 'size' => 32), 'supplier_reference' => array('type' => self::TYPE_STRING, 'size' => 32), 'wholesale_price' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice', 'size' => 27), 'price' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isNegativePrice', 'size' => 20), 'ecotax' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice', 'size' => 20), 'weight' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isFloat'), 'unit_price_impact' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice', 'size' => 20), 'minimal_quantity' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId', 'required' => true), 'default_on' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isBool'), 'available_date' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDateFormat')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Combination.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L63).


### <a name="property-$ean13"></a>$ean13

```php
public mixed $ean13
```





* Visibility: **public**
* Source: [classes/Combination.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L38).


### <a name="property-$ecotax"></a>$ecotax

```php
public mixed $ecotax
```





* Visibility: **public**
* Source: [classes/Combination.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L48).


### <a name="property-$id_product"></a>$id_product

```php
public mixed $id_product
```





* Visibility: **public**
* Source: [classes/Combination.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L30).


### <a name="property-$location"></a>$location

```php
public mixed $location
```





* Visibility: **public**
* Source: [classes/Combination.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L36).


### <a name="property-$minimal_quantity"></a>$minimal_quantity

```php
public mixed $minimal_quantity = 1
```





* Visibility: **public**
* Source: [classes/Combination.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L50).


### <a name="property-$price"></a>$price

```php
public mixed $price
```





* Visibility: **public**
* Source: [classes/Combination.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L44).


### <a name="property-$quantity"></a>$quantity

```php
public mixed $quantity
```





* Visibility: **public**
* Source: [classes/Combination.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L52).


### <a name="property-$reference"></a>$reference

```php
public mixed $reference
```





* Visibility: **public**
* Source: [classes/Combination.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L32).


### <a name="property-$supplier_reference"></a>$supplier_reference

```php
public mixed $supplier_reference
```





* Visibility: **public**
* Source: [classes/Combination.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L34).


### <a name="property-$unit_price_impact"></a>$unit_price_impact

```php
public mixed $unit_price_impact
```





* Visibility: **public**
* Source: [classes/Combination.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L46).


### <a name="property-$upc"></a>$upc

```php
public mixed $upc
```





* Visibility: **public**
* Source: [classes/Combination.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L40).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectNodeName' => 'combination', 'objectsNodeName' => 'combinations', 'fields' => array('id_product' => array('required' => true, 'xlink_resource' => 'products')), 'associations' => array('product_option_values' => array('resource' => 'product_option_value'), 'images' => array('resource' => 'image')))
```





* Visibility: **protected**
* Source: [classes/Combination.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L87).


### <a name="property-$weight"></a>$weight

```php
public mixed $weight
```





* Visibility: **public**
* Source: [classes/Combination.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L54).


### <a name="property-$wholesale_price"></a>$wholesale_price

```php
public mixed $wholesale_price
```





* Visibility: **public**
* Source: [classes/Combination.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L42).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L141).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L131).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L81).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L66).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L96).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L86).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L101).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L91).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L106).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected mixed $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L64).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L55).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L58).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L60).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public mixed $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L62).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L76).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L117).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L120).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L71).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L111).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L136).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ObjectModelCore::__construct(integer $id, integer $id_lang, integer $id_shop)
```

Build object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L169)


#### Arguments
* $id **integer** - Existing object id in order to load object (optional)
* $id_lang **integer** - Required if object is multilingual (optional)
* $id_shop **integer** - ID shop for objects with multishop on langs



### <a name="method-add"></a>add

```php
mixed CombinationCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Combination.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L112)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1097](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1097)


#### Arguments
* $fields **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1144](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1144)


#### Arguments
* $id_shops **integer|array**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1111](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1111)


#### Arguments
* $all **mixed**



### <a name="method-delete"></a>delete

```php
mixed CombinationCore::delete()
```





* Visibility: **public**
* Source: [classes/Combination.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L99)




### <a name="method-deleteAssociations"></a>deleteAssociations

```php
mixed CombinationCore::deleteAssociations()
```





* Visibility: **public**
* Source: [classes/Combination.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L126)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage($force_delete)
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1270](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1270)


#### Arguments
* $force_delete **mixed**



### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 690](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L690)


#### Arguments
* $selection **array**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 890](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L890)


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
* Source: [classes/ObjectModel.php line 1188](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1188)


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
* Source: [classes/ObjectModel.php line 1307](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1307)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $type, integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L335)


#### Arguments
* $type **integer** - FORMAT_COMMON or FORMAT_LANG or FORMAT_SHOP
* $id_lang **integer** - If this parameter is given, only take lang fields



### <a name="method-formatValue"></a>formatValue

```php
mixed ObjectModelCore::formatValue(mixed $value, integer $type, $with_quotes)
```

Format a data



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L381)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array ObjectModelCore::getAssociatedShops()
```

Get the list of associated id_shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1173](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1173)




### <a name="method-getAttributesName"></a>getAttributesName

```php
mixed CombinationCore::getAttributesName($id_lang)
```





* Visibility: **public**
* Source: [classes/Combination.php line 208](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L208)


#### Arguments
* $id_lang **mixed**



### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string $field)
```

Get object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1413](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1413)


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
* Source: [classes/ObjectModel.php line 1490](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1490)


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
* Source: [classes/ObjectModel.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L263)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L300)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1089](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1089)


#### Arguments
* $all **mixed**



### <a name="method-getFieldsShop"></a>getFieldsShop

```php
array ObjectModelCore::getFieldsShop()
```

Prepare fields for multishop
Fields are not validated here, we considere they are already validated in getFields() method, this
not the best solution but this is the only one possible for retro compatibility.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L286)




### <a name="method-getIdByReference"></a>getIdByReference

```php
integer CombinationCore::getIdByReference(integer $id_product, string $reference)
```

For a given product_attribute reference, returns the corresponding id



* Visibility: **public**
* This method is **static**.
* Source: [classes/Combination.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L250)


#### Arguments
* $id_product **integer**
* $reference **string**



### <a name="method-getPrice"></a>getPrice

```php
float CombinationCore::getPrice(integer $id_product_attribute)
```

Retrive the price of combination



* Visibility: **public**
* This method is **static**.
* Source: [classes/Combination.php line 271](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L271)


#### Arguments
* $id_product_attribute **integer**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 722](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L722)


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
* Source: [classes/ObjectModel.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L149)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1031](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1031)


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
* Source: [classes/ObjectModel.php line 957](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L957)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-getWsImages"></a>getWsImages

```php
mixed CombinationCore::getWsImages()
```





* Visibility: **public**
* Source: [classes/Combination.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L171)




### <a name="method-getWsProductOptionValues"></a>getWsProductOptionValues

```php
mixed CombinationCore::getWsProductOptionValues()
```





* Visibility: **public**
* Source: [classes/Combination.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L160)




### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Check if there is more than one entries in associated shop table for current entity



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1213](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1213)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1345](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1345)


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
* Source: [classes/ObjectModel.php line 1364](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1364)


#### Arguments
* $class **string** - Class of objects to hydrate
* $datas **array** - List of data (multi-dimensional array)
* $id_lang **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1126](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1126)


#### Arguments
* $id_shop **integer**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean CombinationCore::isCurrentlyUsed($table, $has_active_column)
```

This method is allow to know if a Combination entity is currently used



* Visibility: **public**
* This method is **static**.
* Source: [classes/Combination.php line 238](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L238)


#### Arguments
* $table **mixed**
* $has_active_column **mixed**



### <a name="method-isFeatureActive"></a>isFeatureActive

```php
boolean CombinationCore::isFeatureActive()
```

This method is allow to know if a feature is active



* Visibility: **public**
* This method is **static**.
* Source: [classes/Combination.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L222)




### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1225](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1225)




### <a name="method-isMultishop"></a>isMultishop

```php
mixed ObjectModelCore::isMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1220](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1220)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 738](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L738)


#### Arguments
* $fields **mixed**
* $fields_array **mixed**
* $id_language **mixed**



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L425)


#### Arguments
* $null_values **boolean**
* $autodate **boolean**



### <a name="method-setAttributes"></a>setAttributes

```php
mixed CombinationCore::setAttributes($ids_attribute)
```





* Visibility: **public**
* Source: [classes/Combination.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L134)


#### Arguments
* $ids_attribute **mixed**



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static
Remove this in 1.6 !



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1436](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1436)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false, langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1516](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1516)


#### Arguments
* $fields **array**



### <a name="method-setImages"></a>setImages

```php
mixed CombinationCore::setImages($ids_image)
```





* Visibility: **public**
* Source: [classes/Combination.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L181)


#### Arguments
* $ids_image **mixed**



### <a name="method-setWsImages"></a>setWsImages

```php
mixed CombinationCore::setWsImages($values)
```





* Visibility: **public**
* Source: [classes/Combination.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L200)


#### Arguments
* $values **mixed**



### <a name="method-setWsProductOptionValues"></a>setWsProductOptionValues

```php
mixed CombinationCore::setWsProductOptionValues($values)
```





* Visibility: **public**
* Source: [classes/Combination.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/Combination.php#L152)


#### Arguments
* $values **mixed**



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 706](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L706)




### <a name="method-update"></a>update

```php
boolean ObjectModelCore::update(boolean $null_values)
```

Update current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 529](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L529)


#### Arguments
* $null_values **boolean**



### <a name="method-updateMultishopTable"></a>updateMultishopTable

```php
boolean ObjectModelCore::updateMultishopTable(string $classname, array $data, string $where, string $specific_where)
```

Update a table and splits the common datas and the shop datas



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1240](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1240)


#### Arguments
* $classname **string**
* $data **array**
* $where **string**
* $specific_where **string** - Only executed for common table



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 905](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L905)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 911](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L911)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 843](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L843)


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
* Source: [classes/ObjectModel.php line 776](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L776)


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
* Source: [classes/ObjectModel.php line 805](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L805)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsRequiredDatabase"></a>validateFieldsRequiredDatabase

```php
mixed ObjectModelCore::validateFieldsRequiredDatabase($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1067](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1067)


#### Arguments
* $htmlentities **mixed**


