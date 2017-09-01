sublime-text-3 win10 x64
========================

本仓库包含了SublimeText的[便携版](https://download.sublimetext.com/Sublime%20Text%20Build%203126%20x64.zip) 和相关的插件. 旨在提供一个快速上手的开发环境.


## 安装方法

通过git克隆或者直接下载zip包的方式获取一份代码副本, 然后直接运行本地文件夹中的 `sublime_text.exe` 即可.

当然, 在真正使用之前, 需要确保相关的依赖软件(插件)正确的被安装

1. 安装 [Python](http://python.org) 和 [pip](http://www.pip-installer.org/en/latest/installing.html)(新版本的默认自带pip).

2. 安装 `flake8`:
   ```
   # For python 2.x
   [sudo] pip install flake8

   # For python 3.x
   [sudo] pip3 install flake8
   ```
**Note:** This plugin requires `flake8` 2.1 or later.

3. 安装 [Nodejs](https://nodejs.org).

**Note:** nodejs默认的安装地址在 `C:/Program Files/nodejs`. 如果变更了地址, 相关的插件设置项中对应修改下即可(我本地的nodejs安装在了D:/Program Files/nodejs下)


### 配置

复制 `Data\Packages\User\SyncSettings.sublime-settings.sample` 并重命名为 `SyncSettings.sublime-settings`, 然后修改 `access_token` 和 `gist_id`,
然后你就可以在线备份恢复本地配置项了,
[access_token](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/)
[gist_id](https://gist.github.com/)

## 贡献
克隆, 然后PR即可, 欢迎共享与贡献~
