+++
date = "2023-09-21"
title = "Projects"
description = "Projects"
categories = ["Programming"]
authors = ["Ahmet Enes Bayraktar"]
lastmod = "2023-09-21"
+++

## [signalr_dart](https://github.com/aeb-dev/signalr_dart)

A SignalR client in dart. It supports all the features of the C# client as long as Dart allows.

## [steamworks_gen](https://github.com/aeb-dev/steamworks_gen)

A generator for Steamworks SDK. It parses the file provided by Steam to generate related APIs in dart in a darty way.

## [steamworks](https://github.com/aeb-dev/steamworks)

The output of the [steamworks_gen](https://github.com/aeb-dev/steamworks_gen)

## [flame_steamworks](https://github.com/aeb-dev/flame_steamworks)

Integrates [steamworks](https://github.com/aeb-dev/steamworks) with [flame-engine](https://github.com/flame-engine/flame/)

## [json_events](https://github.com/aeb-dev/json_events)

There is no way to parse large json object/files in dart because you need to allocate everything in memory beforehand. With this library, you can parse in a streaming way, therefore the size is not important

## [msg_pck](https://github.com/aeb-dev/message_pack_dart)

A [MessagePack](https://msgpack.org/index.html) de/serializer. It has a similar API like [MessagePack-CSharp](https://github.com/MessagePack-CSharp/MessagePack-CSharp)

## [tmx_parser](https://github.com/aeb-dev/tmx_parser)

Let's you parse a map from [Tiled Map Editor](https://www.mapeditor.org/). Both `json` and `tmx` files are supported. The size of the file is not important as the library uses [json_events](https://github.com/aeb-dev/json_events)

## [flame_forge2d_tiled](https://github.com/aeb-dev/flame_forge2d_tiled)

Automatically creates a physical world from the provied [Tiled Map Editor](https://www.mapeditor.org/) map. It uses [tmx_parser](https://github.com/aeb-dev/tmx_parser)
