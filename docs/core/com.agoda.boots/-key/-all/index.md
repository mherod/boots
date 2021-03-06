[core](../../../index.md) / [com.agoda.boots](../../index.md) / [Key](../index.md) / [All](./index.md)

# All

`class All : `[`Key`](../index.md)

All key. Used to select all available [bootables](../../-bootable/index.md) in the system.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `All()`<br>All key. Used to select all available [bootables](../../-bootable/index.md) in the system. |

### Inherited Properties

| Name | Summary |
|---|---|
| [isBooted](../is-booted.md) | `val isBooted: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Property that is `true` when all of this key's matching [bootables](../../-bootable/index.md) are in the [booted](../../-status/-booted/index.md) state. |
| [isBooting](../is-booting.md) | `val isBooting: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Property that is `true` when any of this key's matching [bootables](../../-bootable/index.md) are in the [booting](../../-status/-booting/index.md) state. |
| [isFailed](../is-failed.md) | `val isFailed: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Property that is `true` when any of this key's matching [bootables](../../-bootable/index.md) are in the [failed](../../-status/-failed/index.md) state. |
| [isIdle](../is-idle.md) | `val isIdle: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Property that is `true` when all of this key's matching [bootables](../../-bootable/index.md) are in the [idle](../../-status/-idle/index.md) state. |
| [status](../status.md) | `val status: `[`Status`](../../-status/index.md)<br>Property that contains current general [status](../../-status/index.md) of all of this key's matching [bootables](../../-bootable/index.md). |

### Functions

| Name | Summary |
|---|---|
| [equals](equals.md) | `fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.md) | `fun hashCode(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
