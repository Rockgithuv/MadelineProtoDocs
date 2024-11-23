---
title: "danog\\MadelineProto\\Broadcast\\Action: Interface that represents a broadcast action."
description: ""
image: "https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png"
parent: "MadelineProto API"

---
# `danog\MadelineProto\Broadcast\Action`
[Back to index](../../../index.html)

> Author: Daniil Gentili <daniil@daniil.it>  
  

Interface that represents a broadcast action.  




## Method list:
* [`act(integer $broadcastId, integer $peer, \Amp\Cancellation $cancellation): void`](#act)

## Methods:
### <a name="act"></a> `act(integer $broadcastId, integer $peer, \Amp\Cancellation $cancellation): void`

Do something with a single peer.


Parameters:

* `$broadcastId`: `integer` Broadcast ID  
* `$peer`: `integer` Broadcast peer  
* `$cancellation`: `\Amp\Cancellation` Cancellation token  


#### See also: 
* `\Amp\Cancellation`




---
Generated by [danog/phpdoc](https://phpdoc.daniil.it)