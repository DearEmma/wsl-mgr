# wsl-mgr v0.1

<img src="https://github.com/DearEmma/wsl-mgr/blob/main/wsl-mgr-demo.png" />

一款免费的微软WSL图形化管理软件（没有AI、没有升级提醒、没有自启动、不用注册、没有广告……）

支持远程、本地WSL虚拟机管理，包括：添加、删除、启动、停止  
支持远程、本地WSL虚拟机状态监控，包括：CPU、内存、硬盘、IP  
支持远程、本地WSL虚拟机文件管理，包括：列表、删除、上传、下载  
支持远程、本地WSL虚拟机命令执行，支持TTY，可运行vi  
支持远程、本地WSL虚拟机防火墙映射管理（注意这里没有进行充分测试）

# 如何使用
在宿主机上直接运行WSL-mgr.exe  
如果要从A宿主机管理B宿主机上的WSL虚拟机，需要在B宿主机上运行WSL-Agent.exe，并且复制凭证到A宿主机上的WSL-mgr.exe

# 支持平台
WSL 2.0 on Windows 11  
WSL 3.0.1 on Windows 11
