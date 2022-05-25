---
title: "Buttons"
layout: "single"
description: "Buttons are interactive elements that trigger an action or an event."
components: true
hidden: true
component: buttons
tags: [styles]

---

<script>
$('.nav-styles').addClass('active');
</script>

## Specifications

- All buttons should be interactive and perform an action.
- They should be discoverable, easy to identify, and specific.
- Always have a text label within the button container. Icons are optional.
- Make buttons look and feel clickable.
- If using multiple buttons, label them distinctly.
- The size of the buttons should be used in proportion to the context and content around it.

![spec](/img/in-field/btn-spec.svg) 

**Note**: All items spacing is 8px, the stacked buttom is 4px. Incab sizes only, see mobile for smaller options for infield if required

### Behaviors

All buttons (including icon buttons) should have the following states:

- Default
- Hover
- Pressed
- Disabled

#### Color Mix States

![spec](/img/in-field/btn-color-mix-states.svg) 

**Note:** Focus state uses new blue for High contast. 

#### Ancillary Button States

![spec](/img/in-field/btn-ancillary-states.svg) 

Icon button state colors may vary based on product. Always make sure the colors of all states (except for disabled) meet [color contrast accessibility standards](/foundations/accessibility/).

{{< whats-changed-table >}}
| Date | Version | Notes | Contributors |
| ---------- | ------- | -------------- | ------------ |
| 05/09/2022 | 1.0.1 |Updated full layout. | Mathew Johhs |
{{</ whats-changed-table >}}
