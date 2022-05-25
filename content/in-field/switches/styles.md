---
title: "Switches"
layout: "single"
description:"Switches are used to toggle functionality."
components: true
hidden: true
component: Switches
tags: [styles]
---

<script>
$('.nav-styles').addClass('active');
</script>

## Specifications

- A switch must have a visible label that clearly conveys what option a user will turn on or off.

![spec](/img/in-field/switches-spec.svg) 

**Note:** Incab sizes only, see mobile for smaller options for infield.

### Behaviors

All checkboxes should have the following states:

+ Active
+ Active Focus
+ Active Disabled
+ Active Error
+ Default
+ Default Focus
+ Default Disabled
+ Default Error

#### Checkboxes Progression

![spec](/img/in-field/switches-states.svg) 

**Note:** Focus state uses “global blue”.

#### Labels & Icons

![spec](/img/in-field/switches-states.svg) 

#### Editorial

+ Avoid acronyms.
+ Use 2-5 words.
+ Use the same label text for on and off states

{{< whats-changed-table >}}
| Date | Version | Notes | Contributors |
| ---------- | ------- | -------------- | ------------ |
| 05/09/2022 | 1.0.1 |Updated full layout. | Mathew Johhs |
{{</ whats-changed-table >}}
