---
title: "Messages"
layout: "single"
description: "Messages provide the user with contextual static information. They have a lower priority than a notification or prompt."
components: true
component: Messages
tags: [usage]

---

![spec](/img/in-field/messages-overview.svg)

## Overview

Messages are used within other elements to convey status and helpful information in an unobtrusive way. Messages display low priority content directly on the screen and are not interactive or dismissible. Messages provide supporting information or additional instruction about a data set, dialog, or screen. Messages are typically displayed at the top of the screen and convey information or status about the screen content as a whole.

## Usage

**When to use**

+ Providing the user with helpful, contextual information about a possible action, set of data, or screen.

**When not to use**

- Alerting the user of a high priority warning or error. Instead, use an Alert.  

- Alerting the user of an out-of-context event. Instead, use a Notification.  

- Do not use a Message if there is a system-critical action the user must take. 
  If the user should stop work and immediately attend to a problem or error, 
  use an Alarm.  

- Do not use a Message when you need to communicate contextual information or status about an input field component. Use Helper Text instead.

![spec](/img/in-field/messages-states.svg)

{{< whats-changed-table >}}
| Date | Version | Notes | Contributors |
| ---------- | ------- | -------------- | ------------ |
| 05/09/2022 | 1.0.1 |Updated full layout. | Mathew Johhs |
{{</ whats-changed-table >}}
