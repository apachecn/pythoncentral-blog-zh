# 如何为 Python 新手解决 Python Bugs

> 原文：<https://www.pythoncentral.io/how-to-solve-python-bugs-for-python-novices/>

不管一个人如何学习编写 Python，除非他们花很长时间学习编码，否则修复 bug 的过程不会变得直观。

许多 Python 新手在他们编写的代码不起作用时往往会感到停滞不前和沮丧，他们也不知道哪里出了问题。

我们列出了十个关于修复 bug 的建议，来帮助你改进代码故障排除的方法。

这些技巧将教会你在整个编码生涯中能够使用的基础知识。

## **如何为 Python 新手解决 Python Bugs】**

这里为 Python 新手提供十个关于解决 Python bugs 的初学者小技巧。

### **#1 在已经工作的代码上构建**

即使是最好的程序员有时也会怀疑他们编写 Python 程序的方法是否正确。

因此，当有疑问时，看看别人已经运行的代码是个好主意。编码有一个陡峭的学习曲线；最初，最好依赖现有的结构，并根据需要进行调整。

如果你正在从一本书或一个在线课程中学习编写 Python，你将有机会使用许多参考程序。

然而，如果你在独立完成一个项目，你必须试着用谷歌搜索一个脚本来完成你想做的事情。在对代码进行任何更改之前，运行代码并验证它是否正常工作。

总是做一些小的改动，并在每一步进行测试，看看你的代码是否引入了任何错误。

### **#2 经常使用打印功能**

要理解代码，你应该知道每一行执行时变量的值。如果不确定，使用 print 函数是了解变量值的一个很好的方法。

运行程序，并查看控制台，看看这些值是如何变化的。您可能会发现变量被设置为 null 或其他意外值。

最好在打印变量之前打印一个固定的字符串。这样，您的打印语句就不会一起运行，并且您可以知道哪个变量在哪里被打印。

在一些程序中，你可能很难判断一段代码是否正在运行。像“running”或“got here”这样简单的打印语句就足以确定程序的控制流中是否有错误。检查 if 语句和 for 循环是否不一致。

### **#3 注释掉代码**

像大多数编程语言一样，Python 允许你发表评论。注释是开发人员在代码中做笔记的一种方法。然而，当 Python 试图执行代码时，注释中的文本会被忽略。

你可以使用这个特性来暂时阻止一些代码被语言运行时检测到，而不用从文件中删除它们。这被称为“注释掉”代码。

这样做很简单，只需将注释字符“#”放在不想让运行时检测的代码行的开头。

如果你正在处理一个很长的脚本，你可以注释掉与你正在实现的改变无关的代码块。这样，程序可以运行得更快，并允许您在程序的剩余部分查找错误。

小心使用这个特性是很重要的，因为很容易注释掉设置程序后面要使用的变量的代码。注释中的所有文本都会被完全跳过，因此程序中后面的语句将无法访问被注释掉的行中的变量集。

此外，在测试完代码的其余部分后，你还必须记得删除注释字符。

### **#4 每当你做出改变时运行代码**

无论你是否从一个空白文件开始，不停地修改代码一个小时然后才运行它都不是一个好策略。

你很可能会被几个相互叠加的小错误搞糊涂——如果你慢慢来的话，大部分错误都是可以避免的。

这种情况下最糟糕的事情是，你可能需要更长的时间来剥离你所做的事情，并找出你错在哪里。

你花在编码而不是测试上的时间越长，可能出错的代码就越多。

由于不可能在每次更新时都编码和测试程序并保持高效，所以每隔几分钟运行一次脚本是最好的。

最优秀的程序员记得每次他们运行代码时，都会收到关于他们工作的反馈。他们能够确定他们是否正在把项目引向正确的方向，或者它开始失败了。

### **#5 休息一下，走开**

一般来说，Python 新手和新程序员容易被手头的实现细节所困扰。陷入细节而看不到大局是许多程序员学习处理的常见经历。

如果你发现自己在 20 或 30 分钟内没有取得太大进展，最好离开代码一段时间。选择另一项活动，然后花几分钟时间完全忘记代码，这样当你回来的时候，你就有足够的时间去搞清楚它。

喝杯水或一杯咖啡，散散步，或者吃点零食，都是重新调整心态和放松的好方法。休息过后，你可以探索其他方法。

对于没有尝试过的人来说，这个建议似乎并不令人满意，因为大多数人认为，“如果我现在离开，我会忘记细节。”从头开始和让代码处于中断状态都让人感觉像是后退了一步，而不是前进了一步。

