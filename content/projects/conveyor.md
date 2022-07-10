---
title: Conveyor
date: 2020-01-17T22:19:01-07:00
draft: false
---

[Conveyor](https://github.com/autoinvent/conveyor) is a series of frontend libraries for building an [AutoInvent](https://github.com/autoinvent)
(which is a portmanteau of Automatic Inventory) application. It contains the following packages:

- [conveyor](https://github.com/autoinvent/conveyor/tree/main/packages/conveyor#readme) is a dashboard generator
for inventory data
- [conveyor-redux](https://github.com/autoinvent/conveyor/tree/main/packages/conveyor-redux#readme) generates reducers
and epics for use with conveyor
- [conveyor-schema](https://github.com/autoinvent/conveyor/tree/main/packages/conveyor-schema#readme) is a schema helper
library for conveyor
- [magql-query](https://github.com/autoinvent/conveyor/tree/main/packages/magql-query#readme) is a query builder and
request tool for communicating with a [magql](https://github.com/autoinvent/magql) backend

My contributions to conveyor were mostly to conveyor and conveyor-redux. For conveyor-redux I added automatic generation
of epics and reducers for sorting, filtering, and tooltips. For conveyor I added the ability to automatically show the
Footer component if there was an item that was summable (ie prices) and properly formatted prices in the Footer using
locale information.

You can find all my commits to the repository on the [conveyor GitHub page](https://github.com/autoinvent/conveyor/commits?author=biehlerj)

Skills used:

- JavaScript
- TypeScript
- React
- Redux
- Ramda
