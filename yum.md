# yum

*2020年6月26日*

yum（Yellow dog Updater, Modified）是一个在Fedora和RedHat以及SUSE中的Shell前端软件包管理器。基于RPM包管理，能够从指定的服务器自动下载RPM包并且安装，可以自动处理依赖性关系，并且一次安装所有依赖的软体包，无须繁琐地一次次下载、安装。

 yum提供了查找、安装、删除某一个、一组甚至全部软件包的命令，且命令简洁而又好记。

 

|      | 命令                                                         |
| ---- | ------------------------------------------------------------ |
| 语法 | yum [options] [command] [package ...]                        |
| 解释 | options：可选，选项包括-h（帮助），-y（当安装过程提示选择全部为"yes"），-q（不显示安装的过程）等等。     <br />command：要进行的操作。     <br />package：操作的对象。 |

 

常用命令

| 操作                     | 命令                                                         |
| ------------------------ | ------------------------------------------------------------ |
| 列出所有可更新的软件清单 | yum check-update                                             |
| 更新所有软件             | yum update                                                   |
| 仅安装指定的软件         | yum install <package_name>                                   |
| 仅更新指定的软件         | yum update <package_name>                                    |
| 列出所有可安裝的软件清单 | yum list                                                     |
| 删除软件包               | yum remove <package_name>                                    |
| 查找软件包               | yum search \<keyword>                                        |
| 清除缓存                 | yum  clean packages: 清除缓存目录下的软件包<br />yum clean headers: 清除缓存目录下的 headers<br />yum  clean oldheaders: 清除缓存目录下旧的 headers<br />yum  clean, yum clean all (= yum clean packages; yum clean oldheaders)  :清除缓存目录下的软件包及旧的headers |