但是使用这个技巧会有意想不到的帮助，大量的研究表明它有很多好处，例如 [提高表现](https://psycnet.apa.org/record/2018-12793-001)[降低压力](https://pubmed.ncbi.nlm.nih.gov/20835716/)[提高创造力](https://www.sciencedirect.com/science/article/abs/pii/S074959781630108X) 。

### **#6 读取错误信息**

当你花了很多心血编写的代码出现错误时，你很容易想放弃。新的 Python 程序员看到栈迹也会感到失落。

但是重要的是要记住大多数错误信息都是准确的和描述性的。

阅读错误信息可以让你知道是缺少了什么还是代码中有拼写错误。你也可能漏掉了一行，让程序无法完成它需要做的事情。

错误信息指出哪里出错了，但是如果你不能理解错误，至少你会知道问题在哪一行。您可以使用这些信息开始查找 bug。

### **#7 在线搜索错误**

了解错误信息含义的最好方法之一是将其复制并粘贴到 Google 中。你可以在 Google 上搜索一个栈跟踪的最后一行。

你可能会在社区中找到一些 stackoverflow.com 页面，其他人会询问关于错误的问题，并给出答案和解释。

虽然这种方法经常奏效，但根据错误是特定的还是一般的，它也可能是偶然的。始终阅读问题中的代码，并与您自己的代码进行比较。这是了解答案是否与你的问题相关的唯一方法。

接下来，阅读一些评论和一些答案，看看这些解决方案是否适合你。

### **#8 猜测和检查**

在你编程生涯的早期阶段，你经常会发现许多潜在的解决方案，但并不 100%确定如何修复一个 bug。

在这种情况下，你必须尝试两三种不同的解决方案，看看会发生什么。正如提示 4 所指出的，经常运行你的代码，这样你就能很快得到反馈，如果你的方法看起来不起作用，你就可以改变它。

当你试图修改代码时，很可能会在程序中引入一些其他的错误。这可能会让人很难理解你是离一个固定的计划更近了还是后退了一步。

为了避免完全破坏代码并重新开始，尽量不要太深入你在网上或其他地方找到的解决方案的兔子洞。

在你决定向别人寻求帮助之前，保持尝试几种解决方案的开放态度是很重要的。当你向程序员寻求帮助时，他们首先会问你的一件事就是列出一些你尝试过的解决方案。

尝试了几种解决方案，并向你寻求帮助的人解释它们，这不仅会给他们一个下一步该做什么的线索，还会显示出你解决问题的决心。

### **#9 如果你不能确定问题，运行二分搜索法**

你运行的程序越大，你需要检查错误的地方就越多。

当一个项目超过 50 行时，找出代码中的错误是一项挑战。虽然堆栈跟踪和错误消息可以为您提供在哪里查找 bug 的线索，但有时这些根本没有帮助。

如果你发现自己处于这种情况，最好跑一趟二分搜索法。它将允许你在你的程序中不按预期运行的部分进行区域划分。

下面是二分搜索法工作原理的简要分析:

从高层次来看，二分搜索法包括将数据分成两半，并在这两半中搜索您想要的任何内容。

一旦搜索确定了数据在哪一半，这一半的数据就被一分为二，两者都被搜索以找到感兴趣的对象(在这种情况下，是一个错误)在哪里。

二分搜索法是发现代码错误的最快方法之一，因为它将程序分成两半，让你可以找出问题所在。

当在程序中寻找 bug 时，只运行前半部分，把后半部分注释掉。打印中途运行程序的结果。

如果结果看起来像预期的那样，您可以断定程序的前半部分运行良好。你要找的问题可能在程序的后半部分。

但是，如果结果有问题，错误是在程序的前半部分。

一遍又一遍地重复运行部分代码的过程，直到找到问题的根源。

这个技巧结合了本文前面提到的许多技巧。

### **#10 求助**

如果你已经尝试了所有的方法，但还是找不出程序中的问题所在，你可以向别人寻求帮助。

无论你是向朋友、老师还是同事寻求帮助，都要确保你具备以下所有条件来提出一个好问题:

1.  解释目标。
2.  显示有错误的代码。
3.  显示堆栈跟踪和错误信息。
4.  解释你已经尝试了什么，以及为什么这些解决方案不起作用。

有时候，当你记下这些细节或者在脑海中仔细思考时，一个新的解决方案可能会浮现在脑海中。为什么会发生这种情况背后的想法是，问一个好问题会使解决方案变得显而易见。

由于这个原因，许多程序员在向某人寻求帮助之前收集了上面列出的所有事实。这个建议也许能解决你的问题。