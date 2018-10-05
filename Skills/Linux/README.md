一文件常用指令 (查看、删除) 等<br>
1、linux         日志实时查看<br>
    cat          文件名     查看日志<br>
    tail -f      文件名   实时查看日志  一直等待刷新日志尾部信息<br>
    tail -n 20   文件名 实时查看最后一部分内容默认10行 改为20行<br>
2、显示文件及目录<br>
   ls            显示文件或者目录<br>
      -l         显示文件详细信息<br>
     -a          显示当前目录下所有文件或者文件夹以及隐藏文件<br>
3、文件常用命令<br>
   mkdir         创建目录<br>
       -p        若无父目录，则创建父目录<br>
   chmod         更改文件权限<br>
   touch         创建空文件<br>
   echo          创建带有内容的文件<br>
   cat           查看文件内容<br>
   cp            拷贝<br>
   mv            移动或者重命名<br>
   rm            删除文件<br>
       -r        递归删除，可删除子目录及文件<br>
       -f        强制删除<br>
   find          在文件系统中搜索某个文件v<br>
   wc            统计文本中的行数字数和字符数<br>
   grep          在文本中查看某个字符串<br>
   rmdir         删除空目录<br>
   tree          树形结构查看显示目录，需要安装tree包<br>
   pwd           显示当前目录<br>
   In            创建链接文件<br>
   more、less    分页显示文本文件内容<br>
   head、tail    显示文件头、文件尾<br>
二、系统常用命令<br>
1、系统管理命令<br>
   stat         显示指定文件的详细信息<br>
   who          显示在线登录的用户<br>
   whoami       显示当前操作的用户<br>
   hostname     显示主机名<br>
   uname        显示系统信息<br>
   top          动态显示当前耗费资源最多的进程信息<br>
   ps           显示瞬时进程状态<br>
   du           查看目录大小du  -h /home 带有单位的显示目录信息<br>
   df           查看磁盘大小 df -h  带有单位显示磁盘信息<br>
   ifconfig     查看网络情况等 例如IP值<br>
   ping         测试网络是否连通<br>
   netstat      显示网络状态信息<br>
   man          可以查看Linux中的指令帮助、配置文件帮助和编程帮助<br>
   clear        清屏<br>
   kill         杀死进程<br>
2、关机重启机器<br>
   shutdown<br>
       -r       关机重启<br>
       -h       关机不重启  shutdown -h  10   10分钟后关机<br>
       now      立刻关机<br>
    halt        关机<br>
    reboot      重启<br>
3、vim使用命令<br>
   :q          退出<br>
   :q!         强制退出<br>
   :wq         保存退出<br>
4、打包压缩的命令<br>
  tar:          打包压缩<br>
     -c         归档文件<br>
     -x         压缩文件<br>
     -z         gzip压缩文件<br>
     -j         bzip2压缩文件<br>
     -v         显示压缩或解压缩过程 v(view)<br>
     -f         使用档名<br>
    例如：<br>
       tar -cvf /home/a.tar /home/a            只打包，不压缩<br>
       tar -zcvf /home/a.tar.gz /home/a        打包，并用gzip压缩<br>
       tar -jcvf /home/a.tar.bz2 /home/a       打包，并用bzip2压缩<br>
5.网络常用命令集<br>
  
    
