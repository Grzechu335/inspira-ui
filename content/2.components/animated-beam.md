---
title: Animated Beam
description: An SVG beam connecting elements with animation.
---

::ComponentLoader{label="Preview" componentName="AnimatedBeamDemo" type="examples"}
::

## API

| Prop Name            | Type          | Default                | Description                                                                  |
| -------------------- | ------------- | ---------------------- | ---------------------------------------------------------------------------- |
| `class`              | `string`      | `""`                   | Additional CSS classes to apply to the component for customization.          |
| `containerRef`       | `HTMLElement` | N/A                    | Reference to the container element where the beam is rendered.               |
| `fromRef`            | `HTMLElement` | N/A                    | Reference to the starting element from which the beam originates.            |
| `toRef`              | `HTMLElement` | N/A                    | Reference to the ending element where the beam points to.                    |
| `curvature`          | `number`      | `0`                    | Controls the curvature of the beam; higher values create a more curved path. |
| `reverse`            | `boolean`     | `false`                | Reverses the animation direction of the beam if set to `true`.               |
| `pathColor`          | `string`      | `"gray"`               | Color of the beam's path.                                                    |
| `pathWidth`          | `number`      | `2`                    | Stroke width of the beam's path.                                             |
| `pathOpacity`        | `number`      | `0.2`                  | Opacity of the beam's path.                                                  |
| `gradientStartColor` | `string`      | `"#FFAA40"`            | Starting color of the beam's gradient animation.                             |
| `gradientStopColor`  | `string`      | `"#9C40FF"`            | Ending color of the beam's gradient animation.                               |
| `delay`              | `number`      | `0`                    | Delay before the beam's animation starts, in seconds.                        |
| `duration`           | `number`      | `Random between 4–7 s` | Duration of the beam's animation cycle, in seconds.                          |
| `startXOffset`       | `number`      | `0`                    | Horizontal offset for the beam's starting point.                             |
| `startYOffset`       | `number`      | `0`                    | Vertical offset for the beam's starting point.                               |
| `endXOffset`         | `number`      | `0`                    | Horizontal offset for the beam's ending point.                               |
| `endYOffset`         | `number`      | `0`                    | Vertical offset for the beam's ending point.                                 |

## Example

Double-sided beam.

::ComponentLoader{label="Preview" componentName="AnimatedBeamDemo2" type="examples"}
::

## Component Code

You can copy and paste the following code to create this component:

::CodeViewer{filename="AnimatedBeam.vue" language="vue" componentName="AnimatedBeam" type="ui" id="animated-beam"}
::

## Features

- **Dynamic Beam Drawing**: Automatically renders a beam between two specified elements on the page.
- **Smooth Animation**: Features a gradient animation that flows along the beam's path for a visually engaging effect.
- **Customizable Appearance**: Easily adjust color, width, opacity, and curvature to match your design requirements.
- **Responsive Updates**: The beam adjusts its position and size in response to window resizing and element repositioning.
- **Flexible Animation Control**: Customize the animation's duration, delay, and direction for precise timing.

## Credits

- Inspired and ported from [Magic UI Animated Beam](https://magicui.design/docs/components/animated-beam).