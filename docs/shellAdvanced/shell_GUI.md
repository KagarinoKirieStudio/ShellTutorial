# 图形化脚本编程

多年来，shell 脚本一直都被认为是枯燥乏味的。但如果你准备在图形化环境中运行脚本时，就未必如此了。有很多与脚本用户交互的方式并不依赖 read 和 echo 语句。本章将会深入介绍一些可以让交互式脚本更友好的方法，这样它们看起来就不那么古板了。

这部分优先级太低 之后想写了再写吧

## 创建文本菜单

创建交互式 shell 脚本最常用的方法是使用菜单。提供各种选项可以帮助脚本用户了解脚本能做什么和不能做什么。通常菜单脚本会清空显示区域，然后显示可用的选项列表。用户可以按下与每个选项关联的字母或数字来选择选项。

shell 脚本菜单的核心是 case 命令。case 命令会根据用户在菜单上的选择来执行特定命令。后面几节将会带你逐步了解创建基于菜单的 shell 脚本的步骤。

### 创建菜单布局