# 如何在 Python 中将字典值转换为列表

> 原文：<https://www.pythoncentral.io/convert-dictionary-values-list-python/>

在 Python 中，字典是一种内置的数据类型，可用于以不同于列表或数组的方式存储数据。字典不是序列，所以它们不能由一系列数字索引，而是由一系列关键字索引。在学习字典时，将字典数据看作无序的键:值对是有帮助的，在单个字典中，键需要是唯一的。您可以在一对花括号内轻松创建字典。用 key: value 格式的数据填充括号，用逗号分隔 key: value 对，这样就有了一个字典。

请参见下面的代码，了解字典的样子以及应该如何格式化的示例:

```py
example = {'key1': value1, 'key2': value2, 'key3': value3}
```

如果你的键是字符串，记住把它们放在引号中是很重要的。

字典的有趣之处在于它们可以用来映射数据的不同方式。一个常见的字典操作是从键:值对中提取值，并将它们转换成一个列表，其代码实际上非常简单。要了解这是如何做到的，请查看下面的代码片段。

首先，我们需要一本字典:

```py
food = {'pizza': 324, 'sandwich': 78, 'hot dog': 90}
```

接下来，我们需要可以用来执行从字典到列表的值转换的代码，如下所示:

```py
food_list=list(data.values())
print(food_list)
```

就是这样。上面代码的输出应该是字典中键:值对的数据值，与它们在字典中出现的顺序完全一致。因此，您的输出应该如下所示:

```py
324, 78, 90
```

您可以使用这个代码片段将任何字典的键:值对的值打印为一个列表。