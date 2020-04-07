# MenuItem

**Type:** `Component`

[View Source](../../../../../vime-player/src/plugins/settings/menu/MenuItem.svelte)

A menu list item that may perform an action when clicked.

## Props

{% hint style="info" %}
Any unlisted props are bound directly to the underlying `button` element. This is useful for setting ARIA attributes.
{% endhint %}

### `id`

**Type:** `string|null` | **Default:** `null`

The `id` property of the underlying `button` element.

### `title`

**Type:** `string|null` | **Default:** `null`

The title of the item.

### `hint`

**Type:** `string|null` | **Default:** `null`

Optional text to help give more information about the item.

## Methods

### `getMenuControl`

**Return Type:** [`MenuControl`](./menu-control.md)

The underlying `MenuControl` instance.

## Events

### MenuControl

Forwards all `MenuControl` [events](./menu-control.md#events).