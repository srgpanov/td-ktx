[libtd-ktx](../index.md) / [kotlinx.telegram.coroutines](index.md) / [setUsername](./set-username.md)

# setUsername

`suspend fun `[`TelegramFlow`](../kotlinx.telegram.core/-telegram-flow/index.md)`.setUsername(username: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Suspend function, which changes the username of the current user. If something changes,
updateUser will be sent.

### Parameters

`username` - The new value of the username. Use an empty string to remove the username.