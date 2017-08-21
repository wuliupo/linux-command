# [Linux 命令大全](./)
## 1. 系统管理
  1. 系统安全
    1. [系统默认的日志守护进程](#command/syslog)
    1. [强大的安全套接字层密码库](#command/openssl)
    1. [可定制和可插入式的日志监视系统](#command/logwatch)
    1. [列出登入系统失败的用户相关信息](#command/lastb)
    1. [以其他身份来执行命令](#command/sudo)
    1. [显示系统中所有用户最近一次登录信息](#command/lastlog)
    1. [统日志进行轮转、压缩和删除](#command/logrotate)
    1. [把根目录换成指定的目的目录](#command/chroot)
    1. [将命令的输出信息保存到指定的日志文件](#command/logsave)
    1. [列出目前与过去登入系统的用户相关信息](#command/last)
  1. 进程和作业管理
    1. [删除消息队列、信号集、或者共享内存标识](#command/ipcrm)
    1. [系统服务管理器指令](#command/systemctl)
    1. [显示目前登入系统的用户信息](#command/w)
    1. [周期性的方式执行给定的指令](#command/watch)
    1. [查找指定名称的进程的进程号ID号](#command/pidof)
    1. [向选定的进程发送信号冻结进程](#command/skill)
    1. [设置用户的认证信息，包括用户密码、密码过期时间等](#command/pgrep)
    1. [修改正在运行的进程的调度优先级](#command/renice)
    1. [将程序以忽略挂起信号的方式运行起来](#command/nohup)
    1. [分析消息队列共享内存和信号量 ](#command/ipcs)
    1. [报告进程的内存映射关系](#command/pmap)
    1. [改变程序执行的优先权等级](#command/nice)
    1. [控制系统服务的实用工具](#command/service)
    1. [以树状图的方式展现进程之间的派生关系](#command/pstree)
    1. [切换当前正在运行系统的运行等级](#command/telint)
    1. [使用进程的名称来杀死一组进程](#command/killall)
    1. [打印当前Linux系统的运行等级](#command/runlevel)
    1. [在系统不繁忙的时候执行定时任务](#command/batch)
    1. [报告当前系统的进程状态](#command/ps)
    1. [init进程是所有Linux进程的父进程](#command/init)
    1. [提交和管理用户的需要周期性执行的任务](#command/crontab)
    1. [可以按照进程名杀死进程](#command/pkill)
    1. [删除待执行任务队列中的指定任务](#command/atrm)
    1. [列出当前用户的at任务列表](#command/atq)
    1. [在指定时间执行一个任务](#command/at)
  1. 用户和工作组管理
    1. [修改帐号和密码的有效期限](#command/chage)
    1. [显示用户的ID以及所属群组的ID](#command/id)
    1. [用来开启群组的投影密码](#command/grpconv)
    1. [用来关闭用户的投影密码](#command/pwunconv)
    1. [用来开启用户的投影密码](#command/pwconv)
    1. [拒绝用户登录系统](#command/nologin)
    1. [批量更新用户口令的工具](#command/chpasswd)
    1. [用来关闭群组的投影密码](#command/grpunconv)
    1. [用于验证组文件的完整性](#command/grpck)
    1. [用于删除指定的工作组](#command/groupdel)
    1. [用来更换登录系统时使用的shell](#command/chsh)
    1. [Linux下工作组文件的管理工具](#command/gpasswd)
    1. [用来验证系统认证文件内容和格式的完整性](#command/pwck)
    1. [更改群组识别码或名称](#command/groupmod)
    1. [用于让用户可以更改自己的密码](#command/passwd)
    1. [用来改变finger命令显示的信息](#command/chfn)
    1. [用于批处理的方式一次创建多个命令](#command/newusers)
    1. [用来显示用户名称](#command/logname)
    1. [用来打印指定用户所属的工作组](#command/groups)
    1. [用于查找并显示用户信息](#command/finger)
    1. [用于切换当前用户身份到其他用户身份](#command/su)
    1. [用于修改用户的基本信息](#command/usermod)
    1. [用于创建一个新的工作组](#command/groupadd)
    1. [用于删除给定的用户以及与用户相关的文件](#command/userdel)
    1. [创建的新的系统用户](#command/useradd)
  1. X-Windows
    1. [管理 X 粘贴板](#command/xclip)
    1. [设置X-Window系统中的用户爱好的实用工具](#command/xset)
    1. [列出X Server使用的字体](#command/xlsfonts)
    1. [制哪些X客户端能够在X服务器上显示](#command/xhost)
    1. [列出X服务器内部所有定义的原子成分](#command/xlsatoms)
    1. [显示和编辑被用于连接X服务器的认证信息](#command/xauth)
    1. [列出显示器中的客户端应用程序](#command/xlsclients)
    1. [是Linux下X-Window系统的初始化程序](#command/xinit)
    1. [用来启动X Window](#command/startx)
  1. SELinux
    1. [恢复文件的安全上下文](#command/restorecon)
    1. [默认目录的安全上下文查询与修改](#command/semanage)
    1. [修改SElinux策略内各项规则的布尔值](#command/setsebool)
    1. [查询SElinux策略内各项规则的布尔值](#command/getsebool)
    1. [查询SELinux策略的规则详情](#command/sesearch)
    1. [查询SELinux的策略提供多少相关规则](#command/seinfo)
    1. [修改对象（文件）的安全上下文](#command/chcon)
  1. 文件系统管理
    1. [报表的格式输出磁盘空间限制的状态](#command/repquota)
    1. [设置第二扩展文件系统的卷标](#command/e2label)
    1. [标签或UUID查找文件系统](#command/findfs)
    1. [ ext2/ext2文件系统重新设置大小](#command/resize2fs)
    1. [将处于危险状态的文件系统保存到文件中](#command/e2image)
    1. [调整或查看ext2/ext3文件系统的文件系统参数](#command/tune2fs)
    1. [用于强制被改变的内容立刻写入磁盘](#command/sync)
    1. [关闭指定的交换空间](#command/swapoff)
    1. [激活Linux系统中交换空间](#command/swapon)
    1. [显示磁盘已使用的空间与限制](#command/quota)
    1. [显示系统当前的磁盘配额运行状态信息](#command/quotastats)
    1. [用于编辑指定用户或工作组磁盘配额](#command/edquota)
    1. [激活Linux内核中指定文件系统的磁盘配额功能](#command/quotaon)
    1. [检查磁盘的使用空间与限制](#command/quotacheck)
    1. [关闭Linux内核中指定文件系统的磁盘配额功能](#command/quotaoff)
    1. [用于在设备上创建Linux文件系统](#command/mkfs)
    1. [用来判断指定的目录是否是加载点](#command/mountpoint)
    1. [用于卸载已经加载的文件系统](#command/umount)
    1. [用于检查第二扩展文件系统的完整性](#command/e2fsck)
    1. [用于打印“ext2/ext3”文件系统的超级块和快组信息](#command/dumpe2fs)
    1. [用于加载文件系统到指定的加载点](#command/mount)
    1. [检查并且试图修复文件系统中的错误](#command/fsck)
    1. [创建磁盘分区上的“etc2/etc3”文件系统](#command/mke2fs)
  1. 系统关机和重启
    1. [关闭正在运行的Linux操作系统](#command/halt)
    1. [设置组合键Ctrl+Alt+Del的功能](#command/ctrlaltdel)
    1. [重新启动正在运行的Linux操作系统](#command/reboot)
    1. [用来执行系统关机的命令](#command/shutdown)
    1. [用来关闭计算机操作系统并且切断系统电源](#command/poweroff)
1. 网络管理
  1. 网络应用
    1. [多线程下载工具](#command/axel)
    1. [whois 客户端服务](#command/jwhois)
    1. [利用URL规则在命令行下工作的文件传输工具](#command/curl)
    1. [Linux系统下载文件工具](#command/wget)
    1. [登录远程主机和管理](#command/telnet)
    1. [运程执行Linux系统下命令 ](#command/rexec)
    1. [连接远程主机并执行命令](#command/rsh)
    1. [从当前终端登录到远程Linux主机](#command/rlogin)
    1. [命令行下发送和接收电子邮件](#command/mail)
    1. [显示到达的邮件状态](#command/mailstat)
    1. [纯文本模式的网页浏览器](#command/lynx)
    1. [纯文本邮件客户端程序](#command/elm)
    1. [显示待发送的邮件队列](#command/mailq)
    1. [调用lftp指令下载指定的文件](#command/lftpget)
    1. [纯文本界面的WWW浏览器](#command/elinks)
    1. [简单的IP地址计算器](#command/ipcalc)
    1. [优秀的文件客户端程序](#command/lftp)
  1. 高级网络
    1. [将PCAP包重新发送，用于性能或者功能测试](#command/tcpreplay)
    1. [PF防火墙的配置命令](#command/pfctl)
    1. [实时地监视网卡流量](#command/iptraf)
    1. [获取socket统计信息](#command/ss)
    1. [监视SNMP计数器和网络接口状态](#command/nstat/rtacct)
    1. [显示Linux系统的网路状态](#command/lnstat)
    1. [管理ARP包过滤规则表](#command/arptables)
    1. [收集免费ARP信息](#command/arpd)
    1. [一款sniffer工具](#command/tcpdump)
    1. [网络配置工具](#command/ip)
    1. [还原ip6tables表](#command/ip6tables-restore)
    1. [保存ip6tables表配置](#command/ip6tables-save)
    1. [linux中防火墙软件](#command/ip6tables)
    1. [还原iptables表的配置](#command/iptables-restore)
    1. [备份iptables的表配置](#command/iptables-save)
    1. [Linux上常用的防火墙软件](#command/iptables)
  1. 网络测试
    1. [测试网络及主机的安全](#command/hping3)
    1. [网络性能测试工具](#command/iperf)
    1. [常用的分析域名查询工具](#command/host)
    1. [追踪目的主机经过的路由信息](#command/tracepath)
    1. [监听网络上ARP的记录](#command/arpwatch)
    1. [查询域名DNS信息的工具](#command/nslookup)
    1. [通过发送ARP协议报文测试网络](#command/arping)
    1. [用来设置路由器](#command/nc/netcat)
    1. [域名查询工具](#command/dig)
    1. [显示和修改IP到MAC转换表](#command/arp)
    1. [测试主机之间网络的连通性](#command/ping)
    1. [显示数据包到主机间的路径](#command/traceroute)
    1. [查看Linux中网络系统状态信息](#command/netstat)
  1. 网络安全
    1. [把本地的ssh公钥文件安装到远程主机对应的账户下](#command/ssh-copy-id)
    1. [ssh密钥管理器](#command/ssh-agent)
    1. [把专用密钥添加到ssh-agent的高速缓存中](#command/ssh-add)
    1. [网络探测和安全审核](#command/nmap)
    1. [显示iptables的工作状态](#command/iptstate)
    1. [为ssh生成、管理和转换认证密钥](#command/ssh-keygen)
    1. [sftp协议的服务器端程序](#command/sftp-server)
    1. [openssh软件套件中的服务器守护进程](#command/sshd)
    1. [收集主机公钥的使用工具](#command/ssh-keyscan)
    1. [交互式的文件传输程序](#command/sftp)
    1. [openssh套件中的客户端连接工具](#command/ssh)
  1. 网络配置
    1. [配置网络设备协商方式的工具](#command/mii-tool)
    1. [显示或修改以太网卡的配置信息](#command/ethtool)
    1. [显示主机NIS的域名](#command/nisdomainname)
    1. [动态获取或释放IP地址](#command/dhclient)
    1. [显示和设置系统的NIS域名](#command/domainname)
    1. [显示主机的NIS的域名](#command/ypdomainname)
    1. [被允许时操作指定的网络接口](#command/usernetctl)
    1. [定义DNS系统中FQDN名称的域名](#command/dnsdomainname)
    1. [显示和设置系统的主机名](#command/hostname)
    1. [激活指定的网络接口](#command/ifup)
    1. [置Linux中的网络接口参数](#command/ifcfg)
    1. [配置和显示Linux系统网卡的网络参数](#command/ifconfig)
    1. [禁用指定的网络接口](#command/ifdown)
    1. [显示并设置Linux中静态路由表](#command/route)
  1. 网络服务器
    1. [为MySQL服务器用命令行方式导入数据](#command/mysqlimport)
    1. [在指定的时间关闭FTP服务器](#command/ftpshut)
    1. [显示目前已FTP登入的用户人数](#command/ftpcount)
    1. [管理NFS共享文件系统列表](#command/exportfs)
    1. [Apache服务器前端控制工具](#command/apachectl)
    1. [Apache服务器的性能测试工具](#command/ab)
    1. [squid服务器守护进程](#command/squid)
    1. [MySQL服务器客户端工具](#command/mysql)
    1. [著名电子邮件服务器](#command/sendmail)
    1. [显示MySQL中数据库相关信息](#command/mysqlshow)
    1. [samba用户和密码管理工具](#command/smbpasswd)
    1. [squid服务器的客户端管理工具](#command/squidclient)
    1. [交互方式访问samba服务器](#command/smbclient)
    1. [显示NFS服务器加载的信息](#command/showmount)
    1. [列出NFS客户端和服务器的工作状态](#command/nfsstat)
    1. [MySQL服务器管理客户端](#command/mysqladmin)
    1. [显示当前每个ftp会话信息](#command/ftpwho)
    1. [MySQL数据库中备份工具](#command/mysqldump)
    1. [Apache服务器内置工具](#command/htdigest)
    1. [apache服务器创建密码认证文件](#command/htpasswd)
    1. [proftpd服务器的连接状态](#command/ftptop)
1. 软件 | 打印 | 开发 | 工具
  1. 常用工具命令
    1. [批量管理执行](#command/pssh)
    1. [用于命令行终端切换](#command/screen)
    1. [命令行下测试服务器外网速度](#command/speedtest-cli)
    1. [检测两台linux主机的时间差](#command/clockdiff)
    1. [使用网络计时协议（NTP）设置日期和时间](#command/ntpdate)
    1. [远程数据同步工具](#command/rsync)
    1. [VirtualBox软件挂载VDI分区文件工具](#command/vdfuse)
    1. [方便的数据包匹配和显示工具](#command/ngrep)
    1. [shell中给临时文件命名](#command/tempfile)
    1. [给其他命令传递参数的一个过滤器](#command/xargs)
    1. [文本和数据进行处理的编程语言](#command/awk)
    1. [重复打印指定字符串](#command/yes)
    1. [显示或设置系统时间与日期](#command/date)
    1. [输出已连接的终端类型](#command/consoletype)
    1. [Linux下info格式的帮助指令](#command/info)
    1. [用来打印当前主机的数字化标识](#command/hostid)
    1. [清除当前屏幕终端上的任何信息](#command/clear)
    1. [打印当前有效的用户名称](#command/whoami)
    1. [显示当前登录系统的所有用户](#command/users)
    1. [将目前动作延迟一段时间](#command/sleep)
    1. [计算和校验文件报文摘要的工具程序](#command/md5sum)
    1. [设置当前终端的写权限](#command/mesg)
    1. [显示mtools支持的指令](#command/mtools)
    1. [登录系统或切换用户身份](#command/login)
    1. [修改终端命令行的相关设置](#command/stty)
    1. [让用户和其他用户聊天](#command/talk)
    1. [查看Linux中的指令帮助](#command/man)
    1. [查询一个命令执行什么功能](#command/whatis)
    1. [向指定登录用户终端上发送信息](#command/write)
    1. [显示目前登录系统的用户信息](#command/who)
    1. [计算文件的校验码和显示块数](#command/sum)
    1. [向系统当前所有打开的终端上输出信息](#command/wall)
    1. [置ls命令在显示目录或文件时所用的色彩](#command/dircolors)
    1. [提供文字模式下的滑鼠事件处理](#command/gpm)
    1. [算术操作精密运算工具](#command/bc)
    1. [显示当前日历或指定日期的日历](#command/cal)
    1. [检查文件的CRC是否正确](#command/cksum)
  1. 软件包管理
    1. [新一代的RPM软件包管理器](#command/dnf)
    1. [Debian Linux中重新配制一个已经安装的软件包](#command/dpkg-reconfigure)
    1. [Debian Linux系统上安装、创建和管理软件包](#command/dpkg)
    1. [Debian Linux下对软件包索引文件进行排序的工具](#command/apt-sortpkgs)
    1. [管理Debian Linux系统中的软件包密钥](#command/apt-key)
    1. [Debian Linux系统中软件包管理工具](#command/aptitude)
    1. [Debian Linux发行版中的APT软件包管理工具](#command/apt-get)
    1. [集中管理系统的各种服务](#command/ntsysv)
    1. [检查或设置系统的各种服务](#command/chkconfig)
    1. [使用RPM软件包的签名管理工具](#command/rpmsign)
    1. [初始化和重建RPM数据库](#command/rpmdb)
    1. [基于RPM的软件包管理器](#command/yum)
    1. [Debian Linux下的软件包触发器](#command/dpkg-trigger)
    1. [RPM软件包的管理工具](#command/rpm)
    1. [Debian Linux下的运行等级服务配置工具](#command/rcconf)
    1. [创建RPM的二进制软件包和源码软件包](#command/rpmbuild)
    1. [验证已安装的RPM软件包的正确性](#command/rpmverify)
    1. [从RPM数据库中查询软件包信息](#command/rpmquery)
    1. [为开放源代码软件安装补丁程序](#command/patch)
    1. [将RPM软件包转换为cpio格式的文件](#command/rpm2cpio)
    1. [Debian Linux中覆盖文件的所有权和模式](#command/dpkg-statoverride)
    1. [Debian Linux中软件包安装之前询问问题](#command/dpkg-preconfigure)
    1. [Debian Linux中将大软件包分割成小包](#command/dpkg-split)
    1. [Debian Linux中软件包的查询工具](#command/dpkg-query)
    1. [Debian Linux中创建并管理一个转向列表](#command/dpkg-divert)
    1. [Debian Linux下的软件包管理工具](#command/dpkg-deb)
  1. 编程开发
    1. [动态链接库管理命令](#command/ldconfig)
    1. [用于显示elf格式文件的信息](#command/readelf)
    1. [显示二进制文件信息](#command/objdump)
    1. [显示每个进程的栈跟踪](#command/pstack)
    1. [格式化C语言的源文件](#command/indent)
    1. [功能强大的程序调试器](#command/gdb)
    1. [基于C/C++的编译器](#command/gcc)
    1. [一款表达式计算工具](#command/expr)
    1. [shell环境中测试条件表达式工具](#command/test)
    1. [PHP语言的命令行接口](#command/php)
    1. [GNU-C代码转换为ANSI-C代码](#command/protoize)
    1. [创建临时文件供shell脚本使用](#command/mktemp)
    1. [perl语言解释器](#command/perl)
    1. [GNU的工程化编译工具](#command/make)
    1. [打印程序或者库文件所依赖的共享库列表](#command/ldd)
    1. [显示二进制目标文件的符号表](#command/nm)
    1. [删除C语言源代码文件中的函数原型](#command/unprotoize)
    1. [将目标文件连接为可执行程序](#command/ld)
    1. [测试程序的代码覆盖率的工具](#command/gcov)
    1. [汇编语言编译器](#command/as)
  1. 打印
    1. [指示打印系统拒绝发往指定目标打印机的打印任务](#command/reject)
    1. [配置CUPS套件中的打印机和类](#command/lpadmin)
    1. [启动指定的打印机](#command/cupsenable)
    1. [指示打印系统接受发往指定目标打印机的打印任务](#command/accept)
    1. [显示CUPS中打印机的状态信息](#command/lpstat)
    1. [停止指定的打印机](#command/cupsdisable)
    1. [命令行方式打印机控制程序](#command/lpc)
    1. [取消已存在的打印任务](#command/cancel)
    1. [打印文件或修改排队的打印任务](#command/lp)
    1. [显示打印队列中的打印任务的状态信息](#command/lpq)
    1. [用来退出抽取式设备](#command/eject)
    1. [删除打印队列中的打印任务](#command/lprm)
    1. [将文件发送给指定打印机进行打印](#command/lpr)
1. 文件目录管理
  1. 文件查找和比较
    1. [在对象文件或二进制文件中查找可打印的字符串](#command/strings)
    1. [比较给定的两个文件的不同](#command/diff)
    1. [比较两个文件是否有差异](#command/cmp)
    1. [比较3个文件不同的地方](#command/diff3)
    1. [查找文件或目录](#command/locate/slocate)
    1. [查找并显示给定命令的绝对路径](#command/which)
    1. [在指定目录下查找文件](#command/find)
    1. [查找二进制程序、代码等相关文件路径](#command/whereis)
  1. 文件内容查看
    1. [显示文件十六进制格式](#command/hexdump)
    1. [输出文件的八进制、十六进制等格式编码的字节](#command/od)
    1. [连接文件并打印到标准输出设备上](#command/cut)
    1. [在屏幕上显示指定文件的末尾若干行](#command/tail)
    1. [在屏幕上显示指定文件的开头若干行](#command/head)
    1. [分屏上下翻页浏览文件内容](#command/less)
    1. [显示文件内容，每次显示一屏](#command/more)
  1. 文件处理
    1. [转换文件的编码方式](#command/iconv)
    1. [在Linux系统中计算文件内容行号](#command/nl)
    1. [打印目录或者文件的基本名称](#command/basename)
    1. [系统调用函数unlink去删除指定的文件](#command/unlink)
    1. [检查文件中不可移植的部分](#command/pathchk)
    1. [创建新的空文件](#command/touch)
    1. [用字符串替换的方式批量改变文件名](#command/rename)
    1. [复制文件并对原文件的内容进行转换和格式化处理](#command/dd)
    1. [去除文件名中的非目录部分](#command/dirname)
    1. [创建或更新slocate命令所必需的数据库文件](#command/updatedb)
    1. [用来为文件创件连接](#command/ln)
    1. [连接文件并打印到标准输出设备上](#command/cat)
  1. 文件编辑
    1. [字符终端文本编辑器](#command/nano)
    1. [功能强大的流式文本编辑器](#command/sed)
    1. [功能强大全屏幕的文本编辑器](#command/pico)
    1. [功能强大的全屏文本编辑器](#command/emacs)
    1. [主要用于编辑代码的编辑器](#command/jed)
    1. [强大的纯文本编辑器](#command/joe)
    1. [单行纯文本编辑器](#command/ed)
    1. [启动vim编辑器的ex编辑模式](#command/ex)
    1. [功能强大的纯文本编辑器](#command/vi)
  1. 目录基本操作
    1. [安装或升级软件或备份数据](#command/install)
    1. [树状图列出目录的内容](#command/tree)
    1. [用于删除目录栈中的记录](#command/popd)
    1. [将目录加入命令堆叠中](#command/pushd)
    1. [显示目录记录](#command/dirs)
    1. [用来删除空目录](#command/rmdir)
    1. [用来创建目录](#command/mkdir)
    1. [用于删除给定的文件和目录](#command/rm)
    1. [绝对路径方式显示用户当前工作目录](#command/pwd)
    1. [显示目录内容列表](#command/ls)
    1. [用来对文件或目录重新命名](#command/mv)
    1. [将源文件或目录复制到目标文件或目录中](#command/cp)
    1. [切换用户当前工作目录](#command/cd)
  1. 文件权限属性设置
    1. [将DOS格式文本文件转换成Unix格式](#command/dos2unix)
    1. [设置文件访问控制列表](#command/setfacl)
    1. [用来设置限制新建文件权限的掩码](#command/umask)
    1. [查看文件的第二扩展文件系统属性](#command/lsattr)
    1. [用来变更文件或目录的权限](#command/chmod)
    1. [用来变更文件或目录的拥有者或所属群组](#command/chown)
    1. [用来变更文件或目录的所属群组](#command/chgrp)
    1. [用来改变文件属性](#command/chattr)
    1. [用于显示文件的状态信息](#command/stat)
    1. [用来探测给定文件的类型。](#command/file)
  1. 文件过滤分割与合并
    1. [在文件内查找指定的字符串](#command/egrep)
    1. [为文件搜索文字字符串](#command/fgrep)
    1. [分割任意大小的文件](#command/split)
    1. [强大的文本搜索工具](#command/grep)
    1. [两个文件之间的比较](#command/comm)
    1. [格式化并输出结果](#command/printf)
    1. [将文件的制表符转换为空白字符](#command/expand)
    1. [对文件进行拼写检查](#command/spell)
    1. [将文本文件转换成适合打印的格式](#command/pr)
    1. [显示文件中以指定字符串开头的任意行](#command/look)
    1. [将文件已行为单位的反序输出](#command/tac)
    1. [统计文件的字节数、字数、行数](#command/wc)
    1. [读取文件后优化处理并输出](#command/fmt)
    1. [将文件内容以字符为单位反序输出](#command/rev)
    1. [显示diff命令输出信息的柱状图](#command/diffstat)
    1. [检查文件中出现的拼写错误](#command/ispell)
    1. [报告或忽略文件中的重复行](#command/uniq)
    1. [把数据重定向到给定文件和屏幕上](#command/tee)
    1. [将多个文件按列队列合并](#command/paste)
    1. [将文件进行排序并输出](#command/sort)
    1. [将文件的空白字符转换为制表符](#command/unexpand)
    1. [将一个大文件分割成小的碎片文件](#command/csplit)
    1. [控制文件内容输出时所占用的屏幕宽度](#command/fold)
    1. [两个文件中指定栏位内容相同的行连接起来](#command/join)
    1. [过滤控制字符](#command/col)
    1. [将字符进行替换压缩和删除](#command/tr)
    1. [删除文件中的指定列](#command/colrm)
  1. 文件压缩与解压
    1. [压缩或解压缩lzh格式文件](#command/lha)
    1. [比较两个压缩包中的文件](#command/bzcmp)
    1. [解压缩指定的.bz2文件](#command/bzcat)
    1. [解压缩由arj命令创建的压缩包](#command/unarj)
    1. [显示压缩包中文件的内容](#command/zcat)
    1. [将.Z压缩包重新转化为gzip命令压缩的.gz压缩包](#command/znew)
    1. [将较大的zip压缩包分割成各个较小的压缩包](#command/zipsplit)
    1. [用于创建和管理.arj压缩包](#command/arj)
    1. [用来压缩可执行文件](#command/gzexe)
    1. [使用正则表达式搜索.bz2压缩包中文件](#command/bzgrep)
    1. [使用Lempress-Ziv编码压缩数据文件](#command/compress)
    1. [强制为gzip格式的压缩文件添加.gz后缀](#command/zfore)
    1. [增强.bz2压缩包查看器](#command/bzless)
    1. [查看bzip2压缩过的文本文件的内容](#command/bzmore)
    1. [用来列出压缩文件信息](#command/zipinfo)
    1. [用于解压缩由zip命令压缩的压缩包](#command/unzip)
    1. [恢复被破坏的.bz2压缩包中的文件](#command/bzip2recover)
    1. [Linux下的归档使用工具，用来打包和备份。](#command/tar)
    1. [创一个bz2文件压缩包](#command/bunzip2)
    1. [用来解压缩文件](#command/gunzip)
    1. [直接比较两个.bz2压缩包中文件的不同](#command/bzdiff)
    1. [可以用来解压缩文件](#command/zip)
    1. [将文件压缩成bz2格式](#command/bzip2)
    1. [用来压缩文件](#command/gzip)
    1. [用来解压.Z文件](#command/uncompress)
  1. 文件备份和恢复
    1. [用来建立、还原备份档的工具程序](#command/cpio)
    1. [所进行的操作和dump指令相反](#command/restore)
    1. [用于备份ext2或者ext3文件系统](#command/dump)
  1. 文件传输
    1. [用来设置文件系统相关功能](#command/ftp)
    1. [在本机和tftp服务器之间使用TFTP协议传输文件](#command/tftp)
    1. [加密的方式在本地主机和远程主机之间复制文件](#command/scp)
    1. [是增强的的FTP工具](#command/ncftp)
    1. [使在两台Linux主机之间的文件复制操作更简单](#command/rcp)
1. 硬件 | 监测 | 内核 | Shell
  1. Shell内建命令
    1. [shell命令解释器](#command/sh)
    1. [指定在接收到信号后将要采取的动作](#command/trap)
    1. [简单的计算器](#command/let)
    1. [以指定增量从首数开始打印数字到尾数](#command/seq)
    1. [通过terminfo数据库对终端会话进行初始化和操作](#command/tput)
    1. [在 whatis 数据库中查找字符串](#command/apropos)
    1. [显示或设置shell特性及shell变量](#command/set)
    1. [调用并执行指定的命令](#command/command)
    1. [显示和清空目录堆栈中的内容](#command/dris)
    1. [修改历史命令并执行](#command/fc)
    1. [显示或设置键盘按键与其相关的功能](#command/bind)
    1. [定义只读shell变量或函数](#command/readonly)
    1. [从键盘读取变量值](#command/read)
    1. [用于将作业放到后台运行](#command/bg)
    1. [控制shell程序的资源](#command/ulimit)
    1. [启动或关闭shell内建命令](#command/enable)
    1. [声明或显示shell变量](#command/declare)
    1. [等待进程执行完后返回](#command/wait)
    1. [执行shell内部命令](#command/builtin)
    1. [显示和设置shell操作选项](#command/shopt)
    1. [退出当前的shell](#command/exit)
    1. [显示Linux中的任务列表及任务状态](#command/jobs)
    1. [显示帮助信息](#command/help)
    1. [用于显示历史命令](#command/history)
    1. [退出当前登录的Shell](#command/logout)
    1. [设置或显示系统环境变量](#command/export)
    1. [调用并执行指定的命令](#command/exec)
    1. [显示系统中已存在的环境变量](#command/env)
    1. [删除指定的shell变量或函数](#command/unset)
    1. [删除执行中的程序或工作](#command/kill)
    1. [删除由alias设置的别名](#command/unalias)
    1. [显示指定命令的类型](#command/type)
    1. [将后台作业放到前台终端运行](#command/fg)
    1. [用来设置指令的别名](#command/alias)
    1. [输出指定的字符串或者变量](#command/echo)
  1. 性能监测与优化
    1. [异步文件系统监控机制](#command/inotifywait)
    1. [终端下的网络流量监控工具](#command/nethogs)
    1. [统计网络接口流量状态](#command/ifstat)
    1. [通用的系统资源统计工具](#command/dstat)
    1. [用来跟踪进程调用库函数的情况](#command/ltrace)
    1. [用来监视磁盘I/O使用状况的工具](#command/iotop)
    1. [跟踪系统调用和信号](#command/strace)
    1. [使用文件或文件结构识别进程](#command/fuser)
    1. [显示Linux系统当前已打开的所有文件列表](#command/lsof)
    1. [显示系统负载状况](#command/tload)
    1. [统计给定命令所花费的总时间](#command/time)
    1. [显示虚拟内存状态](#command/vmstat)
    1. [系统运行状态统计工具](#command/sar)
    1. [显示各个可用CPU的状态](#command/mpstat)
    1. [监视系统输入输出设备和CPU的使用情况](#command/iostat)
    1. [显示内存的使用情况](#command/free)
    1. [查看Linux系统负载信息](#command/uptime)
    1. [显示或管理执行中的程序](#command/top)
  1. 硬件管理
    1. [设定与控制循环（loop）设备](#command/losetup)
    1. [在Linux系统下获取有关硬件方面的信息](#command/dmidecode)
    1. [显示与设定硬件时钟](#command/hwclock)
    1. [Linux系统下光盘刻录功能命令](#command/cdrecord)
    1. [查询和配置PCI设备的使用工具](#command/setpci)
    1. [显示当前主机的所有PCI总线信息](#command/lspci)
    1. [显示本机的USB设备列表信息](#command/lsusb)
    1. [显示当前主机的硬件架构类型](#command/arch)
    1. [显示指定的ISO-9660格式的设备的卷名称](#command/volname)
    1. [显示基于总线、类和拓扑显示系统中设备的信息](#command/systool)
  1. 内核与模块管理
    1. [显示发行版本信息](#command/lsb_release)
    1. [时动态地修改内核的运行参数](#command/sysctl)
    1. [实时显示内核slab内存缓存信息](#command/slabtop)
    1. [打印当前内核的主版本号](#command/kernelversion)
    1. [获取Linux内核模块的详细信息](#command/get_module)
    1. [从当前正在运行的内核引导到一个新内核](#command/kexec)
    1. [显示Linux系统启动信息](#command/dmesg)
    1. [显示Linux系统信息](#command/uname)
    1. [分析可载入模块的相依性](#command/depmod)
    1. [显示给定模块的详细信息](#command/bmodinfo)
    1. [自动处理可载入模块](#command/modprobe)
    1. [从运行的内核中移除指定的内核模块](#command/rmmod)
    1. [将给定的模块加载到内核中](#command/insmod)
    1. [显示已载入系统的模块](#command/lsmod)
  1. 磁盘管理
    1. [查看块设备的文件系统类型、LABEL、UUID等信息](#command/blkid)
    1. [显示每个文件和目录的磁盘使用空间](#command/du)
    1. [列出块设备信息](#command/lsblk)
    1. [用于用户删除LVM卷组](#command/vgremove)
    1. [调整逻辑卷空间大小](#command/lvresize)
    1. [删除指定LVM逻辑卷](#command/lvremove)
    1. [收缩逻辑卷空间](#command/lvreduce)
    1. [输出物理卷信息报表](#command/pvs)
    1. [修改物理卷属性](#command/pvchange)
    1. [检测物理卷的LVM元数据的一致性](#command/pvck)
    1. [删除一个存在的物理卷](#command/pvremove)
    1. [扩展逻辑卷空间](#command/lvextend)
    1. [显示物理卷的属性](#command/pvdisplay)
    1. [显示逻辑卷属性](#command/lvdisplay)
    1. [扫描系统中所有硬盘的物理卷列表](#command/pvscan)
    1. [扫描逻辑卷](#command/lvscan)
    1. [用于创建LVM的逻辑卷](#command/lvcreate)
    1. [将物理硬盘分区初始化为物理卷](#command/pvcreate)
    1. [转换卷组元数据格式](#command/vgconvert)
    1. [从命令行调用区块设备控制程序](#command/blockdev)
    1. [建立和设置SWAP交换分区](#command/mkswap)
    1. [修改卷组属性](#command/vgchange)
    1. [创建字符设备文件和块设备文件](#command/mknod)
    1. [建立ISO 9660映像文件](#command/mkisofs)
    1. [建立要载入ramdisk的映像文件](#command/mkinitrd)
    1. [从卷组中删除物理卷](#command/vgreduce)
    1. [显示与设定硬盘的参数](#command/hdparm)
    1. [向卷组中添加物理卷](#command/vgextend)
    1. [不重启的情况下重读分区](#command/partprobe)
    1. [扫描并显示系统中的卷组](#command/vgscan)
    1. [用于创建LVM卷组](#command/vgcreate)
    1. [查看磁盘使用情况和磁盘分区](#command/fdisk)
    1. [查找磁盘中损坏的区块](#command/badblocks)
    1. [显示LVM卷组的信息](#command/vgdisplay)
    1. [可建立目前系统的启动盘](#command/mkbootdisk)
    1. [多重引导程序grub的命令行shell工具](#command/grub)
    1. [把老的配额文件转换为新的格式](#command/convertquota)
    1. [安装核心载入开机管理程序](#command/lilo)
    1. [显示磁盘的相关信息](#command/df)
    1. [磁盘分区和分区大小调整工具](#command/parted)