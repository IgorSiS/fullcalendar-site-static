---
title: firstHour
since_version: 1.4
---

Determines the first hour that will be visible in the scroll pane.

<div class='spec' markdown='1'>
Integer, *default*: `6`
</div>

Values must be from 0-23, where 0=midnight, 1=1am, etc.

The user will be able to scroll upwards to see events before this time. If you want to prevent users from doing this, use the [minTime](minTime) option instead.
