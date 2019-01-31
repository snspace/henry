---
layout: post
author: Henry Ma
---

> [JSON-Server](https://github.com/typicode/json-server): Get a full fake REST API with zero coding in less than 30 seconds (seriously)

> Created with <3 for __front-end developers__ who need a __quick back-end__ for __prototyping and mocking__. :rocket:

![JSON Server](/assets/images/JSON Server.png)

:warning: **_For Real Production_**
> * The focus on prototyping and mocking may implies that it's not tuned for serious production.
> * Based on the latest version(0.14.2 - 2018.12.27), __cli__ uses __FileASync__ adapter, while __server__ seems like only exposes __FileSync__, and the __lowdb__ which is the storage backend suggests __FileAsync__ adapter for concurrency which is reasonable for real production.
> * If you really use it for real production, you may end up *doing custom programming*, which sometimes involves working with the underlying [lowdb](https://github.com/typicode/lowdb).


> :whale: This is part of the [__A Search For JSON Storage as a Service__](/2019/01/23/A-Search-For-JSON-Storage-as-a-Service.html).