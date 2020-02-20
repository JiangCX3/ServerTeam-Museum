# ServerTeam-Museum
ServerTeam历史博物馆，我们的历史将永远被保存在这个Github仓库里。

任何ServerTeam成员均有权编辑ServerTeam博物馆。

我们计划在某一天，将编辑完成的博物馆印刷成册，让我们的记忆永远保存在纸上。


## 编辑指南
请仔细阅读编辑指南，再编辑博物馆中的条目。

条目以Markdown的形式编辑、储存与修改。

`/Entries`为条目储存目录，请直接将条目的Markdown文件放置在条目目录中。

`/PageGenerator/run.py`为条目HTML生成器，每次当新增、修改或删除完条目后，
请务必使用`Python3.7.0`运行生成器，然后再commit.

`/html/entry-menu.json`为条目目录，供博物馆网站的js使用，在运行生成器后会自动更新。

`/files`用来储存条目中的一些文件，killlove源码之类的都储存在里面。
