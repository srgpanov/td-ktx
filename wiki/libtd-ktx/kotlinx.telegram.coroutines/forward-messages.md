[libtd-ktx](../index.md) / [kotlinx.telegram.coroutines](index.md) / [forwardMessages](./forward-messages.md)

# forwardMessages

`suspend fun `[`TelegramFlow`](../kotlinx.telegram.core/-telegram-flow/index.md)`.forwardMessages(chatId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, fromChatId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, messageIds: `[`LongArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long-array/index.html)`?, options: `[`SendMessageOptions`](https://tdlibx.github.io/td/docs/org/drinkless/td/libcore/telegram/TdApi/SendMessageOptions.html)`?, asAlbum: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, sendCopy: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, removeCaption: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Messages`](https://tdlibx.github.io/td/docs/org/drinkless/td/libcore/telegram/TdApi/Messages.html)

Suspend function, which forwards previously sent messages. Returns the forwarded messages in the
same order as the message identifiers passed in messageIds. If a message can't be forwarded, null
will be returned instead of the message.

### Parameters

`chatId` - Identifier of the chat to which to forward messages.

`fromChatId` - Identifier of the chat from which to forward messages.

`messageIds` - Identifiers of the messages to forward.

`options` - Options to be used to send the messages.

`asAlbum` - True, if the messages should be grouped into an album after forwarding. For this
to work, no more than 10 messages may be forwarded, and all of them must be photo or video messages.

`sendCopy` - True, if content of the messages needs to be copied without links to the original
messages. Always true if the messages are forwarded to a secret chat.

`removeCaption` - True, if media captions of message copies needs to be removed. Ignored if
sendCopy is false.

**Return**
[Messages](https://tdlibx.github.io/td/docs/org/drinkless/td/libcore/telegram/TdApi/Messages.html) Contains a list of messages.
