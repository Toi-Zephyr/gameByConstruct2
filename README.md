# The Aline from the Moon.
> A game by construct 2

[![Travis](https://img.shields.io/travis/rust-lang/rust.svg)](https://github.com/Toi-Zephyr/gameByConstruct2)
[![Travis](https://img.shields.io/badge/License-GPL--v3-green.svg)](https://github.com/Toi-Zephyr/gameByConstruct2/blob/master/LICENSE)
[![Travis](https://img.shields.io/badge/web-zephyr.today-blue.svg)](http://zephyr.today/game)

## 项目简介

------

### 角色设计

+ a) 楔子:来自外太空的小朋友误入地球上的几处奇妙的地方,这 里有怪物、不知名的小花和许多“台阶”......外星人的身体构 造跟我们不同,它们不能吸入氧气。每碰到怪物一次,它戴的 头罩就会破损一些;如果掉下“台阶”,头罩就会整个破损。 好在还有不知名的小花,它能解除部分氧气给外星人身体带来 的负面影响。重重关卡,外星人能不能回到它的家园呢......

+ b) 玩法:玩家用键盘方向键“↑”、“←”、“→”(手机用户点击 屏幕中显示的方向按钮)控制外星人跳跃或左右移动,通过所 有关卡后任务完成,生命值为 0 则任务失败。玩家使用方向键 在台阶上行走,避开怪物,寻找小花,通过关卡。当玩家跳到 怪物头顶时,怪物死亡。关卡不断更新,目前更至第三关,每 一关都会有新的挑战......

------

### 精灵描述

+ A.外星人:初始生命值为 3,可以承受怪物的三次触碰。它可以左右移动和跳跃,掉下“台阶”后生命值归零,死亡。
+ B.台阶:有很强生命值,可承受多次撞击。
+ C.不知名小花:随机出现,外星人获得后生命值加一。
+ D.按钮:手机玩家可点此按钮,随后屏幕会出现方向键按钮,即 可借此控制外星人。
+ E.方向键按钮:手机玩家点此按钮,便可控制外星人的行动。
+ F.生命值:用爱心表示,初始值为 3。被怪物触碰一次减一,吃到 不知名小花后加一。外星人掉下台阶生命值清零。
+ G.月球:外星人通过这一关卡所有台阶后,便会遇到。走进月球, 便能进入下一关卡,离家园更进一步。
+ H.怪物:在第二关之后出现。在部分台阶上左右“巡逻”,外星人 被触碰后生命值减一。怪物头部被外星人踩到后死亡。
+ I.可移动台阶:在第三关出现。台阶会左右来回移动。有两种形式 的移动方式。
+ J.水流:第二关出现。外星人碰到水流,每三秒会减一点生命值。
+ K.火焰:第三关出现。外星人碰到火焰,每一秒会减一点生命值。
+ L.喷火怪物:第三关出现。以一定的频率喷射火球,外星人接触 到火球就会减一点生命值。
+ M.易碎台阶:第三关出现。外星人接触此台阶三秒后,台阶便会 破碎,外星人有掉下去的危险。
+ N.冰渣台阶:第三关出现。外星人站在此台阶上,每三秒会减一 点生命值。
+ O.蜡烛:站到蜡烛上,就能进入第四关,离家园更近一步。
   