---
title: "checkboxes"
layout: "single"
description: "Checkboxes are used for a list of options where the user may select multiple options, including all or none."
components: true
hidden: true
component: checkboxes
tags: [accessibility]

---

## Accessibility

The checkbox: 

- The checkbox has an accessible label provided by one of the following:  
- Visible text content contained within the element with role checkbox.
- If a set of checkboxes is presented as a logical group with a visible label, the checkboxes are included in an element with role group that has the property aria-labelledby set to the ID of the element containing the label.  
- If the presentation includes additional descriptive static text relevant to a checkbox or checkbox group, the checkbox or checkbox group has the property aria-describedby set to the ID of the element containing the description.  
- Use fieldset to create a checkbox group.  
