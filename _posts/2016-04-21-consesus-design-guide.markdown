---
layout:     post
title:      "一致性原则是条万能法则吗"
date:       2016-04-21 12:00:00
author:     "Austina W"
header-img: "img/post-bg-nextgen-web-pwa.jpg"
header-mask: 0.3
tags:
    - 设计原则
    - 交互设计
---





一致性原则是条万能法则吗？

答案一定是否定的！

为啥？

因为高中生物老师曾教育我，做选择题的时候，说的太绝对的选项一定是错的。

好吧，这句话也挺绝对的。

**Anyway**

我们通常会认可一致性在设计中是一条很重要的原则。在用户的角度，它有助于用户可以直觉性的理解页面，支持其经验的复用，某种程度上减少其在记忆与认知上的负担。在开发的角度而言，维护使用统一的控件库是很重要的一件事，很有效的降低了开发成本。P.S.工具化的思维真的很有效率，作为没有点亮开发技能的设计师，利用各种工具整理图片文字等一些素材还是蛮有意思的一件事。就算随意翻翻一般的可用性原则里或设计规范，大多都会找到一致性这条原则。

所以，问题来了，这条到处见的法则万能吗？回答这个问题，先需要看哈这条原则的正确打开方式。

## 看着长一样

人都是视觉动物，所以对于一致性而言，看起来最基本的似乎就是长得一样。下面是几条刚好早上看文章的时候看的几条tips，帮助你建立设计的一致性。

> Here’s a few tips from the e-course on how to make your design consistent:
>
> - Introduce strong visual hierarchy, with the most important things big and bold
> - Align everything nicely along the grid, or introduce any other kind of visual order
> - Use a consistent color scheme throughout the app
> - Keep the navigation consistent across all screens
> - Re-use the same elements for different situations. For example, design a sample notification and color-code it for different situations.

看起来并不是很难，但其实保持长得一样这件事并不容易。同一个控件并不是总能支持不同场景下的任务。比如当一个下拉菜单需要承载的信息量加大的时候，可能需要开始对其中的内容进行分类，或者增加搜索功能的支持，那么对应的数据库内的表是否可以很好的支持这一功能。再或者这个控件将无法承载该功能的需求，需要更换控件，或者此时使用其他控件将会更符合场景的使用特点，从而为用户创造更为清晰的体验流程。因此，就好像salesforce在建立设计原则时，一致性很重要但并不是第一位的。p.s.这个Lightning Experience的设计感觉真的还蛮讨我喜欢的。

> At one point, while designing Lightning Experience, there was a big debate over how we should label a feature. Hours and hours were spent discussing the merits of one label versus another. Sleep was lost. Then we decided that to figure it out, we needed to go back to basics and back to our design principles.
>
> Our question came down to whether we were comfortable with some inconsistency in the naming convention of two similar features, or if the inconsistent label’s clarity for users in that particular context outweighed the negatives of an inconsistent name. Clarity is design principle #1, consistency is #3. Decision made.

当一致性的保障开始会影响到界面理解的清晰的时候，可以考虑使用不一致的界面元素以保证用户对于界面的快速理解，从而减少学习成本。这里就涉及到一个很有意思的话题，一致性对于易学性与易用性的影响。体现的不止是长得一样这件事，而是内部逻辑的一致性。

## 逻辑保持一致

举一个我猜你一定听过的例子。普通的一个家庭中可能有很多不同种类的刀，有切水果的、有切菜的、有抹黄油的、有切面包的。。。总之种类很多。按照一致性的原则，似乎应该把它们放在一个地方，因为他们有一个分类叫做刀嘛。而且具有较高的易学性，想找刀都去一个地方就好了。但是也许他们的尺寸并不适合收纳在同一个地方，而且他们的使用场景是有一定差异的，有的刀的使用场景集中在客厅和餐厅，有的则集中在厨房。如果按照使用场景划分，这些刀应该被储存在不同的地方，易用性会提高，因为其的储存位置符合了人们使用的需求，但并不利于统一的管理机制的建立。对于初次使用的用户而言，因为使用经验可能不能很好的复用，会降低易学性。但其实其内部的逻辑上一致的，以使用场景作为储存位置的判断标准。但相较于长得一样这种一致性而言，内部的一致性是很难被注意到的。

所以不要因为追求一致性，而限制了设计的方式，这也是salesforce团队并没有将一致性的优先级排在原则中的第一位。在这方面design think提供了一种很好的思维方式 ——在Ideate的阶段不拒绝任何可能的想法，尤其是内些看起来不大可能的方式，然后通过prototype的方式去验证。可能会带来不一样的想法。

所以你认为一致性的思维对于扩展设计思路这事没有帮助吗？

**too young, too simple, sometimes naive.**

## 其实人人都爱一致性

一致性除了可以用于虚拟世界以外，还明显存在于物理世界中，所以在物理世界与虚拟世界之间也一定是存在的。

从最早的纸质地图到电子地图，再到基于移动设备发展的移动地图，随着使用场景的不同，满足了用户不同的需求特性，但其作为地图的界面理解方式还是延续了最初的地图概念——这个人们比较熟悉的的事物。好吧，这事有个学术名词，叫界面比拟，啥意思？

看个案例。P.S.顺手安利下这个质量比较高的weekly redesign challenge，虽然PO主已弃坑。

[https://medium.com/weekly-redesign-challenge/redesign-challenge-6-52-nest-for-iphone-d322c6778941#.ao3g2tel1](https://medium.com/weekly-redesign-challenge/redesign-challenge-6-52-nest-for-iphone-d322c6778941#.ao3g2tel1)

## 片尾彩蛋

最近在写论文，有个部分叫做文献参考，据说有装逼的作用，所以。。。

> http://dl.acm.org/citation.cfm?doid=67933.67934                    
>
> http://www.id-book.com/chapter2_assignment.php
