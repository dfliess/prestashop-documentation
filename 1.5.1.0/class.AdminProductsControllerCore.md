Class AdminProductsControllerCore
=====================





* Class name: AdminProductsControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminProductsController.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L28)


Contents
--------


### Properties

* [$_category](#property-$_category)
* [$available_tabs](#property-$available_tabs)
* [$available_tabs_lang](#property-$available_tabs_lang)
* [$default_tab](#property-$default_tab)
* [$max_file_size](#property-$max_file_size)
* [$max_image_size](#property-$max_image_size)
* [$position_identifier](#property-$position_identifier)
* [$submitted_tabs](#property-$submitted_tabs)
* [$tab_display](#property-$tab_display)
* [$tab_display_module](#property-$tab_display_module)
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
* [$_listsql](#property-$_listsql)
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
* [$addons_url](#property-$addons_url)
* [$allow_employee_form_lang](#property-$allow_employee_form_lang)
* [$base_tpl_form](#property-$base_tpl_form)
* [$base_tpl_view](#property-$base_tpl_view)
* [$bo_theme](#property-$bo_theme)
* [$boxes](#property-$boxes)
* [$breadcrumbs](#property-$breadcrumbs)
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
* [$explicitSelect](#property-$explicitSelect)
* [$fieldImageSettings](#property-$fieldImageSettings)
* [$fields_form](#property-$fields_form)
* [$fields_form_override](#property-$fields_form_override)
* [$fields_list](#property-$fields_list)
* [$fields_options](#property-$fields_options)
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
* [$multishop_context_group](#property-$multishop_context_group)
* [$noLink](#property-$noLink)
* [$object](#property-$object)
* [$path](#property-$path)
* [$required_database](#property-$required_database)
* [$required_fields](#property-$required_fields)
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
* [_applyTaxToEcotax](#method-_applyTaxToEcotax)
* [_childValidation](#method-_childValidation)
* [_cleanMetaKeywords](#method-_cleanMetaKeywords)
* [_displayDraftWarning](#method-_displayDraftWarning)
* [_displayLabelField](#method-_displayLabelField)
* [_displayLabelFields](#method-_displayLabelFields)
* [_displaySpecificPriceModificationForm](#method-_displaySpecificPriceModificationForm)
* [_displayUnavailableProductWarning](#method-_displayUnavailableProductWarning)
* [_getCustomizationFieldIds](#method-_getCustomizationFieldIds)
* [_getFinalPrice](#method-_getFinalPrice)
* [_removeTaxFromEcotax](#method-_removeTaxFromEcotax)
* [_validateSpecificPrice](#method-_validateSpecificPrice)
* [addCSS](#method-addCSS)
* [addCarriers](#method-addCarriers)
* [addJS](#method-addJS)
* [addJquery](#method-addJquery)
* [addJqueryPlugin](#method-addJqueryPlugin)
* [addJqueryUI](#method-addJqueryUI)
* [addProductImage](#method-addProductImage)
* [addRowAction](#method-addRowAction)
* [addRowActionSkipList](#method-addRowActionSkipList)
* [addonsRequest](#method-addonsRequest)
* [afterAdd](#method-afterAdd)
* [afterDelete](#method-afterDelete)
* [afterImageUpload](#method-afterImageUpload)
* [afterUpdate](#method-afterUpdate)
* [ajaxPreProcess](#method-ajaxPreProcess)
* [ajaxProcessAddImage](#method-ajaxProcessAddImage)
* [ajaxProcessCheckProductName](#method-ajaxProcessCheckProductName)
* [ajaxProcessDefaultProductAttribute](#method-ajaxProcessDefaultProductAttribute)
* [ajaxProcessDeleteProductAttribute](#method-ajaxProcessDeleteProductAttribute)
* [ajaxProcessDeleteProductImage](#method-ajaxProcessDeleteProductImage)
* [ajaxProcessDeleteSpecificPrice](#method-ajaxProcessDeleteSpecificPrice)
* [ajaxProcessDeleteVirtualProduct](#method-ajaxProcessDeleteVirtualProduct)
* [ajaxProcessEditProductAttribute](#method-ajaxProcessEditProductAttribute)
* [ajaxProcessHelpAccess](#method-ajaxProcessHelpAccess)
* [ajaxProcessProductManufacturers](#method-ajaxProcessProductManufacturers)
* [ajaxProcessProductQuantity](#method-ajaxProcessProductQuantity)
* [ajaxProcessPublishProduct](#method-ajaxProcessPublishProduct)
* [ajaxProcessUpdateCover](#method-ajaxProcessUpdateCover)
* [ajaxProcessUpdateImagePosition](#method-ajaxProcessUpdateImagePosition)
* [ajaxProcessUpdatePositions](#method-ajaxProcessUpdatePositions)
* [ajaxProcessUpdateProductImageShopAsso](#method-ajaxProcessUpdateProductImageShopAsso)
* [beforeAdd](#method-beforeAdd)
* [beforeDelete](#method-beforeDelete)
* [beforeUpdateOptions](#method-beforeUpdateOptions)
* [checkAccess](#method-checkAccess)
* [checkFeatures](#method-checkFeatures)
* [checkProduct](#method-checkProduct)
* [checkToken](#method-checkToken)
* [copyFromPost](#method-copyFromPost)
* [copyImage](#method-copyImage)
* [createTemplate](#method-createTemplate)
* [display](#method-display)
* [displayAjax](#method-displayAjax)
* [displayFooter](#method-displayFooter)
* [displayHeader](#method-displayHeader)
* [displayInformation](#method-displayInformation)
* [displayNoSmarty](#method-displayNoSmarty)
* [displayRequiredFields](#method-displayRequiredFields)
* [displayWarning](#method-displayWarning)
* [filterToField](#method-filterToField)
* [getCarrierList](#method-getCarrierList)
* [getCombinationImagesJS](#method-getCombinationImagesJS)
* [getController](#method-getController)
* [getFieldValue](#method-getFieldValue)
* [getFieldsValue](#method-getFieldsValue)
* [getL](#method-getL)
* [getLanguages](#method-getLanguages)
* [getList](#method-getList)
* [getPackItems](#method-getPackItems)
* [getPreviewUrl](#method-getPreviewUrl)
* [getSelectedAssoShop](#method-getSelectedAssoShop)
* [haveThisAccessory](#method-haveThisAccessory)
* [init](#method-init)
* [initBreadcrumbs](#method-initBreadcrumbs)
* [initContent](#method-initContent)
* [initCursedPage](#method-initCursedPage)
* [initFooter](#method-initFooter)
* [initFormAssociations](#method-initFormAssociations)
* [initFormAttachments](#method-initFormAttachments)
* [initFormAttributes](#method-initFormAttributes)
* [initFormCombinations](#method-initFormCombinations)
* [initFormCustomization](#method-initFormCustomization)
* [initFormFeatures](#method-initFormFeatures)
* [initFormImages](#method-initFormImages)
* [initFormInformations](#method-initFormInformations)
* [initFormModules](#method-initFormModules)
* [initFormPack](#method-initFormPack)
* [initFormPrices](#method-initFormPrices)
* [initFormQuantities](#method-initFormQuantities)
* [initFormSeo](#method-initFormSeo)
* [initFormShipping](#method-initFormShipping)
* [initFormSuppliers](#method-initFormSuppliers)
* [initFormVirtualProduct](#method-initFormVirtualProduct)
* [initFormWarehouses](#method-initFormWarehouses)
* [initHeader](#method-initHeader)
* [initPack](#method-initPack)
* [initProcess](#method-initProcess)
* [initShopContext](#method-initShopContext)
* [initToolbar](#method-initToolbar)
* [initToolbarTitle](#method-initToolbarTitle)
* [isFresh](#method-isFresh)
* [isProductFieldUpdated](#method-isProductFieldUpdated)
* [isTabSubmitted](#method-isTabSubmitted)
* [isXmlHttpRequest](#method-isXmlHttpRequest)
* [jsonConfirmation](#method-jsonConfirmation)
* [jsonError](#method-jsonError)
* [l](#method-l)
* [loadObject](#method-loadObject)
* [postImage](#method-postImage)
* [postProcess](#method-postProcess)
* [processAdd](#method-processAdd)
* [processAddAttachments](#method-processAddAttachments)
* [processAttachments](#method-processAttachments)
* [processBulkAffectZone](#method-processBulkAffectZone)
* [processBulkDelete](#method-processBulkDelete)
* [processBulkDisableSelection](#method-processBulkDisableSelection)
* [processBulkEnableSelection](#method-processBulkEnableSelection)
* [processBulkStatusSelection](#method-processBulkStatusSelection)
* [processCustomizationConfiguration](#method-processCustomizationConfiguration)
* [processDelete](#method-processDelete)
* [processDeleteImage](#method-processDeleteImage)
* [processDuplicate](#method-processDuplicate)
* [processFeatures](#method-processFeatures)
* [processFilter](#method-processFilter)
* [processImage](#method-processImage)
* [processPosition](#method-processPosition)
* [processPriceAddition](#method-processPriceAddition)
* [processPricesModification](#method-processPricesModification)
* [processProductAttribute](#method-processProductAttribute)
* [processProductCustomization](#method-processProductCustomization)
* [processResetFilters](#method-processResetFilters)
* [processSave](#method-processSave)
* [processSpecificPricePriorities](#method-processSpecificPricePriorities)
* [processStatus](#method-processStatus)
* [processSuppliers](#method-processSuppliers)
* [processUpdate](#method-processUpdate)
* [processUpdateFields](#method-processUpdateFields)
* [processUpdateOptions](#method-processUpdateOptions)
* [processWarehouses](#method-processWarehouses)
* [recurseCategoryForInclude](#method-recurseCategoryForInclude)
* [redirect](#method-redirect)
* [refresh](#method-refresh)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [renderListAttributes](#method-renderListAttributes)
* [renderOptions](#method-renderOptions)
* [renderView](#method-renderView)
* [run](#method-run)
* [setHelperDisplay](#method-setHelperDisplay)
* [setMedia](#method-setMedia)
* [setTemplate](#method-setTemplate)
* [smartyOutputContent](#method-smartyOutputContent)
* [updateAccessories](#method-updateAccessories)
* [updateAssoShop](#method-updateAssoShop)
* [updateDownloadProduct](#method-updateDownloadProduct)
* [updatePackItems](#method-updatePackItems)
* [updateTags](#method-updateTags)
* [uploadImage](#method-uploadImage)
* [validateField](#method-validateField)
* [validateRules](#method-validateRules)
* [viewAccess](#method-viewAccess)
* [viewDetails](#method-viewDetails)




Properties
----------


### <a name="property-$_category"></a>$_category

```php
protected mixed $_category
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L36).


### <a name="property-$available_tabs"></a>$available_tabs

```php
protected array $available_tabs = array()
```

The order in the array decides the order in the list of tab. If an element's value is a number, it will be preloaded.

The tabs are preloaded from the smallest to the highest number.

* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L48).


### <a name="property-$available_tabs_lang"></a>$available_tabs_lang

```php
protected mixed $available_tabs_lang = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L52).


### <a name="property-$default_tab"></a>$default_tab

```php
protected mixed $default_tab = 'Informations'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L50).


### <a name="property-$max_file_size"></a>$max_file_size

```php
protected integer $max_file_size = null
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L33).


### <a name="property-$max_image_size"></a>$max_image_size

```php
protected mixed $max_image_size = null
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L34).


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected mixed $position_identifier = 'id_product'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L54).


### <a name="property-$submitted_tabs"></a>$submitted_tabs

```php
protected mixed $submitted_tabs
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L56).


### <a name="property-$tab_display"></a>$tab_display

```php
protected string $tab_display
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L40).


### <a name="property-$tab_display_module"></a>$tab_display_module

```php
protected mixed $tab_display_module
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L41).


### <a name="property-$_defaultOrderBy"></a>$_defaultOrderBy

```php
protected string $_defaultOrderBy = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L74).


### <a name="property-$_defaultOrderWay"></a>$_defaultOrderWay

```php
protected mixed $_defaultOrderWay = 'ASC'
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L75).


### <a name="property-$_filter"></a>$_filter

```php
protected array $_filter
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L140).


### <a name="property-$_group"></a>$_group

```php
protected string $_group
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L206).


### <a name="property-$_having"></a>$_having

```php
protected string $_having
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L209).


### <a name="property-$_includeContainer"></a>$_includeContainer

```php
protected mixed $_includeContainer = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L230).


### <a name="property-$_join"></a>$_join

```php
protected string $_join
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L200).


### <a name="property-$_languages"></a>$_languages

```php
public mixed $_languages = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L40).


### <a name="property-$_list"></a>$_list

```php
protected array $_list = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L116).


### <a name="property-$_listTotal"></a>$_listTotal

```php
protected integer $_listTotal
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L134).


### <a name="property-$_listsql"></a>$_listsql

```php
protected string $_listsql = ''
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L113).


### <a name="property-$_orderBy"></a>$_orderBy

```php
protected string $_orderBy
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L149).


### <a name="property-$_orderWay"></a>$_orderWay

```php
protected string $_orderWay
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L152).


### <a name="property-$_pagination"></a>$_pagination

```php
protected array $_pagination = array(20, 50, 100, 300)
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L146).


### <a name="property-$_redirect"></a>$_redirect

```php
protected boolean $_redirect = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L237).


### <a name="property-$_select"></a>$_select

```php
protected string $_select
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L197).


### <a name="property-$_tmpTableFilter"></a>$_tmpTableFilter

```php
protected array $_tmpTableFilter = ''
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L143).


### <a name="property-$_where"></a>$_where

```php
protected string $_where
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L203).


### <a name="property-$action"></a>$action

```php
protected mixed $action
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L228).


### <a name="property-$actions"></a>$actions

```php
protected array $actions = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L158).


### <a name="property-$actions_available"></a>$actions_available

```php
protected array $actions_available = array('view', 'edit', 'delete', 'duplicate')
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L155).


### <a name="property-$addons_url"></a>$addons_url

```php
protected mixed $addons_url = 'api.addons.prestashop.com'
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L38).


### <a name="property-$allow_employee_form_lang"></a>$allow_employee_form_lang

```php
public mixed $allow_employee_form_lang
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L42).


### <a name="property-$base_tpl_form"></a>$base_tpl_form

```php
public mixed $base_tpl_form = null
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L85).


### <a name="property-$base_tpl_view"></a>$base_tpl_view

```php
public mixed $base_tpl_view = null
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L84).


### <a name="property-$bo_theme"></a>$bo_theme

```php
protected mixed $bo_theme
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L234).


### <a name="property-$boxes"></a>$boxes

```php
protected array $boxes
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L191).


### <a name="property-$breadcrumbs"></a>$breadcrumbs

```php
protected mixed $breadcrumbs
```

Current breadcrumb position as an array of tab names



* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 262](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L262).


### <a name="property-$bulk_actions"></a>$bulk_actions

```php
protected array $bulk_actions
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L186).


### <a name="property-$cache_lang"></a>$cache_lang

```php
public array $cache_lang = array()
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L169).


### <a name="property-$className"></a>$className

```php
public string $className
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L57).


### <a name="property-$colorOnBackground"></a>$colorOnBackground

```php
protected mixed $colorOnBackground
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L224).


### <a name="property-$confirmations"></a>$confirmations

```php
public mixed $confirmations = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L35).


### <a name="property-$content"></a>$content

```php
public mixed $content
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L32).


### <a name="property-$controller_name"></a>$controller_name

```php
public \current $controller_name
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 254](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L254).


### <a name="property-$currentIndex"></a>$currentIndex

```php
public mixed $currentIndex
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L31).


### <a name="property-$default_form_language"></a>$default_form_language

```php
public mixed $default_form_language
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L41).


### <a name="property-$deleted"></a>$deleted

```php
protected boolean $deleted = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L217).


### <a name="property-$display"></a>$display

```php
protected mixed $display
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L229).


### <a name="property-$errors"></a>$errors

```php
public array $errors = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L93).


### <a name="property-$explicitSelect"></a>$explicitSelect

```php
protected string $explicitSelect = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L194).


### <a name="property-$fieldImageSettings"></a>$fieldImageSettings

```php
public array $fieldImageSettings = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L240).


### <a name="property-$fields_form"></a>$fields_form

```php
protected array $fields_form
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L102).


### <a name="property-$fields_form_override"></a>$fields_form_override

```php
protected \override $fields_form_override
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L105).


### <a name="property-$fields_list"></a>$fields_list

```php
protected array $fields_list
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L99).


### <a name="property-$fields_options"></a>$fields_options

```php
protected array $fields_options
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L108).


### <a name="property-$fields_value"></a>$fields_value

```php
public mixed $fields_value = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L90).


### <a name="property-$filter"></a>$filter

```php
protected boolean $filter
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L221).


### <a name="property-$id"></a>$id

```php
public integer $id = -1
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L63).


### <a name="property-$id_object"></a>$id_object

```php
protected \current $id_object
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L249).


### <a name="property-$identifier"></a>$identifier

```php
protected string $identifier = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L54).


### <a name="property-$imageType"></a>$imageType

```php
public string $imageType = 'jpg'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L243).


### <a name="property-$informations"></a>$informations

```php
public mixed $informations = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L34).


### <a name="property-$is_cms"></a>$is_cms

```php
protected mixed $is_cms = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L211).


### <a name="property-$lang"></a>$lang

```php
public boolean $lang = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L137).


### <a name="property-$layout"></a>$layout

```php
public mixed $layout = 'layout.tpl'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L44).


### <a name="property-$list_no_link"></a>$list_no_link

```php
protected boolean $list_no_link = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L166).


### <a name="property-$list_simple_header"></a>$list_simple_header

```php
protected \define $list_simple_header
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L96).


### <a name="property-$list_skip_actions"></a>$list_skip_actions

```php
protected array $list_skip_actions = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L161).


### <a name="property-$lite_display"></a>$lite_display

```php
protected mixed $lite_display = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L164).


### <a name="property-$meta_title"></a>$meta_title

```php
protected mixed $meta_title
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L46).


### <a name="property-$multiple_fieldsets"></a>$multiple_fieldsets

```php
public boolean $multiple_fieldsets = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L88).


### <a name="property-$multishop_context"></a>$multishop_context

```php
public mixed $multishop_context = -1
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L256).


### <a name="property-$multishop_context_group"></a>$multishop_context_group

```php
public mixed $multishop_context_group = true
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L257).


### <a name="property-$noLink"></a>$noLink

```php
protected mixed $noLink
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L222).


### <a name="property-$object"></a>$object

```php
protected \instanciation $object
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L246).


### <a name="property-$path"></a>$path

```php
public mixed $path
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L30).


### <a name="property-$required_database"></a>$required_database

```php
public mixed $required_database = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L65).


### <a name="property-$required_fields"></a>$required_fields

```php
public array $required_fields = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L172).


### <a name="property-$row_hover"></a>$row_hover

```php
protected boolean $row_hover = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L226).


### <a name="property-$shopLink"></a>$shopLink

```php
protected mixed $shopLink
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L110).


### <a name="property-$shopLinkType"></a>$shopLinkType

```php
public string $shopLinkType
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L71).


### <a name="property-$shopShareDatas"></a>$shopShareDatas

```php
public mixed $shopShareDatas = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L36).


### <a name="property-$show_toolbar"></a>$show_toolbar

```php
protected boolean $show_toolbar = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L128).


### <a name="property-$show_toolbar_options"></a>$show_toolbar_options

```php
protected boolean $show_toolbar_options = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L131).


### <a name="property-$specificConfirmDelete"></a>$specificConfirmDelete

```php
protected mixed $specificConfirmDelete = null
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L223).


### <a name="property-$tabAccess"></a>$tabAccess

```php
public array $tabAccess
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L60).


### <a name="property-$table"></a>$table

```php
public string $table
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L51).


### <a name="property-$template"></a>$template

```php
public mixed $template = 'content.tpl'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L48).


### <a name="property-$token"></a>$token

```php
public string $token
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L68).


### <a name="property-$toolbar_btn"></a>$toolbar_btn

```php
protected array $toolbar_btn = null
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L122).


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

```php
protected boolean $toolbar_scroll = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L125).


### <a name="property-$toolbar_title"></a>$toolbar_title

```php
protected \define $toolbar_title
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L119).


### <a name="property-$tpl_delete_link_vars"></a>$tpl_delete_link_vars

```php
public mixed $tpl_delete_link_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L79).


### <a name="property-$tpl_folder"></a>$tpl_folder

```php
public mixed $tpl_folder
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L232).


### <a name="property-$tpl_form_vars"></a>$tpl_form_vars

```php
public mixed $tpl_form_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L77).


### <a name="property-$tpl_list_vars"></a>$tpl_list_vars

```php
public mixed $tpl_list_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L78).


### <a name="property-$tpl_option_vars"></a>$tpl_option_vars

```php
public mixed $tpl_option_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L80).


### <a name="property-$tpl_required_fields_vars"></a>$tpl_required_fields_vars

```php
public mixed $tpl_required_fields_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L82).


### <a name="property-$tpl_view_vars"></a>$tpl_view_vars

```php
public mixed $tpl_view_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L81).


### <a name="property-$warnings"></a>$warnings

```php
public mixed $warnings = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L33).


### <a name="property-$ajax"></a>$ajax

```php
public boolean $ajax = false
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L71).


### <a name="property-$content_only"></a>$content_only

```php
protected string $content_only = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L66).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L36).


### <a name="property-$controller_type"></a>$controller_type

```php
public mixed $controller_type
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L77).


### <a name="property-$css_files"></a>$css_files

```php
public array $css_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L41).


### <a name="property-$display_footer"></a>$display_footer

```php
protected string $display_footer
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L61).


### <a name="property-$display_header"></a>$display_header

```php
protected boolean $display_header
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L51).


### <a name="property-$js_files"></a>$js_files

```php
public array $js_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L46).


### <a name="property-$json"></a>$json

```php
protected mixed $json = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L72).


### <a name="property-$redirect_after"></a>$redirect_after

```php
protected mixed $redirect_after = null
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L75).


### <a name="property-$status"></a>$status

```php
protected mixed $status = ''
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L73).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminProductsControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L58)




### <a name="method-_applyTaxToEcotax"></a>_applyTaxToEcotax

```php
mixed AdminProductsControllerCore::_applyTaxToEcotax($product)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1917](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1917)


#### Arguments
* $product **mixed**



### <a name="method-_childValidation"></a>_childValidation

```php
mixed AdminControllerCore::_childValidation()
```

Overload this method for custom checking



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2293](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2293)




### <a name="method-_cleanMetaKeywords"></a>_cleanMetaKeywords

```php
mixed AdminProductsControllerCore::_cleanMetaKeywords($keywords)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L257)


#### Arguments
* $keywords **mixed**



### <a name="method-_displayDraftWarning"></a>_displayDraftWarning

```php
mixed AdminProductsControllerCore::_displayDraftWarning($active)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2191](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2191)


#### Arguments
* $active **mixed**



### <a name="method-_displayLabelField"></a>_displayLabelField

```php
mixed AdminProductsControllerCore::_displayLabelField($label, $languages, $default_language, $type, $fieldIds, $id_customization_field)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3165](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L3165)


#### Arguments
* $label **mixed**
* $languages **mixed**
* $default_language **mixed**
* $type **mixed**
* $fieldIds **mixed**
* $id_customization_field **mixed**



### <a name="method-_displayLabelFields"></a>_displayLabelFields

```php
mixed AdminProductsControllerCore::_displayLabelFields($obj, $labels, $languages, $default_language, $type)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3188](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L3188)


#### Arguments
* $obj **mixed**
* $labels **mixed**
* $languages **mixed**
* $default_language **mixed**
* $type **mixed**



### <a name="method-_displaySpecificPriceModificationForm"></a>_displaySpecificPriceModificationForm

```php
mixed AdminProductsControllerCore::_displaySpecificPriceModificationForm($defaultCurrency, $shops, $currencies, $countries, $groups)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2966](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2966)


#### Arguments
* $defaultCurrency **mixed**
* $shops **mixed**
* $currencies **mixed**
* $countries **mixed**
* $groups **mixed**



### <a name="method-_displayUnavailableProductWarning"></a>_displayUnavailableProductWarning

```php
mixed AdminProductsControllerCore::_displayUnavailableProductWarning()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 4123](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L4123)




### <a name="method-_getCustomizationFieldIds"></a>_getCustomizationFieldIds

```php
mixed AdminProductsControllerCore::_getCustomizationFieldIds($labels, $alreadyGenerated, $obj)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3147](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L3147)


#### Arguments
* $labels **mixed**
* $alreadyGenerated **mixed**
* $obj **mixed**



### <a name="method-_getFinalPrice"></a>_getFinalPrice

```php
mixed AdminProductsControllerCore::_getFinalPrice($specific_price, $product_price, $tax_rate)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2961](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2961)


#### Arguments
* $specific_price **mixed**
* $product_price **mixed**
* $tax_rate **mixed**



### <a name="method-_removeTaxFromEcotax"></a>_removeTaxFromEcotax

```php
mixed AdminProductsControllerCore::_removeTaxFromEcotax()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1910](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1910)




### <a name="method-_validateSpecificPrice"></a>_validateSpecificPrice

```php
mixed AdminProductsControllerCore::_validateSpecificPrice($id_shop, $id_currency, $id_country, $id_group, $id_customer, $price, $from_quantity, $reduction, $reduction_type, $from, $to, $id_combination)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1426](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1426)


#### Arguments
* $id_shop **mixed**
* $id_currency **mixed**
* $id_country **mixed**
* $id_group **mixed**
* $id_customer **mixed**
* $price **mixed**
* $from_quantity **mixed**
* $reduction **mixed**
* $reduction_type **mixed**
* $from **mixed**
* $to **mixed**
* $id_combination **mixed**



### <a name="method-addCSS"></a>addCSS

```php
true ControllerCore::addCSS(mixed $css_uri, string $css_media_type)
```

Add a new stylesheet in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L237)


#### Arguments
* $css_uri **mixed** - Path to css file, or list of css files like this : array(array(uri =&gt; media_type), ...)
* $css_media_type **string**



### <a name="method-addCarriers"></a>addCarriers

```php
mixed AdminProductsControllerCore::addCarriers()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3394](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L3394)




### <a name="method-addJS"></a>addJS

```php
void ControllerCore::addJS(mixed $js_uri)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L269)


#### Arguments
* $js_uri **mixed**



### <a name="method-addJquery"></a>addJquery

```php
void ControllerCore::addJquery($version, $folder, $minifier)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 292](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L292)


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
* Source: [classes/controller/Controller.php line 323](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L323)


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
* Source: [classes/controller/Controller.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L303)


#### Arguments
* $component **mixed**
* $theme **mixed**
* $check_dependencies **mixed**



### <a name="method-addProductImage"></a>addProductImage

```php
mixed AdminProductsControllerCore::addProductImage(object $product, $method)
```

Add or update a product image



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1481](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1481)


#### Arguments
* $product **object** - Product object to add image
* $method **mixed**



### <a name="method-addRowAction"></a>addRowAction

```php
mixed AdminControllerCore::addRowAction($action)
```

Declare an action to use for each row in the list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1359](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L1359)


#### Arguments
* $action **mixed**



### <a name="method-addRowActionSkipList"></a>addRowActionSkipList

```php
mixed AdminControllerCore::addRowActionSkipList($action, $list)
```

Add  an action to use for each row in the list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1368](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L1368)


#### Arguments
* $action **mixed**
* $list **mixed**



### <a name="method-addonsRequest"></a>addonsRequest

```php
mixed AdminControllerCore::addonsRequest($request, $params)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2719](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2719)


#### Arguments
* $request **mixed**
* $params **mixed**



### <a name="method-afterAdd"></a>afterAdd

```php
mixed AdminControllerCore::afterAdd($object)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2326](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2326)


#### Arguments
* $object **mixed**



### <a name="method-afterDelete"></a>afterDelete

```php
boolean AdminControllerCore::afterDelete(object $object, $oldId)
```

Called before deletion



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2321](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2321)


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
* Source: [classes/controller/AdminController.php line 2342](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2342)




### <a name="method-afterUpdate"></a>afterUpdate

```php
mixed AdminControllerCore::afterUpdate($object)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2331](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2331)


#### Arguments
* $object **mixed**



### <a name="method-ajaxPreProcess"></a>ajaxPreProcess

```php
mixed AdminProductsControllerCore::ajaxPreProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1331](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1331)




### <a name="method-ajaxProcessAddImage"></a>ajaxProcessAddImage

```php
mixed AdminProductsControllerCore::ajaxProcessAddImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1212](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1212)




### <a name="method-ajaxProcessCheckProductName"></a>ajaxProcessCheckProductName

```php
mixed AdminProductsControllerCore::ajaxProcessCheckProductName()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4138](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L4138)




### <a name="method-ajaxProcessDefaultProductAttribute"></a>ajaxProcessDefaultProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessDefaultProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1288](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1288)




### <a name="method-ajaxProcessDeleteProductAttribute"></a>ajaxProcessDeleteProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1247](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1247)




### <a name="method-ajaxProcessDeleteProductImage"></a>ajaxProcessDeleteProductImage

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteProductImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1396](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1396)




### <a name="method-ajaxProcessDeleteSpecificPrice"></a>ajaxProcessDeleteSpecificPrice

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteSpecificPrice()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 884](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L884)




### <a name="method-ajaxProcessDeleteVirtualProduct"></a>ajaxProcessDeleteVirtualProduct

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteVirtualProduct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 343](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L343)




### <a name="method-ajaxProcessEditProductAttribute"></a>ajaxProcessEditProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessEditProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1314](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1314)




### <a name="method-ajaxProcessHelpAccess"></a>ajaxProcessHelpAccess

```php
mixed AdminControllerCore::ajaxProcessHelpAccess()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 397](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L397)




### <a name="method-ajaxProcessProductManufacturers"></a>ajaxProcessProductManufacturers

```php
mixed AdminProductsControllerCore::ajaxProcessProductManufacturers()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2135](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2135)




### <a name="method-ajaxProcessProductQuantity"></a>ajaxProcessProductQuantity

```php
mixed AdminProductsControllerCore::ajaxProcessProductQuantity()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3959](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L3959)




### <a name="method-ajaxProcessPublishProduct"></a>ajaxProcessPublishProduct

```php
mixed AdminProductsControllerCore::ajaxProcessPublishProduct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4191](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L4191)




### <a name="method-ajaxProcessUpdateCover"></a>ajaxProcessUpdateCover

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateCover()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1381](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1381)




### <a name="method-ajaxProcessUpdateImagePosition"></a>ajaxProcessUpdateImagePosition

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateImagePosition()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1360](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1360)




### <a name="method-ajaxProcessUpdatePositions"></a>ajaxProcessUpdatePositions

```php
mixed AdminProductsControllerCore::ajaxProcessUpdatePositions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4161](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L4161)




### <a name="method-ajaxProcessUpdateProductImageShopAsso"></a>ajaxProcessUpdateProductImageShopAsso

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateProductImageShopAsso()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1340](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1340)




### <a name="method-beforeAdd"></a>beforeAdd

```php
boolean AdminControllerCore::beforeAdd(object $object)
```

Called before Add



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2633](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2633)


#### Arguments
* $object **object** - Object



### <a name="method-beforeDelete"></a>beforeDelete

```php
boolean AdminControllerCore::beforeDelete(object $object)
```

Called before deletion



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2310](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2310)


#### Arguments
* $object **object** - Object



### <a name="method-beforeUpdateOptions"></a>beforeUpdateOptions

```php
mixed AdminControllerCore::beforeUpdateOptions()
```

Can be overriden



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2456](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2456)




### <a name="method-checkAccess"></a>checkAccess

```php
mixed AdminControllerCore::checkAccess()
```

Check if the token is valid, else display a warning page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1071](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L1071)




### <a name="method-checkFeatures"></a>checkFeatures

```php
mixed AdminProductsControllerCore::checkFeatures($languages, $feature_id)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1446](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1446)


#### Arguments
* $languages **mixed**
* $feature_id **mixed**



### <a name="method-checkProduct"></a>checkProduct

```php
mixed AdminProductsControllerCore::checkProduct()
```

Check that a saved product is valid



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1770](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1770)




### <a name="method-checkToken"></a>checkToken

```php
mixed AdminControllerCore::checkToken()
```

Check for security token



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 391](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L391)




### <a name="method-copyFromPost"></a>copyFromPost

```php
mixed AdminProductsControllerCore::copyFromPost($object, $table)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L275)


#### Arguments
* $object **mixed**
* $table **mixed**



### <a name="method-copyImage"></a>copyImage

```php
mixed AdminProductsControllerCore::copyImage(integer $id_product, integer $id_image, $method)
```

Copy a product image



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1516](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1516)


#### Arguments
* $id_product **integer** - Product Id for product image filename
* $id_image **integer** - Image Id for product image filename
* $method **mixed**



### <a name="method-createTemplate"></a>createTemplate

```php
\Template AdminControllerCore::createTemplate(string $tpl_name)
```

Create a template from the override file, else from the base file.



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2658](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2658)


#### Arguments
* $tpl_name **string** - filename



### <a name="method-display"></a>display

```php
mixed AdminControllerCore::display()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1122](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L1122)




### <a name="method-displayAjax"></a>displayAjax

```php
mixed AdminControllerCore::displayAjax()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1104](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L1104)




### <a name="method-displayFooter"></a>displayFooter

```php
mixed ControllerCore::displayFooter($display)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L200)


#### Arguments
* $display **mixed**



### <a name="method-displayHeader"></a>displayHeader

```php
mixed ControllerCore::displayHeader($display)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L195)


#### Arguments
* $display **mixed**



### <a name="method-displayInformation"></a>displayInformation

```php
mixed AdminControllerCore::displayInformation(string $msg)
```

add a info message to display at the top of the page



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1204](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L1204)


#### Arguments
* $msg **string**



### <a name="method-displayNoSmarty"></a>displayNoSmarty

```php
mixed AdminControllerCore::displayNoSmarty()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1100](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L1100)




### <a name="method-displayRequiredFields"></a>displayRequiredFields

```php
mixed AdminControllerCore::displayRequiredFields()
```

prepare the view to display the required fields form



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2641](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2641)




### <a name="method-displayWarning"></a>displayWarning

```php
mixed AdminControllerCore::displayWarning(string $msg)
```

add a warning message to display at the top of the page



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1194](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L1194)


#### Arguments
* $msg **string**



### <a name="method-filterToField"></a>filterToField

```php
mixed AdminControllerCore::filterToField($key, $filter)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1090](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L1090)


#### Arguments
* $key **mixed**
* $filter **mixed**



### <a name="method-getCarrierList"></a>getCarrierList

```php
mixed AdminProductsControllerCore::getCarrierList()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3377](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L3377)




### <a name="method-getCombinationImagesJS"></a>getCombinationImagesJS

```php
mixed AdminProductsControllerCore::getCombinationImagesJS()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4017](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L4017)




### <a name="method-getController"></a>getController

```php
mixed ControllerCore::getController(string $class_name, boolean $auth, boolean $ssl)
```

Get an instance of a controller



* Visibility: **public**
* This method is **static**.
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L127)


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
* Source: [classes/controller/AdminController.php line 2179](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2179)


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
* Source: [classes/controller/AdminController.php line 2129](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2129)


#### Arguments
* $obj **object** - Object



### <a name="method-getL"></a>getL

```php
mixed AdminProductsControllerCore::getL($key)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4110](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L4110)


#### Arguments
* $key **mixed**



### <a name="method-getLanguages"></a>getLanguages

```php
mixed AdminControllerCore::getLanguages()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2099](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2099)




### <a name="method-getList"></a>getList

```php
mixed AdminProductsControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 305](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L305)


#### Arguments
* $id_lang **mixed**
* $orderBy **mixed**
* $orderWay **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-getPackItems"></a>getPackItems

```php
array AdminProductsControllerCore::getPackItems(\Product $product)
```

Get an array of pack items for display from the product object if specified, else from POST/GET values



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2839](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2839)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-getPreviewUrl"></a>getPreviewUrl

```php
mixed AdminProductsControllerCore::getPreviewUrl(\Product $product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2417](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2417)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-getSelectedAssoShop"></a>getSelectedAssoShop

```php
array AdminControllerCore::getSelectedAssoShop(string $table)
```

Returns an array with selected shops and type (group or boutique shop)



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2386](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2386)


#### Arguments
* $table **string**



### <a name="method-haveThisAccessory"></a>haveThisAccessory

```php
mixed AdminProductsControllerCore::haveThisAccessory($accessory_id, $accessories)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4035](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L4035)


#### Arguments
* $accessory_id **mixed**
* $accessories **mixed**



### <a name="method-init"></a>init

```php
mixed AdminControllerCore::init()
```

Init context and dependencies, handles POST and GET



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1661](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L1661)




### <a name="method-initBreadcrumbs"></a>initBreadcrumbs

```php
mixed AdminControllerCore::initBreadcrumbs()
```

Set breadcrumbs array for the controller page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 337](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L337)




### <a name="method-initContent"></a>initContent

```php
mixed AdminProductsControllerCore::initContent($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2048](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2048)


#### Arguments
* $token **mixed**



### <a name="method-initCursedPage"></a>initCursedPage

```php
void AdminControllerCore::initCursedPage()
```

initialize the invalid doom page of death



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1429](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L1429)




### <a name="method-initFooter"></a>initFooter

```php
mixed AdminControllerCore::initFooter()
```

Assign smarty variables for the footer



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1437](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L1437)




### <a name="method-initFormAssociations"></a>initFormAssociations

```php
mixed AdminProductsControllerCore::initFormAssociations($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2689](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2689)


#### Arguments
* $obj **mixed**



### <a name="method-initFormAttachments"></a>initFormAttachments

```php
mixed AdminProductsControllerCore::initFormAttachments($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3235](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L3235)


#### Arguments
* $obj **mixed**



### <a name="method-initFormAttributes"></a>initFormAttributes

```php
mixed AdminProductsControllerCore::initFormAttributes($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3470](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L3470)


#### Arguments
* $product **mixed**



### <a name="method-initFormCombinations"></a>initFormCombinations

```php
mixed AdminProductsControllerCore::initFormCombinations($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3465](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L3465)


#### Arguments
* $obj **mixed**



### <a name="method-initFormCustomization"></a>initFormCustomization

```php
mixed AdminProductsControllerCore::initFormCustomization($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3201](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L3201)


#### Arguments
* $obj **mixed**



### <a name="method-initFormFeatures"></a>initFormFeatures

```php
mixed AdminProductsControllerCore::initFormFeatures($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3910](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L3910)


#### Arguments
* $obj **mixed**



### <a name="method-initFormImages"></a>initFormImages

```php
mixed AdminProductsControllerCore::initFormImages($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3406](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L3406)


#### Arguments
* $obj **mixed**



### <a name="method-initFormInformations"></a>initFormInformations

```php
mixed AdminProductsControllerCore::initFormInformations($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3277](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L3277)


#### Arguments
* $product **mixed**



### <a name="method-initFormModules"></a>initFormModules

```php
mixed AdminProductsControllerCore::initFormModules($obj)
```

AdminProducts display hook



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4069](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L4069)


#### Arguments
* $obj **mixed**



### <a name="method-initFormPack"></a>initFormPack

```php
mixed AdminProductsControllerCore::initFormPack($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2880](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2880)


#### Arguments
* $product **mixed**



### <a name="method-initFormPrices"></a>initFormPrices

```php
mixed AdminProductsControllerCore::initFormPrices($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2747](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2747)


#### Arguments
* $obj **mixed**



### <a name="method-initFormQuantities"></a>initFormQuantities

```php
mixed AdminProductsControllerCore::initFormQuantities($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3640](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L3640)


#### Arguments
* $obj **mixed**



### <a name="method-initFormSeo"></a>initFormSeo

```php
mixed AdminProductsControllerCore::initFormSeo($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2818](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2818)


#### Arguments
* $product **mixed**



### <a name="method-initFormShipping"></a>initFormShipping

```php
mixed AdminProductsControllerCore::initFormShipping($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3363](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L3363)


#### Arguments
* $obj **mixed**



### <a name="method-initFormSuppliers"></a>initFormSuppliers

```php
mixed AdminProductsControllerCore::initFormSuppliers($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3782](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L3782)


#### Arguments
* $obj **mixed**



### <a name="method-initFormVirtualProduct"></a>initFormVirtualProduct

```php
mixed AdminProductsControllerCore::initFormVirtualProduct($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2915](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2915)


#### Arguments
* $product **mixed**



### <a name="method-initFormWarehouses"></a>initFormWarehouses

```php
mixed AdminProductsControllerCore::initFormWarehouses($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3860](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L3860)


#### Arguments
* $obj **mixed**



### <a name="method-initHeader"></a>initHeader

```php
mixed AdminControllerCore::initHeader()
```

Assign smarty variables for the header



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1212](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L1212)




### <a name="method-initPack"></a>initPack

```php
mixed AdminProductsControllerCore::initPack(\Product $product)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 4043](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L4043)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-initProcess"></a>initProcess

```php
mixed AdminProductsControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 991](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L991)




### <a name="method-initShopContext"></a>initShopContext

```php
mixed AdminControllerCore::initShopContext()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1719](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L1719)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminProductsControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2206](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2206)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

```php
mixed AdminProductsControllerCore::initToolbarTitle()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2282](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2282)




### <a name="method-isFresh"></a>isFresh

```php
mixed AdminControllerCore::isFresh($file, $timeout)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2699](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2699)


#### Arguments
* $file **mixed**
* $timeout **mixed**



### <a name="method-isProductFieldUpdated"></a>isProductFieldUpdated

```php
boolean AdminProductsControllerCore::isProductFieldUpdated(string $field, integer $id_lang)
```

Check if a field is edited (if the checkbox is checked)
This method will do something only for multishop with a context all / group



* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1894](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1894)


#### Arguments
* $field **string** - Name of field
* $id_lang **integer**



### <a name="method-isTabSubmitted"></a>isTabSubmitted

```php
mixed AdminProductsControllerCore::isTabSubmitted($tab_name)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1634](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1634)


#### Arguments
* $tab_name **mixed**



### <a name="method-isXmlHttpRequest"></a>isXmlHttpRequest

```php
boolean ControllerCore::isXmlHttpRequest()
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 346](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L346)




### <a name="method-jsonConfirmation"></a>jsonConfirmation

```php
mixed AdminControllerCore::jsonConfirmation($message)
```

Shortcut to set up a json success payload



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2678](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2678)


#### Arguments
* $message **mixed** - success message



### <a name="method-jsonError"></a>jsonError

```php
mixed AdminControllerCore::jsonError($message)
```

Shortcut to set up a json error payload



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2691](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2691)


#### Arguments
* $message **mixed** - error message



### <a name="method-l"></a>l

```php
string AdminControllerCore::l(mixed $string, string $class, \boolan $addslashes, boolean $htmlentities)
```

non-static method which uses AdminController::translate()



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1647](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L1647)


#### Arguments
* $string **mixed** - term or expression in english
* $class **string** - name of the class
* $addslashes **boolan** - if set to true, the return value will pass through addslashes(). Otherwise, stripslashes().
* $htmlentities **boolean** - if set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)



### <a name="method-loadObject"></a>loadObject

```php
object AdminProductsControllerCore::loadObject(boolean $opt)
```

Override parent to add stock data to object
We don't want to make a "full" product load because of side effects to prices



* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1145](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1145)


#### Arguments
* $opt **boolean** - Return an empty object if load fail



### <a name="method-postImage"></a>postImage

```php
boolean AdminControllerCore::postImage(integer $id)
```

Overload this method for custom checking



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2466](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2466)


#### Arguments
* $id **integer** - Object id used for deleting images



### <a name="method-postProcess"></a>postProcess

```php
void AdminProductsControllerCore::postProcess()
```

postProcess handle every checks before saving products information



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1164](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1164)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminProductsControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1553](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1553)




### <a name="method-processAddAttachments"></a>processAddAttachments

```php
void AdminProductsControllerCore::processAddAttachments()
```

Upload new attachment



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 362](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L362)




### <a name="method-processAttachments"></a>processAttachments

```php
void AdminProductsControllerCore::processAttachments()
```

Attach an existing attachment to the product



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 458](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L458)




### <a name="method-processBulkAffectZone"></a>processBulkAffectZone

```php
mixed AdminControllerCore::processBulkAffectZone()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2609](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2609)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
mixed AdminProductsControllerCore::processBulkDelete()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 598](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L598)




### <a name="method-processBulkDisableSelection"></a>processBulkDisableSelection

```php
boolean AdminControllerCore::processBulkDisableSelection()
```

Disable multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2584](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2584)




### <a name="method-processBulkEnableSelection"></a>processBulkEnableSelection

```php
boolean AdminControllerCore::processBulkEnableSelection()
```

Enable multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2574](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2574)




### <a name="method-processBulkStatusSelection"></a>processBulkStatusSelection

```php
boolean AdminControllerCore::processBulkStatusSelection($status)
```

Toggle status of multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2594](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2594)


#### Arguments
* $status **mixed**



### <a name="method-processCustomizationConfiguration"></a>processCustomizationConfiguration

```php
mixed AdminProductsControllerCore::processCustomizationConfiguration()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 932](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L932)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminProductsControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 518](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L518)




### <a name="method-processDeleteImage"></a>processDeleteImage

```php
mixed AdminControllerCore::processDeleteImage()
```

Object Delete images



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 552](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L552)




### <a name="method-processDuplicate"></a>processDuplicate

```php
mixed AdminProductsControllerCore::processDuplicate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 469](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L469)




### <a name="method-processFeatures"></a>processFeatures

```php
mixed AdminProductsControllerCore::processFeatures()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 758](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L758)




### <a name="method-processFilter"></a>processFilter

```php
mixed AdminControllerCore::processFilter()
```

Set the filters used for the list display



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 418](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L418)




### <a name="method-processImage"></a>processImage

```php
mixed AdminProductsControllerCore::processImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 555](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L555)




### <a name="method-processPosition"></a>processPosition

```php
mixed AdminProductsControllerCore::processPosition()
```

Overrides parent for custom redirect link



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 978](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L978)




### <a name="method-processPriceAddition"></a>processPriceAddition

```php
mixed AdminProductsControllerCore::processPriceAddition()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 840](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L840)




### <a name="method-processPricesModification"></a>processPricesModification

```php
mixed AdminProductsControllerCore::processPricesModification()
```

This function is never called at the moment (specific prices cannot be edited)



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 800](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L800)




### <a name="method-processProductAttribute"></a>processProductAttribute

```php
mixed AdminProductsControllerCore::processProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 658](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L658)




### <a name="method-processProductCustomization"></a>processProductCustomization

```php
mixed AdminProductsControllerCore::processProductCustomization()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 959](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L959)




### <a name="method-processResetFilters"></a>processResetFilters

```php
mixed AdminControllerCore::processResetFilters()
```

Cancel all filters for this tab



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 835](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L835)




### <a name="method-processSave"></a>processSave

```php
mixed AdminControllerCore::processSave()
```

Call the right method for creating or updating object



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 619](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L619)




### <a name="method-processSpecificPricePriorities"></a>processSpecificPricePriorities

```php
mixed AdminProductsControllerCore::processSpecificPricePriorities()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 915](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L915)




### <a name="method-processStatus"></a>processStatus

```php
mixed AdminControllerCore::processStatus()
```

Change object status (active, inactive)



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 791](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L791)




### <a name="method-processSuppliers"></a>processSuppliers

```php
mixed AdminProductsControllerCore::processSuppliers()
```

Post treatment for suppliers



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2459](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2459)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminProductsControllerCore::processUpdate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1645](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1645)




### <a name="method-processUpdateFields"></a>processUpdateFields

```php
mixed AdminControllerCore::processUpdateFields()
```

Change object required fields



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 774](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L774)




### <a name="method-processUpdateOptions"></a>processUpdateOptions

```php
mixed AdminControllerCore::processUpdateOptions()
```

Update options and preferences



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 868](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L868)




### <a name="method-processWarehouses"></a>processWarehouses

```php
mixed AdminProductsControllerCore::processWarehouses()
```

Post treatment for warehouses



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2612](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2612)




### <a name="method-recurseCategoryForInclude"></a>recurseCategoryForInclude

```php
mixed AdminProductsControllerCore::recurseCategoryForInclude($id_obj, array $indexedCategories, array $categories, array $current, integer $id_category, $id_category_default, $has_suite)
```

Build a categories tree



* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminProductsController.php line 2153](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2153)


#### Arguments
* $id_obj **mixed**
* $indexedCategories **array** - Array with categories where product is indexed (in order to check checkbox)
* $categories **array** - Categories to list
* $current **array** - Current category
* $id_category **integer** - Current category id
* $id_category_default **mixed**
* $has_suite **mixed**



### <a name="method-redirect"></a>redirect

```php
mixed AdminControllerCore::redirect()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1117](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L1117)




### <a name="method-refresh"></a>refresh

```php
mixed AdminControllerCore::refresh($file_to_refresh, $external_file)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2711](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2711)


#### Arguments
* $file_to_refresh **mixed**
* $external_file **mixed**



### <a name="method-renderForm"></a>renderForm

```php
void AdminProductsControllerCore::renderForm()
```

renderForm contains all necessary initialization needed for all tabs



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2295](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2295)




### <a name="method-renderList"></a>renderList

```php
mixed AdminProductsControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2127](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2127)




### <a name="method-renderListAttributes"></a>renderListAttributes

```php
mixed AdminProductsControllerCore::renderListAttributes($product, $currency)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3542](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L3542)


#### Arguments
* $product **mixed**
* $currency **mixed**



### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminControllerCore::renderOptions()
```

Function used to render the options for this controller



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1536](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L1536)




### <a name="method-renderView"></a>renderView

```php
mixed AdminControllerCore::renderView()
```

Override to render the view page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1484](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L1484)




### <a name="method-run"></a>run

```php
mixed ControllerCore::run()
```

Start controller process (this method shouldn't be overriden !)



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L149)




### <a name="method-setHelperDisplay"></a>setHelperDisplay

```php
void AdminControllerCore::setHelperDisplay(\Helper $helper)
```

this function set various display option for helper list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1563](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L1563)


#### Arguments
* $helper **[Helper](class.HelperCore.md)**



### <a name="method-setMedia"></a>setMedia

```php
mixed AdminControllerCore::setMedia()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1607](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L1607)




### <a name="method-setTemplate"></a>setTemplate

```php
mixed ControllerCore::setTemplate($template)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L205)


#### Arguments
* $template **mixed**



### <a name="method-smartyOutputContent"></a>smartyOutputContent

```php
mixed ControllerCore::smartyOutputContent($content)
```





* Visibility: **protected**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 351](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/Controller.php#L351)


#### Arguments
* $content **mixed**



### <a name="method-updateAccessories"></a>updateAccessories

```php
mixed AdminProductsControllerCore::updateAccessories(object $product)
```

Update product accessories



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2010](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2010)


#### Arguments
* $product **object** - Product



### <a name="method-updateAssoShop"></a>updateAssoShop

```php
mixed AdminProductsControllerCore::updateAssoShop($id_object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1547](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1547)


#### Arguments
* $id_object **mixed**



### <a name="method-updateDownloadProduct"></a>updateDownloadProduct

```php
boolean AdminProductsControllerCore::updateDownloadProduct(object $product, $edit)
```

Update product download



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1930](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L1930)


#### Arguments
* $product **object** - Product
* $edit **mixed**



### <a name="method-updatePackItems"></a>updatePackItems

```php
boolean AdminProductsControllerCore::updatePackItems(\Product $product)
```

delete all items in pack, then check if type_product value is 2.

if yes, add the pack items from input "inputPackItems"

* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4086](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L4086)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-updateTags"></a>updateTags

```php
boolean AdminProductsControllerCore::updateTags($languages, object $product)
```

Update product tags



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2031](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/controllers/admin/AdminProductsController.php#L2031)


#### Arguments
* $languages **mixed**
* $product **object** - Product



### <a name="method-uploadImage"></a>uploadImage

```php
mixed AdminControllerCore::uploadImage($id, $name, $dir, $ext, $width, $height)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2477](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2477)


#### Arguments
* $id **mixed**
* $name **mixed**
* $dir **mixed**
* $ext **mixed**
* $width **mixed**
* $height **mixed**



### <a name="method-validateField"></a>validateField

```php
mixed AdminControllerCore::validateField($value, $field)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2435](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2435)


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
* Source: [classes/controller/AdminController.php line 2194](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2194)


#### Arguments
* $class_name **mixed**



### <a name="method-viewAccess"></a>viewAccess

```php
boolean AdminControllerCore::viewAccess(boolean $disable)
```

Check rights to view the current tab



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 378](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L378)


#### Arguments
* $disable **boolean**



### <a name="method-viewDetails"></a>viewDetails

```php
mixed AdminControllerCore::viewDetails()
```

Display object details



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2300](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/controller/AdminController.php#L2300)



