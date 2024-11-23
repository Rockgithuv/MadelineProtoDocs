---
title: "messages.checkHistoryImport"
description: "Obtains information about a chat export file, generated by a foreign chat app, [click here for more info about imported chats »](https://core.telegram.org/api/import)."
grand_parent: "Telegram RPC API"
parent: "Methods"
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
redirect_from: /API_docs/methods/messages_checkHistoryImport.html
---
# Method: messages.checkHistoryImport
[Back to methods index](index.html)



Obtains information about a chat export file, generated by a foreign chat app, [click here for more info about imported chats »](https://core.telegram.org/api/import).

### Parameters:

| Name     |    Type       | Description | Required |
|----------|---------------|-------------|----------|
|import\_head|[string](/API_docs/types/string.html) | Beginning of the message file; up to 100 lines. | Optional|


### Return type: [messages.HistoryImportParsed](/API_docs/types/messages.HistoryImportParsed.html)

### Can bots use this method: **NO**


### MadelineProto Example ([now async for huge speed and parallelism!](https://docs.madelineproto.xyz/docs/ASYNC.html)):


```php
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$messages_HistoryImportParsed = $MadelineProto->messages->checkHistoryImport(import_head: 'string', );
```
