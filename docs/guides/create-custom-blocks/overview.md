# 自定义块

本文档面向希望在Blockly中创建新块的开发人员。假设有一个人可以编辑的Blockly的本地副本，一个人通常熟悉Blockly的用法，一个人对JavaScript有基本的了解。

![logo](./logo.png)

Blockly附带了大量预定义的块。从数学函数到循环结构的一切。但是，为了与外部应用程序连接，必须创建自定义块以形成API。例如，在创建绘图程序时，可能需要创建“ 半径为R的绘制圆 ”块。

在大多数情况下，最简单的方法是找到一个已经存在的非常相似的块，复制它，并根据需要进行修改。以下文档适用于需要更多帮助的人员。

## 定义一个块

第一步是创建一个块; 指定其形状，字段和连接点。使用Blockly Developer Tools是编写此代码的最简单方法。

或者，可以在研究API之后手动编写此代码。

高级块可以响应于用户或其他因素动态地改变它们的形状。

## 代码生成

第二步是创建生成器代码以将新块导出为编程语言（例如JavaScript，Python，PHP，Lua或Dart）。

要生成既干净又正确的代码，必须注意给定语言的操作列表顺序。

创建更复杂的块需要使用临时变量和/或实用程序功能。当输入使用两次并且需要缓存时尤其如此。

## 使用新块
创建块后，不要忘记将其添加到工具箱中或在工作区中使用它。
