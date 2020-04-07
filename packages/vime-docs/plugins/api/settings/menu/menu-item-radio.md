# MenuItemRadio

**Type:** `Component`

[View Source](../../../../../vime-player/src/plugins/settings/menu/MenuItemRadio.svelte)

A menu radio button used to select a particular value from a group of values.

## Props

### `title`

**Type:** `string|undefined` | **Default:** `undefined`

The title of the radio button.

### `value`

**Type:** `any` | **Default:** `undefined`

The value of the radio button.

### `group`

**Type:** `any` | **Default:** `undefined`

The current group value.

### `badge`

**Type:** `string|null` | **Default:** `null`

Optional text used to give more context to the value associated with the button.

### `getMenuControl`

**Return Type:** [`MenuControl`](./menu-control.md)

The underlying `MenuControl` instance.

## Events

### MenuControl

Forwards all `MenuControl` [events](./menu-control.md#events).

### `valuechange`

**Data Type:** `any`

Fired with the `value` of the radio button when it is clicked.