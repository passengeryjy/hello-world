# hello-world
作为一个业余爱好者，未来的专业人员，在经过不懈的搜寻，总算找到了一个新手小白看得懂的github的生动教程
在此借来并稍加修改教程如下：
#什么是 Github ？
（需要加图）
必须要放这张图了！！！
（图片来源（图片来源GitHub 是怎样的一个存在？ - Deep Reader 的回答）
Git 是由 Linux 之父 Linus Tovalds 为了更好地管理linux内核开发而创立的分布式版本控制／软件配置管理软件。

好吧，我相信看到这里你已经晕了，这也是我一开始看那些所谓经典教程的感受。写这些教程的人都是几年以上的程序员呀，他们往往直接就告诉你所有命令的含义或者整个体系。
专家盲点（expert blind spot）就是对一个事物知道的越多，就越发不记得“不知道这个事”的情形。

简单来说，Git 是一个管理你的「代码的历史记录」的工具。
我不是程序员为什么要学这个啊啊啊！又不要管理代码们！我不是程序员为什么要学这个啊啊啊！又不要管理代码们！

别急，虽然 github 学习门槛高，一会你就知道为什么人人都应该会这个啦！

----------------------------
学习步骤

##注册安装
去官网注册一个账号（这个你应该会，恩就不放链接了）
然后，下载一个GitHub Desktop mac客户端是最方便的啦！（命令行什么的真的是会越来越晕！先别管他们！）
（此处不加图了）
--
(⊙v⊙)嗯！终于可以正式开始了！

#step1:创建新项目
我们三个人在不同的城市要远程共同写一本书，要有一个漂亮的笔记本吧？


「repositories」就是你的笔记本们。你只需知道 Repository 是个放项目的地方就行。有时候会出现 Repositories，是多个 Repository 的意思。

**fork**
如果你不想新建一个笔记本，看到小四之前写过一个好到炸裂的文章，想把他的直接全部偷过来，修改修改就成你自己的文章了，这应该怎么办呢？
github 还提供了一个很赞的功能叫做 fork ，你只需要点击这个神奇的按钮，就可以把他的「笔记本」变成你自己的啦！任意修改都可以哦~



#step2：把「笔记本」克隆到本地
「笔记本」在云端，你要把它摘下来放到自己的电脑上写小说才方便呀，在这里我们叫「clone」是不是很形象？步骤如图：
或者是直接去我们的客户端或者是直接去我们的客户端


#step3：可以开始写作啦！
你的笔记本里已经自动有一个文档了，这个时候让我们回到网页版[微笑脸]
你只需要在 web 端点开这个README.md可以开始在里面写你的小说了。

或者直接点开刚刚 clone 到电脑上的文件夹直接在里面写。
ps:需要注意的是，文本支持 markdown 格式，可以先参考这个献给写作者的 Markdown 新手指南。

#step4:上传你写的小说
在本地写完之后你要上传到云端让我和小四都能看见你写出什么幺蛾子了吧？
回到客户端，你发现有变化！！！

没错，在你头像旁边给你这次提交内容起一个名字，以后如果再次寻找的时候会很方便。然后点下面的 Commit to master，还有右上角的 Sync 就好啦！

#step5：回退到之前的版本
夜深人静的时候，我趁着你们都在睡觉把小说的结局偷偷地改成女主死掉了！
你醒来觉得我这结局改的也太悲伤了，完全不能接受！结局必须要和之前那样王子公主幸福的生活在一起的 happy ending！
问题又来了，怎么退回到我修改结局之前的 happy ending？

还是刚刚那个客户端，选择History 然后点击小齿轮，选择潇洒地点 roll back to this commit！
你又回到happy ending的状态啦！！


#step6：
小四写了一章华丽无比的番外，你要更新本地的小说和他写的保持一致怎么办？
git pull


-----------
好了，知道这些基本操作入门应该够了，我们来回顾一下（不要嫌弃我的画工啊喂！）


