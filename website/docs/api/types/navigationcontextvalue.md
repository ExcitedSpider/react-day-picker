---
id: "navigationcontextvalue"
title: "Type alias: NavigationContextValue"
sidebar_label: "NavigationContextValue"
custom_edit_url: null
hide_title: true
---

# Type alias: NavigationContextValue

Ƭ **NavigationContextValue**: *object*

#### Type declaration:

Name | Type | Description |
:------ | :------ | :------ |
`displayMonths` | Date[] | The months to display, according to `numberOfMonths`.   |
`month` | Date | The current month. Note that when `numberOfMonths > 1` represent the first month in the displayed months.   |
`nextMonth`? | Date | The next month to display. `undefined` if no months left   |
`previousMonth`? | Date | The previous month to display. `undefined` if no months left   |
`setMonth` | (`month`: Date) => *void* | Navigate to the specified month.   |
