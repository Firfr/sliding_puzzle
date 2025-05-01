sliding_puzzle
==============



## 原项目README

A simple sliding blocks puzzle game. You can also create your own puzzle and then click on "Get Url" to get 
a link which will recreate the puzzle whenever someone clicks on it.   
一个简单的滑动方块拼图游戏。你也可以自定义自己的拼图，然后点击 "Get Url" 按钮生成一个链接，
任何人点击这个链接都可以还原你当前的拼图布局。

Here's a tiny commentary about the coding style. I have, in a long time, deviated from using separate screens 
and provided you with a game in its first screen. I was trying to emulate the actual hardware toy of 
the same game which is just there and does not have a Main Menu. One of the consequences of this approach  
这里有一段关于代码风格的小评论：我已经很久没有采用“多页面分离”的方式来开发了，
这次我尝试直接呈现游戏的第一个界面，而非主菜单。
我是想模仿现实中那种实体玩具——它就在那里，没有多余的菜单界面。

is a few lines (maybe more than a few) of repeated code and inefficient algorithms. 
If you go through the code of game.js file, you'll see a lot of places where you may go "WHY!?" and in certain cases, 
I've genuinely forgotten why,  even though the I made the whole game in less than a day.   
这种设计方式的一个后果是出现了几行（可能不止几行）重复的代码，
以及一些效率并不高的算法。
如果你阅读 game.js 文件中的代码，会有很多地方让你忍不住问：“为什么这么做！？”
而在某些情况下，我自己甚至也已经忘记了当初这么写的理由了，
尽管整个游戏是我不到一天的时间内完成的。

So please forgive the crass coding and try and enjoy the game!

所以，请原谅这些粗糙的代码，尽量享受这个游戏吧！
