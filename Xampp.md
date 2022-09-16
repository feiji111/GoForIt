# Laravel框架的搭建流程（XAMPP篇）
我们采取的开发环境是apache + php + mysql的开发环境。对于初学者，这三者的关系可能并不是非常清晰，将在之后的文章中阐述。我们首先开始搭建环境。
首先个人不建议三个软件各自单独安装，单独安装之后配置环境会非常麻烦。这里推荐使用XAMPP。XAMPP已经为我们集成了php，mysql和apache，所以我们安装好后对于配置文件就不需要有非常多的修改。这里放上官网链接  
[XAMPP](https://www.apachefriends.org/zh_cn/index.html)  
如果先前就已经安装过mysql或者apache，再安装XAMPP的话就需要删除注册表中原先安装的apache与mysql的内容。XAMPP下载好后会自动帮我们配置好环境变量，如果没有配置，可以手动将apache，mysql以及php下的bin目录加入到PATH中。  
之后我们以管理员模式打开xampp-control。  
![打开xampp-control](../photos/2.png)  
**注意要用管理员模式打开，不然在退出时会报如下错误**
![XAMPP退出时报错](../photos/3.png)  
打开后的界面如下所示，之后config选项可以供我们快速打开并修改一些配置文件  
![XAMPP界面](../photos/4.png)  
一般来说，XAMPP会帮助我们讲大部分的文件配置好，省去了一些工作，但仍然有一些点需要我们来修改



