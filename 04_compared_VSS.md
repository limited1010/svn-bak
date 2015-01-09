# SVN与VSS比较

* **支持重命名**(这对 Java 开发来说非常重要)

  为了得到更好的代码，开发中需要经常进行重构，重构就经常涉及到文件的重构名，而重命名 VSS中是不被支持的。

* **开发的时候不一定要锁定**

  一方面导致重构不方便，另一方面，不能离线开发，使用 SVN就不同，可以带回家继续开发，回来后，提交就行了。

* **多平台**

  可以支持多个平台下的操作

* **更好的客户端支持**

  Eclipse 中的 VSS Plugin 不如它的 SVN Plugin 好用。一个在 Windows 下用的 SVN客户端TortoiseSVN 也比VSS 的客户端好用（VSS 只有微软提供的一个 GUI 客户端）。

* **更好地与外围工具集成**
  
  各种各样的外围工具（主要是服务器端），满足多种需要。如果有需要，也可以自己写插件或管理脚本，开放的架构，允许我们这样做。

* **方便**
  
  一个例子：部署应用的时候，以前的做法是找出一个项目中修改过的文件，更新到服务器上去，可以在服务器上执行 svn export 命令，把代码库中的最新版本导出，完成部署（也可以替换回老版本）。

* **速度与稳定性看起来都不错**
  
  学习它的管理、它的工作方式，是值得的。而 VSS是一个已经被逐渐抛弃的软件。如果时间不是多得没处用，那么就把时间花在最值得花的东西上面。