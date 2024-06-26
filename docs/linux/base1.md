# 一、基础知识
## 1.1 Linux系统的文件结构
::: code-group

``` sh
/bin        二进制文件，系统常规命令
/boot       系统启动分区，系统启动时读取的文件
/dev        设备文件
/etc        大多数配置文件
/home       普通用户的家目录
/lib        32位函数库
/lib64      64位库
/media      手动临时挂载点
/mnt        手动临时挂载点
/opt        第三方软件安装位置
/proc       进程信息及硬件信息
/root       临时设备的默认挂载点
/sbin       系统管理命令
/srv        数据
/var        数据
/sys        内核相关信息
/tmp        临时文件
/usr        用户相关设定
```
:::
## 1.2 Linux系统命令行的含义

::: code-group
``` sh
示例：root@app00:~# 
root    //用户名，root为超级用户
@       //分隔符
app00   //主机名称
~       //当前所在目录，默认用户目录为~，会随着目录切换而变化，例如：（root@app00:/bin# ，当前位置在bin目录下）
#       //表示当前用户是超级用户，普通用户为$，例如：（"yao@app00:/root$" ，表示使用用户"yao"访问/root文件夹）

```
:::
## 1.3 命令的组成

```
示例：命令 参数名 参数值
```
