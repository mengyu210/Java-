一文件常用指令 (查看、删除) 等
1、linux         日志实时查看
    cat          文件名     查看日志
    tail -f      文件名   实时查看日志  一直等待刷新日志尾部信息
    tail -n 20   文件名 实时查看最后一部分内容默认10行 改为20行
2、显示文件及目录
   ls            显示文件或者目录
      -l         显示文件详细信息
     -a          显示当前目录下所有文件或者文件夹以及隐藏文件
3、文件常用命令
   mkdir         创建目录
       -p        若无父目录，则创建父目录
   chmod         更改文件权限
   touch         创建空文件
   echo          创建带有内容的文件
   cat           查看文件内容
   cp            拷贝
   mv            移动或者重命名
   rm            删除文件
       -r        递归删除，可删除子目录及文件
       -f        强制删除
   find          在文件系统中搜索某个文件
   wc            统计文本中的行数字数和字符数
   grep          在文本中查看某个字符串
   rmdir         删除空目录
   tree          树形结构查看显示目录，需要安装tree包
   pwd           显示当前目录
   In            创建链接文件
   more、less    分页显示文本文件内容
   head、tail    显示文件头、文件尾
二、系统常用命令
1、系统管理命令
   stat         显示指定文件的详细信息
   who          显示在线登录的用户
   whoami       显示当前操作的用户
   hostname     显示主机名
   uname        显示系统信息
   top          动态显示当前耗费资源最多的进程信息
   ps           显示瞬时进程状态
   du           查看目录大小du  -h /home 带有单位的显示目录信息
   df           查看磁盘大小 df -h  带有单位显示磁盘信息
   ifconfig     查看网络情况等 例如IP值
   ping         测试网络是否连通
   netstat      显示网络状态信息
   man          可以查看Linux中的指令帮助、配置文件帮助和编程帮助
   clear        清屏
   kill         杀死进程
2、关机重启机器
   shutdown 
       -r       关机重启
       -h       关机不重启  shutdown -h  10   10分钟后关机
       now      立刻关机
    halt        关机
    reboot      重启
3、vim使用命令
   :q          退出
   :q!         强制退出
   :wq         保存退出
4、打包压缩的命令
  tar:          打包压缩
     -c         归档文件
     -x         压缩文件
     -z         gzip压缩文件
     -j         bzip2压缩文件
     -v         显示压缩或解压缩过程 v(view)
     -f         使用档名
    例如：
       tar -cvf /home/a.tar /home/a            只打包，不压缩
       tar -zcvf /home/a.tar.gz /home/a        打包，并用gzip压缩
       tar -jcvf /home/a.tar.bz2 /home/a       打包，并用bzip2压缩
5.网络常用命令
  
    
