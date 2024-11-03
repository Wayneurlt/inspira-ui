---
title: Ripple
description: An animated ripple effect typically used behind elements to emphasize them.
navBadges:
  - value: New
    type: lime
---

::ComponentLoader{label="Preview" componentName="RippleDemo" type="examples" id="ripple"}
::

## API

| Prop Name       | Type     | Default | Description                             |
| --------------- | -------- | ------- | --------------------------------------- |
| `circleSize`    | `number` | `210`   | The size of the main circle in pixels.  |
| `circleOpacity` | `number` | `0.24`  | The opacity of the main circle.         |
| `count`         | `number` | `8`     | The number of ripple circles to render. |

## Component Code

You can copy and paste the following code to create these components:

::CodeViewer{filename="Ripple.vue" language="vue" componentName="Ripple" type="ui" id="ripple"}
::

## Features

- **Slot Support**: Easily add any content inside the component using the default slot.

## Credits

- Credits to [Magic UI](https://magicui.design/docs/components/ripple).
- Credits to [SivaReddy Uppathi](https://github.com/sivareddyuppathi) for porting this component.