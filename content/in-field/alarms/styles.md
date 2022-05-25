---
title: "Alarms"
layout: "single"
description:"Alarms tell the user of a critical system problem."
components: true
hidden: true
component: Alarms
tags: [styles]
---

<script>
$('.nav-styles').addClass('active');
</script>

## Specifications

![spec](/img/in-field/alarm-spec.svg) 

**Note:** Incab sizes only, see mobile for smaller options for infield.

### Behaviors

All buttons (including icon buttons) should have the following states:

+ Alarms indicate that a show-stopping condition exists—the operator may NOT continue to work
+ The system is unable to function until the underlying issue is addressed. Unresolved Alarms will also appear in the Alarms & Alerts message tray under the Bell icon in the Action bar
+ Unresolved Alarms that are related to onboard devices, or other configuration errors will result in red Dashboard tiles
+ Unresolved alarms may also result in error messages in the System Status screen, or Form Validation errors in Job Setup screens

Persistent: Yes.
**Visibility:** Full Screen. Remains visible until acknowledged.
**Actions:** Can have one button (e.g. OK) or two (rare).
**Shade rest of screen:** N/A - alarm is a full screen message.
**Audio:** One long continuous beep on entry.
**Message Centre:** Recorded in the log. Active until resolved, badge number on bell.

#### Editorial

+ Messages should be brief, full sentences, with proper punctuation.
+ They should provide the user with helpful, contextual information about a possible action or a set of data.

{{< whats-changed-table >}}
| Date | Version | Notes | Contributors |
| ---------- | ------- | -------------- | ------------ |
| 05/09/2022 | 1.0.1 |Updated full layout. | Mathew Johhs |
{{</ whats-changed-table >}}
