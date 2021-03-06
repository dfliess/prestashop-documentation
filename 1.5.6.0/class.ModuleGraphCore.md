Class ModuleGraphCore
=====================





* Class name: ModuleGraphCore
* This is an **abstract** class
* Parent class: [Module](class.ModuleCore.md)
* Source: [classes/module/ModuleGraph.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/ModuleGraph.php#L27)


Contents
--------


### Properties

* [$_employee](#property-$_employee)
* [$_legend](#property-$_legend)
* [$_render](#property-$_render)
* [$_titles](#property-$_titles)
* [$_values](#property-$_values)
* [$_INSTANCE](#property-$_INSTANCE)
* [$_confirmations](#property-$_confirmations)
* [$_errors](#property-$_errors)
* [$_generate_config_xml_mode](#property-$_generate_config_xml_mode)
* [$_lang](#property-$_lang)
* [$_path](#property-$_path)
* [$active](#property-$active)
* [$author](#property-$author)
* [$cache_permissions](#property-$cache_permissions)
* [$classInModule](#property-$classInModule)
* [$context](#property-$context)
* [$current_subtemplate](#property-$current_subtemplate)
* [$database_version](#property-$database_version)
* [$dependencies](#property-$dependencies)
* [$description](#property-$description)
* [$displayName](#property-$displayName)
* [$id](#property-$id)
* [$identifier](#property-$identifier)
* [$l_cache](#property-$l_cache)
* [$limited_countries](#property-$limited_countries)
* [$local_path](#property-$local_path)
* [$modules_cache](#property-$modules_cache)
* [$name](#property-$name)
* [$need_instance](#property-$need_instance)
* [$ps_versions_compliancy](#property-$ps_versions_compliancy)
* [$registered_version](#property-$registered_version)
* [$smarty](#property-$smarty)
* [$tab](#property-$tab)
* [$table](#property-$table)
* [$version](#property-$version)
* [$warning](#property-$warning)

### Methods

* [__construct](#method-__construct)
* [_clearCache](#method-_clearCache)
* [_displayCsv](#method-_displayCsv)
* [_generateConfigXml](#method-_generateConfigXml)
* [_getApplicableTemplateDir](#method-_getApplicableTemplateDir)
* [_isTemplateOverloaded](#method-_isTemplateOverloaded)
* [_isTemplateOverloadedStatic](#method-_isTemplateOverloadedStatic)
* [addOverride](#method-addOverride)
* [adminDisplayInformation](#method-adminDisplayInformation)
* [adminDisplayWarning](#method-adminDisplayWarning)
* [cleanPositions](#method-cleanPositions)
* [configXmlStringFormat](#method-configXmlStringFormat)
* [create](#method-create)
* [csvExport](#method-csvExport)
* [disable](#method-disable)
* [disableByName](#method-disableByName)
* [display](#method-display)
* [displayConfirmation](#method-displayConfirmation)
* [displayError](#method-displayError)
* [displayFlags](#method-displayFlags)
* [draw](#method-draw)
* [editExceptions](#method-editExceptions)
* [enable](#method-enable)
* [enableByName](#method-enableByName)
* [engine](#method-engine)
* [findTranslation](#method-findTranslation)
* [getAuthorizedModules](#method-getAuthorizedModules)
* [getCacheId](#method-getCacheId)
* [getConfirmations](#method-getConfirmations)
* [getCurrentSubTemplate](#method-getCurrentSubTemplate)
* [getData](#method-getData)
* [getDate](#method-getDate)
* [getDateBetween](#method-getDateBetween)
* [getEmployee](#method-getEmployee)
* [getErrors](#method-getErrors)
* [getExceptions](#method-getExceptions)
* [getInstanceById](#method-getInstanceById)
* [getInstanceByName](#method-getInstanceByName)
* [getLang](#method-getLang)
* [getLocalPath](#method-getLocalPath)
* [getModuleIdByName](#method-getModuleIdByName)
* [getModuleName](#method-getModuleName)
* [getModuleNameFromClass](#method-getModuleNameFromClass)
* [getModulesDirOnDisk](#method-getModulesDirOnDisk)
* [getModulesInstalled](#method-getModulesInstalled)
* [getModulesOnDisk](#method-getModulesOnDisk)
* [getNonNativeModuleList](#method-getNonNativeModuleList)
* [getPathUri](#method-getPathUri)
* [getPaymentModules](#method-getPaymentModules)
* [getPaypalIgnore](#method-getPaypalIgnore)
* [getPermission](#method-getPermission)
* [getPermissionStatic](#method-getPermissionStatic)
* [getPosition](#method-getPosition)
* [getTemplatePath](#method-getTemplatePath)
* [getUpgradeStatus](#method-getUpgradeStatus)
* [hookExec](#method-hookExec)
* [hookExecPayment](#method-hookExecPayment)
* [initUpgradeModule](#method-initUpgradeModule)
* [install](#method-install)
* [installOverrides](#method-installOverrides)
* [isCached](#method-isCached)
* [isEnabled](#method-isEnabled)
* [isHookableOn](#method-isHookableOn)
* [isInstalled](#method-isInstalled)
* [isRegisteredInHook](#method-isRegisteredInHook)
* [l](#method-l)
* [loadUpgradeVersionList](#method-loadUpgradeVersionList)
* [needUpgrade](#method-needUpgrade)
* [preCall](#method-preCall)
* [registerExceptions](#method-registerExceptions)
* [registerHook](#method-registerHook)
* [removeOverride](#method-removeOverride)
* [resetCurrentSubTemplate](#method-resetCurrentSubTemplate)
* [runUpgradeModule](#method-runUpgradeModule)
* [setDateGraph](#method-setDateGraph)
* [setEmployee](#method-setEmployee)
* [setLang](#method-setLang)
* [setOption](#method-setOption)
* [setUpgradeMessage](#method-setUpgradeMessage)
* [uninstall](#method-uninstall)
* [uninstallOverrides](#method-uninstallOverrides)
* [unregisterExceptions](#method-unregisterExceptions)
* [unregisterHook](#method-unregisterHook)
* [updatePosition](#method-updatePosition)
* [upgradeModuleVersion](#method-upgradeModuleVersion)




Properties
----------


### <a name="property-$_employee"></a>$_employee

```php
protected mixed $_employee
```





* Visibility: **protected**
* Source: [classes/module/ModuleGraph.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/ModuleGraph.php#L29).


### <a name="property-$_legend"></a>$_legend

```php
protected string $_legend = array()
```





* Visibility: **protected**
* Source: [classes/module/ModuleGraph.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/ModuleGraph.php#L35).


### <a name="property-$_render"></a>$_render

```php
protected \ModuleGraphEngine $_render
```





* Visibility: **protected**
* Source: [classes/module/ModuleGraph.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/ModuleGraph.php#L41).


### <a name="property-$_titles"></a>$_titles

```php
protected mixed $_titles = array('main' => null, 'x' => null, 'y' => null)
```





* Visibility: **protected**
* Source: [classes/module/ModuleGraph.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/ModuleGraph.php#L38).


### <a name="property-$_values"></a>$_values

```php
protected integer $_values = array()
```





* Visibility: **protected**
* Source: [classes/module/ModuleGraph.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/ModuleGraph.php#L32).


### <a name="property-$_INSTANCE"></a>$_INSTANCE

```php
protected \protected $_INSTANCE = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L105).


### <a name="property-$_confirmations"></a>$_confirmations

```php
protected \protected $_confirmations = array()
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L93).


### <a name="property-$_errors"></a>$_errors

```php
protected \protected $_errors = array()
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L90).


### <a name="property-$_generate_config_xml_mode"></a>$_generate_config_xml_mode

```php
protected \protected $_generate_config_xml_mode = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L108).


### <a name="property-$_lang"></a>$_lang

```php
protected array $_lang = array()
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L79).


### <a name="property-$_path"></a>$_path

```php
protected string $_path = null
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L82).


### <a name="property-$active"></a>$active

```php
public boolean $active = false
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L67).


### <a name="property-$author"></a>$author

```php
public string $author
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L58).


### <a name="property-$cache_permissions"></a>$cache_permissions

```php
protected \protected $cache_permissions = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L114).


### <a name="property-$classInModule"></a>$classInModule

```php
public array $classInModule = array()
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L76).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L117).


### <a name="property-$current_subtemplate"></a>$current_subtemplate

```php
protected \currentSmartySubTemplate $current_subtemplate = null
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L123).


### <a name="property-$database_version"></a>$database_version

```php
public mixed $database_version
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L34).


### <a name="property-$dependencies"></a>$dependencies

```php
public array $dependencies = array()
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L46).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L55).


### <a name="property-$displayName"></a>$displayName

```php
public string $displayName
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L52).


### <a name="property-$id"></a>$id

```php
public integer $id = null
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L30).


### <a name="property-$identifier"></a>$identifier

```php
protected \protected $identifier = 'id_module'
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L99).


### <a name="property-$l_cache"></a>$l_cache

```php
protected \protected $l_cache = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L111).


### <a name="property-$limited_countries"></a>$limited_countries

```php
public array $limited_countries = array()
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L73).


### <a name="property-$local_path"></a>$local_path

```php
protected string $local_path = null
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L87).


### <a name="property-$modules_cache"></a>$modules_cache

```php
protected \protected $modules_cache
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L102).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L49).


### <a name="property-$need_instance"></a>$need_instance

```php
public integer $need_instance = 1
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L61).


### <a name="property-$ps_versions_compliancy"></a>$ps_versions_compliancy

```php
public array $ps_versions_compliancy = array('min' => '1.4', 'max' => '1.6')
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L43).


### <a name="property-$registered_version"></a>$registered_version

```php
public string $registered_version
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L40).


### <a name="property-$smarty"></a>$smarty

```php
protected \Smarty_Data $smarty
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L120).


### <a name="property-$tab"></a>$tab

```php
public string $tab = null
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L64).


### <a name="property-$table"></a>$table

```php
protected \protected $table = 'module'
```





* Visibility: **protected**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L96).


### <a name="property-$version"></a>$version

```php
public float $version
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L33).


### <a name="property-$warning"></a>$warning

```php
public string $warning
```





* Visibility: **public**
* This property is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L70).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ModuleCore::__construct(string $name, \Context $context)
```

Constructor



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L142)


#### Arguments
* $name **string** - Module unique name
* $context **[Context](class.ContextCore.md)**



### <a name="method-_clearCache"></a>_clearCache

```php
mixed ModuleCore::_clearCache($template, $cache_id, $compile_id)
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1729](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1729)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### <a name="method-_displayCsv"></a>_displayCsv

```php
mixed ModuleGraphCore::_displayCsv()
```





* Visibility: **protected**
* Source: [classes/module/ModuleGraph.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/ModuleGraph.php#L223)




### <a name="method-_generateConfigXml"></a>_generateConfigXml

```php
mixed ModuleCore::_generateConfigXml()
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1738](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1738)




### <a name="method-_getApplicableTemplateDir"></a>_getApplicableTemplateDir

```php
mixed ModuleCore::_getApplicableTemplateDir($template)
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1715](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1715)


#### Arguments
* $template **mixed**



### <a name="method-_isTemplateOverloaded"></a>_isTemplateOverloaded

```php
mixed ModuleCore::_isTemplateOverloaded($template)
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1626](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1626)


#### Arguments
* $template **mixed**



### <a name="method-_isTemplateOverloadedStatic"></a>_isTemplateOverloadedStatic

```php
mixed ModuleCore::_isTemplateOverloadedStatic($module_name, $template)
```





* Visibility: **protected**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1611](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1611)


#### Arguments
* $module_name **mixed**
* $template **mixed**



### <a name="method-addOverride"></a>addOverride

```php
boolean ModuleCore::addOverride(string $classname)
```

Add all methods in a module override to the override class



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1980](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1980)


#### Arguments
* $classname **string**



### <a name="method-adminDisplayInformation"></a>adminDisplayInformation

```php
mixed ModuleCore::adminDisplayInformation(string $msg)
```

add a info message to display at the top of the admin page



* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1926](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1926)


#### Arguments
* $msg **string**



### <a name="method-adminDisplayWarning"></a>adminDisplayWarning

```php
mixed ModuleCore::adminDisplayWarning(string $msg)
```

add a warning message to display at the top of the admin page



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1914](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1914)


#### Arguments
* $msg **string**



### <a name="method-cleanPositions"></a>cleanPositions

```php
mixed ModuleCore::cleanPositions($id_hook, $shop_list)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1479](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1479)


#### Arguments
* $id_hook **mixed**
* $shop_list **mixed**



### <a name="method-configXmlStringFormat"></a>configXmlStringFormat

```php
mixed ModuleCore::configXmlStringFormat($string)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 939](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L939)


#### Arguments
* $string **mixed**



### <a name="method-create"></a>create

```php
mixed ModuleGraphCore::create($render, $type, $width, $height, $layers)
```





* Visibility: **public**
* Source: [classes/module/ModuleGraph.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/ModuleGraph.php#L232)


#### Arguments
* $render **mixed**
* $type **mixed**
* $width **mixed**
* $height **mixed**
* $layers **mixed**



### <a name="method-csvExport"></a>csvExport

```php
mixed ModuleGraphCore::csvExport($datas)
```





* Visibility: **protected**
* Source: [classes/module/ModuleGraph.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/ModuleGraph.php#L159)


#### Arguments
* $datas **mixed**



### <a name="method-disable"></a>disable

```php
mixed ModuleCore::disable(boolean $forceAll)
```

Desactivate current module.



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 624](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L624)


#### Arguments
* $forceAll **boolean** - If true, disable module for all shop



### <a name="method-disableByName"></a>disableByName

```php
true ModuleCore::disableByName(array|string $name)
```

This function disable module $name. If an $name is an array,
this will disable all of them



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 606](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L606)


#### Arguments
* $name **array|string**



### <a name="method-display"></a>display

```php
mixed ModuleCore::display($file, $template, $cacheId, $compileId)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1648](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1648)


#### Arguments
* $file **mixed**
* $template **mixed**
* $cacheId **mixed**
* $compileId **mixed**



### <a name="method-displayConfirmation"></a>displayConfirmation

```php
mixed ModuleCore::displayConfirmation($string)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1514](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1514)


#### Arguments
* $string **mixed**



### <a name="method-displayError"></a>displayError

```php
mixed ModuleCore::displayError($error)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1504](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1504)


#### Arguments
* $error **mixed**



### <a name="method-displayFlags"></a>displayFlags

```php
mixed ModuleCore::displayFlags(array $languages, integer $default_language, string $ids, string $id, boolean $return, boolean $use_vars_instead_of_ids)
```

Display flags in forms for translations



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 641](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L641)


#### Arguments
* $languages **array** - All languages available
* $default_language **integer** - Default language id
* $ids **string** - Multilingual div ids in form
* $id **string** - Current div id]
* $return **boolean** - define the return way : false for a display, true for a return
* $use_vars_instead_of_ids **boolean** - use an js vars instead of ids seperate by &quot;¤&quot;



### <a name="method-draw"></a>draw

```php
mixed ModuleGraphCore::draw()
```





* Visibility: **public**
* Source: [classes/module/ModuleGraph.php line 248](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/ModuleGraph.php#L248)




### <a name="method-editExceptions"></a>editExceptions

```php
boolean ModuleCore::editExceptions($id_hook, array $excepts)
```

Edit exceptions for module->Hook



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 831](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L831)


#### Arguments
* $id_hook **mixed**
* $excepts **array** - List of shopID and file name



### <a name="method-enable"></a>enable

```php
mixed ModuleCore::enable(boolean $forceAll)
```

Activate current module.



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 573](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L573)


#### Arguments
* $forceAll **boolean** - If true, enable module for all shop



### <a name="method-enableByName"></a>enableByName

```php
true ModuleCore::enableByName(array|string $name)
```

This function enable module $name. If an $name is an array,
this will enable all of them



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 555](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L555)


#### Arguments
* $name **array|string**



### <a name="method-engine"></a>engine

```php
mixed ModuleGraphCore::engine($params)
```





* Visibility: **public**
* Source: [classes/module/ModuleGraph.php line 260](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/ModuleGraph.php#L260)


#### Arguments
* $params **mixed**



### <a name="method-findTranslation"></a>findTranslation

```php
mixed ModuleCore::findTranslation($name, $string, $source)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1399](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1399)


#### Arguments
* $name **mixed**
* $string **mixed**
* $source **mixed**



### <a name="method-getAuthorizedModules"></a>getAuthorizedModules

```php
mixed ModuleCore::getAuthorizedModules($group_id)
```

Get Unauthorized modules for a client group



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1823](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1823)


#### Arguments
* $group_id **mixed**



### <a name="method-getCacheId"></a>getCacheId

```php
mixed ModuleCore::getCacheId($name)
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1631](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1631)


#### Arguments
* $name **mixed**



### <a name="method-getConfirmations"></a>getConfirmations

```php
array ModuleCore::getConfirmations()
```

Get module messages confirmation



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1858](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1858)




### <a name="method-getCurrentSubTemplate"></a>getCurrentSubTemplate

```php
mixed ModuleCore::getCurrentSubTemplate($template, $cache_id, $compile_id)
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1673](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1673)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### <a name="method-getData"></a>getData

```php
mixed ModuleGraphCore::getData($layers)
```





* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/module/ModuleGraph.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/ModuleGraph.php#L43)


#### Arguments
* $layers **mixed**



### <a name="method-getDate"></a>getDate

```php
mixed ModuleGraphCore::getDate()
```





* Visibility: **public**
* Source: [classes/module/ModuleGraph.php line 316](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/ModuleGraph.php#L316)




### <a name="method-getDateBetween"></a>getDateBetween

```php
mixed ModuleGraphCore::getDateBetween($employee)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/ModuleGraph.php line 321](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/ModuleGraph.php#L321)


#### Arguments
* $employee **mixed**



### <a name="method-getEmployee"></a>getEmployee

```php
mixed ModuleGraphCore::getEmployee($employee, \Context $context)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/module/ModuleGraph.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/ModuleGraph.php#L293)


#### Arguments
* $employee **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getErrors"></a>getErrors

```php
array ModuleCore::getErrors()
```

Get module errors



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1847](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1847)




### <a name="method-getExceptions"></a>getExceptions

```php
mixed ModuleCore::getExceptions($id_hook, $dispatch)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1529](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1529)


#### Arguments
* $id_hook **mixed**
* $dispatch **mixed**



### <a name="method-getInstanceById"></a>getInstanceById

```php
\Module ModuleCore::getInstanceById(integer $id_module)
```

Return an instance of the specified module



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 920](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L920)


#### Arguments
* $id_module **integer** - Module ID



### <a name="method-getInstanceByName"></a>getInstanceByName

```php
\Module ModuleCore::getInstanceByName(string $module_name)
```

Return an instance of the specified module



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 891](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L891)


#### Arguments
* $module_name **string** - Module name



### <a name="method-getLang"></a>getLang

```php
mixed ModuleGraphCore::getLang()
```





* Visibility: **public**
* Source: [classes/module/ModuleGraph.php line 328](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/ModuleGraph.php#L328)




### <a name="method-getLocalPath"></a>getLocalPath

```php
string ModuleCore::getLocalPath()
```

Get local path for module



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1869](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1869)




### <a name="method-getModuleIdByName"></a>getModuleIdByName

```php
integer ModuleCore::getModuleIdByName($name)
```

Get id module by name



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1836](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1836)


#### Arguments
* $name **mixed**



### <a name="method-getModuleName"></a>getModuleName

```php
mixed ModuleCore::getModuleName($module)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 945](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L945)


#### Arguments
* $module **mixed**



### <a name="method-getModuleNameFromClass"></a>getModuleNameFromClass

```php
boolean|string ModuleCore::getModuleNameFromClass(mixed $currentClass)
```

This function is used to determine the module name
of an AdminTab which belongs to a module, in order to keep translation
related to a module in its directory (instead of $_LANGADM)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 853](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L853)


#### Arguments
* $currentClass **mixed** - the



### <a name="method-getModulesDirOnDisk"></a>getModulesDirOnDisk

```php
array ModuleCore::getModulesDirOnDisk()
```

Return modules directory list



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1259](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1259)




### <a name="method-getModulesInstalled"></a>getModulesInstalled

```php
array ModuleCore::getModulesInstalled(integer $position)
```

Return installed modules



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1306](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1306)


#### Arguments
* $position **integer** - Take only positionnables modules



### <a name="method-getModulesOnDisk"></a>getModulesOnDisk

```php
array ModuleCore::getModulesOnDisk(boolean $useConfig, $loggedOnAddons, $id_employee)
```

Return available modules



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 980](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L980)


#### Arguments
* $useConfig **boolean** - in order to use config.xml file in module dir
* $loggedOnAddons **mixed**
* $id_employee **mixed**



### <a name="method-getNonNativeModuleList"></a>getNonNativeModuleList

```php
array ModuleCore::getNonNativeModuleList()
```

Return non native module



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1282](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1282)




### <a name="method-getPathUri"></a>getPathUri

```php
string ModuleCore::getPathUri()
```

Get uri path for module



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1880](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1880)




### <a name="method-getPaymentModules"></a>getPaymentModules

```php
array ModuleCore::getPaymentModules()
```

Returns the list of the payment module associated to the current customer



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1355](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1355)




### <a name="method-getPaypalIgnore"></a>getPaypalIgnore

```php
mixed ModuleCore::getPaypalIgnore()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1341](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1341)




### <a name="method-getPermission"></a>getPermission

```php
boolean ModuleCore::getPermission(array $variable, object $employee)
```

Check employee permission for module



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1780](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1780)


#### Arguments
* $variable **array** - (action)
* $employee **object**



### <a name="method-getPermissionStatic"></a>getPermissionStatic

```php
boolean ModuleCore::getPermissionStatic(integer $id_module, array $variable, object $employee)
```

Check employee permission for module (static method)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1792](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1792)


#### Arguments
* $id_module **integer**
* $variable **array** - (action)
* $employee **object**



### <a name="method-getPosition"></a>getPosition

```php
mixed ModuleCore::getPosition($id_hook)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1891](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1891)


#### Arguments
* $id_hook **mixed**



### <a name="method-getTemplatePath"></a>getTemplatePath

```php
string ModuleCore::getTemplatePath(string $template)
```

Get realpath of a template of current module (check if template is overriden too)



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1699](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1699)


#### Arguments
* $template **string**



### <a name="method-getUpgradeStatus"></a>getUpgradeStatus

```php
boolean ModuleCore::getUpgradeStatus($module_name)
```

Return the status of the upgraded module



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 495](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L495)


#### Arguments
* $module_name **mixed**



### <a name="method-hookExec"></a>hookExec

```php
string ModuleCore::hookExec(string $hook_name, array $hookArgs, $id_module)
```

Execute modules for specified hook



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1324](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1324)


#### Arguments
* $hook_name **string** - Hook Name
* $hookArgs **array** - Parameters for the functions
* $id_module **mixed**



### <a name="method-hookExecPayment"></a>hookExecPayment

```php
mixed ModuleCore::hookExecPayment()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1330](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1330)




### <a name="method-initUpgradeModule"></a>initUpgradeModule

```php
boolean ModuleCore::initUpgradeModule($module)
```

Init the upgrade module



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 321](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L321)


#### Arguments
* $module **mixed**



### <a name="method-install"></a>install

```php
mixed ModuleCore::install()
```

Insert module into datable



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L195)




### <a name="method-installOverrides"></a>installOverrides

```php
boolean ModuleCore::installOverrides()
```

Install overrides files for the module



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1938](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1938)




### <a name="method-isCached"></a>isCached

```php
mixed ModuleCore::isCached($template, $cacheId, $compileId)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1720](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1720)


#### Arguments
* $template **mixed**
* $cacheId **mixed**
* $compileId **mixed**



### <a name="method-isEnabled"></a>isEnabled

```php
mixed ModuleCore::isEnabled($module_name)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1583](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1583)


#### Arguments
* $module_name **mixed**



### <a name="method-isHookableOn"></a>isHookableOn

```php
boolean ModuleCore::isHookableOn(string $hook_name)
```

Check if the module is transplantable on the hook in parameter



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1768](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1768)


#### Arguments
* $hook_name **string**



### <a name="method-isInstalled"></a>isInstalled

```php
mixed ModuleCore::isInstalled($module_name)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1573](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1573)


#### Arguments
* $module_name **mixed**



### <a name="method-isRegisteredInHook"></a>isRegisteredInHook

```php
mixed ModuleCore::isRegisteredInHook($hook)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1596](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1596)


#### Arguments
* $hook **mixed**



### <a name="method-l"></a>l

```php
string ModuleCore::l(string $string, boolean|string $specific)
```

Get translation for a given module text

Note: $specific parameter is mandatory for library files.
Otherwise, translation key will not match for Module library
when module is loaded with eval() Module::getModulesOnDisk()

* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1415](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1415)


#### Arguments
* $string **string** - String to translate
* $specific **boolean|string** - filename to use in translation key



### <a name="method-loadUpgradeVersionList"></a>loadUpgradeVersionList

```php
boolean ModuleCore::loadUpgradeVersionList($module_name, $module_version, $registered_version)
```

Load the available list of upgrade of a specified module
with an associated version



* Visibility: **protected**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 445](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L445)


#### Arguments
* $module_name **mixed**
* $module_version **mixed**
* $registered_version **mixed**



### <a name="method-needUpgrade"></a>needUpgrade

```php
boolean ModuleCore::needUpgrade($module)
```

Check if a module need to be upgraded.

This method modify the module_cache adding an upgrade list file

* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 421](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L421)


#### Arguments
* $module **mixed**



### <a name="method-preCall"></a>preCall

```php
mixed ModuleCore::preCall($module_name)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1336](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1336)


#### Arguments
* $module_name **mixed**



### <a name="method-registerExceptions"></a>registerExceptions

```php
boolean ModuleCore::registerExceptions(integer $id_hook, array $excepts, array $shop_list)
```

Add exceptions for module->Hook



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 797](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L797)


#### Arguments
* $id_hook **integer** - Hook id
* $excepts **array** - List of file name
* $shop_list **array** - List of shop



### <a name="method-registerHook"></a>registerHook

```php
boolean ModuleCore::registerHook(string $hook_name, array $shop_list)
```

Connect module to a hook



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 671](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L671)


#### Arguments
* $hook_name **string** - Hook name
* $shop_list **array** - List of shop linked to the hook (if null, link hook to all shops)



### <a name="method-removeOverride"></a>removeOverride

```php
boolean ModuleCore::removeOverride(string $classname)
```

Remove all methods in a module override from the override class



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 2040](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L2040)


#### Arguments
* $classname **string**



### <a name="method-resetCurrentSubTemplate"></a>resetCurrentSubTemplate

```php
mixed ModuleCore::resetCurrentSubTemplate($template, $cache_id, $compile_id)
```





* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1687](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1687)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### <a name="method-runUpgradeModule"></a>runUpgradeModule

```php
array ModuleCore::runUpgradeModule()
```

Run the upgrade for a given module name and version



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 351](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L351)




### <a name="method-setDateGraph"></a>setDateGraph

```php
mixed ModuleGraphCore::setDateGraph($layers, $legend)
```





* Visibility: **protected**
* Source: [classes/module/ModuleGraph.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/ModuleGraph.php#L55)


#### Arguments
* $layers **mixed**
* $legend **mixed**



### <a name="method-setEmployee"></a>setEmployee

```php
mixed ModuleGraphCore::setEmployee($id_employee)
```





* Visibility: **public**
* Source: [classes/module/ModuleGraph.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/ModuleGraph.php#L45)


#### Arguments
* $id_employee **mixed**



### <a name="method-setLang"></a>setLang

```php
mixed ModuleGraphCore::setLang($id_lang)
```





* Visibility: **public**
* Source: [classes/module/ModuleGraph.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/ModuleGraph.php#L50)


#### Arguments
* $id_lang **mixed**



### <a name="method-setOption"></a>setOption

```php
mixed ModuleGraphCore::setOption($option, $layers)
```





* Visibility: **public**
* Source: [classes/module/ModuleGraph.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/ModuleGraph.php#L256)


#### Arguments
* $option **mixed**
* $layers **mixed**



### <a name="method-setUpgradeMessage"></a>setUpgradeMessage

```php
mixed ModuleCore::setUpgradeMessage($upgrade_detail)
```

Set errors, warning or success message of a module upgrade



* Visibility: **protected**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L285)


#### Arguments
* $upgrade_detail **mixed**



### <a name="method-uninstall"></a>uninstall

```php
boolean ModuleCore::uninstall()
```

Delete module from datable



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 506](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L506)




### <a name="method-uninstallOverrides"></a>uninstallOverrides

```php
boolean ModuleCore::uninstallOverrides()
```

Uninstall overrides files for the module



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1959](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1959)




### <a name="method-unregisterExceptions"></a>unregisterExceptions

```php
boolean ModuleCore::unregisterExceptions($hook_id, array $shop_list)
```

Unregister exceptions linked to module



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 781](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L781)


#### Arguments
* $hook_id **mixed**
* $shop_list **array** - List of shop



### <a name="method-unregisterHook"></a>unregisterHook

```php
boolean ModuleCore::unregisterHook($hook_id, array $shop_list)
```

Unregister module from hook



* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 744](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L744)


#### Arguments
* $hook_id **mixed**
* $shop_list **array** - List of shop



### <a name="method-updatePosition"></a>updatePosition

```php
mixed ModuleCore::updatePosition($id_hook, $way, $position)
```





* Visibility: **public**
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 1430](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L1430)


#### Arguments
* $id_hook **mixed**
* $way **mixed**
* $position **mixed**



### <a name="method-upgradeModuleVersion"></a>upgradeModuleVersion

```php
boolean ModuleCore::upgradeModuleVersion($name, $version)
```

Upgrade the registered version to a new one



* Visibility: **public**
* This method is **static**.
* This method is defined by [ModuleCore](class.ModuleCore.md).
* Source: [classes/module/Module.php line 404](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/module/Module.php#L404)


#### Arguments
* $name **mixed**
* $version **mixed**


