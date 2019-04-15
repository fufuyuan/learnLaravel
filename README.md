# learnLaravel
环境安装
1.线上环境安装
名词解释

vagrant 是管理虚拟机的工具，主要作用是提供一个可配置、可移植和复用的软件环境
VirtualBox 是虚拟机软件这个没有错
Homestead 里面包含了 Nginx Web 服务器、PHP 7、MySQL、Postgres、Redis、Memcached、Node，以及所有你在使用 Laravel 开发时需要用到的各种软件（Homestead Box 虚拟机盒子），它一套可配置的 Laravel 开发环境（Homestead 管理脚本）



通过虚拟机模拟线上环境
统一开发环境
Homestead 是 Laravel 官方推荐的开发环境。
在日常的团队开发中，由于开发环境的不一致，往往会导致出现各种各样的问题。即便是经验丰富的工程师，在遇到这种问题时也会特别头疼。Vagrant可以解决这种问题！Vagrant 是一个用于创建和部署虚拟化开发环境的工具，其依赖于 VirtualBox 虚拟机，致力于帮助开发者快速构建一个环境统一的虚拟系统。Vagrant 最强大的地方是在于它在构建虚拟系统时的快捷简便，使开发者可以在短短几分钟内完成一个虚拟系统的删除与构建。

Laravel 希望在 Vagrant 的基础上让开发环境更加统一，让开发者都能在指定的具体开发环境下使用 Laravel，这时便有了 Homestead。Homestead 是一个基于 Ubuntu 构建的虚拟机，它包含了所有 Laravel 开发时需要用到的东西，你可以很轻松的通过指定的 Laravel 版本来找到相对应版本的 Homestead 并进行安装。Homestead 提供的默认开发环境还会装上很多常用的开发工具来辅助 Laravel 进行项目开发，包括 PHP7, Nginx, Redis, Memcached, MySQL, Git, Node.js, NPM


1.1 window环境安装
安装环境需要windows7以上系统
暂时未使用
https://learnku.com/docs/laravel-development-environment/5.7/development-environment-windows/2902

1.2 mac环境安装
https://learnku.com/docs/laravel-development-environment/5.7/development-environment-macos/2901#84907d

遇到的问题
1.virtualbox 安装问题 

1.1 Go to System Preferences > Security & Privacy. Click the ‘Allow’ button at the bottom. Re-run the installer. More detailed instructions are below.
2.before install. Navigate to System Preferences > Security & Privacy. At the bottom of the window, you should see a message saying “System software from developer, ‘Oracle, America, Inc.‘ was blocked from loading.”

解决问题的网页 1.https://matthewpalmer.net/blog/2017/12/10/install-virtualbox-mac-high-sierra/index.html
2.https://forums.virtualbox.org/viewtopic.php?f=8&t=84092&start=60






2.本地环境安装

