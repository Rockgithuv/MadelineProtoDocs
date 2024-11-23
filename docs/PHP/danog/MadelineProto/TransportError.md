---
title: "danog\\MadelineProto\\TransportError: Indicates a transport error returned by Telegram's API."
description: ""
image: "https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png"
parent: "MadelineProto API"

---
# `danog\MadelineProto\TransportError`
[Back to index](../../index.html)

> Author: Daniil Gentili <daniil@daniil.it>  
  

Indicates a transport error returned by Telegram's API.  



## Properties
* `$error`: `int` 
* `$tlTrace`: `string` TL trace.

## Method list:
* [`__construct(int $error, ?\danog\MadelineProto\Exception $previous = NULL)`](#__construct)
* [`extension(string $extensionName): self`](#extension)
* [`getMessage(): string`](#getMessage)
* [`getCode()`](#getCode)
* [`getFile(): string`](#getFile)
* [`getLine(): int`](#getLine)
* [`getTrace(): array`](#getTrace)
* [`getPrevious(): ?Throwable`](#getPrevious)
* [`getTraceAsString(): string`](#getTraceAsString)
* [`getTLTrace(): string`](#getTLTrace)

## Methods:
### <a name="__construct"></a> `__construct(int $error, ?\danog\MadelineProto\Exception $previous = NULL)`




Parameters:

* `$error`: `int`   
* `$previous`: `?\danog\MadelineProto\Exception`   


#### See also: 
* [`\danog\MadelineProto\Exception`: Basic exception.](../../danog/MadelineProto/Exception.html)




### <a name="extension"></a> `extension(string $extensionName): self`

Complain about missing extensions.


Parameters:

* `$extensionName`: `string` Extension name  



### <a name="getMessage"></a> `getMessage(): string`





### <a name="getCode"></a> `getCode()`





### <a name="getFile"></a> `getFile(): string`





### <a name="getLine"></a> `getLine(): int`





### <a name="getTrace"></a> `getTrace(): array`





### <a name="getPrevious"></a> `getPrevious(): ?Throwable`




#### See also: 
* `Throwable`




### <a name="getTraceAsString"></a> `getTraceAsString(): string`





### <a name="getTLTrace"></a> `getTLTrace(): string`

Get TL trace.



---
Generated by [danog/phpdoc](https://phpdoc.daniil.it)