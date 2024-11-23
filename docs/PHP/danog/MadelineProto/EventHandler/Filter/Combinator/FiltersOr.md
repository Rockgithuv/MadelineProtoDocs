---
title: "danog\\MadelineProto\\EventHandler\\Filter\\Combinator\\FiltersOr: ORs multiple filters."
description: ""
image: "https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png"
parent: "MadelineProto API"

---
# `danog\MadelineProto\EventHandler\Filter\Combinator\FiltersOr`
[Back to index](../../../../../index.html)

> Author: Daniil Gentili <daniil@daniil.it>  
  

ORs multiple filters.  




## Method list:
* [`__construct(\danog\MadelineProto\EventHandler\Filter\Filter ...$filters)`](#__construct)
* [`initialize(\danog\MadelineProto\EventHandler $API): \danog\MadelineProto\EventHandler\Filter\Filter`](#initialize)
* [`apply(\danog\MadelineProto\EventHandler\Update $update): bool`](#apply)
* [`fromReflectionType(\ReflectionType $type): \danog\MadelineProto\EventHandler\Filter\Filter`](#fromReflectionType)

## Methods:
### <a name="__construct"></a> `__construct(\danog\MadelineProto\EventHandler\Filter\Filter ...$filters)`




Parameters:

* `...$filters`: `\danog\MadelineProto\EventHandler\Filter\Filter`   


#### See also: 
* [\danog\MadelineProto\EventHandler\Filter\Filter](../../../../../danog/MadelineProto/EventHandler/Filter/Filter.html)




### <a name="initialize"></a> `initialize(\danog\MadelineProto\EventHandler $API): \danog\MadelineProto\EventHandler\Filter\Filter`




Parameters:

* `$API`: `\danog\MadelineProto\EventHandler`   


#### See also: 
* [`\danog\MadelineProto\EventHandler`: Event handler.](../../../../../danog/MadelineProto/EventHandler.html)
* [\danog\MadelineProto\EventHandler\Filter\Filter](../../../../../danog/MadelineProto/EventHandler/Filter/Filter.html)




### <a name="apply"></a> `apply(\danog\MadelineProto\EventHandler\Update $update): bool`




Parameters:

* `$update`: `\danog\MadelineProto\EventHandler\Update`   


#### See also: 
* [`\danog\MadelineProto\EventHandler\Update`: Represents a generic update.](../../../../../danog/MadelineProto/EventHandler/Update.html)




### <a name="fromReflectionType"></a> `fromReflectionType(\ReflectionType $type): \danog\MadelineProto\EventHandler\Filter\Filter`




Parameters:

* `$type`: `\ReflectionType`   


#### See also: 
* `\ReflectionType`




---
Generated by [danog/phpdoc](https://phpdoc.daniil.it)