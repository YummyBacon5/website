---
slug: introducing-flet
title: Introducing Flet
author: Feodor Fitsner
author_title: Flet founder and developer
author_url: https://github.com/FeodorFitsner
author_image_url: https://avatars0.githubusercontent.com/u/5041459?s=400&v=4
tags: [news, product]
---

Today we announce the first release of Flet!

Flet is a framework for building real-time web, desktop and mobile applications in Python.

No more complex architecture with JavaScript frontend, REST API backend, database, cache, etc. With Flet you just write a monolith stateful app in Python only and get multi-user, realtime Single-Page Application (SPA) or a mobile app.

To start developing with Flet, you just need your favorite IDE or text editor. No SDKs, no thousands of dependencies, no complex tooling - Flet has built-in web server with assets hosting and desktop clients.

Flet UI is built with [Flutter](https://flutter.dev), so your app looks professional and can be delivered to any platform. Flet simplifies Flutter model by combining smaller "widgets" into ready-to-use "controls" with imperative programming model.
You get all the power of Flutter without having to learn Dart!

Flet app is deployed as a regular web app and can be instanly accessed with a browser or installed as a [PWA](https://web.dev/what-are-pwas/) on a mobile device. Web app also exposes an API that can be used by a Flet client (planned for [future releases](/docs/roadmap)) running on iOS and Android and providing native mobile experience.

Some examples:

* [Greeter](https://github.com/flet-dev/flet/blob/main/sdk/python/examples/apps/greeter/greeter.py)
* [Counter](https://github.com/flet-dev/flet/blob/main/sdk/python/examples/apps/counter/counter-home.py)
* [To-Do](https://github.com/flet-dev/flet/blob/main/sdk/python/examples/apps/todo/todo.py)
* [Icons Browser](https://github.com/flet-dev/flet/blob/main/sdk/python/examples/apps/icons-browser/icons-browser.py) ([Online Demo](https://flet-icons-browser.fly.dev/))

[Give Flet a try](/docs/getting-started/python) and [let us know](https://discord.gg/dhYUcB3R) what you think!
