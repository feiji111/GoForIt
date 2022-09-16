# Composer的作用以及工作原理
与npm相似，composer也是帮助我们读取和安装组件的工具。对于已有的一个项目，如果我们克隆到我们的电脑上，我们首先需要将一些组件安装上，出了用npm安装一些javascript模块外。composer可以根据composer.lock(或composer.json)文件中的内容，帮助我们安装一些php模块到vendor目录下。  
![项目中的vendor文件以及composer.lock(json)文件](../photos/8.png)  
至于composer与npm的区别,composer是php的管理器，而npm是nodejs的包管理器，一个是php语言，一个是javascript语言