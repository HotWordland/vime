# Icons

**ID:** `vIcons` | **Type:** [`Plugin`](../../complete/api/plugin.md)

[View Source](../../../vime-complete/src/plugins/Icons.svelte)

This plugin loads the default Vime icons into the browser.

## Defaults

- play
- pause
- captionsOn
- captionsOff
- enterFullscreen
- exitFullscreen
- enterPiP
- exitPiP
- seekForward
- seekBackward
- volumeLow
- volumeHigh
- volumeMute
- settings
- checkmark

## Setup

{% tabs %}
{% tab title="Basic" %}
```js
import { Player, Icons } from '@vime-js/complete';

// ...

const player = new Player({
  target,
  props: {
    plugins: [Icons]
  }
});
```
{% endtab %}

{% tab title="Manager" %}
```js
import { Player, Icons } from '@vime-js/complete';

// ...

player
  .getPluginsManager()
  .addPlugin(Icons)
  .then((icons) => {
    // ...
  });
```
{% endtab %}
{% endtabs %}
