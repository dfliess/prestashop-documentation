Class AdminImportControllerCore
=====================





* Class name: AdminImportControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminImportController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L41)


Contents
--------


### Properties

* [$available_fields](#property-$available_fields)
* [$column_mask](#property-$column_mask)
* [$default_values](#property-$default_values)
* [$entities](#property-$entities)
* [$required_fields](#property-$required_fields)
* [$validators](#property-$validators)
* [$_defaultOrderBy](#property-$_defaultOrderBy)
* [$_defaultOrderWay](#property-$_defaultOrderWay)
* [$_filter](#property-$_filter)
* [$_group](#property-$_group)
* [$_having](#property-$_having)
* [$_includeContainer](#property-$_includeContainer)
* [$_join](#property-$_join)
* [$_languages](#property-$_languages)
* [$_list](#property-$_list)
* [$_listTotal](#property-$_listTotal)
* [$_orderBy](#property-$_orderBy)
* [$_orderWay](#property-$_orderWay)
* [$_pagination](#property-$_pagination)
* [$_redirect](#property-$_redirect)
* [$_select](#property-$_select)
* [$_tmpTableFilter](#property-$_tmpTableFilter)
* [$_where](#property-$_where)
* [$action](#property-$action)
* [$actions](#property-$actions)
* [$actions_available](#property-$actions_available)
* [$allow_employee_form_lang](#property-$allow_employee_form_lang)
* [$base_tpl_form](#property-$base_tpl_form)
* [$base_tpl_view](#property-$base_tpl_view)
* [$bo_theme](#property-$bo_theme)
* [$boxes](#property-$boxes)
* [$bulk_actions](#property-$bulk_actions)
* [$cache_lang](#property-$cache_lang)
* [$className](#property-$className)
* [$colorOnBackground](#property-$colorOnBackground)
* [$confirmations](#property-$confirmations)
* [$content](#property-$content)
* [$controller_name](#property-$controller_name)
* [$currentIndex](#property-$currentIndex)
* [$default_form_language](#property-$default_form_language)
* [$deleted](#property-$deleted)
* [$display](#property-$display)
* [$errors](#property-$errors)
* [$fieldImageSettings](#property-$fieldImageSettings)
* [$fieldsDisplay](#property-$fieldsDisplay)
* [$fields_form](#property-$fields_form)
* [$fields_form_override](#property-$fields_form_override)
* [$fields_value](#property-$fields_value)
* [$filter](#property-$filter)
* [$id](#property-$id)
* [$id_object](#property-$id_object)
* [$identifier](#property-$identifier)
* [$imageType](#property-$imageType)
* [$informations](#property-$informations)
* [$is_cms](#property-$is_cms)
* [$lang](#property-$lang)
* [$layout](#property-$layout)
* [$list_no_link](#property-$list_no_link)
* [$list_simple_header](#property-$list_simple_header)
* [$list_skip_actions](#property-$list_skip_actions)
* [$lite_display](#property-$lite_display)
* [$meta_title](#property-$meta_title)
* [$multiple_fieldsets](#property-$multiple_fieldsets)
* [$multishop_context](#property-$multishop_context)
* [$noLink](#property-$noLink)
* [$object](#property-$object)
* [$options](#property-$options)
* [$path](#property-$path)
* [$position_identifier](#property-$position_identifier)
* [$required_database](#property-$required_database)
* [$row_hover](#property-$row_hover)
* [$shopLink](#property-$shopLink)
* [$shopLinkType](#property-$shopLinkType)
* [$shopShareDatas](#property-$shopShareDatas)
* [$show_toolbar](#property-$show_toolbar)
* [$show_toolbar_options](#property-$show_toolbar_options)
* [$specificConfirmDelete](#property-$specificConfirmDelete)
* [$tabAccess](#property-$tabAccess)
* [$table](#property-$table)
* [$template](#property-$template)
* [$token](#property-$token)
* [$toolbar_btn](#property-$toolbar_btn)
* [$toolbar_scroll](#property-$toolbar_scroll)
* [$toolbar_title](#property-$toolbar_title)
* [$tpl_delete_link_vars](#property-$tpl_delete_link_vars)
* [$tpl_folder](#property-$tpl_folder)
* [$tpl_form_vars](#property-$tpl_form_vars)
* [$tpl_list_vars](#property-$tpl_list_vars)
* [$tpl_option_vars](#property-$tpl_option_vars)
* [$tpl_required_fields_vars](#property-$tpl_required_fields_vars)
* [$tpl_view_vars](#property-$tpl_view_vars)
* [$warnings](#property-$warnings)
* [$ajax](#property-$ajax)
* [$content_only](#property-$content_only)
* [$context](#property-$context)
* [$controller_type](#property-$controller_type)
* [$css_files](#property-$css_files)
* [$display_footer](#property-$display_footer)
* [$display_header](#property-$display_header)
* [$js_files](#property-$js_files)
* [$json](#property-$json)
* [$redirect_after](#property-$redirect_after)
* [$status](#property-$status)

### Methods

* [__construct](#method-__construct)
* [_childValidation](#method-_childValidation)
* [addCSS](#method-addCSS)
* [addJS](#method-addJS)
* [addJquery](#method-addJquery)
* [addJqueryPlugin](#method-addJqueryPlugin)
* [addJqueryUI](#method-addJqueryUI)
* [addProductWarning](#method-addProductWarning)
* [addRowAction](#method-addRowAction)
* [addRowActionSkipList](#method-addRowActionSkipList)
* [addressImport](#method-addressImport)
* [afterAdd](#method-afterAdd)
* [afterDelete](#method-afterDelete)
* [afterImageUpload](#method-afterImageUpload)
* [afterUpdate](#method-afterUpdate)
* [ajaxProcessHelpAccess](#method-ajaxProcessHelpAccess)
* [arrayWalk](#method-arrayWalk)
* [attributeImport](#method-attributeImport)
* [beforeAdd](#method-beforeAdd)
* [beforeDelete](#method-beforeDelete)
* [beforeUpdateOptions](#method-beforeUpdateOptions)
* [categoryImport](#method-categoryImport)
* [checkAccess](#method-checkAccess)
* [checkToken](#method-checkToken)
* [closeCsvFile](#method-closeCsvFile)
* [copyFromPost](#method-copyFromPost)
* [copyImg](#method-copyImg)
* [createMultiLangField](#method-createMultiLangField)
* [createTemplate](#method-createTemplate)
* [customerImport](#method-customerImport)
* [display](#method-display)
* [displayAjax](#method-displayAjax)
* [displayFooter](#method-displayFooter)
* [displayHeader](#method-displayHeader)
* [displayInformation](#method-displayInformation)
* [displayNoSmarty](#method-displayNoSmarty)
* [displayRequiredFields](#method-displayRequiredFields)
* [displayWarning](#method-displayWarning)
* [fillInfo](#method-fillInfo)
* [filterToField](#method-filterToField)
* [generateContentTable](#method-generateContentTable)
* [getAssoShop](#method-getAssoShop)
* [getAvailableFields](#method-getAvailableFields)
* [getBoolean](#method-getBoolean)
* [getController](#method-getController)
* [getFieldValue](#method-getFieldValue)
* [getFieldsValue](#method-getFieldsValue)
* [getLanguages](#method-getLanguages)
* [getList](#method-getList)
* [getMaskedRow](#method-getMaskedRow)
* [getNbrColumn](#method-getNbrColumn)
* [getPrice](#method-getPrice)
* [getTranslationsFlags](#method-getTranslationsFlags)
* [getTypeValuesOptions](#method-getTypeValuesOptions)
* [init](#method-init)
* [initContent](#method-initContent)
* [initCursedPage](#method-initCursedPage)
* [initFooter](#method-initFooter)
* [initHeader](#method-initHeader)
* [initProcess](#method-initProcess)
* [initShopContext](#method-initShopContext)
* [initToolbar](#method-initToolbar)
* [initToolbarTitle](#method-initToolbarTitle)
* [l](#method-l)
* [loadObject](#method-loadObject)
* [manufacturerImport](#method-manufacturerImport)
* [openCsvFile](#method-openCsvFile)
* [postImage](#method-postImage)
* [postProcess](#method-postProcess)
* [processAdd](#method-processAdd)
* [processBulkAffectZone](#method-processBulkAffectZone)
* [processBulkDelete](#method-processBulkDelete)
* [processDelete](#method-processDelete)
* [processDeleteImage](#method-processDeleteImage)
* [processFilter](#method-processFilter)
* [processPosition](#method-processPosition)
* [processResetFilters](#method-processResetFilters)
* [processSave](#method-processSave)
* [processStatus](#method-processStatus)
* [processUpdate](#method-processUpdate)
* [processUpdateFields](#method-processUpdateFields)
* [processUpdateOptions](#method-processUpdateOptions)
* [productImport](#method-productImport)
* [receiveTab](#method-receiveTab)
* [redirect](#method-redirect)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [renderOptions](#method-renderOptions)
* [renderView](#method-renderView)
* [rewindBomAware](#method-rewindBomAware)
* [run](#method-run)
* [setDefaultValues](#method-setDefaultValues)
* [setEntityDefaultValues](#method-setEntityDefaultValues)
* [setHelperDisplay](#method-setHelperDisplay)
* [setLocale](#method-setLocale)
* [setMedia](#method-setMedia)
* [setTemplate](#method-setTemplate)
* [split](#method-split)
* [supplierImport](#method-supplierImport)
* [supplyOrdersDetailsImport](#method-supplyOrdersDetailsImport)
* [supplyOrdersImport](#method-supplyOrdersImport)
* [truncateTables](#method-truncateTables)
* [updateAssoShop](#method-updateAssoShop)
* [uploadImage](#method-uploadImage)
* [usortFiles](#method-usortFiles)
* [utf8EncodeArray](#method-utf8EncodeArray)
* [validateField](#method-validateField)
* [validateRules](#method-validateRules)
* [viewAccess](#method-viewAccess)
* [viewDetails](#method-viewDetails)




Properties
----------


### <a name="property-$available_fields"></a>$available_fields

```php
public mixed $available_fields = array()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L47).


### <a name="property-$column_mask"></a>$column_mask

```php
public mixed $column_mask
```





* Visibility: **public**
* This property is **static**.
* Source: [controllers/admin/AdminImportController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L43).


### <a name="property-$default_values"></a>$default_values

```php
public mixed $default_values = array()
```





* Visibility: **public**
* This property is **static**.
* Source: [controllers/admin/AdminImportController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L51).


### <a name="property-$entities"></a>$entities

```php
public mixed $entities = array()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L45).


### <a name="property-$required_fields"></a>$required_fields

```php
public mixed $required_fields = array('name')
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L49).


### <a name="property-$validators"></a>$validators

```php
public mixed $validators = array('active' => array('AdminImportController', 'getBoolean'), 'tax_rate' => array('AdminImportController', 'getPrice'), 'price_tex' => array('AdminImportController', 'getPrice'), 'price_tin' => array('AdminImportController', 'getPrice'), 'reduction_price' => array('AdminImportController', 'getPrice'), 'reduction_percent' => array('AdminImportController', 'getPrice'), 'wholesale_price' => array('AdminImportController', 'getPrice'), 'ecotax' => array('AdminImportController', 'getPrice'), 'name' => array('AdminImportController', 'createMultiLangField'), 'description' => array('AdminImportController', 'createMultiLangField'), 'description_short' => array('AdminImportController', 'createMultiLangField'), 'meta_title' => array('AdminImportController', 'createMultiLangField'), 'meta_keywords' => array('AdminImportController', 'createMultiLangField'), 'meta_description' => array('AdminImportController', 'createMultiLangField'), 'link_rewrite' => array('AdminImportController', 'createMultiLangField'), 'available_now' => array('AdminImportController', 'createMultiLangField'), 'available_later' => array('AdminImportController', 'createMultiLangField'), 'category' => array('AdminImportController', 'split'), 'online_only' => array('AdminImportController', 'getBoolean'))
```





* Visibility: **public**
* This property is **static**.
* Source: [controllers/admin/AdminImportController.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L53).


### <a name="property-$_defaultOrderBy"></a>$_defaultOrderBy

```php
protected string $_defaultOrderBy = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L72).


### <a name="property-$_defaultOrderWay"></a>$_defaultOrderWay

```php
protected mixed $_defaultOrderWay = 'ASC'
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L73).


### <a name="property-$_filter"></a>$_filter

```php
protected array $_filter
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L135).


### <a name="property-$_group"></a>$_group

```php
protected string $_group
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L198).


### <a name="property-$_having"></a>$_having

```php
protected string $_having
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L201).


### <a name="property-$_includeContainer"></a>$_includeContainer

```php
protected mixed $_includeContainer = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L222).


### <a name="property-$_join"></a>$_join

```php
protected string $_join
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L192).


### <a name="property-$_languages"></a>$_languages

```php
public mixed $_languages = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L38).


### <a name="property-$_list"></a>$_list

```php
protected array $_list = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L111).


### <a name="property-$_listTotal"></a>$_listTotal

```php
protected integer $_listTotal
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L129).


### <a name="property-$_orderBy"></a>$_orderBy

```php
protected string $_orderBy
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L144).


### <a name="property-$_orderWay"></a>$_orderWay

```php
protected string $_orderWay
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L147).


### <a name="property-$_pagination"></a>$_pagination

```php
protected array $_pagination = array(20, 50, 100, 300)
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L141).


### <a name="property-$_redirect"></a>$_redirect

```php
protected boolean $_redirect = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L229).


### <a name="property-$_select"></a>$_select

```php
protected string $_select
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L189).


### <a name="property-$_tmpTableFilter"></a>$_tmpTableFilter

```php
protected array $_tmpTableFilter = ''
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L138).


### <a name="property-$_where"></a>$_where

```php
protected string $_where
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L195).


### <a name="property-$action"></a>$action

```php
protected mixed $action
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L220).


### <a name="property-$actions"></a>$actions

```php
protected array $actions = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L153).


### <a name="property-$actions_available"></a>$actions_available

```php
protected array $actions_available = array('view', 'edit', 'delete', 'duplicate')
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L150).


### <a name="property-$allow_employee_form_lang"></a>$allow_employee_form_lang

```php
public mixed $allow_employee_form_lang
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L40).


### <a name="property-$base_tpl_form"></a>$base_tpl_form

```php
public mixed $base_tpl_form = null
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L83).


### <a name="property-$base_tpl_view"></a>$base_tpl_view

```php
public mixed $base_tpl_view = null
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L82).


### <a name="property-$bo_theme"></a>$bo_theme

```php
protected mixed $bo_theme
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L226).


### <a name="property-$boxes"></a>$boxes

```php
protected array $boxes
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L186).


### <a name="property-$bulk_actions"></a>$bulk_actions

```php
protected array $bulk_actions
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L181).


### <a name="property-$cache_lang"></a>$cache_lang

```php
public array $cache_lang = array()
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L164).


### <a name="property-$className"></a>$className

```php
public string $className
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L55).


### <a name="property-$colorOnBackground"></a>$colorOnBackground

```php
protected mixed $colorOnBackground
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L216).


### <a name="property-$confirmations"></a>$confirmations

```php
public mixed $confirmations = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L35).


### <a name="property-$content"></a>$content

```php
public mixed $content
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L32).


### <a name="property-$controller_name"></a>$controller_name

```php
public \current $controller_name
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L246).


### <a name="property-$currentIndex"></a>$currentIndex

```php
public mixed $currentIndex
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L31).


### <a name="property-$default_form_language"></a>$default_form_language

```php
public mixed $default_form_language
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L39).


### <a name="property-$deleted"></a>$deleted

```php
protected boolean $deleted = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L209).


### <a name="property-$display"></a>$display

```php
protected mixed $display
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L221).


### <a name="property-$errors"></a>$errors

```php
public array $errors = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L91).


### <a name="property-$fieldImageSettings"></a>$fieldImageSettings

```php
public array $fieldImageSettings = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L232).


### <a name="property-$fieldsDisplay"></a>$fieldsDisplay

```php
protected array $fieldsDisplay
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L97).


### <a name="property-$fields_form"></a>$fields_form

```php
protected array $fields_form
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L100).


### <a name="property-$fields_form_override"></a>$fields_form_override

```php
protected \override $fields_form_override
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L103).


### <a name="property-$fields_value"></a>$fields_value

```php
public mixed $fields_value = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L88).


### <a name="property-$filter"></a>$filter

```php
protected boolean $filter
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L213).


### <a name="property-$id"></a>$id

```php
public integer $id = -1
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L61).


### <a name="property-$id_object"></a>$id_object

```php
protected \current $id_object
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L241).


### <a name="property-$identifier"></a>$identifier

```php
protected string $identifier = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L52).


### <a name="property-$imageType"></a>$imageType

```php
public string $imageType = 'jpg'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L235).


### <a name="property-$informations"></a>$informations

```php
public mixed $informations = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L34).


### <a name="property-$is_cms"></a>$is_cms

```php
protected mixed $is_cms = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L203).


### <a name="property-$lang"></a>$lang

```php
public boolean $lang = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L132).


### <a name="property-$layout"></a>$layout

```php
public mixed $layout = 'layout.tpl'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L42).


### <a name="property-$list_no_link"></a>$list_no_link

```php
protected boolean $list_no_link = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L161).


### <a name="property-$list_simple_header"></a>$list_simple_header

```php
protected \define $list_simple_header
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L94).


### <a name="property-$list_skip_actions"></a>$list_skip_actions

```php
protected array $list_skip_actions = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L156).


### <a name="property-$lite_display"></a>$lite_display

```php
protected mixed $lite_display = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L159).


### <a name="property-$meta_title"></a>$meta_title

```php
public mixed $meta_title = 'Administration panel'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L44).


### <a name="property-$multiple_fieldsets"></a>$multiple_fieldsets

```php
public boolean $multiple_fieldsets = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L86).


### <a name="property-$multishop_context"></a>$multishop_context

```php
public mixed $multishop_context = -1
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 248](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L248).


### <a name="property-$noLink"></a>$noLink

```php
protected mixed $noLink
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L214).


### <a name="property-$object"></a>$object

```php
protected \instanciation $object
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 238](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L238).


### <a name="property-$options"></a>$options

```php
protected array $options
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L106).


### <a name="property-$path"></a>$path

```php
public mixed $path
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L30).


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected string $position_identifier
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L206).


### <a name="property-$required_database"></a>$required_database

```php
public mixed $required_database = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L63).


### <a name="property-$row_hover"></a>$row_hover

```php
protected boolean $row_hover = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L218).


### <a name="property-$shopLink"></a>$shopLink

```php
protected mixed $shopLink
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L108).


### <a name="property-$shopLinkType"></a>$shopLinkType

```php
public string $shopLinkType
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L69).


### <a name="property-$shopShareDatas"></a>$shopShareDatas

```php
public mixed $shopShareDatas = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L36).


### <a name="property-$show_toolbar"></a>$show_toolbar

```php
protected boolean $show_toolbar = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L123).


### <a name="property-$show_toolbar_options"></a>$show_toolbar_options

```php
protected boolean $show_toolbar_options = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L126).


### <a name="property-$specificConfirmDelete"></a>$specificConfirmDelete

```php
protected mixed $specificConfirmDelete = null
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L215).


### <a name="property-$tabAccess"></a>$tabAccess

```php
public array $tabAccess
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L58).


### <a name="property-$table"></a>$table

```php
public string $table
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L49).


### <a name="property-$template"></a>$template

```php
public mixed $template = 'content.tpl'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L46).


### <a name="property-$token"></a>$token

```php
public string $token
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L66).


### <a name="property-$toolbar_btn"></a>$toolbar_btn

```php
protected array $toolbar_btn = null
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L117).


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

```php
protected boolean $toolbar_scroll = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L120).


### <a name="property-$toolbar_title"></a>$toolbar_title

```php
protected \define $toolbar_title
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L114).


### <a name="property-$tpl_delete_link_vars"></a>$tpl_delete_link_vars

```php
public mixed $tpl_delete_link_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L77).


### <a name="property-$tpl_folder"></a>$tpl_folder

```php
public mixed $tpl_folder
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L224).


### <a name="property-$tpl_form_vars"></a>$tpl_form_vars

```php
public mixed $tpl_form_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L75).


### <a name="property-$tpl_list_vars"></a>$tpl_list_vars

```php
public mixed $tpl_list_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L76).


### <a name="property-$tpl_option_vars"></a>$tpl_option_vars

```php
public mixed $tpl_option_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L78).


### <a name="property-$tpl_required_fields_vars"></a>$tpl_required_fields_vars

```php
public mixed $tpl_required_fields_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L80).


### <a name="property-$tpl_view_vars"></a>$tpl_view_vars

```php
public mixed $tpl_view_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L79).


### <a name="property-$warnings"></a>$warnings

```php
public mixed $warnings = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L33).


### <a name="property-$ajax"></a>$ajax

```php
protected boolean $ajax = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L71).


### <a name="property-$content_only"></a>$content_only

```php
protected string $content_only = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L66).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L36).


### <a name="property-$controller_type"></a>$controller_type

```php
public mixed $controller_type
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L77).


### <a name="property-$css_files"></a>$css_files

```php
public array $css_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L41).


### <a name="property-$display_footer"></a>$display_footer

```php
protected string $display_footer
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L61).


### <a name="property-$display_header"></a>$display_header

```php
protected boolean $display_header
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L51).


### <a name="property-$js_files"></a>$js_files

```php
public array $js_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L46).


### <a name="property-$json"></a>$json

```php
protected mixed $json = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L72).


### <a name="property-$redirect_after"></a>$redirect_after

```php
protected mixed $redirect_after = null
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L75).


### <a name="property-$status"></a>$status

```php
protected mixed $status = ''
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L73).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminImportControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L77)




### <a name="method-_childValidation"></a>_childValidation

```php
mixed AdminControllerCore::_childValidation()
```

Overload this method for custom checking



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2214](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2214)




### <a name="method-addCSS"></a>addCSS

```php
true ControllerCore::addCSS(mixed $css_uri, string $css_media_type)
```

Add a new stylesheet in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L235)


#### Arguments
* $css_uri **mixed** - Path to css file, or list of css files like this : array(array(uri =&gt; media_type), ...)
* $css_media_type **string**



### <a name="method-addJS"></a>addJS

```php
void ControllerCore::addJS(mixed $js_uri)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L267)


#### Arguments
* $js_uri **mixed**



### <a name="method-addJquery"></a>addJquery

```php
void ControllerCore::addJquery($version, $folder, $minifier)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 290](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L290)


#### Arguments
* $version **mixed**
* $folder **mixed**
* $minifier **mixed**



### <a name="method-addJqueryPlugin"></a>addJqueryPlugin

```php
void ControllerCore::addJqueryPlugin($name, $folder)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 321](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L321)


#### Arguments
* $name **mixed**
* $folder **mixed**



### <a name="method-addJqueryUI"></a>addJqueryUI

```php
void ControllerCore::addJqueryUI($component, $theme, $check_dependencies)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 301](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L301)


#### Arguments
* $component **mixed**
* $theme **mixed**
* $check_dependencies **mixed**



### <a name="method-addProductWarning"></a>addProductWarning

```php
mixed AdminImportControllerCore::addProductWarning($product_name, $product_id, $message)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImportController.php line 2259](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L2259)


#### Arguments
* $product_name **mixed**
* $product_id **mixed**
* $message **mixed**



### <a name="method-addRowAction"></a>addRowAction

```php
mixed AdminControllerCore::addRowAction($action)
```

Declare an action to use for each row in the list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1311](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1311)


#### Arguments
* $action **mixed**



### <a name="method-addRowActionSkipList"></a>addRowActionSkipList

```php
mixed AdminControllerCore::addRowActionSkipList($action, $list)
```

Add  an action to use for each row in the list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1320](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1320)


#### Arguments
* $action **mixed**
* $list **mixed**



### <a name="method-addressImport"></a>addressImport

```php
mixed AdminImportControllerCore::addressImport()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 1572](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L1572)




### <a name="method-afterAdd"></a>afterAdd

```php
mixed AdminControllerCore::afterAdd($object)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2247](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2247)


#### Arguments
* $object **mixed**



### <a name="method-afterDelete"></a>afterDelete

```php
boolean AdminControllerCore::afterDelete(object $object, $oldId)
```

Called before deletion



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2242](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2242)


#### Arguments
* $object **object** - Object
* $oldId **mixed**



### <a name="method-afterImageUpload"></a>afterImageUpload

```php
boolean AdminControllerCore::afterImageUpload()
```

Check rights to view the current tab



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2263](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2263)




### <a name="method-afterUpdate"></a>afterUpdate

```php
mixed AdminControllerCore::afterUpdate($object)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2252](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2252)


#### Arguments
* $object **mixed**



### <a name="method-ajaxProcessHelpAccess"></a>ajaxProcessHelpAccess

```php
mixed AdminControllerCore::ajaxProcessHelpAccess()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L372)




### <a name="method-arrayWalk"></a>arrayWalk

```php
mixed AdminImportControllerCore::arrayWalk($array, $funcname, $user_data)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 733](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L733)


#### Arguments
* $array **mixed**
* $funcname **mixed**
* $user_data **mixed**



### <a name="method-attributeImport"></a>attributeImport

```php
mixed AdminImportControllerCore::attributeImport()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 1281](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L1281)




### <a name="method-beforeAdd"></a>beforeAdd

```php
boolean AdminControllerCore::beforeAdd(object $object)
```

Called before Add



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2553](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2553)


#### Arguments
* $object **object** - Object



### <a name="method-beforeDelete"></a>beforeDelete

```php
boolean AdminControllerCore::beforeDelete(object $object)
```

Called before deletion



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2231](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2231)


#### Arguments
* $object **object** - Object



### <a name="method-beforeUpdateOptions"></a>beforeUpdateOptions

```php
mixed AdminControllerCore::beforeUpdateOptions()
```

Can be overriden



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2382](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2382)




### <a name="method-categoryImport"></a>categoryImport

```php
mixed AdminImportControllerCore::categoryImport()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 793](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L793)




### <a name="method-checkAccess"></a>checkAccess

```php
mixed AdminControllerCore::checkAccess()
```

Check if the token is valid, else display a warning page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1044](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1044)




### <a name="method-checkToken"></a>checkToken

```php
mixed AdminControllerCore::checkToken()
```

Check for security token



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 366](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L366)




### <a name="method-closeCsvFile"></a>closeCsvFile

```php
mixed AdminImportControllerCore::closeCsvFile($handle)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImportController.php line 2093](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L2093)


#### Arguments
* $handle **mixed**



### <a name="method-copyFromPost"></a>copyFromPost

```php
mixed AdminControllerCore::copyFromPost($object, string $table)
```

Copy datas from $_POST to object



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2274](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2274)


#### Arguments
* $object **mixed**
* $table **string** - Object table



### <a name="method-copyImg"></a>copyImg

```php
void AdminImportControllerCore::copyImg(integer $id_entity, integer $id_image, string $url, $entity)
```

copyImg copy an image located in $url and save it in a path
according to $entity->$id_entity .

$id_image is used if we need to add a watermark

* Visibility: **private**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 754](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L754)


#### Arguments
* $id_entity **integer** - id of product or category (set in entity)
* $id_image **integer** - (default null) id of the image if watermark enabled.
* $url **string** - path or url to use
* $entity **mixed**



### <a name="method-createMultiLangField"></a>createMultiLangField

```php
mixed AdminImportControllerCore::createMultiLangField($field)
```





* Visibility: **private**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 627](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L627)


#### Arguments
* $field **mixed**



### <a name="method-createTemplate"></a>createTemplate

```php
\Template AdminControllerCore::createTemplate(string $tpl_name)
```

Create a template from the override file, else from the base file.



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2578](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2578)


#### Arguments
* $tpl_name **string** - filename



### <a name="method-customerImport"></a>customerImport

```php
mixed AdminImportControllerCore::customerImport()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 1522](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L1522)




### <a name="method-display"></a>display

```php
mixed AdminControllerCore::display()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1095](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1095)




### <a name="method-displayAjax"></a>displayAjax

```php
mixed AdminControllerCore::displayAjax()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1077](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1077)




### <a name="method-displayFooter"></a>displayFooter

```php
mixed ControllerCore::displayFooter($display)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L198)


#### Arguments
* $display **mixed**



### <a name="method-displayHeader"></a>displayHeader

```php
mixed ControllerCore::displayHeader($display)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 193](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L193)


#### Arguments
* $display **mixed**



### <a name="method-displayInformation"></a>displayInformation

```php
mixed AdminControllerCore::displayInformation(string $msg)
```

add a info message to display at the top of the page



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1173](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1173)


#### Arguments
* $msg **string**



### <a name="method-displayNoSmarty"></a>displayNoSmarty

```php
mixed AdminControllerCore::displayNoSmarty()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1073](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1073)




### <a name="method-displayRequiredFields"></a>displayRequiredFields

```php
mixed AdminControllerCore::displayRequiredFields()
```

prepare the view to display the required fields form



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2561](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2561)




### <a name="method-displayWarning"></a>displayWarning

```php
mixed AdminControllerCore::displayWarning(string $msg)
```

add a warning message to display at the top of the page



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1163](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1163)


#### Arguments
* $msg **string**



### <a name="method-fillInfo"></a>fillInfo

```php
mixed AdminImportControllerCore::fillInfo($infos, $key, $entity)
```





* Visibility: **private**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 718](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L718)


#### Arguments
* $infos **mixed**
* $key **mixed**
* $entity **mixed**



### <a name="method-filterToField"></a>filterToField

```php
mixed AdminControllerCore::filterToField($key, $filter)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1063](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1063)


#### Arguments
* $key **mixed**
* $filter **mixed**



### <a name="method-generateContentTable"></a>generateContentTable

```php
mixed AdminImportControllerCore::generateContentTable($current_table, $nb_column, $handle, $glue)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImportController.php line 524](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L524)


#### Arguments
* $current_table **mixed**
* $nb_column **mixed**
* $handle **mixed**
* $glue **mixed**



### <a name="method-getAssoShop"></a>getAssoShop

```php
mixed AdminControllerCore::getAssoShop(string $table, integer $id_object)
```

Returns an array with selected shops and type (group or boutique shop)



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2307](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2307)


#### Arguments
* $table **string**
* $id_object **integer**



### <a name="method-getAvailableFields"></a>getAvailableFields

```php
mixed AdminImportControllerCore::getAvailableFields($in_array)
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 661](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L661)


#### Arguments
* $in_array **mixed**



### <a name="method-getBoolean"></a>getBoolean

```php
mixed AdminImportControllerCore::getBoolean($field)
```





* Visibility: **private**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 594](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L594)


#### Arguments
* $field **mixed**



### <a name="method-getController"></a>getController

```php
mixed ControllerCore::getController(string $class_name, boolean $auth, boolean $ssl)
```

Get an instance of a controller



* Visibility: **public**
* This method is **static**.
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L127)


#### Arguments
* $class_name **string**
* $auth **boolean**
* $ssl **boolean**



### <a name="method-getFieldValue"></a>getFieldValue

```php
string AdminControllerCore::getFieldValue(object $obj, string $key, integer $id_lang)
```

Return field value if possible (both classical and multilingual fields)

Case 1 : Return value if present in $_POST / $_GET
Case 2 : Return object value

* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2113](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2113)


#### Arguments
* $obj **object** - Object
* $key **string** - Field name
* $id_lang **integer** - Language id (optional)



### <a name="method-getFieldsValue"></a>getFieldsValue

```php
array AdminControllerCore::getFieldsValue(object $obj)
```

Return the list of fields value



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2059](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2059)


#### Arguments
* $obj **object** - Object



### <a name="method-getLanguages"></a>getLanguages

```php
mixed AdminControllerCore::getLanguages()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2029](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2029)




### <a name="method-getList"></a>getList

```php
mixed AdminControllerCore::getList(integer $id_lang, string $order_by, $order_way, integer $start, integer $limit, $id_lang_shop)
```

Get the current objects' list form the database



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1878](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1878)


#### Arguments
* $id_lang **integer** - Language used for display
* $order_by **string** - ORDER BY clause
* $order_way **mixed**
* $start **integer** - Offset in LIMIT clause
* $limit **integer** - Row count in LIMIT clause
* $id_lang_shop **mixed**



### <a name="method-getMaskedRow"></a>getMaskedRow

```php
mixed AdminImportControllerCore::getMaskedRow($row)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 695](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L695)


#### Arguments
* $row **mixed**



### <a name="method-getNbrColumn"></a>getNbrColumn

```php
mixed AdminImportControllerCore::getNbrColumn($handle, $glue)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImportController.php line 2061](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L2061)


#### Arguments
* $handle **mixed**
* $glue **mixed**



### <a name="method-getPrice"></a>getPrice

```php
mixed AdminImportControllerCore::getPrice($field)
```





* Visibility: **private**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 599](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L599)


#### Arguments
* $field **mixed**



### <a name="method-getTranslationsFlags"></a>getTranslationsFlags

```php
string AdminControllerCore::getTranslationsFlags(array $languages, integer $default_language, string $ids, string $id, $return, boolean $use_vars_instead_of_ids)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2522](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2522)


#### Arguments
* $languages **array** - All languages available
* $default_language **integer** - Default language id
* $ids **string** - Multilingual div ids in form
* $id **string** - Current div id]
* $return **mixed**
* $use_vars_instead_of_ids **boolean** - use an js vars instead of ids seperate by &quot;¤&quot;



### <a name="method-getTypeValuesOptions"></a>getTypeValuesOptions

```php
mixed AdminImportControllerCore::getTypeValuesOptions($nb_c)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImportController.php line 636](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L636)


#### Arguments
* $nb_c **mixed**



### <a name="method-init"></a>init

```php
mixed AdminImportControllerCore::init()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 564](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L564)




### <a name="method-initContent"></a>initContent

```php
mixed AdminImportControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 571](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L571)




### <a name="method-initCursedPage"></a>initCursedPage

```php
void AdminControllerCore::initCursedPage()
```

initialize the invalid doom page of death



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1373](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1373)




### <a name="method-initFooter"></a>initFooter

```php
mixed AdminControllerCore::initFooter()
```

Assign smarty variables for the footer



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1381](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1381)




### <a name="method-initHeader"></a>initHeader

```php
mixed AdminControllerCore::initHeader()
```

Assign smarty variables for the header



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1181](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1181)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminControllerCore::initProcess()
```

Retrieve GET and POST value and translate them to actions



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1702](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1702)




### <a name="method-initShopContext"></a>initShopContext

```php
mixed AdminControllerCore::initShopContext()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1641](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1641)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminImportControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 500](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L500)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

```php
void AdminControllerCore::initToolbarTitle()
```

set default toolbar_title to admin breadcrumb



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L313)




### <a name="method-l"></a>l

```php
string AdminControllerCore::l(mixed $string, string $class, \boolan $addslashes, boolean $htmlentities)
```

non-static method which uses AdminController::translate()



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1579](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1579)


#### Arguments
* $string **mixed** - term or expression in english
* $class **string** - name of the class, without &quot;Controller&quot; suffix
* $addslashes **boolan** - if set to true, the return value will pass through addslashes(). Otherwise, stripslashes().
* $htmlentities **boolean** - if set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)



### <a name="method-loadObject"></a>loadObject

```php
object AdminControllerCore::loadObject(boolean $opt)
```

Load class object using identifier in $_GET (if possible)
otherwise return an empty object, or die



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1013](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1013)


#### Arguments
* $opt **boolean** - Return an empty object if load fail



### <a name="method-manufacturerImport"></a>manufacturerImport

```php
mixed AdminImportControllerCore::manufacturerImport()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 1718](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L1718)




### <a name="method-openCsvFile"></a>openCsvFile

```php
mixed AdminImportControllerCore::openCsvFile()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImportController.php line 2079](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L2079)




### <a name="method-postImage"></a>postImage

```php
boolean AdminControllerCore::postImage(integer $id)
```

Overload this method for custom checking



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2392](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2392)


#### Arguments
* $id **integer** - Object id used for deleting images



### <a name="method-postProcess"></a>postProcess

```php
mixed AdminImportControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 2159](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L2159)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminControllerCore::processAdd(string $token)
```

Object creation



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 596](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L596)


#### Arguments
* $token **string**



### <a name="method-processBulkAffectZone"></a>processBulkAffectZone

```php
mixed AdminControllerCore::processBulkAffectZone($token)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2491](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2491)


#### Arguments
* $token **mixed**



### <a name="method-processBulkDelete"></a>processBulkDelete

```php
boolean AdminControllerCore::processBulkDelete($token)
```

Delete multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2446](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2446)


#### Arguments
* $token **mixed**



### <a name="method-processDelete"></a>processDelete

```php
mixed AdminControllerCore::processDelete(string $token)
```

Object Delete



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 528](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L528)


#### Arguments
* $token **string**



### <a name="method-processDeleteImage"></a>processDeleteImage

```php
mixed AdminControllerCore::processDeleteImage(string $token)
```

Object Delete images



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 506](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L506)


#### Arguments
* $token **string**



### <a name="method-processFilter"></a>processFilter

```php
mixed AdminControllerCore::processFilter()
```

Set the filters used for the list display



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 393](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L393)




### <a name="method-processPosition"></a>processPosition

```php
mixed AdminControllerCore::processPosition(string $token)
```

Change object position



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 786](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L786)


#### Arguments
* $token **string**



### <a name="method-processResetFilters"></a>processResetFilters

```php
mixed AdminControllerCore::processResetFilters()
```

Cancel all filters for this tab



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 809](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L809)




### <a name="method-processSave"></a>processSave

```php
mixed AdminControllerCore::processSave($token)
```

Call the right method for creating or updating object



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 580](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L580)


#### Arguments
* $token **mixed**



### <a name="method-processStatus"></a>processStatus

```php
mixed AdminControllerCore::processStatus(string $token)
```

Change object status (active, inactive)



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 761](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L761)


#### Arguments
* $token **string**



### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminControllerCore::processUpdate(string $token)
```

Object update



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 647](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L647)


#### Arguments
* $token **string**



### <a name="method-processUpdateFields"></a>processUpdateFields

```php
mixed AdminControllerCore::processUpdateFields(string $token)
```

Change object required fields



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 742](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L742)


#### Arguments
* $token **string**



### <a name="method-processUpdateOptions"></a>processUpdateOptions

```php
mixed AdminControllerCore::processUpdateOptions(string $token)
```

Update options and preferences



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 845](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L845)


#### Arguments
* $token **string**



### <a name="method-productImport"></a>productImport

```php
mixed AdminImportControllerCore::productImport()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 926](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L926)




### <a name="method-receiveTab"></a>receiveTab

```php
mixed AdminImportControllerCore::receiveTab()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImportController.php line 687](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L687)




### <a name="method-redirect"></a>redirect

```php
mixed AdminControllerCore::redirect()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1090](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1090)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminImportControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 415](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L415)




### <a name="method-renderList"></a>renderList

```php
mixed AdminControllerCore::renderList()
```

Function used to render the list to display for this controller



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1397](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1397)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminControllerCore::renderOptions()
```

Function used to render the options for this controller



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1477](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1477)




### <a name="method-renderView"></a>renderView

```php
mixed AdminImportControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 459](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L459)




### <a name="method-rewindBomAware"></a>rewindBomAware

```php
mixed AdminImportControllerCore::rewindBomAware($handle)
```





* Visibility: **private**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 586](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L586)


#### Arguments
* $handle **mixed**



### <a name="method-run"></a>run

```php
mixed ControllerCore::run()
```

Start controller process (this method shouldn't be overriden !)



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L148)




### <a name="method-setDefaultValues"></a>setDefaultValues

```php
mixed AdminImportControllerCore::setDefaultValues($info)
```





* Visibility: **private**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 703](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L703)


#### Arguments
* $info **mixed**



### <a name="method-setEntityDefaultValues"></a>setEntityDefaultValues

```php
mixed AdminImportControllerCore::setEntityDefaultValues($entity)
```





* Visibility: **private**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 710](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L710)


#### Arguments
* $entity **mixed**



### <a name="method-setHelperDisplay"></a>setHelperDisplay

```php
void AdminControllerCore::setHelperDisplay(\Helper $helper)
```

this function set various display option for helper list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1500](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1500)


#### Arguments
* $helper **[Helper](class.HelperCore.md)**



### <a name="method-setLocale"></a>setLocale

```php
mixed AdminImportControllerCore::setLocale()
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 2252](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L2252)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminControllerCore::setMedia()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1544](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L1544)




### <a name="method-setTemplate"></a>setTemplate

```php
mixed ControllerCore::setTemplate($template)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/Controller.php#L203)


#### Arguments
* $template **mixed**



### <a name="method-split"></a>split

```php
mixed AdminImportControllerCore::split($field)
```





* Visibility: **private**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 606](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L606)


#### Arguments
* $field **mixed**



### <a name="method-supplierImport"></a>supplierImport

```php
mixed AdminImportControllerCore::supplierImport()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 1776](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L1776)




### <a name="method-supplyOrdersDetailsImport"></a>supplyOrdersDetailsImport

```php
mixed AdminImportControllerCore::supplyOrdersDetailsImport()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 1933](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L1933)




### <a name="method-supplyOrdersImport"></a>supplyOrdersImport

```php
mixed AdminImportControllerCore::supplyOrdersImport()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 1837](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L1837)




### <a name="method-truncateTables"></a>truncateTables

```php
mixed AdminImportControllerCore::truncateTables($case)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImportController.php line 2098](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L2098)


#### Arguments
* $case **mixed**



### <a name="method-updateAssoShop"></a>updateAssoShop

```php
mixed AdminControllerCore::updateAssoShop(integer $id_object, integer $new_id_object)
```

Update the associations of shops



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2339](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2339)


#### Arguments
* $id_object **integer**
* $new_id_object **integer**



### <a name="method-uploadImage"></a>uploadImage

```php
mixed AdminControllerCore::uploadImage($id, $name, $dir, $ext, $width, $height)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2403](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2403)


#### Arguments
* $id **mixed**
* $name **mixed**
* $dir **mixed**
* $ext **mixed**
* $width **mixed**
* $height **mixed**



### <a name="method-usortFiles"></a>usortFiles

```php
mixed AdminImportControllerCore::usortFiles($a, $b)
```





* Visibility: **private**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 2068](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L2068)


#### Arguments
* $a **mixed**
* $b **mixed**



### <a name="method-utf8EncodeArray"></a>utf8EncodeArray

```php
mixed AdminImportControllerCore::utf8EncodeArray($array)
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 2050](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/controllers/admin/AdminImportController.php#L2050)


#### Arguments
* $array **mixed**



### <a name="method-validateField"></a>validateField

```php
mixed AdminControllerCore::validateField($value, $field)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2361](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2361)


#### Arguments
* $value **mixed**
* $field **mixed**



### <a name="method-validateRules"></a>validateRules

```php
mixed AdminControllerCore::validateRules($class_name)
```

Manage page display (form, list.

..)

* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2128](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2128)


#### Arguments
* $class_name **mixed**



### <a name="method-viewAccess"></a>viewAccess

```php
boolean AdminControllerCore::viewAccess(boolean $disable)
```

Check rights to view the current tab



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 353](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L353)


#### Arguments
* $disable **boolean**



### <a name="method-viewDetails"></a>viewDetails

```php
mixed AdminControllerCore::viewDetails()
```

Display object details



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2221](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/controller/AdminController.php#L2221)



