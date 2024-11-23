---
title: "danog\\MadelineProto\\EventHandler\\Participant\\Rights\\Admin: Represents the rights of an admin in a [channel/supergroup](https://core.telegram.org/api/channel)."
description: ""
image: "https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png"
parent: "MadelineProto API"

---
# `danog\MadelineProto\EventHandler\Participant\Rights\Admin`
[Back to index](../../../../../index.html)

> Author: Daniil Gentili <daniil@daniil.it>  
  

Represents the rights of an admin in a [channel/supergroup](https://core.telegram.org/api/channel).  



## Properties
* `$changeInfo`: `bool` If set, allows the admin to modify the description of the [channel/supergroup](https://core.telegram.org/api/channel)
* `$postMessages`: `bool` If set, allows the admin to post messages in the [channel](https://core.telegram.org/api/channel)
* `$editMessages`: `bool` If set, allows the admin to also edit messages from other admins in the [channel](https://core.telegram.org/api/channel)
* `$deleteMessages`: `bool` If set, allows the admin to also delete messages from other admins in the [channel](https://core.telegram.org/api/channel)
* `$banUsers`: `bool` If set, allows the admin to ban users from the [channel/supergroup](https://core.telegram.org/api/channel)
* `$inviteUsers`: `bool` If set, allows the admin to invite users in the [channel/supergroup](https://core.telegram.org/api/channel)
* `$pinMessages`: `bool` If set, allows the admin to pin messages in the [channel/supergroup](https://core.telegram.org/api/channel)
* `$addAdmins`: `bool` If set, allows the admin to add other admins with the same (or more limited) permissions in the [channel/supergroup](https://core.telegram.org/api/channel)
* `$anonymous`: `bool` Whether this admin is anonymous
* `$manageCall`: `bool` If set, allows the admin to change group call/livestream settings
* `$other`: `bool` Set this flag if none of the other flags are set,
but you still want the user to be an admin: if this or any of the other flags are set,
the admin can get the chat [admin log](https://core.telegram.org/api/recent-actions), get [chat statistics](https://core.telegram.org/api/stats), get [message statistics in channels](https://core.telegram.org/api/stats), get channel members,
see anonymous administrators in supergroups and ignore slow mode.
* `$manageTopics`: `bool` If set, allows the admin to create, delete or modify [forum topics »](https://core.telegram.org/api/forum#forum-topics).
---
Generated by [danog/phpdoc](https://phpdoc.daniil.it)