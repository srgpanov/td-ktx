[libtd-ktx](../index.md) / [kotlinx.telegram.coroutines](index.md) / [searchChatRecentLocationMessages](./search-chat-recent-location-messages.md)

# searchChatRecentLocationMessages

`suspend fun `[`TelegramFlow`](../kotlinx.telegram.core/-telegram-flow/index.md)`.searchChatRecentLocationMessages(chatId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, limit: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Messages`](https://tdlibx.github.io/td/docs/org/drinkless/td/libcore/telegram/TdApi/Messages.html)

Suspend function, which returns information about the recent locations of chat members that were
sent to the chat. Returns up to 1 location message per user.

### Parameters

`chatId` - Chat identifier.

`limit` - The maximum number of messages to be returned.

**Return**
[Messages](https://tdlibx.github.io/td/docs/org/drinkless/td/libcore/telegram/TdApi/Messages.html) Contains a list of messages.
