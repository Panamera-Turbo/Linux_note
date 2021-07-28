# 软件的安装卸载（ubantu环境）

*2020年2月21日*

| 方式  | 命令                                                         |
| ----- | ------------------------------------------------------------ |
| 在线  | 方法一：使用apt-get <br/>      安装：sudo apt-get install 软件名<br/>      更新：sudo apt-get update 软件列表<br/>      卸载：sudo apt-get remove 软件名<br/>      清理所有安装包：sudo apt-get clean<br />            （实际清理的是/var/cache/apt/archives目录下的.deb文件）<br />方法二：使用aptitude<br />       安装：sudo aptitude install 软件名<br />       重新安装：sudo aptitude reinstall 软件名<br />       更新：sudo aptitude update<br />       移除：sudo aptitude remove软件名<br />       显示状态：sudo aptitude show 软件名 |
| deb包 | 安装：sudo dpkg -i 软件名.deb    卸载：sudo dpkg -r 软件名   |