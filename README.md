
（邪恶的）兔宝宝木马 - Evil Bunny Trojan
=================

A simple trojan keylogger written in Python, disguised as an animated ASCII
bunny (made for pedagogical purposes)

一个简单的键盘记录木马，用Python编写，用了一个会动的兔宝宝（ASCII码）作为伪装

It uses [this small keylogging python lib](https://github.com/amoffat/pykeylogger)

它使用了[这个小小的Python键盘记录库](https://github.com/amoffat/pykeylogger)

使用方法 - Usage
-----

Command：“本工具只能跑在linux下，因为依赖的库只是用了X11的api”

- In a first console, type `python evilBunnyServer.py`
- In another console, type `python evilBunnyTrojan.py`
- Get ~~hyptnotized~~ hypnotized by the dancing bunny
- Press keys anywhere in your OS and watch the server getting logs of which
  keys you pressed


- 在第一个终端中，输入`python evilBunnyServer.py`，回车
- 在另一个终端里，输入`python evilBunnyTrojan.py`，回车
- 在第二步的终端（Trojan）里看见一个魔性的跳舞兔宝宝
- 在你系统的任何地方按下按键，并在第一个终端（Server）里看见你按下的键已被记录。

Forked & Translated by Command
-----

因为觉得挺好玩所以就Fork了

随手翻译。
