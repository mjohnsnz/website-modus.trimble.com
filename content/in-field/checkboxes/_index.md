---
title: "Checkboxes"
layout: "single"
description: "Checkboxes are used for a list of options where the user may select multiple options, including all or none."
components: true
component: Checkboxes
tags: [usage]

---

![spec](/img/in-field/checkboxes-overview.svg)

## Overview

The user can select or alternatively deselect a checkbox. The user may select none, one, or multiple checkboxes, depending on their needs. A partial select is possible where parent/child checkbox lists occur. The state of the Checkbox must be clear to the user. The Checkbox should visually appear to depict if it is in a selected vs deselected state, or enabled vs disabled state

****Note:**** Checkboxes for touch screen apps, this component includes a large, invisible touch target around the Checkbox and Label to ensure highly usab*ility.

## Usage

**When to use**

+ Can be used in forms on a full page, in modals, or on side panels.

+ Filtering and batch action

+ Used to filter data either on a page, in a menu, or within a component. Checkboxes     are found in the Data table for batch editing purposes.

+ Terms and conditions
  Selecting or deselecting the checkbox can indicate whether you agree to the terms. 

+ Lists and tables 

+ Used when there is a parent and child relationship. You can use a parent  checkbox to make a bulk selection of all list items. Unchecking the parent deselects all of the list items. Alternatively, you can select children individually when the parent is not selected, which is where the indeterminate state comes in to play.

**When not to use**

- If a user can select only one option from a list, radio buttons should be used instead of checkboxes. Checkboxes allow the user to select multiple items in a set whereas radio buttons allow the user to select only one option.  
+ Do not use a Checkbox to turn a function on or off.
  
   
  
  ![spec](/img/in-field/checkboxes-example.svg)

{{< whats-changed-table >}}
| Date | Version | Notes | Contributors |
| ---------- | ------- | -------------- | ------------ |
| 05/09/2022 | 1.0.1 |Updated full layout. | Mathew Johhs |
{{</ whats-changed-table >}}
