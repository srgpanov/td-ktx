[libtd-ktx](../index.md) / [kotlinx.telegram.coroutines](index.md) / [getFileDownloadedPrefixSize](./get-file-downloaded-prefix-size.md)

# getFileDownloadedPrefixSize

`suspend fun `[`TelegramFlow`](../kotlinx.telegram.core/-telegram-flow/index.md)`.getFileDownloadedPrefixSize(fileId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, offset: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Count`](https://tdlibx.github.io/td/docs/org/drinkless/td/libcore/telegram/TdApi/Count.html)

Suspend function, which returns file downloaded prefix size from a given offset.

### Parameters

`fileId` - Identifier of the file.

`offset` - Offset from which downloaded prefix size should be calculated.

**Return**
[Count](https://tdlibx.github.io/td/docs/org/drinkless/td/libcore/telegram/TdApi/Count.html) Contains a counter.
