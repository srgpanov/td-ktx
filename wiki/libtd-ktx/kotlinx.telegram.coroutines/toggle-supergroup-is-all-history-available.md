[libtd-ktx](../index.md) / [kotlinx.telegram.coroutines](index.md) / [toggleSupergroupIsAllHistoryAvailable](./toggle-supergroup-is-all-history-available.md)

# toggleSupergroupIsAllHistoryAvailable

`suspend fun `[`TelegramFlow`](../kotlinx.telegram.core/-telegram-flow/index.md)`.toggleSupergroupIsAllHistoryAvailable(supergroupId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, isAllHistoryAvailable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Suspend function, which toggles whether the message history of a supergroup is available to new
members; requires canChangeInfo rights.

### Parameters

`supergroupId` - The identifier of the supergroup.

`isAllHistoryAvailable` - The new value of isAllHistoryAvailable.