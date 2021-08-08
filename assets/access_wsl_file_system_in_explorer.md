## 在windows文件管理器中访问wsl（windows subsystem for linux）文件系统
1. 进入安装好的wsl终端，输入如下命令：
    ```bash
    $ explorer.exe .
    ```
    其中，```explorer.exe```为文件管理器的可执行文件，```.```代表当前目录（家目录）。
## 在wsl中访问windows的本地文件
1. 默认情况下，windows的各个分区以盘符作为挂载点，在wsl中可以通过目录```/mnt/c```进行访问，其中```c```代表C盘，其他分区依次类推。
	```bash
    $ cd /mnt/c
    ```
    > 在linux哲学中，一切皆是文件。

