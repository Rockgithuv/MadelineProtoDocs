---
title: "danog\\MadelineProto\\EventHandler\\ChatInvite\\ChatInviteExported: Represents an exported chat invite."
description: ""
image: "https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png"
parent: "MadelineProto API"

---
# `danog\MadelineProto\EventHandler\ChatInvite\ChatInviteExported`
[Back to index](../../../../index.html)

> Author: Daniil Gentili <daniil@daniil.it>  
  

Represents an exported chat invite.  



## Properties
* `$revoked`: `bool` Whether this chat invite was revoked.
* `$permanent`: `bool` Whether this chat invite has no expiration.
* `$requestNeeded`: `bool` Whether users importing this invite link will have to be [approved to join the channel or group](https://core.telegram.org/api/invites#join-requests).
* `$link`: `string` Chat invitation link.
* `$adminId`: `int` ID of the admin that created this chat invite.
* `$date`: `int` When was this chat invite last modified.
* `$created`: `?int` When was this chat invite last modified.
* `$expire`: `?int` When does this chat invite expire.
* `$limit`: `?int` Maximum number of users that can join using this link.
* `$used`: `?int` How many users joined using this link.
* `$requested`: `?int` Number of users that have already used this link to join.
* `$title`: `?string` Custom description for the invite link, visible only to admins.

## Method list:
* [`fromRawChatInvite(array $rawChatInvite): self`](#fromRawChatInvite)

## Methods:
### <a name="fromRawChatInvite"></a> `fromRawChatInvite(array $rawChatInvite): self`




Parameters:

* `$rawChatInvite`: `array`   



---
Generated by [danog/phpdoc](https://phpdoc.daniil.it)