#mac 终端命令

```c
mkdir //创建目录
```



ls: 列出当前目录下的文件和文件夹。
cd: 切换目录，例如 cd Documents 进入 Documents 目录。
pwd: 显示当前工作目录的路径。
cp: 复制文件或目录，例如 cp file.txt destination/。
mv: 移动或重命名文件，例如 mv file.txt newfile.txt 或 mv file.txt Documents/。
文件查看和编辑：

cat: 查看文件内容，例如 cat file.txt。
more 或 less: 分屏查看文件内容，例如 less file.txt。
nano 或 vim: 在终端中编辑文件，例如 nano file.txt 或 vim file.txt。
文件搜索：

find: 搜索文件，例如 find /path/to/search -name filename。
grep: 在文件中搜索指定的文本，例如 grep "search_text" file.txt。
系统信息查看：

uname -a: 显示系统信息。
df -h: 显示磁盘空间使用情况。
top: 实时显示系统资源使用情况。
进程管理：

ps: 显示当前运行的进程。
kill: 终止进程，例如 kill -9 process_id。
网络相关：

ping: 测试网络连接，例如 ping example.com。
traceroute: 跟踪数据包的路径，例如 traceroute example.com。
ifconfig 或 ipconfig: 显示网络接口配置信息。
权限管理：

chmod: 修改文件或目录的权限，例如 chmod 755 file.txt。
chown: 修改文件或目录的所有者，例如 chown user:group file.txt。
压缩和解压缩：

tar: 创建或解压 tar 文件，例如 tar -cvf archive.tar file1 file2 或 tar -xvf archive.tar。
软件包管理（Homebrew）：

brew install: 安装软件，例如 brew install wget。
brew update: 更新 Homebrew 软件包列表。
brew upgrade: 升级已安装的软件包。