入门初期迅速得到一些正反馈对于学习一门新技能来说实在是太重要了！尤其是编程这么炫酷的事情！
所以先不要管什么复杂的 issue 呀 wiki 呀乱七八糟的操作，按照上面的一步一步来，如果遇到什么问题 google 之，一般都会解决的。

有一个段子不就是说，当你遇到问题去找最高级的工程师，他们一般都会直接 google 吗？而且自带的帮助手册也是解决问题的好办法，比如你要新建一个 branch=》Create a new branch with git and manage branches · Kunena/Kunena-Forum Wiki · GitHub

这种遇到问题先自己尝试解决的小技巧，也是我自从学编程以来最大的收获。

------------------------

#除了写代码你还可以用 github 做什么？

回到文章开头，我又不是程序猿不用写代码玩这个干啥？

你有没有碰到过团队里几个人共同协作写一个文档的时候？或者说需要反复修改的东西？比如最简单的写论文，用 word 保存一个一个版本 e-mail 给 boss？下次再找上次修改了什么地方简直要死啊有木有！！！

相信你看了我的远程协作写小说的例子应该已经明白了， github 说白了就是一个「版本控制工具」。我们所谓的「回退」到历史记录，随时查看更改了什么地方，利用这个功能可以做的事情简直太多啦！

就像 github 其中一位创始人[Chris](defunkt (Chris Wanstrath) · GitHub)也详细描述了[GitHub初创的前因后果](Startup Riot 2009 Keynote 路 GitHub)，他说道：
Do whatever you want.

所以不是程序猿可以用这个来做什么呢？
1、写书
和 33 一起写小说的例子，还记得吧？几个人你一章我一章共同修改一本书，或是几个出版社的编辑对新书进行校对，利用这个神器就可以随时看到哪里出现了问题和更改。如果想自己写书的话 gitbook 也是不错的选择（又是一个坑。。）

2、写文档神器
身为科研狗、产品狗、射鸡湿的你，是不是经常写文档？一个成熟的文档可能会有好几个版本，需要不断地迭代，然后不断提交给老板看哪里需要修改。在不同版本间自如切换就要用到git branch和git rebase了。
想想看，用 git 的分支管理不比拷贝粘贴更方便吗？

3、健身
有个哥们为了激励自己健身把每日计划都放上去了，还可以邀请其他人一起来相互监督！（我才不会说我自己也开了一个呢哈哈哈）
hoosin/EveryDaySport · GitHub

4、找男票
没错，看这个项目！利用众包的形式一起罗列男友条件的 list 然后试图自己开发出一个男票233333
YixuanFranco/YourBoyfriend · GitHub
有人评论问我用这个找到男票了吗？
统一回复：
并！没！有！

5、用GitHub搭建博客、个人网站或者公司官网
一个有自己域名的独立博客，是不是很帅？！

GitHub本身提供免费的托管服务，又提供了贴心的 Pages 功能，可以绑定你自己的域名，免费、高效、不限流量，做一个个人页面绰绰有余。

Jekyll 的教程和我自己的博客会稍后放出。。（先给自己挖个坑）


6、用GitHub协作翻译

苹果官方发布的各种官方手册，比如最近开源的 Swiftnumbbbbb/the-swift-programming-language-in-chinese · GitHub 就是国内一个自发组织起来的团队，30多个人用9天时间即将翻译和校对工作全部完成，他们每人都还有自己的事情，上班、上线、创业，这么大的工作量在以往简直是不可能完成的任务！


7、项目管理

GitHub最初是为了开发的管理而生，当然也就具备了项目管理的潜质，特别是与开发密切联系的项目中，它的优势尽显。比如这篇文章介绍了如何使用GitHub结合 Trello 等其它工具进行项目管理：使用GitHub进行团队合作。当然，GitHub还是很偏重开发的管理，一般的项目管理还是适合使用 wortile 之类的产品。

