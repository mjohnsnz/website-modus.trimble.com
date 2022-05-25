---
title: "Checkboxes"
layout: "single"
description: "Checkboxes are used for a list of options where the user may select multiple options, including all or none."
components: true
hidden: true
component: Checkboxes
tags: [styles]
---

<script>
$('.nav-styles').addClass('active');
</script>

## Specifications

- A switch must have a visible label that clearly conveys what option a user will turn on or off.

![spec](/img/in-field/checkboxes-spec.svg) 

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
+ Indeterminate
+ Indeterminate Focus
+ Indeterminate Disabled
+ Indeterminate Error

#### Checkboxes Progression

![spec](/img/in-field/checkboxes-states.svg) 

**Note:** Focus state uses “global blue”.

#### Labels 
![spec](/img/in-field/checkboxes-labels.svg)

#### Editorial

+ Checkbox labels may be capitalized in 2 ways, depending on their length and placement on the UI:
+ Use title case for short labels (fewer than 3 words) that are to the left or above a checkbox.
+ Use sentence case for longer labels (more than 3 words) that are placed to the right of a check box, especially if the label reads like a phrase.

**Default**

+ Use full sentences with punctuation.
+ If user is consenting to something, start the sentence with “I,” and also run the phrasing you choose by compliance.

**Groups**

+ Use full sentences with punctuation for the checkbox group label.
+ Try to keep checkbox labels brief and start them with verbs.

{{< whats-changed-table >}}
| Date | Version | Notes | Contributors |
| ---------- | ------- | -------------- | ------------ |
| 05/09/2022 | 1.0.1 |Updated full layout. | Mathew Johhs |
{{</ whats-changed-table >}}
