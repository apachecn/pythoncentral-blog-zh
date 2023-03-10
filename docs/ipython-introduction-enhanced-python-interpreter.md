# IPython 简介:增强的 Python 解释器

> 原文：<https://www.pythoncentral.io/ipython-introduction-enhanced-python-interpreter/>

简而言之，IPython 可以让你做各种真正强大的事情。它在科学家和数学家中非常流行，并且有很多他们非常欣赏的特性。它还有很多对其他使用 Python 的人非常有用的特性。

IPython 提供了许多简单的*钩子*供你定制和扩展它的工作方式。因为修改 IPython 的功能非常容易，所以很难准确定义它是什么。当你第一次安装它时，你会得到一个应用程序，它本质上是一个增强的 Python 交互式解释器。你可以在一个常规的互动会议上做所有你能做的事情，而且你还可以做更多。

## IPython 魔法命令

你会注意到的第一个特性是彩色提示，一个绿色的`In [1]:`。颜色总是很酷，而且用得很好，但是 IPython 不仅仅是一个漂亮的堆栈跟踪。对标准 Python 会话的一个更强大的增强是使用了*神奇命令*——可以使用类似 shell 的语法调用的 Python 函数。你得到一堆内置的，一些非常聪明的，你可以很容易地定义自己的。要使用一个神奇的命令，你只需输入它的名字，然后输入任何参数，中间用空格隔开。例如:

```py

magicname arg0 arg1

```

一些内置的魔法使 Python 会话的操作更像传统的 shell。你有`cd`、`ls`、`cp`等等。如果您喜欢使用这些命令，您可以像平常一样键入它们:

```py

cd ~/scripts

```

如果您想使用没有魔法设置的 shell 命令，您只需砰的一声开始该行，并编写任何正常工作的命令:

```py

!echo IPython

```

## 编辑 IPython 名称空间

我认为最有用的魔法之一是`edit`。如果您想编写任何中等复杂的 Python，您不希望在命令行中完成。在 IPython 中，不是像通常那样从文本编辑器开始，然后运行文件，而是相反的过程:我们在提示符下开始，并简单地从会话中调用编辑器。你可以使用任何你喜欢的编辑器，但是 Vim 规则。

你可以在提示符下输入“edit”来使用 edit。IPython 将用一个空的 tempfile 打开您的编辑器。当您保存并退出编辑器时，您编写的任何代码都会被注入到命名空间中。

例如，您可以在提示符下输入“edit ”,然后在编辑器中定义一个名为 spam 的函数，保存文件并退出编辑器，然后在提示符下调用 spam，传递您喜欢的任何参数。特别酷的是，如果你稍后在提示符下输入“edit spam ”, IPython 会重新打开任何包含垃圾邮件的 tempfile，这样你就可以对它进行更多的编辑。

还有一些方法可以将常规文件的内容注入到同一个名称空间中。当然，您可以使用编辑器的保存功能保存您构建的内容，或者只是从命令行将内容写入文件。还有一个名为 *store* 的魔术，您可以使用它使对象跨会话持久化。

能够轻松地以交互方式构建名称空间，并在进行过程中不断开发，这为您探索正在创建的对象并与之交互提供了更多的自由。这种方法非常适合编写 Python，通常可以快速地、以非常小的增量开发 Python。

## 配置 IPython 解释器

IPython 有一个强大的配置系统，本身就是纯 Python。您可以使用它来创建和管理任意数量的配置，定制 IPython 的每个特性，以及指定自动注入到新会话中的代码，进一步增强您完全定制您的解释器工作方式的能力。

几乎所有东西都是可配置的，如果你懂一点 Python，这很容易做到。

## 开发您的 IPython 环境

一旦您熟练使用 IPython，您应该查看 Python Central 上的其他文章，这些文章更详细地介绍了主要特性，包括定义您自己的神奇命令和配置会话。

随着时间的推移，随着您使用 IPython 越来越多，并向其中添加更多内容，您将开发出一个高度定制的控制台 IDE，方便地将您正在用 Python 做的其他事情包装起来。

从[ipython.org](https://ipython.org/)那里拿一份，让我们知道你最终会把它带到哪里。

另外，要更深入地了解和回顾 IPython，请参阅文章[IPython 回顾](https://www.pythoncentral.io/review-of-ipython-alternative-python-shell/ "Review of IPython (alternative Python shell)")。