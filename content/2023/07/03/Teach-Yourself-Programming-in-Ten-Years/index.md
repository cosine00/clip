---
title: "在十年内自学编程"
date: 2023-07-03T09:37:21+08:00
---
原标题：Teach Yourself Programming in Ten Years

Peter Norvig

彼得·诺维格

## 为什么大家都这么着急呢？

Why is everyone in such a rush?

---
Walk into any bookstore, and you’ll see how to *Teach Yourself Java in 24 Hours* alongside endless variations offering to teach C, SQL, Ruby, Algorithms, and so on in a few days or hours. The Amazon advanced search for \[title: teach, yourself, hours, since: 2000 and found 512 such books. Of the top ten, nine are programming books (the other is about bookkeeping). Similar results come from replacing “teach yourself” with “learn” or “hours” with “days.”

走进任何一家书店，您都会看到如何在 24 小时内自学 Java，以及提供在几天或几小时内教授 C、SQL、Ruby、算法等的无数变体。亚马逊高级搜索\[标题：教，你自己，时间，自：2000年以来，找到了512本这样的书。前十名中，九本是编程书籍（另一本是关于簿记的）。将“自学”替换为“学习”或将“小时”替换为“天”，也会得到类似的结果。

The conclusion is that either people are in a big rush to learn about programming, or that programming is somehow fabulously easier to learn than anything else. Felleisen *et al.* give a nod to this trend in their book How to Design Programs, when they say “Bad programming is easy. *Idiots* can learn it in *21 days*, even if they are *dummies*.” The Abtruse Goose comic also had **their take.

结论是，要么人们急于学习编程，要么编程在某种程度上比其他任何东西都更容易学习。费莱森等人。他们在《如何设计程序》一书中承认了这一趋势，他们说“糟糕的编程很容易。白痴可以在 21 天内学会它，即使他们是傻瓜。” 《深奥的鹅》漫画也有自己的看法。

Let’s analyze what a title like *Teach Yourself C++ in 24 Hours* could mean:

让我们分析一下《24 小时自学 C++》这样的标题可能意味着什么：

- **Teach Yourself:** In 24 hours you won’t have time to write several significant programs, and learn from your successes and failures with them. You won’t have time to work with an experienced programmer and understand what it is like to live in a C++ environment. In short, you won’t have time to learn much. So the book can only be talking about a superficial familiarity, not a deep understanding. As Alexander Pope said, a little learning is a dangerous thing.
    
    自学：在 24 小时内，您将没有时间编写几个重要的程序，并从它们的成功和失败中学习。您将没有时间与经验丰富的程序员一起工作并了解生活在 C++ 环境中的感觉。简而言之，你没有时间学习太多东西。所以这本书只能讲表面的熟悉，而不是深入的理解。正如亚历山大·波普所说，学习一点点是一件危险的事情。
    
- **C++:** In 24 hours you might be able to learn some of the syntax of C++ (if you already know another language), but you couldn’t learn much about how to use the language. In short, if you were, say, a Basic programmer, you could learn to write programs in the style of Basic using C++ syntax, but you couldn’t learn what C++ is actually good (and bad) for. So what’s the point? Alan Perlis once said: “A language that doesn’t affect the way you think about programming, is not worth knowing”. One possible point is that you have to learn a tiny bit of C++ (or more likely, something like JavaScript or Processing) because you need to interface with an existing tool to accomplish a specific task. But then you’re not learning how to program; you’re learning to accomplish that task.
    
    C++：24小时内你也许能够学习C++的一些语法（如果你已经了解另一种语言），但你无法了解如何使用该语言。简而言之，如果您是一名 Basic 程序员，您可以学习使用 C++ 语法以 Basic 风格编写程序，但您无法了解 C++ 实际上有什么好处（和坏处）。那么有什么意义呢？ Alan Perlis 曾经说过：“一种不影响你思考编程方式的语言，不值得了解”。一个可能的观点是，您必须学习一点点 C++（或更可能是 JavaScript 或处理之类的东西），因为您需要与现有工具交互才能完成特定任务。但这样你就不是在学习如何编程；而是在学习如何编程。你正在学习完成这项任务。
    
- **in 24 Hours:** Unfortunately, this is not enough, as the next section shows.
    
    24 小时内：不幸的是，这还不够，如下一节所示。
    

## 十年自学编程

Teach Yourself Programming in Ten Years

---

Researchers (Bloom (1985), Bryan & Harter (1899), Hayes (1989), Simmon & Chase (1973)) have shown it takes about ten years to develop expertise in any of a wide variety of areas, including chess playing, music composition, telegraph operation, painting, piano playing, swimming, tennis, and research in neuropsychology and topology. The key is *deliberative* practice: not just doing it again and again, but challenging yourself with a task that is just beyond your current ability, trying it, analyzing your performance while and after doing it, and correcting any mistakes. Then repeat. And repeat again. There appear to be no real shortcuts: even Mozart, who was a musical prodigy at age 4, took 13 more years before he began to produce world-class music. In another genre, the Beatles seemed to burst onto the scene with a string of #1 hits and an appearance on the Ed Sullivan show in 1964. But they had been playing small clubs in Liverpool and Hamburg since 1957, and while they had mass appeal early on, their first great critical success, *Sgt. Peppers*, was released in 1967.

研究人员（Bloom (1985)、Bryan & Harter (1899)、Hayes (1989)、Simmon & Chase (1973)）表明，培养各个领域的专业知识大约需要十年的时间，包括国际象棋、音乐作曲、电报操作、绘画、钢琴演奏、游泳、网球以及神经心理学和拓扑学研究。关键是刻意练习：不仅仅是一次又一次地做，而是用一项超出你当前能力的任务来挑战自己，尝试它，分析你在做时和做后的表现，并纠正任何错误。然后重复。并再次重复。似乎没有真正的捷径：即使是 4 岁时就成为音乐神童的莫扎特，也花了 13 年时间才开始创作世界级的音乐。在另一种流派中，披头士乐队似乎凭借一系列排名第一的热门歌曲和 1964 年埃德·沙利文秀的亮相而崭露头角。但自 1957 年以来，他们一直在利物浦和汉堡的小俱乐部演出，尽管他们具有广泛的吸引力早些时候，他们的第一个重大成功，中士。 《辣椒》于 1967 年上映。

Malcolm Gladwell has popularized the idea, although he concentrates on 10,000 hours, not 10 years. Henri Cartier-Bresson (1908-2004) had another metric: “Your first 10,000 photographs are your worst.” (He didn’t anticipate that with digital cameras, some people can reach that mark in a week.) True expertise may take a lifetime: Samuel Johnson (1709-1784) said “Excellence in any department can be attained only by the labor of a lifetime; it is not to be purchased at a lesser price.” And Chaucer (1340-1400) complained “the lyf so short, the craft so long to lerne.” Hippocrates (c. 400BC) is known for the excerpt “ars longa, vita brevis”, which is part of the longer quotation “Ars longa, vita brevis, occasio praeceps, experimentum periculosum, iudicium difficile”, which in English renders as “Life is short, [the] craft long, opportunity fleeting, experiment treacherous, judgment difficult.” Of course, no single number can be the final answer: it doesn’t seem reasonable to assume that all skills (e.g., programming, chess playing, checkers playing, and music playing) could all require exactly the same amount of time to master, nor that all people will take exactly the same amount of time. As Prof. K. Anders Ericsson puts it, “In most domains it’s remarkable how much time even the most talented individuals need in order to reach the highest levels of performance. The 10,000 hour number just gives you a sense that we’re talking years of 10 to 20 hours a week which those who some people would argue are the most innately talented individuals still need to get to the highest level.”

马尔科姆·格拉德威尔（Malcolm Gladwell）普及了这个想法，尽管他专注于 10,000 小时，而不是 10 年。亨利·卡地亚·布列松（Henri Cartier-Bresson，1908-2004）有另一个衡量标准：“你的前 10,000 张照片是最糟糕的。” （他没有预料到，使用数码相机，有些人可以在一周内达到这一水平。）真正的专业知识可能需要一生的时间：塞缪尔·约翰逊（Samuel Johnson，1709-1784）说“任何部门的卓越只有通过努力才能获得”一生；它不能以更低的价格购买。”乔叟（1340-1400）抱怨说“生命如此短暂，学习技艺却如此漫长”。希波克拉底（约公元前 400 年）以摘录“ars longa, vita brevis”而闻名，该摘录是较长引文“Ars longa, vita brevis, occasio praeceps, Experimentum periculosum, iudicium difficile”的一部分，在英语中翻译为“生命”时间短，工艺长，机会转瞬即逝，实验危险，判断困难。”当然，没有一个数字可以作为最终答案：假设所有技能（例如编程、下棋、跳棋和音乐演奏）都需要完全相同的时间来掌握似乎并不合理，也不保证所有人都会花费完全相同的时间。正如 K. Anders Ericsson 教授所说：“在大多数领域，即使是最有才华的个人也需要花费大量时间才能达到最高水平的绩效。10,000 小时的数字只会让您感觉我们正在谈论数年那些被一些人认为是最有天赋的人仍然需要每周工作 10 到 20 个小时才能达到最高水平。”

## 所以你想成为一名程序员

So You Want to be a Programmer

---

Here’s my recipe for programming success:

这是我成功编程的秘诀：

- Get **interested** in programming, and do some because it is fun. Make sure that it keeps being enough fun so that you will be willing to put in your ten years/10,000 hours.
    
    对编程感兴趣，并且因为它很有趣而去做一些事情。确保它保持足够的乐趣，这样你才会愿意投入十年/一万个小时。
    
- **Program**. The best kind of learning is learning by doing. To put it more technically, “the maximal level of performance for individuals in a given domain is not attained automatically as a function of extended experience, but the level of performance can be increased even by highly experienced individuals as a result of deliberate efforts to improve.” (p. 366) and “the most effective learning requires a well-defined task with an appropriate difficulty level for the particular individual, informative feedback, and opportunities for repetition and corrections of errors.” (p. 20-21) The book *Cognition in Practice: Mind, Mathematics, and Culture in Everyday Life* is an interesting reference for this viewpoint.
    
    程序。最好的学习方式是边做边学。更专业地说，“在给定领域中，个人的最高绩效水平并不是随着丰富的经验而自动达到的，但即使是经验丰富的个人，也可以通过刻意努力提高绩效水平来提高” ”。 （第366页）和“最有效的学习需要明确的任务，对特定个人有适当的难度，信息丰富的反馈，以及重复和纠正错误的机会。” （第 20-21 页）《实践中的认知：日常生活中的思维、数学和文化》一书是这一观点的有趣参考。
    
- **Talk with** other programmers; read other programs. This is more important than any book or training course.
    
    与其他程序员交谈；阅读其他程序。这比任何书籍或培训课程都更重要。
    
- If you want, put in four years at a **college** (or more at a graduate school). This will give you access to some jobs that require credentials, and it will give you a deeper understanding of the field, but if you don’t enjoy school, you can (with some dedication) get similar experience on your own or on the job. In any case, book learning alone won’t be enough. “Computer science education cannot make anybody an expert programmer any more than studying brushes and pigment can make somebody an expert painter” says Eric Raymond, author of *The New Hacker’s Dictionary*. One of the best programmers I ever hired had only a High School degree; he’s produced a lot of great software, has his own news group, and made enough in stock options to buy his own nightclub.
    
    如果你愿意，可以在大学学习四年（或者在研究生院学习更长的时间）。这将使您能够获得一些需要证书的工作，并且将使您对该领域有更深入的了解，但如果您不喜欢上学，您可以（通过一些奉献）自己或在工作中获得类似的经验。无论如何，仅靠书本学习是不够的。 《新黑客词典》的作者埃里克·雷蒙德说：“计算机科学教育不能使任何人成为专家程序员，就像学习画笔和颜料不能使人成为专家画家一样。”我雇用过的最好的程序员之一只有高中学历；他开发了许多出色的软件，拥有自己的新闻组，并赚了足够的股票期权来购买自己的夜总会。
    
- Work on **projects with** other programmers. Be the best programmer on some projects; be the worst on some others. When you’re the best, you get to test your abilities to lead a project, and to inspire others with your vision. When you’re the worst, you learn what the masters do, and you learn what they don’t like to do (because they make you do it for them).
    
    与其他程序员一起开发项目。成为某些项目上最好的程序员；对其他人来说是最糟糕的。当你成为最优秀的人时，你就可以测试自己领导项目的能力，并用你的愿景激励他人。当你最差的时候，你会了解大师做什么，你会了解他们不喜欢做什么（因为他们让你为他们做）。
    
- Work on **projects *after*** other programmers. Understand a program written by someone else. See what it takes to understand and fix it when the original programmers are not around. Think about how to design your programs to make it easier for those who will maintain them after you.
    
    跟随其他程序员从事项目。理解别人写的程序。看看当原始程序员不在时，如何理解并修复它。考虑如何设计您的程序，以便让您之后的维护者更轻松地维护它们。
    
- Learn at least a half dozen **programming languages**. Include one language that emphasizes class abstractions (like Java or C++), one that emphasizes functional abstraction (like Lisp or ML or Haskell), one that supports syntactic abstraction (like Lisp), one that supports declarative specifications (like Prolog or C++ templates), and one that emphasizes parallelism (like Clojure or Go).
    
    学习至少六种编程语言。包括一种强调类抽象的语言（如 Java 或 C++）、一种强调函数抽象的语言（如 Lisp、ML 或 Haskell）、一种支持句法抽象的语言（如 Lisp）、一种支持声明性规范的语言（如 Prolog 或 C++ 模板） ，以及强调并行性的一种（如 Clojure 或 Go）。
    
- Remember that there is a “**computer**” in “computer science”. Know how long it takes your computer to execute an instruction, fetch a word from memory (with and without a cache miss), read consecutive words from disk, and seek to a new location on disk. (Answers here.)
    
    请记住，“计算机科学”中有一个“计算机”。了解计算机执行一条指令、从内存中获取一个字（有或没有缓存未命中）、从磁盘读取连续的字以及在磁盘上寻找新位置需要多长时间。 （答案在这里。）
    
- Get involved in a language **standardization** effort. It could be the ANSI C++ committee, or it could be deciding if your local coding style will have 2 or 4 space indentation levels. Either way, you learn about what other people like in a language, how deeply they feel so, and perhaps even a little about why they feel so.
    
    参与语言标准化工作。它可能是 ANSI C++ 委员会，也可能决定您的本地编码风格是否具有 2 个或 4 个空格缩进级别。无论哪种方式，您都会了解其他人喜欢某种语言的内容，他们的感受有多深，甚至可能会了解他们为什么会有这样的感受。
    
- Have the good sense to **get off** the language standardization effort as quickly as possible.
    
    要有良好的判断力，尽快完成语言标准化工作。
    

With all that in mind, its questionable how far you can get just by book learning. Before my first child was born, I read all the *How To* books, and still felt like a clueless novice. 30 Months later, when my second child was due, did I go back to the books for a refresher? No. Instead, I relied on my personal experience, which turned out to be far more useful and reassuring to me than the thousands of pages written by experts.

考虑到所有这些，仅仅通过书本学习能走多远就值得怀疑了。在我的第一个孩子出生之前，我读了所有的《如何做》书籍，但仍然感觉自己像个无知的新手。 30 个月后，当我的第二个孩子出生时，我是否又回到书本上复习一下？不。相反，我依靠的是我的个人经验，事实证明，这比专家写的数千页内容更有用、更令人放心。

Fred Brooks, in his essay *No Silver Bullet* identified a three-part plan for finding great software designers:

Fred Brooks 在他的文章《No Silver Bullet》中提出了一个由三部分组成的寻找优秀软件设计师的计划：

1. Systematically identify top designers as early as possible.
    
    尽早系统地甄别顶尖设计师。
    
2. Assign a career mentor to be responsible for the development of the prospect and carefully keep a career file.
    
    指派一名职业导师负责潜在客户的发展，并仔细保存职业档案。
    
3. Provide opportunities for growing designers to interact and stimulate each other.
    
    为成长中的设计师提供互动和互相激励的机会。
    

This assumes that some people already have the qualities necessary for being a great designer; the job is to properly coax them along. Alan Perlis put it more succinctly: “Everyone can be taught to sculpt: Michelangelo would have had to be taught how not to. So it is with the great programmers”. Perlis is saying that the greats have some internal quality that transcends their training. But where does the quality come from? Is it innate? Or do they develop it through diligence? As Auguste Gusteau (the fictional chef in *Ratatouille*) puts it, “anyone can cook, but only the fearless can be great.” I think of it more as willingness to devote a large portion of one’s life to deliberative practice. But maybe *fearless* is a way to summarize that. Or, as Gusteau’s critic, Anton Ego, says: “Not everyone can become a great artist, but a great artist can come from anywhere.”

这是假设有些人已经具备成为一名伟大设计师所必需的品质；工作就是适当地哄骗他们。 Alan Perlis 更简洁地说：“每个人都可以被教导雕刻：米开朗基罗必须被教导如何不这样做。伟大的程序员也是如此”。玻璃市说，伟人有一些超越训练的内在品质。但质量从何而来？是天生的吗？还是他们通过勤奋发展的？正如奥古斯特·古斯托（《料理鼠王》中虚构的厨师）所说，“任何人都可以做饭，但只有无所畏惧的人才能成为伟大的人。”我认为它更多的是愿意将一生的大部分时间投入到深思熟虑的实践中。但也许“无所畏惧”是对这一点的一种总结。或者，正如古斯托的批评家安东·伊戈所说：“不是每个人都能成为伟大的艺术家，但伟大的艺术家可以来自任何地方。”

So go ahead and buy that Java/Ruby/Javascript/PHP book; you’ll probably get some use out of it. But you won’t change your life, or your real overall expertise as a programmer in 24 hours or 21 days. How about working hard to continually improve over 24 months? Well, now you’re starting to get somewhere…

所以，去买那本 Java/Ruby/Javascript/PHP 的书吧；你可能会从中得到一些用处。但你不会在 24 小时或 21 天之内改变你的生活，也不会改变你作为程序员的真正的整体专业知识。在 24 个月内努力持续改进怎么样？好吧，现在你开始有所进展了……

## 参考

References

---

Bloom, Benjamin (ed.) *Developing Talent in Young People*, Ballantine, 1985.

Bloom, Benjamin（主编）《培养年轻人的才能》，Ballantine，1985 年。

Brooks, Fred, *No Silver Bullets*, IEEE Computer, vol. 20, no. 4, 1987, p. 10-19.

弗雷德·布鲁克斯，《没有银弹》，IEEE 计算机，卷。 20、没有。 4，1987 年，第 4 页。 10-19。

Bryan, W.L. & Harter, N. "Studies on the telegraphic language: The acquisition of a hierarchy of habits. *Psychology Review*, 1899, 8, 345-375

布莱恩，W.L. & Harter, N.“电报语言的研究：习惯层次结构的习得。心理学评论，1899, 8, 345-375

Hayes, John R., *Complete Problem Solver* Lawrence Erlbaum, 1989.

Hayes, John R.，完整的问题解决者劳伦斯·埃尔鲍姆，1989 年。

Chase, William G. & Simon, Herbert A. “Perception in Chess” *Cognitive Psychology*, 1973, 4, 55-81.

Chase, William G. & Simon, Herbert A.“国际象棋中的感知”认知心理学，1973 年，4，55-81。

Lave, Jean, *Cognition in Practice: Mind, Mathematics, and Culture in Everyday Life*, Cambridge University Press, 1988.

Lave, Jean，《实践中的认知：日常生活中的思维、数学和文化》，剑桥大学出版社，1988 年。

## 答案

Answers

---

Approximate timing for various operations on a typical PC:

典型 PC 上各种操作的大致时序：

execute typical instruction

执行典型指令 | 1/1,000,000,000 sec = 1 nanosec

1/1,000,000,000 秒 = 1 纳秒 | | fetch from L1 cache memory

从 L1 高速缓存中获取 | 0.5 nanosec 0.5纳秒 | | branch misprediction分支预测错误 | 5 nanosec 5纳秒 | | fetch from L2 cache memory

从 L2 高速缓存中获取 | 7 nanosec 7纳秒 | | Mutex lock/unlock互斥锁/解锁 | 25 nanosec 25纳秒 | | fetch from main memory

从主存中获取 | 100 nanosec 100纳秒 | | send 2K bytes over 1Gbps network

通过 1Gbps 网络发送 2K 字节 | 20,000 nanosec 20,000 纳秒 | | read 1MB sequentially from memory

从内存中顺序读取 1MB | 250,000 nanosec 250,000 纳秒 | | fetch from new disk location (seek)

从新的磁盘位置获取（查找） | 8,000,000 nanosec 8,000,000 纳秒 | | read 1MB sequentially from disk

从磁盘顺序读取 1MB | 20,000,000 nanosec 20,000,000 纳秒 | | send packet US to Europe and back

将数据包从美国发送到欧洲并返回 | 150 milliseconds = 150,000,000 nanosec

150 毫秒 = 150,000,000 纳秒 |

## 附录：语言选择

Appendix: Language Choice

---

Several people have asked what programming language they should learn first. There is no one answer, but consider these points:

有几个人问他们应该首先学习什么编程语言。没有一个答案，但请考虑以下几点：

- *Use your friends*. When asked “what operating system should I use, Windows, Unix, or Mac?”, my answer is usually: “use whatever your friends use.” The advantage you get from learning from your friends will offset any intrinsic difference between OS, or between programming languages. Also consider your future friends: the community of programmers that you will be a part of if you continue. Does your chosen language have a large growing community or a small dying one? Are there books, web sites, and online forums to get answers from? Do you like the people in those forums?
利用你的朋友。当被问到“我应该使用什么操作系统，Windows、Unix 还是 Mac？”时，我的回答通常是：“使用你朋友使用的任何操作系统。”您从朋友那里学习所获得的优势将抵消操作系统之间或编程语言之间的任何内在差异。还要考虑一下你未来的朋友：如果你继续下去，你将成为程序员社区的一部分。您选择的语言是否有一个不断发展的大型社区或一个正在消亡的小型社区？是否有书籍、网站和在线论坛可以获取答案？你喜欢那些论坛里的人吗？
- *Keep it simple*. Programming languages such as C++ and Java are designed for professional development by large teams of experienced programmers who are concerned about the run-time efficiency of their code. As a result, these languages have complicated parts designed for these circumstances. You’re concerned with learning to program. You don’t need that complication. You want a language that was designed to be easy to learn and remember by a single new programmer.
把事情简单化。 C++ 和 Java 等编程语言是由经验丰富的程序员组成的大型团队为专业开发而设计的，他们关心代码的运行时效率。因此，这些语言具有针对这些情况而设计的复杂部分。您关心的是学习编程。你不需要那么复杂。您需要一种易于新程序员学习和记忆的语言。
- *Play.* Which way would you rather learn to play the piano: the normal, interactive way, in which you hear each note as soon as you hit a key, or “batch” mode, in which you only hear the notes after you finish a whole song? Clearly, interactive mode makes learning easier for the piano, and also for programming. Insist on a language with an interactive mode and use it.
玩。您更愿意以哪种方式学习弹钢琴：正常的交互式方式，在这种方式中，您一敲击琴键就可以听到每个音符，或者“批量”模式，在这种方式中，您只在完成整首歌曲后才能听到音符？显然，交互模式使钢琴学习和编程变得更加容易。坚持使用具有交互模式的语言并使用它。

Given these criteria, my recommendations for a first programming language would be **Python** or **Scheme**. Another choice is Javascript, not because it is perfectly well-designed for beginners, but because there are so many online tutorials for it, such as Khan Academy’s tutorial. But your circumstances may vary, and there are other good choices. If your age is a single-digit, you might prefer Alice or Squeak or Blockly (older learners might also enjoy these). The important thing is that you choose and get started.

考虑到这些标准，我对第一种编程语言的建议是 Python 或 Scheme。另一个选择是Javascript，不是因为它为初学者设计得非常好，而是因为它的在线教程太多了，比如可汗学院的教程。但您的情况可能会有所不同，并且还有其他不错的选择。如果您的年龄是个位数，您可能更喜欢 Alice 或 Squeak 或 Blockly（年龄较大的学习者也可能喜欢这些）。重要的是您选择并开始。

## 附录：书籍和其他资源

Appendix: Books and Other Resources

---

Several people have asked what books and web pages they should learn from. I repeat that “book learning alone won’t be enough” but I can recommend the following:

有几个人问他们应该学习哪些书籍和网页。我重复一遍“仅靠书本学习是不够的”，但我可以推荐以下内容：

- **Scheme:** Structure and Interpretation of Computer Programs (Abelson & Sussman) is probably the best introduction to computer science, and it does teach programming as a way of understanding the computer science. You can see online videos of lectures on this book, as well as the complete text online. The book is challenging and will weed out some people who perhaps could be successful with another approach.
方案：计算机程序的结构和解释（Abelson & Sussman）可能是计算机科学的最佳入门，它确实将编程作为理解计算机科学的一种方式进行教授。您可以在线观看本书的讲座视频，以及在线全文。这本书很有挑战性，会淘汰一些可能通过其他方法取得成功的人。
- **Scheme:** How to Design Programs (Felleisen *et al.*[)](http://www.amazon.com/gp/product/0262062186) is one of the best books on how to actually design programs in an elegant and functional way.
《Scheme：如何设计程序》（Felleisen 等人）是关于如何以优雅且实用的方式实际设计程序的最佳书籍之一。
- **Python:** Python Programming: An Intro to CS (Zelle) is a good introduction using Python.
Python：Python 编程：CS 简介 (Zelle) 是使用 Python 的一个很好的介绍。
- **Python:** Several online tutorials are available at Python.org.
Python：Python.org 上提供了一些在线教程。
- **Oz:** Concepts, Techniques, and Models of Computer Programming (Van Roy & Haridi) is seen by some as the modern-day successor to Abelson & Sussman. It is a tour through the big ideas of programming, covering a wider range than Abelson & Sussman while being perhaps easier to read and follow. It uses a language, Oz, that is not widely known but serves as a basis for learning other languages. <
奥兹：计算机编程的概念、技术和模型（Van Roy 和 Haridi）被一些人视为 Abelson 和 Sussman 的现代继承者。这是对编程大思想的一次游览，涵盖的范围比 Abelson & Sussman 更广泛，同时可能更容易阅读和遵循。它使用一种语言，Oz，这种语言并不广为人知，但可以作为学习其他语言的基础。 <

## 笔记

Notes

---

T. Capey points out that the Complete Problem Solver page on Amazon now has the “Teach Yourself Bengali in 21 days” and “Teach Yourself Grammar and Style” books under the “Customers who shopped for this item also shopped for these items” section. I guess that a large portion of the people who look at that book are coming from this page. Thanks to Ross Cohen for help with Hippocrates.

T. Capey 指出，亚马逊上的“完整问题解决者”页面现在在“购买该商品的顾客也购买了这些商品”部分下提供了“21 天自学孟加拉语”和“自学语法和风格”书籍。我猜想看那本书的很大一部分人都是从这个页面来的。感谢罗斯·科恩对希波克拉底的帮助。

原文链接: [https://norvig.com/21-days.html](https://norvig.com/21-days.html)