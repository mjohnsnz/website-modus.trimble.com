---
title: "Alarms"
layout: "single"
description: "Alarms tell the user of a critical system problem."
components: true
component: Alarms
tags: [usage]

---

![spec](/img/in-field/alarm-overview.svg)

## Overview

An Alarm tells the user of a critical system problem that causes the system to not function correctly in a fundamental way and should stop work. Alarms always have an "error" status type since it always relates to an important system issue where something has gone wrong. 

It is likely that the software will not be able to function correctly so the user is kept out of most parts of the UI. Making the alarm dismissible relies on there being a place outside the main UI that the user can be kept in until the system returns to an operable state. For example, in Earthworks, this is the "Dashboard".

**Note:** An alarm is the most serious and significant form of system status communicated in our interfaces.  Alarms must be very carefully considered. A cross-discipline team is typically consulted to identify situations requiring an alarm

## Usage

**When to use**

+ There is a system critical action the user must take. The user must stop work and immediately attend to a problem or error.

**When not to use**

- The user should attend to the issue but can carry on working for a time until the issue is resolved and/or the UI can sensibly be rendered while the issue is in play. A Prompt is a better choice here.  
- Do not use an Alarm if there is minor information that is "nice-to-know" but does not require the user to take any action. Use a Notification for such scenarios where basic information is conveyed to the user, but such information does not require user action.

![spec](/img/in-field/alarm-landscape-portrait.svg)

{{< whats-changed-table >}}
| Date | Version | Notes | Contributors |
| ---------- | ------- | -------------- | ------------ |
| 05/09/2022 | 1.0.1 |Updated full layout. | Mathew Johhs |
{{</ whats-changed-table >}}
