⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️------⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️
🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵 GCE 简介 🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵
⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️------⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️

GCE 简介
================================================================================

🔸 GCE 优惠政策   
--------------------------------------------------------------------------------  

    现在只要绑定信用卡就送300刀(一年后失效,所以尽量在一年内花完 300刀.)
    有双币卡信用卡就行.. 免费注册. (放心 不会自动续费的!! )
    好像5块钱淘宝买了张美国信用卡/虚拟信用卡也行????
    申请地址：https://cloud.google.com/free/


🔸 缺点
--------------------------------------------------------------------------------  

    ⦿ 重启非常慢. 2分钟+ 帮瓦工的重启只要2秒...
   
    ⦿ SSD 慢! 几乎比帮瓦工慢10倍..
        gce的ssd 是容量越大速度越快的!!!!! 

        ssd 绝对没有 帮瓦工的快 . 
        gce装个lnmp 环境要 141 分钟..
        帮瓦工 好像只要半小时吧


🔸 优点
--------------------------------------------------------------------------------  

    ⦿ ❗️❗️KVM 架构: 可自定义的功能却远比 VPS 多  ❗️❗️
  
    ⦿  按分钟收费.不是包年的.可以临时开很多服务器.不用关闭了就不收费.


🔸 计费方式.
--------------------------------------------------------------------------------  

    ❗️❗️ 是按照时间(分钟)计费的!!!  越高的配置 每分钟的费用也就越高.
    ❗️❗️ 是按照时间(分钟)计费的!!!  越高的配置 每分钟的费用也就越高.


🔸 流量
--------------------------------------------------------------------------------  

    ❗️❗️ 到中国的流量是要另外收费的   $0.23/1GB  ️❗️
    ❗️❗️ 到中国的流量是要另外收费的   $0.23/1GB  ️❗️


🔸 CPU 选择
--------------------------------------------------------------------------------  

    f1-micro（0.6 GB）和 g1-small（1.7GB）这两个版本使用的是共享核心.

    0.6G 内存 只要 5刀一月. 1.7G 内存 就要 16刀一月.  区别还是很大很大的.
    虽然都是共享cpu 但是性能是不一样的!!! 千万要注意.
    0.6G 的配置随便编译安装下软件 cpu就 100% . 然后就死机了..死机啊 ... 
        ❗️不要选择最低配! 强烈建议选择倒数1.7G 的配置❗️
        ❗️不要选择最低配! 强烈建议选择倒数1.7G 的配置❗️

        ❗️ 0.60GB 是 0.2 vCPU;  1.70GB 是 0.5 vCPU.❗️
        ❗️ 0.60GB 是 0.2 vCPU;  1.70GB 是 0.5 vCPU.❗️


🔸 内部IP
--------------------------------------------------------------------------------  

    每个实例都有其对应的内网 IP，方便两个主机间建立直接的连接，
    这个内网 IP 的神奇之处在于：它可以跨可用区使用，包括跨大洲。


🔸 快照/备份
--------------------------------------------------------------------------------  

    你可以为主机增加快照，方便在其他实例中恢复快照，或者用做备份功能。
    GCE 的快照是增量备份，这意味着如果有两个快照，第二份快照只备份与第一份快照的差异部分。



🔸 固定IP
--------------------------------------------------------------------------------  

    控制面板 ➜ 网络 ➜ 外部IP 地址 ➜  保留静态地址 ➜ 选择实例把ip加到实例上.

    你申请了静态IP地址 但是不用的话是要按小时收费的!
    你申请了静态IP地址. 然后绑定到实例(停止的实例也可以)后就免费了.



🔸 地区选择
--------------------------------------------------------------------------------  

    官方区域详细介绍
    https://cloud.google.com/compute/docs/regions-zones/regions-zones#available

    ❗️❗️ asia-east1-a/b/c 是台湾中部的 国内是最快的!! ️❗️
    ❗️❗️ asia-east1-a/b/c 是台湾中部的 国内是最快的!! ️❗️
    asia-east1	      Taiwan
    asia-northeast1   Tokyo


🔸 免费配置
--------------------------------------------------------------------------------  
 
    美国地区的 可能 cpu 内存 硬盘 有免费的. 但是任何到中国的流量都是另外收费的.








⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️------⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️
🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵  帮瓦工 简介 🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵
⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️------⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️

帮瓦工 简介
================================================================================


🔸 架构选择: KVM/openVZ
--------------------------------------------------------------------------------  

    VPS 可以理解为云服务器, 一般都是一台物理服务器用虚拟化技术虚拟出很多台虚拟机,
    每台虚拟机可以看成一个vps.虚拟化技术分两种: KVM、openVZ

    KVM 可以看成 vmware. 是彻底的虚拟化,几乎可以看成物理机. 
        在vmware/kvm的虚拟机里你可以装win/linux/Mac/.... 等等

    OpenVZ 是Linux系统 上的一个软件. 可以把一个linux 物理机虚拟成很多linux 虚拟机.
        OPENVZ虚拟化出来的VPS可以安装各种linux操作系统，但是不能安装windows系统
        OPENVZ虚拟化出来的VPS可以安装各种linux操作系统，但是不能安装windows系统

    ⦿ KVM 特点:
        • 支持 Docker 
        • 价格贵.适合高端需求.
        • 可以完美的加速. 可以做到秒开youtube高清1080P视频.

    ⦿ openVZ
        • 价格便宜

    ⦿ 总结
        KVM、VMware这样的平台是今后VPS的发展方向.
        但是因为OPENVZ价格低,仍是最受欢迎的低价VPS首选。
        同等价格. openVZ 比 KVM 多出一倍内存,还多出一倍流量.



🔸 多机房✗ vs 单机房✔︎
--------------------------------------------------------------------------------  

    ⦿ 多机房

    ❗️❗️❗️官方规定: 被国内屏蔽的IP 不能切换机房,即使你选的是多机房方案❗️❗️❗️
    ❗️❗️❗️官方规定: 被国内屏蔽的IP 不能切换机房,即使你选的是多机房方案❗️❗️❗️
    ❗️❗️❗️ 多机房切换IP 只能在IP没被屏蔽的情况下进行切换 ❗️❗️❗️
    ❗️❗️❗️ 多机房切换IP 只能在IP没被屏蔽的情况下进行切换 ❗️❗️❗️


        帮瓦工里的 换机房就是换IP!!!  所以提供机房切换的 就提供多个IP切换!
        比如有6个机房可以切换. 不代表只有6个ip可以切换.
        比如原来机房1 的ip是 ip1 
        切换到机房2 后变ip2
        但是再切换回机房1 .这时候你分配到的ip. 可能是ip1 但是也可能是ip3
        这里你机房3 多用些时间再切换回机房1  变成IP3的概率大很多.

    ⦿ 单机房
        ❗️❗️❗️单机房是不能换IP或者机房的❗️❗️❗️
        ❗️❗️❗️单机房是不能换IP或者机房的❗️❗️❗️
        ❗️❗️❗️单机房是不能换IP或者机房的❗️❗️❗️
            除非是新开的机器,如果IP不通 是可以提交工单申请更换.


        单机房的优点. 很多都是流量翻倍啊!! 1T/月 和2T/月的区别 很心动啊.
        官方推出单机房的目的 就是为了 官方的IP 被合理的利用.
        你选择单机房之后 就不能乱搭建vpn了. 被封后你就苦了..


    ⦿ 总结
        选择单机房.  
        万一IP被封了.其实单机房和多机房是一样的 都不能换IP.
        万一IP没被封, 单机房的流量是双倍的! 价格也便宜很多.

        如果你确实需要多IP，那么付费周期选择月付方式，能尽量的减少我们的损失!!


    ⦿ 如何避免IP被封

        如果你购买搬瓦工产品不是为了建站，而是为了搭建某些所谓的上网工具，那么IP地址被封都是很正常的，或许你会说我选择搬瓦工就是为了搭建上网工具，如果这样是不是就不能用了。
        用是可以用，但是不可以公开使用，你一个人单独使用是很少出现IP被封的情况，大多数IP被封都是在网上公开使用而导致的。
        假如你确实是为了公开使用的，大家可以选择月付的方式进行购买，即便是出了问题对于我们的损失也能最小化，这个月出了问题，下个月我们再购买新的产品继续使用也不影响什么，如果年付的话也就等于这个VPS已经彻底费了。
        搬瓦工的速度和稳定性都是很不错的，我们用来学习和建站也都没问题。
        本站不建议使用搬瓦工来搭建所谓上网工具，这些在我们国家是不允许的，你违反了国家的规定IP被封那是很正常的。



🔸 机房地区选择
--------------------------------------------------------------------------------  

        洛杉矶在国内的速度是最好的!! 其次是凤凰城.
        同样的服务器配置,同样都是单机房.但是凤凰城的价格可能是洛杉矶的一半.
            vps 2t /1g  19刀  凤凰城 单机房  https://bwh1.net/cart.php?a=confproduct&i=3
            vps 2t /1g  40刀  洛杉矶 单机房

        ⦿ 所有最新套餐 http://www.banwagong.me/10.html

        ⦿ PS
            购买付款先退出代理!!!!!
            因为这个是可以退款的. 你用代理可能认为你是欺诈.. 反正别挂代理买就行了

            找个优惠码去 很多的. 能便宜 6% 




⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️------⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛⬛️⬛️
🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵 Linux 系统 🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵
⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️------⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️

🔸 CentOS 6 VS CentOS7
================================================================================

    最新版本是7. 但是一般服务器.以及各种教程都是6.
    新手避免不了学各种教程还是建议6.  

        常见区别区别: 比如某些服务的启动和停止 
            [CentOS6]
            $ service service_name start
            $ service service_name stop
            $ service sshd restart/status/reload

            [CentOS7]
            $ systemctl start service_name
            $ systemctl stop service_name
            $ systemctl restart/status/reload sshd

🔸 系统版本
    CentOS X86               这个就是 32位系统 (❗️我的选择❗️)
    CentOS X86-devel         开发版本,软件新但是不太稳定.
    CentOS X86-minimal       精简版本,很多功能需要手动下载安装.
    CentOS X86_64            这个就是 64位系统
    CentOS X86_64-devel
    CentOS X86_64-minimal


🔸 MySQL 版本选择: 5.5
    ❗️❗️ Mysql 这种尽量避免升级. 版本安装一次性到位. 升级有很多很多坑的.❗️❗️
    ❗️❗️ Mysql 这种尽量避免升级. 版本安装一次性到位. 升级有很多很多坑的.❗️❗️
                1G 一下内存的只能选择 MySQL 5.5  不要做死上5.6


🔸 php 版本选择: 越新越好... 






⦿ VPS 简介
    • 更新时间:   2017-06-21-12
    • 本地电脑:   MacOS 10.12
    • VPS服务器1: 23.105.192.96   .5G内存、500 G流量、100￥/年、多机房
    • VPS服务器2: 104.224.139.45  1G内存、 2000G流量、120￥/年、单机房
    • VPS类型:    openVZ, 不是KVM! 两种类型有区别的!很多命令不通用的.
    • 适用系统:   Centos6 x86 和 Centos7 x86_64
    • 服务器IP:   104.224.139.45

    ❗️ 精力有限. 默认所有本地操作都是在Mac上进行的.
    ❗️ 精力有限. 默认所有本地操作都是在Mac上进行的.

    ❗️ 服务器 Centos6 x86 和 Centos7 x64 的命令都会有介绍.
    ❗️ 服务器 Centos6 x86 和 Centos7 x64 的命令都会有介绍.



⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️------⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️
基础设置
⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️------⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️


🔸 初始设置 Mac
    ⦿ 更新本地 known_hosts ( Mac 如果连不上!)
        vi /Users/v/.ssh/known_hosts  >删除带你要ssh服务器IP的行 如: > [104.224.139.45]

    • Mac sed 删除 所有包含104.224.139.45的行 ??? ❓
        sed -i 's/104.224.139.45//g' /Users/v/.ssh/known_hosts   ?




🔸 SSH 端口修改
================================================================================

    ⦿ 登录VPS:    
        ssh -p 27401 root@23.105.192.96
        27401 改成你自己的ssh初始端口,23.105.192.96 改成你服务器的外网IP

    ⦿ 改ssh(root)密码:  🔅 passwd     输入两次密码 就改掉了.

    ⦿ 改ssh端口成2222
        • vi /etc/ssh/ssh_config   取消Port 22 前的注释，并将22改成2222
        • 这个文件好像没必要改的.
            🔅 sed -i 's/^#...Port.22/Port 2222/g' /etc/ssh/ssh_config
 
 
        • vi /etc/ssh/sshd_config  取消Port 22 前的注释，并将22改成2222
            🔅 sed -i 's/^Port.22/Port 2222/g' /etc/ssh/sshd_config

    ⦿ 重启sshd  
        🔅 systemctl restart sshd.service   CentOS7 的重启方法.
        🔅 service sshd restart             CentOS6 的重启方法

    ⦿ 重新登录
        ssh -p 2222 root@198.74.49.76


🔸 系统用户设置
================================================================================

    ⦿ 简介
        默认的管理员 用户名是root. 密码虽然可以自己设置.但是用户名永远是root.
        别人只要猜对你密码就可以登录你ssh了. 我们必须添加额外一个管理员账户. 用户名和密码都自己设置. 这样安全性能大大提高.

        让新建的用户有和 root 一样的权限.只需要把v加入到和root相同的组里去就可以了.


    ⦿ 常用命令
        • 用户信息: id root    ➜ uid=0(root) gid=0(root) groups=0(root)
        • 添加用户: 🔅 useradd v  ➜ id v ➜ uid=1002(v) gid=1002(v) groups=1002(v)
        • 修改密码: 🔅 passwd v
        • 改用户组: 🔅 usermod -g root v  ➜ 把v加到root组里; usermod -g 用户组名 用户名

    ⦿ 相关文件
        /etc/passwd 注：用户（user）的配置文件；
        /etc/shadow 注：用户（user）影子口令文件；

        /etc/group 注：用户组（group）配置文件；
        /etc/gshadow 注：用户组（group）的影子文件；




🔸 SSH 密钥登录
================================================================================

    ❗️❗️❗️  Mac 本地的公钥是放在服务器用户目录下的. 也就是说一个用户就要进行一次密钥上传操作.
    ❗️❗️❗️  比如你要在mac上 同时用密钥登录 root账户和 v账户. 那么就需要执行两次操作!

    ⦿ 流程:
        1. 本地生成一对密钥(公钥+私钥).
        2. 服务器用户目录建立 .ssh 文件夹, 并给700权限
        3. 把本地的公钥用scp命令传到服务器
        4. 服务器上把公钥加到公钥验证列表.


    ⦿ 密钥配置
        🔅VPS: cd && mkdir .ssh && chmod 700 .ssh
        🔅Mac: cd /Users/v/.ssh/ && ls && scp -P 2222 -r id_rsa.pub root@104.224.139.45:~/.ssh/
        🔅VPS: cat ~/.ssh/id_rsa.pub >> ~/.ssh/authorized_keys && systemctl restart sshd.service

    ⦿ 测试     ssh -p 2222 root@104.224.139.45
    

    ⦿ Misc
            Mac OS 密钥默认生成路径: /Users/v/.ssh/
            里面如果有个 id_rsa.pub 就说明生成成功了.


        • 客户端: 上传公钥文件(id_rsa.pub):
             cd /Users/v/.ssh/
             scp -P 2222 -r id_rsa.pub root@23.105.192.96:~/.ssh/
                    P             必须大写.
                    2222         服务器的SSh端口     
                    root          服务器的ssh用户名
                    23.105.192.96 服务器IP
                
        • 注册公钥文件: 把你的公钥添加到公钥验证列表.
             cat ~/.ssh/id_rsa.pub >> ~/.ssh/authorized_keys
            作用就是把id_rsa.pub文件里的内容 全部追加到authorized_keys这个文件 后面.
            如果没有 authorized_keys这个文件会自动帮你建立的.
            用这种方法 一台服务器可以有很多人都ssh 免密码登录.
            因为authorized_keys这个身份验证文件中可以添加很多人的公钥(id_rsa.pub)

            也可以直接重命名上传的文件.   mv id_rsa.pub authorized_keys
            这种方法 整个验证列表中 只有你的公钥.这个服务器只有你能ssh 免密码登录.



🔸 禁止 root 登录ssh (可选)
    • vi /etc/ssh/sshd_config
        PermitRootLogin yes  ➜ 改为➜ PermitRootLogin no
    • 重启sshd服务: service sshd restart


🔸 禁止密码登录(只能用 密钥登录)
    • vim /etc/ssh/sshd_config
        PasswordAuthentication no ➜ 去掉注释,并改为no
    • 重启ssh服务  service sshd restart



🔸 锁定重要文件

    ⦿ 禁止修改密码
        chattr +i /etc/passwd 
        chattr +i /etc/shadow
        假如你锁定了 /etc/shadow 这个文件是修改用户密码的. 
        一旦锁定 你就无法用passwd 来修改密码

    ⦿ 禁止修改用户组
        chattr +i /etc/group
        chattr +i /etc/gshadow




🔸 防火墙配置 ???

    # 避免放大攻击
    net.ipv4.icmp_echo_ignore_broadcasts = 1

    # 开启恶意icmp错误消息保护
    net.ipv4.icmp_ignore_bogus_error_responses = 1

    # 开启SYN洪水攻击保护
    net.ipv4.tcp_syncookies = 1

    # 开启并记录欺骗，源路由和重定向包
    net.ipv4.conf.all.log_martians = 1
    net.ipv4.conf.default.log_martians = 1

    # 处理无源路由的包
    net.ipv4.conf.all.accept_source_route = 0
    net.ipv4.conf.default.accept_source_route = 0

    # 开启反向路径过滤
    net.ipv4.conf.all.rp_filter = 1
    net.ipv4.conf.default.rp_filter = 1

    # 确保无人能修改路由表
    net.ipv4.conf.all.accept_redirects = 0
    net.ipv4.conf.default.accept_redirects = 0
    net.ipv4.conf.all.secure_redirects = 0
    net.ipv4.conf.default.secure_redirects = 0

    # 不充当路由器
    net.ipv4.ip_forward = 0
    net.ipv4.conf.all.send_redirects = 0
    net.ipv4.conf.default.send_redirects = 0

    # 开启execshild
    kernel.exec-shield = 1
    kernel.randomize_va_space = 1

    # IPv6设置
    net.ipv6.conf.default.router_solicitations = 0
    net.ipv6.conf.default.accept_ra_rtr_pref = 0
    net.ipv6.conf.default.accept_ra_pinfo = 0
    net.ipv6.conf.default.accept_ra_defrtr = 0
    net.ipv6.conf.default.autoconf = 0
    net.ipv6.conf.default.dad_transmits = 0
    net.ipv6.conf.default.max_addresses = 1



    # 增加系统IP端口限制
    net.ipv4.ip_local_port_range = 2000 65000





🔸 Fail2Ban

    ⦿ 简介
        监控系统日志. 执行相应的屏蔽动作. 用e-mail 通知管理员.
        如:当有人在试探你的SSH、SMTP、FTP密码，只要达到你预设的次数，fail2ban就会调用防火墙屏蔽这个IP，而且可以发送e-mail通知系统管理员，是一款很实用、很强大的软件！



    ⦿ 安装1
        wget https://github.com/fail2ban/fail2ban/archive/0.9.7.tar.gz
        tar xvfj fail2ban-0.10.0.tar.bz2
        cd fail2ban-0.10.0
        python setup.py install

    ⦿ 安装2
        yum install epel-release
        yum install fail2ban -y

    ⦿ 要求     python 2.6+


    ⦿ 使用:

        启用(非启动) systemctl enable fail2ban
        查询状态：  fail2ban-client status
        重启fail2ban： systemctl restart fail2ban


    ⦿ 配置:

        Fail2ban服务的配置文件在/etc/fail2ban目录。
        在其中可以找到jail.conf配置文件，我不会直接编辑这个文件，因为在升级软件包时，会覆盖这个文件，使配置失效。我们应该创建一个新文件jail.local，在jail.local定义的值会覆盖jail.conf中的值。


        vim /etc/fail2ban/jail.local

        [DEFAULT]
        # 禁止一个IP一小时
        bantime = 3600
        
        # 覆写 /etc/fail2ban/jail.d/00-firewalld.conf:
        banaction = iptables-multiport
        
        [sshd]
        enabled = true

        上面覆写了三个配置，bantime，使用iptables，开启sshd。
        配置完成之后，重启fail2ban： 



    ⦿ 其他命令
        最近一次启动，fail2ban日志：

        # journalctl -b -u fail2ban
        实时跟踪显示fail2ban日志：

        # tail -F /var/log/fail2ban.log
        显示防火墙规则：

        # iptables -L
        显示防火墙规则对应的命令：


🔸 ssh 日志

    cat /var/log/auth.log
    more /var/log/secure
    who /var/log/wtmp


🔸 禁用ipv6

    #编辑/etc/sysconfig/network添加行：
    NETWORKING_IPV6=no
    #修改/etc/hosts,把ipv6本地主机名解析的注释掉（可选）：

    #::1 localhost localhost6 localhost6.localdomain6

    #禁止系统加载ipv6相关模块，创建modprobe关于禁用ipv6的设定文件/etc/modprobe.d/disable_ipv6.conf(名字随便起)（RHEL6.0之后没有/etc/modprobe.conf这个文件），内容如下，三选其一（本次使用的第一种）：
    alias net-pf-10 off
    options ipv6 disable=1
    #禁止开机启动
    chkconfig ip6tables off
    #查看ipv6是否被禁用
    lsmod | grep -i ipv6
    ifconfig | grep -i inet6




🔸 阻止百度收录真实位置 恩，免得上门查水表
    安装了很多流氓软件, 会后台传数据.
    修改 域名解析 让域名失效就可以阻止这了


    vim /etc/hosts

    0.0.0.0 api.map.baidu.com
    0.0.0.0 ps.map.baidu.com
    0.0.0.0 sv.map.baidu.com
    0.0.0.0 offnavi.map.baidu.com
    0.0.0.0 newvector.map.baidu.com
    0.0.0.0 ulog.imap.baidu.com
    0.0.0.0 newloc.map.n.shifen.com

    :: api.map.baidu.com
    :: ps.map.baidu.com
    :: sv.map.baidu.com
    :: offnavi.map.baidu.com
    :: newvector.map.baidu.com
    :: ulog.imap.baidu.com
    :: newloc.map.n.shifen.com









🔸 必备

    ⦿ 系统更新            yum update -y
    ⦿ Tree 目录工具       yum install tree -y
    ⦿ GCC 编译必备.必装.  yum group install "Development Tools" -y

    🔅🔅 
    yum update -y && yum install tree -y && yum group install "Development Tools" -y


🔸 SELinux (可选)
    /usr/sbin/sestatus -v      
    enabled即为开启状态, 确保这里是Disabled 


🔸 VI 配置 (防止打开文件乱码)
================================================================================

    ⦿ 中文乱码
       vi ~/.vimrc 添加3行

        echo "set fileencodings=utf-8,gb2312,gb18030,gbk" >> ~/.vimrc
        echo "set enc=utf8" >> ~/.vimrc
        echo "set fencs=utf8,gbk,gb2312,gb18030" >> ~/.vimrc

    ⦿ 显示行号 (不建议启用)
        复制内容的时候 会连行号一起复制. 非常不方便.
         echo ":set nu" >> ~/.vimrc && cat ~/.vimrc

    ⦿ 设置缩进
        echo "set ts=4" >> ~/.vimrc && cat ~/.vimrc
        echo "set expandtab" >> ~/.vimrc && cat ~/.vimrc

        
        echo "set autoindent" >> ~/.vimrc && cat ~/.vimrc
        ❗️❗️ 千万不要加这行 自动缩进. 特别是 .py 文件会导致导致文件结构混乱❗️❗️
        ❗️❗️ 千万不要加这行 自动缩进. 特别是 .py 文件会导致导致文件结构混乱❗️❗️



    🔅🔅
    echo "set fileencodings=utf-8,gb2312,gb18030,gbk,ucs-bom,cp936,latin1" >> ~/.vimrc && echo "set enc=utf8" >> ~/.vimrc && echo "set fencs=utf8,gbk,gb2312,gb18030" >> ~/.vimrc && echo ":set nu" >> ~/.vimrc && cat ~/.vimrc





🔸 ZSH 配置
================================================================================


    ⦿ ZSH 简介
        默认的shell 太难看. 黑白的,废话不多说. 直接用全世界公认的最好的shell: ZSH.
        ZSH 配置有点麻烦. 这也不是事情.有人早把你配好了.这人就是 oh-my-zsh


    ⦿ ZSH 安装

    🔅 sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"

        - 查看当前已装 shell   🔅 cat /etc/shells
        - 设置zsh为默认shell   🔅 chsh -s /bin/zsh



         yum install zsh -y && yum install git -y

         sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"

        🔅🔅 
        yum install zsh -y && yum install git -y && sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"



    ⦿ ZSH 禁止更新.
        每当登录ssh 是不是就要你更新 zsh 烦死了..
        大概就是 100 年更新一次
        vi .zshrc 
        添加
        export UPDATE_ZSH_DAYS=36500



🔸 Autojump (zsh 插件)
    
    ⦿ 简介
        autojump插件使你能够快速切换路径，
        再也不需要逐个敲入目录，只需敲入目标目录，就可以迅速切换目录。

        📌 最终效果:
            ➜  crypto git:(manyuser) ✗ pwd
            /root/shadowsocksr/shadowsocks/crypto
            ➜  crypto git:(manyuser) ✗ cd /
            ➜  / j cry
            /root/shadowsocksr/shadowsocks/crypto
            ➜  crypto git:(manyuser) ✗

            4个命令.  
            第一个: 输出当前目录.
            第二个: 跳转到根目录.
            第三个: 使用 j 快速跳转.
            第四个: 看到没. 只输入了 j cry 就跳转过去了.
            你手速慢,估计得输入半天吧.... 
            安装好autojump 就可以使用j 命令了.

    ⦿ 安装

         git clone https://github.com/joelthelion/autojump.git && cd autojump && ./install.py
         
                ❗️❗️❗️ 注意安装完最后的提示!!! ❗️❗️❗️
                Please manually add the following line(s) to ~/.zshrc:
                        [[ -s /root/.autojump/etc/profile.d/autojump.sh ]] && source /root/.a
                utojump/etc/profile.d/autojump.sh
                        autoload -U compinit && compinit -u
                Please restart terminal(s) before running autojump.

                就是让你手动把下面两行 加到  ~/.zshrc 中行尾.

            vi ~/.zshrc
                [[ -s /root/.autojump/etc/profile.d/autojump.sh ]] && source /root/.autojump/etc/profile.d/autojump.sh
                autoload -U compinit && compinit -u

                注意是两行!!!! 有时候终端不够宽.会自动把你分成多行, 给你添加几个空格.就会出错!!!
                让后重启shell.如果是远程vps的话.直接断开ssh 重连就可以.

                然后就可以用 j 命令了. 只要你cd 过某个文件夹. 这个插件就会记住这个路径.


            🔅🔅
                git clone https://github.com/joelthelion/autojump.git && cd autojump && ./install.py && echo "[[ -s /root/.autojump/etc/profile.d/autojump.sh ]] && source /root/.autojump/etc/profile.d/autojump.sh
                                    autoload -U compinit && compinit -u" >> ~/.zshrc && cd .. && rm -R autojump




🔸 Shell 提示符
================================================================================

    提示符就是一个变量 输入: echo “$PS1”  就能显示当前提示符.
    🔅 vi ~/.zshrc 添加
    PS1="%F{red}✘✘%F{black}∙%f%B%F{magenta}𝒗2%f%b %{$fg[cyan]%}%c%{$reset_color%} %{$reset_color%}${ret_status}"

    这里的xx、v 可以自定义最后重连ssh 就生效了. 原来的 ~ 就变成 ✘✘∙𝒗2 ~ 了
    注意 这里用echo 可能会失败. 还是手动输入吧.




🔸 ssh 自定义欢迎界面 
     _        _    ___ ______   _  ___   ___  ____   ____
    | |      / \  / _ \__  / | | |/ _ \ / _ \|  _ \ / ___|
    | |     / _ \| | | |/ /| | | | | | | | | | |_) | |  _
    | |___ / ___ \ |_| / /_| |_| | |_| | |_| |  _ <| |_| |
    |_____/_/   \_\___/____|\___/ \___(_)___/|_| \_\\____|

    类似这种 都是用  figlet 工具生成的.
    在任何电脑安装这个 figlet 工具, 然后自定义内容, 复制文字内容到服务器就可以.


    ⦿ figlet 安装.

        cd /usr/local/src/ && wget ftp://ftp.figlet.org/pub/figlet/program/unix/figlet-2.2.5.tar.gz && 
        tar -zxvf figlet-2.2.5.tar.gz && cd figlet-2.2.5 && make figlet


    ⦿ figlet 使用

        cd /usr/local/src/figlet-2.2.5
        语法: ./figlet 生成内容 -f 指定字体
        字体: 在 fonts 文件夹下 以.flf 结尾的都是.

        ⦿ ./figlet Xu.jian -f fonts/standard.flf
        __  __        _ _
        \ \/ /   _   (_|_) __ _ _ __
        \  / | | |  | | |/ _` | '_ \
        /  \ |_| |_ | | | (_| | | | |
        /_/\_\__,_(_)/ |_|\__,_|_| |_|
                |__/


        ⦿ ./figlet Xu.jian -f fonts/bubble.flf
        _   _   _   _   _   _   _
        / \ / \ / \ / \ / \ / \ / \
        ( X | u | . | j | i | a | n )
        \_/ \_/ \_/ \_/ \_/ \_/ \_/


        ⦿ ./figlet Xu.jian -f fonts/digital.flf
        +-+-+-+-+-+-+-+
        |X|u|.|j|i|a|n|
        +-+-+-+-+-+-+-+


    ⦿ SSH 登录界面修改.

        vi /etc/motd           motd即messageoftoday（布告栏信息）
        添加要显示的文字然后重连ssh
        就可以了.






🔸 SSH 保持连接
================================================================================

    ⦿ 原因 防火墙 + ssh服务端设置
        • 服务器的ssh服务 为了安全在客户端一段时间没响应后也会断开客户端.
        • 服务器/路由器/客户端的防火墙，会关闭超时空闲连接.

    ⦿ 解决办法
        根本原因就在客户端长时间没响应, 
        只要服务器定时给客户端发个数据,客户端会自动响应,
        这样就相对于双方在定时通信了,也就可以保持长时间登录ssh了
        想要服务器定时给客户端发数据需要配置服务器的 ssh 配置文件.
    
    ⦿ sshd_config
        服务器 sshd 配置文件路径 vi /etc/ssh/sshd_config

        三个重要参数解释:

        • TCPKeepAlive        是否要去判断客户端是否活动的.默认yes
        • ClientAliveInterval 表示每隔多少秒，服务器端向客户端发送心跳.
        • ClientAliveCountMax 表示上述多少次心跳无响应之后，会认为Client已经断开。


        添加下面三行 到 /etc/ssh/sshd_config , 然后重启ssh 就可以了

        TCPKeepAlive no
        ClientAliveInterval 60
        ClientAliveCountMax 6000

            🔅 echo "TCPKeepAlive yes" >> /etc/ssh/sshd_config
            🔅 echo "ClientAliveInterval 60" >> /etc/ssh/sshd_config
            🔅 echo "ClientAliveCountMax 360" >> /etc/ssh/sshd_config
            🔅 cat /etc/ssh/sshd_config
            🔅 /etc/init.d/sshd restart


    ⦿ PS
        如果你对服务器没有控制权限. 那么就只能让客户端定时给服务器发数据了
        在Mac的 sudo vi /etc/ssh/ssh_config 下添加行 
        ServerAliveInterval 30  就会 每隔30秒自动给服务器发数据 
        ServerAliveCountMax 6000

        sudo echo "ServerAliveInterval 30" >> /etc/ssh/ssh_config
        用这个命令你会报错, 没权限! 
        这是因为 sudo 默认只适用于第一个命令 echo "ServerAliveInterval 30"
        后面的 >> 是另外一个命令了. 这命令没有sudo权限. 所以报错了.
        我们想要的是sudo 后面所有命令都是 sudo权限执行的. 需要添加参数: sh -c
        它可以让 bash 将一个字串作为完整的命令来执行，这样就可以将 sudo 的影响范围扩展到整条命令。

        Mac:  🔅 sudo sh -c "echo ServerAliveInterval 30 >> /etc/ssh/ssh_config"

        还有种办法就是在ssh 命令的时候 添加参数.. 不实用..知道就好
        ssh -o ServerAliveInterval=30 -p 2222 root@104.224.139.45



🔸 终端别名配置
================================================================================

    永久设置: ~/.bashrc  或者 ~/.zshrc 里面

    ⦿ vim  ➜  echo 'alias vi="vim"' >> ~/.zshrc
    ⦿ ls   ➜  echo 'alias ls="ls -l"' >> ~/.zshrc
    ⦿ rm   ➜  echo 'alias rm="rm -R"' >> ~/.zshrc

    🔅🔅
    echo 'alias vi="vim"' >> ~/.zshrc && echo 'alias ls="ls -l"' >> ~/.zshrc && echo 'alias rm="rm -R"' >> ~/.zshrc && source ~/.zshrc



🔵 NetSpeed 网络加速 (可选)
================================================================================

    ❗️❗️❗️ 安装开启后，VPN不能使用!!! ❗️❗️❗️
    官方中文教程 https://github.com/snooda/net-speeder

    🔸 Centos6 x86 ✔︎
        ⦿ 下载
           wget https://coding.net/u/njzhenghao/p/download/git/raw/master/net_speeder-installer.sh

        ⦿ 编译并安装
            bash net_speeder-installer.sh

        ⦿ 开启端口加速
            nohup /usr/local/net_speeder/net_speeder venet0 "ip" >/dev/null 2>&1 &
        
        ⦿ 查看是否成功开启 
            ping 服务器. 会返回两个一模一样的数据包. (DUP). 说明成功了.

        ⦿ 设置开机启动
            echo 'nohup /usr/local/net_speeder/net_speeder venet0 "ip" >/dev/null 2>&1 &' >> /etc/rc.local


    🔸 Centos7 x64 ✔︎

        ⦿ 下载并安装第三方 epel 源
            wget http://dl.fedoraproject.org/pub/epel/7/x86_64/e/epel-release-7-9.noarch.rpm && rpm -ivh epel-release-7-9.noarch.rpm

        ⦿ 安装依赖：
            yum install libnet libpcap libnet-devel libpcap-devel -y

        ⦿ 软件下载 & 解压 & cd:
            cd /usr/local/ && wget https://github.com/snooda/net-speeder/archive/master.zip && unzip master.zip && cd net-speeder-master/

        ⦿ 软件编译
            sh build.sh -DCOOKED

        ⦿ 使用方法 (这个软件文件夹不能删除.)

            • 语法：./net_speeder 网卡名 加速规则（bpf规则）
            • ./net_speeder venet0 "ip"    加速venet0 网卡上的所有IP
            我们日常使用是要开机启动并后台运行的. 上面的命令是前台运行的.
            nohup /usr/local/net-speeder-master/net_speeder venet0 "ip"

        ⦿ 开机启动
            只要把运行软件的命令 写进 /etc/rc.d/rc.local 文件中 就可以实现开机启动
            /etc/rc.local  就是 /etc/rc.d/rc.local; 前面是个快捷方式. 后面才是真正路径.
            ❗️❗️❗️ Centos7  的开机启动文件: 默认是没有执行权限的! 必须手动给执行权限 
            ❗️❗️❗️ Centos7  的开机启动文件: 默认是没有执行权限的! 必须手动给执行权限
            ❗️❗️❗️ Centos7  的开机启动文件: 默认是没有执行权限的! 必须手动给执行权限

            ❗️❗️❗️ 必须延迟几秒不然可能会不成功!!1   sleep 10 
            ❗️❗️❗️ 必须延迟几秒不然可能会不成功!!1   sleep 10 

            chmod 755 /etc/rc.d/rc.local

            echo 'sleep 10' >> /etc/rc.local
            
            echo 'nohup /usr/local/net-speeder-master/net_speeder venet0 "ip" >/dev/null 2>&1 &' >> /etc/rc.local

        ⦿ 测试
            重启服务器. 然后本地ping 服务器 看到有(DUP!) 就说明正常运行了
            64 bytes from 104.224.139.45: icmp_seq=10 ttl=46 time=190.322 ms
            64 bytes from 104.224.139.45: icmp_seq=10 ttl=70 time=190.495 ms (DUP!)



        🔅🔅
        wget http://dl.fedoraproject.org/pub/epel/7/x86_64/e/epel-release-7-9.noarch.rpm && rpm -ivh epel-release-7-9.noarch.rpm && yum install libnet libpcap libnet-devel libpcap-devel -y && cd /usr/local/ && wget https://github.com/snooda/net-speeder/archive/master.zip && unzip master.zip && cd net-speeder-master/ && sh build.sh -DCOOKED 
        🔅🔅
        chmod 755 /etc/rc.d/rc.local && echo 'sleep 10' >> /etc/rc.local && echo 'nohup /usr/local/net-speeder-master/net_speeder venet0 "ip" >/dev/null 2>&1 &' >> /etc/rc.local && reboot





⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️------⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️
⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️------⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️

🔵 LNMP 环境
================================================================================

    Mysql 三个最常见版本: 5.1、5.5、5.7
        5.1 运行内存 20M -
        5.5 运行内存 300M +
        5.7 占用内存 1000M + 

    一般的vps 也就512/1G内存, 就算你装好 Mysql5.7 其他什么都不干 也卡死的.
  ❗️❗️❗️ 内存小于等于 1G 的服务器 mysql 只能选择 5.5、5.1 ; 我们选 5.5 ❗️❗️❗️
  ❗️❗️❗️ 内存小于等于 1G 的服务器 mysql 只能选择 5.5、5.1 ; 我们选 5.5 ❗️❗️❗️

  ❗❗️❗️ php 尽量选择最新版本 7+, 必须 选择 5.6+ 版本 ❗️❗️❗️
  ❗❗️❗️ php 尽量选择最新版本 7+, 必须 选择 5.6+ 版本 ❗️❗️❗️
        最新版本 7.1  尽量用最新版.不像mysql有内存要求.
    ⦿ phpinfo()  ➜  http://104.224.139.45/phpinfo.php  这里显示各种信息



    直接运行下面命令就会自动安装LNMP环境了.
    🔅 wget -c http://soft.vpser.net/lnmp/lnmp1.4.tar.gz && tar zxf lnmp1.4.tar.gz && cd lnmp1.4 && ./install.sh lnmp

    1. mysql 版本   选 5.5
    2. 输入数据库密码  
    3. 启用InnoDB  选 y
    4. php   版本  选 7.1.5
    5. menory      不安装
    6. 按回车键 & 等好久 ETC 20分钟
    7. 安装好后 nginx 80端口开了.  mysql 3306端口也开了.



    ⦿ 检验是否成功安装:

        • 正常可以直接用 🔅 http://23.105.192.96/  登录服务器初始网站了. 这里IP地址改成你自己的就可以. 
            这个网站是用nginx搭建的. 
            网站内容是这个lnmp脚本自动生成的.
            网站的默认根目录是 /home/wwwroot/default/index.php

        • 正常可以直接用 🔅 http://23.105.192.96/phpmyadmin/  登录数据库了. 这里IP地址改成你自己的就可以.
            📌 默认数据库是只能用网页登录的. 你要用别的工具 需要手动开启数据库的远程功能.


        • 最好我们在本地机器 用nmap 来测试服务器到底开放了哪些端口.
            ✘✘∙𝒗 Desktop nmap 23.105.192.96

            Starting Nmap 7.25BETA1 ( https://nmap.org ) at 2017-03-31 09:51 CST
            Nmap scan report for 23.105.192.96.16clouds.com (23.105.192.96)
            Host is up (0.17s latency).
            Not shown: 992 closed ports
            PORT     STATE    SERVICE
            53/tcp   open     domain
            80/tcp   open     http
            111/tcp  filtered rpcbind
            443/tcp  open     https
            1723/tcp filtered pptp
            2190/tcp open     tivoconnect
            3306/tcp open     mysql
            6666/tcp open     irc

            Nmap done: 1 IP address (1 host up) scanned in 19.65 seconds

            发现有个 3306 的数据库端口.说明数据库正常启动了.




    ⦿ LNMP状态管理命令：

        LNMP 1.2+状态管理:     lnmp {start|stop|reload|restart|kill|status}
        LNMP 1.2+各个程序状态: lnmp {nginx|mysql|mariadb|php-fpm|pureftpd} {start|stop|reload|restart|kill|status}
        Nginx状态管理：        /etc/init.d/nginx {start|stop|reload|restart}
        MySQL状态管理：        /etc/init.d/mysql {start|stop|restart|reload|force-reload|status}
        Memcached状态管理：    /etc/init.d/memcached {start|stop|restart}
        PHP-FPM状态管理：      /etc/init.d/php-fpm {start|stop|quit|restart|reload|logrotate}
        PureFTPd状态管理：     /etc/init.d/pureftpd {start|stop|restart|kill|status}
        ProFTPd状态管理：      /etc/init.d/proftpd {start|stop|restart|reload}
        Redis状态管理：        /etc/init.d/redis {start|stop|restart|kill}
            如重启LNMP，1.2+输入命令：lnmp restart 即可；
            单独重启mysql：/etc/init.d/mysql restart 也可以 lnmp mysql restart ，两个是一样的。




    ⦿ 各种版本升级方法 https://lnmp.org/faq/lnmp1-2-upgrade.html
        ❗️❗️❗️以下操作均需要在lnmp压缩包解压后的目录里运行

        • PHP 升级:
             ./upgrade.sh php          回车
             输入一个 版本号 如 7.1.3  回车，再次回车确认即可开始升级。
            到http://www.php.net/downloads.php 获取版本号， 
            这个升级非常慢!!! 操 几乎就是安装整个LNMP环境的时间了....


        • Mysql 升级 5.6
            cd 到lnmp的解压包
            (升级前 不能关闭数据库.)
            ./upgrade.sh mysql 
            输入root密码
            输入版本号 5.7.18



    ❗️❗️❗️❗️❗️ 最后, 搭建好基础的环境后. 务必务必 去控制面板 做系统快照. ❗️❗️❗️❗️❗️
    https://kiwivm.64clouds.com/main.php
    → Snapshots → 快照就是系统备份.   备份和恢复只要几秒钟!!!!! 
    再也不用担心服务器被你折腾坏了. 













⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️------⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️
⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️------⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️


🔵 Mysql 远程访问
================================================================================

        主从服务器都开启外网访问. 好让Mac 用navicast 连接数据库.方便操作
    
    LNMP 一键安装包 环境安装好之后. 
    你就可以用网页 http://104.224.139.45/phpmyadmin/   来登录mysql 数据库了
    网页操作 比命令简单点... 
    注意 mysql 版本 和 phpmyadmin 版本是对应的. 
    如果你LNMP 安装的时候 php选择7+版本 mysql选择5.1,网页登录数据库就会报错
    是因为 phpmyadmin版本 相对于 Mysql5.1 太新,
    For mySQL 5.5, use phpMyAdmin 4.4.x and above
    For mySQL 5.1, use phpMyAdmin 4.0.x

    我们直接用 mysql 命令行来操作.

    • mysql -u root -p
    • mysql> use mysql;                      切换到mysql数据库.
    • mysql> select user,host from user;     查询user表中的 user 和 host字段
        +------+-----------+
        | user | host      |
        +------+-----------+
        | root | 127.0.0.1 |
        | root | ::1       |
        | root | localhost |
        +------+-----------+


    可以看出: root 只能在ipv4的 127.0.0.1 下,ipv6的 ::1 下, 还有 localhost 下连接数据库,
    下面我们另外添加一个新的 root 用户, 密码为空, 允许所有IP连接服务器的数据库

    • mysql> GRANT ALL PRIVILEGES ON *.* TO 'root'@'%' IDENTIFIED BY '' WITH GRANT OPTION;

    • mysql> select user,host from user;
        +------+-----------+
        | user | host      |
        +------+-----------+
        | root | %         |
        | root | 127.0.0.1 |
        | root | ::1       |
        | root | localhost |
        +------+-----------+
    
    • mysql> select user,host,password from user;
        +------+-----------+-------------------------------------------+
        | user | host      | password                                  |
        +------+-----------+-------------------------------------------+
        | root | localhost | *B447E0684B5719E1C4C9D1B65BF00F7373747CE1 |
        | root | 127.0.0.1 | *B447E0684B5719E1C4C9D1B65BF00F7373747CE1 |
        | root | ::1       | *B447E0684B5719E1C4C9D1B65BF00F7373747CE1 |
        | root | %         |                                           |
        +------+-----------+-------------------------------------------+


    • mysql> UPDATE mysql.user SET password=PASSWORD('你的密码') WHERE host='%';
        +------+-----------+-------------------------------------------+
        | user | host      | password                                  |
        +------+-----------+-------------------------------------------+
        | root | localhost | *B447E0684B5719E1C4C9D1B65BF00F7373747CE1 |
        | root | 127.0.0.1 | *B447E0684B5719E1C4C9D1B65BF00F7373747CE1 |
        | root | ::1       | *B447E0684B5719E1C4C9D1B65BF00F7373747CE1 |
        | root | %         | *B447E0684B5719E1C4C9D1B65BF00F7373747CE1 |
        +------+-----------+-------------------------------------------+

    • mysql> flush privileges;
        更新数据库数据.

    ⦿ PS
    上面是详细教程. 其实我们可以直接把 root | ::1 更新成 root %. 
    用下面一个命令就可以了. 
    当然 -pxujian0219 要改成 -p+你自己的mysql登录密码.其他不用改.
    如果你的密码是 1234 就改成 -p1234

    🔅🔅
    mysql -u root -pxujian0219 -e "UPDATE mysql.user SET host='%' WHERE host='::1';" && mysql -u root -pxujian0219 -e "flush privileges;"

    ⦿ Navicast 测试连接, 如果还不行就停掉服务器的防火墙









🔵  双网卡使用(wifi + 手机热点; 可选)
================================================================================

    ⦿ 简介
        Mac电脑已经用wifi了. 但是蹭网的,不稳定.
        所有到服务器IP的数据都走手机.  ➜  设置路由表

    ⦿ Mac 多网卡
        其实你Mac 连多个网卡是会自动帮你配置的.
        比如你同时连公司的内网和公司的外网.是会自动选择网关的
        如果你们公司网络情况复制,那么可能需要手动编辑路由表.
        一般人是不用折腾这个的

    ⦿ 蓝牙热点
        我们让电脑通过蓝牙来连接手机的热点(配对好就连上了)
        然后去网络面板 添加 bluetooth pan  


    ⦿ 网关
        wifi: 192.168.11.222、255.255.255.0、192.168.11.1
        Blue: 172.20.10.8、255.255.255.240、172.20.10.1


    ⦿ 查看使用那个网卡

        traceroute 23.105.192.96  第一个出来  192.168.11.1 说走的是Wi-Fi
        traceroute 23.105.192.96  第一个出来  172.20.10.1  就走的是手机流量.

    ⦿ 查看Mac 路由表  netstat -rl -f inet
        Internet:
        Destination        Gateway            Flags        Refs      Use    Mtu   Netif Expire
        default            192.168.11.1       UGSc           11        0   1500     en0
        default            172.20.10.1        UGScI           2        0   1500     en4


    ⦿ 添加路由表:
        sudo route -n add -net 23.105.192.96/32 172.20.10.1
        sudo route -n add -net 104.224.139.45/32 172.20.10.1

        sudo route -n add -net 23.105.192.96/32 172.20.10.1 && sudo route -n add -net 104.224.139.45/32 172.20.10.1 && netstat -rl -f inet


        再看 Mac的路由表. 会多出一条路由
        23.105.192.96/32   172.20.10.1        UGSc            0        0   1500     en4

    ⦿ 恢复路由

        下面我们关闭蓝牙. 
        由于没有了手机网关那么.. 再ping 23.105.192.96 就变成用wifi的网关了.
        再打来蓝牙 连接iphone..  你会看到路由表信息又变成默认了.
        你想然服务器ip 都手机. 又得重新设置路由...


    ⦿ 路由操作命令

        修改路由表,同时使用有线网卡和无线网卡
        netstat -nr 查看路由表
        sudo route delete 0.0.0.0  删除默认路由
        sudo route add -net 0.0.0.0 192.168.1.1 默认使用192.168.1.1网关
        sudo route add 10.200.0.0 10.200.22.254 有线网卡使用该网关
        sudo route add 10.0.1.0/24 10.200.22.254 其它网段指定网关







🔵 PostgreSQL 9.6.3
================================================================================

    Linux软件有 三种安装方式: RPM包安装、 yum 安装、 源码包安装.
        yum  安装/卸载 最简单
        rpm  安装/卸载 稍麻烦
        源码 安装/卸载 最麻烦
        (源码安装如果指定安装路径卸载就很简单,为了卸载方便必须要指定路径!!!) 

    ⦿ 安装9.6(RPM 方法) ✔︎ 
          其他系统看官网安装教程: https://www.postgresql.org/download/linux/redhat/

        • 源安装 (Centos6 x86)
            yum install https://download.postgresql.org/pub/repos/yum/9.6/redhat/rhel-6-i386/pgdg-centos96-9.6-3.noarch.rpm

        • 源安装 (Centos7 x64)
            yum install https://download.postgresql.org/pub/repos/yum/9.6/redhat/rhel-7-x86_64/pgdg-centos96-9.6-3.noarch.rpm

        • 软件安装:  
            yum update -y && yum install postgresql96-server postgresql96-devel postgresql96 -y

        • bash 环境路径配置  echo "export PATH=/usr/pgsql-9.6/bin:\$PATH" >> /etc/bashrc
        • ZSH  环境路径配置  echo "export PATH=/usr/pgsql-9.6/bin:\$PATH" >> ~/.zshrc
        • 重新加载 zsh       source ~/.zshrc    PS: bash的话,自己重新连ssh来重启吧.我不会.
        • 查看Postgresql 版本: postgres -V

        🔅🔅 Centos7 x64
        yum install https://download.postgresql.org/pub/repos/yum/9.6/redhat/rhel-7-x86_64/pgdg-centos96-9.6-3.noarch.rpm -y && yum update -y && yum install postgresql96-server postgresql96-devel postgresql96 -y && echo "export PATH=/usr/pgsql-9.6/bin:\$PATH" >> /etc/bashrc && echo "export PATH=/usr/pgsql-9.6/bin:\$PATH" >> ~/.zshrc &&  source ~/.zshrc && postgres -V



    ⦿ Postgres 初始设置 
        ❗️❗️❗️安装好之后是不能直接启动的. 会报错. 需要先初始化数据库后再启动❗️❗️❗️
        ❗️❗️❗️安装好之后是不能直接启动的. 会报错. 需要先初始化数据库后再启动❗️❗️❗️
        ❗️❗️❗️安装好之后是不能直接启动的. 会报错. 需要先初始化数据库后再启动❗️❗️❗️

        • 初始化 (Centos6 x86)      service postgresql-9.6 initdb
        • 初始化 (Centos7 x64)      /usr/pgsql-9.6/bin/postgresql96-setup initdb

        • 启动Postgres (Centos6 x86)   /etc/init.d/postgresql-9.6 start
        • 启动Postgres (Centos7 x64)   systemctl start postgresql-9.6

        • 开机启动 (Centos6 x86)    echo "/etc/init.d/postgresql-9.6 start" >> /etc/rc.local
        • 开机启动 (Centos7 x64)    systemctl enable postgresql-9.6

        🔅🔅 centos7 x64 初始化+开机启动
        /usr/pgsql-9.6/bin/postgresql96-setup initdb && systemctl enable postgresql-9.6


        • 切换用户              🔅 su postgres
        • 进入 postgres 命令行  🔅 psql
        • 设置数据库用户 postgres 的密码
            注意 postgres 安装好后 自动建立了两个用户
            一个是 linux系统下的 postgres; 一个是 postgres 数据库下的 postgres 
            虽然名字一样但是密码是分开的, linux 下的postgres 用户的密码不用管.
            我们现在来设置 postgres 数据库下的名为 postgres 用户的密码.
            语法: \password + 用户名 > 回车 > 设置密码 
            🔅 \password postgres 






    ⦿ 卸载9.4 (可选 centos6 x86)

        如果9.4 想升级9.6;不一定要卸载的9.4, 两个版本可以一起存在的!!!
        估计你也卸载不干净. 反正我是卸载不干净. 干脆不卸载.

            查看PostgreSQL状态   /etc/init.d/postgresql-9.4 status
            停止PostgreSQL服务   /etc/init.d/postgresql-9.4 stop
            查看已安装的包       rpm -qa|grep postgres
                postgresql94-libs-9.4.12-1PGDG.rhel6.i686
                postgresql94-9.4.12-1PGDG.rhel6.i686
                postgresql94-devel-9.4.12-1PGDG.rhel6.i686
                postgresql94-server-9.4.12-1PGDG.rhel6.i686

            然后用 rpm -e 命令卸载.
                rpm -e postgresql94-devel-9.4.12-1PGDG.rhel6.i686
                rpm -e postgresql94-server-9.4.12-1PGDG.rhel6.i686
                rpm -e postgresql94-9.4.12-1PGDG.rhel6.i686
                rpm -e postgresql94-libs-9.4.12-1PGDG.rhel6.i686

            卸载可能有问题.可以不管它.
            就是系统存在两版本的的postgresql.只要你启动命令使用对了就行
            一个是9.6 一个是9.4
            /etc/init.d/postgresql-9.4 staat
            /etc/init.d/postgresql-9.6 start



    🔸 Postgres 常用命令
        ❗️❗️ Postgres 相关命令 必须在 Postgres 用户下运行. 不能用root❗️❗️
        ❗️❗️ Postgres 相关命令 必须在 Postgres 用户下运行. 不能用root❗️❗️
    
        • 切换用户     su postgres

        • 启/停/状态Centos6 x86   /etc/init.d/postgresql-9.6 start/stop/status
        • 启/停/状态centos7 x64   systemctl start/stop/status postgresql-9.6
        


    🔸 Postgres 远程访问

        默认外网电脑无法访问本地 postsql，开启远程访问需设置两个地方.
            • postgresql.conf > 允许外网访问5432端口
            • pg_hba.conf     > 允许外网用某种加密方式连接服务器

        ⦿ postgresql.conf 配置
            • 添加行 listen_addresses = '*' 到 /var/lib/pgsql/9.6/data/postgresql.conf
                • echo "listen_addresses = '*'" >> /var/lib/pgsql/9.6/data/postgresql.conf
        
        ⦿ pg_hba.conf 配置
            • /var/lib/pgsql/9.6/data/pg_hba.conf 添加行
                host    all             all        0.0.0.0/0               md5

                • echo "host    all             all        0.0.0.0/0               md5" >> /var/lib/pgsql/9.6/data/pg_hba.conf

        ⦿ 重启数据库
               x86 • sudo service postgresql-9.6 restart
               x64 • sudo systemctl restart postgresql-9.6

        ⦿ 测试Navicast 连接


        🔅🔅 Centos7 x64
        echo "listen_addresses = '*'" >> /var/lib/pgsql/9.6/data/postgresql.conf && echo "host    all             all        0.0.0.0/0               md5" >> /var/lib/pgsql/9.6/data/pg_hba.conf && sudo systemctl restart postgresql-9.6





🔵 Python 配置
================================================================================

    🔸 简介
        CentOS6 x86 自带 Python2.6.6 (默认不带 pip);
        CentOS7 x64 自带 Python2.7.5 (默认不带 pip);
        很多软件要求 2.7+; 个别软件需要 3.0+
        最好的办法就是 2.7 和 3.6 共存,
        python 命令使用 Python2.7; python3 命令使用 Python 3.6

        当然一台服务器安装了多个Python. 配置不当.很可能会出现各种报错.
        我已经踩过很多坑了,你只要照做就可以了

        ⦿ 注意点
            用pip 安装的软件是 安装到对应版本的 python下的.
            如果你最初是 python2.6  那时候用运行了 pip install cymysql
            那么当你升级 python2.7  后, 必须再重新运行一次 pip install cymysql
            最初的pip 是把cymysql 安装在 python2.6 的目录下的.
            之后的pip 是把cymysql 安装在 python2.7 的目录下的.

        ⦿ Python 版本查看: python -V
        ⦿ yum    版本查看: yum --version
        ⦿ pip    版本查看: pip -V 

        • Centos6 
            必须把 2.6.6 升级到 2.7+ 然后也安装 3.6+ 
            最终实现 Python2.7 和 Python3.0 同存

        • Centos 7 
            安装pip  
            然后安装下python3.6



    🔸 ❗️依赖安装❗️
        安装Python就是编译软件.需要用到很多依赖.
        🔅 yum -y update && yum install sqlite-devel -y



    🔸 Centos 7 
        我们先来弄简单的 也就是Centos7 安装pip 和 python3.6 

        ⦿ pip 安装
            wget https://bootstrap.pypa.io/get-pip.py
            python get-pip.py
            现在 pip -V 就显示 pip 9.0.1 ... (python2.7) 了

        ⦿ Python 3.6.1 安装
                • wget https://www.python.org/ftp/python/3.6.1/Python-3.6.1.tar.xz
                                    注意.如果新版本 就用新版本的网址. 免得以后升级
                • tar -Jxvf Python-3.6.1.tar.xz && cd Python-3.6.1
                • ./configure && make && make install

                这个安装很简单了. 执行上面三个命令就安装好了!!!
                要用python3 运行某文件: python3 xxx.py

                • python3 -V        查看python3 的版本: Python 3.6.1


        🔅🔅 Centos7 x64
        cd ~ && wget https://bootstrap.pypa.io/get-pip.py && python get-pip.py && wget https://www.python.org/ftp/python/3.6.1/Python-3.6.1.tar.xz && tar -Jxvf Python-3.6.1.tar.xz && cd Python-3.6.1 && ./configure && make && make install && python3 -V 



    🔸 Centos 6

        ⦿ 源码编译 Python 2.7.9 

            • wget https://www.python.org/ftp/python/2.7.9/Python-2.7.9.tar.xz
            • tar -Jxvf Python-2.7.9.tar.xz && cd Python-2.7.9
            • ./configure && make && make install 

            手动编译源代码的基本流程. 所有源代码都是这么安装的:
            下载、解压、./configure、make && make install

            默认路径编译. 一般在/usr/local/bin下面;

            现在你只是安装好了软件.但是还没配置环境路径!
            现在你用 python -V 看到的还是 python 2.6.6
            现在你用 type python 看到的是当前python的命令路径:/usr/bin/python

            可以这么理解: 
            终端里的 python 命令就是个Windows下的快捷方式.
            终端里的 type python 命令就是查看这个快捷方式对应的软件安装目录.

            系统自带的 python 2.6.6 是一个安装在 /usr/bin/python 路径下的软件,有一个叫python的快捷方式.
            我们新装的 python 2.7.9 是一个安装在 /usr/local/bin  路径下的软件.有一个叫python的快捷方式.

            那么当前系统就有两个叫python的快捷方式了. 有冲突怎么办.当然是系统默认的为准.
            所以现在的 python -V 对应的是 系统自带的 2.6.6
            怎么才能让 python -V 对应的是 我们新装的 2.7.9
            把系统自带的快捷方式的名称改成别的名字.如 python2.6.6
            那么系统里就只剩下一个叫python的快捷方式了 对应的是我们新装的2.7.9

            怎么改名称呢: 用重命名命令 mv
            • mv /usr/bin/python /usr/bin/python2.6.6

            现在 python -V 就出现 2.7.9 了
            现在 python2.6.6 -V 就变成 2.6.6 了
            所以现在的情况就是 2.6.6 和 2.7.9 共存.
            你要用 2.7.9 就用 python xxxx.py
            你要用 2.6.6 就用 python2.6.6 xxxxx.py
            现在 python 是正常了. 但是yum 就不正常了! 不信你试试 yum -V去
            系统自带的软件尽量别动, 不然会导致很多问题.
            但是这个Python是不得不动, 只能想办法解决 yum 问题了


        ⦿ yum 修复
            yum 是基于 python的. 
            系统自带的python路径是 /usr/bin/python
            yum 这个软件比较傻. 只会去/usr/bin/python 路径下找python.
            但是之前我们把 /usr/bin/python 改成 /usr/bin/python2.6.6 了
            所以当前系统 根本没有 /usr/bin/python 这个路径了.
            yum 找不到 python 那么自然不能正常工作了.

            我们只要能让 yum 能找到 python 就能解决我们的问题
            只要在 /usr/bin 下创建一个 python 的快捷方式就可以了.
            这个快捷方式 目的指向我们新装的 python 2.7.9 的路径:/usr/local/bin/python


            • 我们先看看 2.7.9软件目录下面看看情况.

                cd /usr/local/bin && ll
                注意下面这三行
                lrwxrwxrwx 1 root root    7 Apr  8 11:52 python -> python2
                lrwxrwxrwx 1 root root    9 Apr  8 11:52 python2 -> python2.7
                -rwxr-xr-x 1 root root 4.5M Apr  8 11:52 python2.7

                lrwxrwxrwx            最前面的l 代表这是个链接. 不是目录 也不是文件夹.
                python -> python2     表示python  这个链接是指向 python2   这个文件的.
                python2 -> python2.7  表示python2 这个链接是指向 python2.7 这个文件的
                python2.7             真正的 可执行文件!!! 类似于windouws下的 xxx.exe

                意思就是说.  
                python  -> python2    ➜  你输入 python  其实就是输入 python2    
                python2 -> python2.7  ➜  你输入 python2 其实就是输入 python2.7    
                python2.7             ➜  真正的程序
                所以现在 不管你输入 python 还是python2 还是python2.7 最终都是执行python2.7这个命令.

            • 再看看 /usr/bin 目录下情况
                cd /usr/bin && ll | grep python
                lrwxrwxrwx   1 root root       6 Jun 19 17:07 python2 -> python
                -rwxr-xr-x   2 root root    3.6K Aug 18  2016 python2.6
                -rwxr-xr-x   2 root root    3.6K Aug 18  2016 python2.6.6

                上面列出了所有带有python的文件.  
                第一个是快捷方式.  下面两个是文件
                傻傻的 yum 只会到这个目录来找python 文件, 
                但是这里没有 python 这个文件.因为原来的 python文件被我们重命名成 python2.6.6了.
                那么我们只能创建一个叫 python链接了. 
                把这个叫python链接的目的地设置成/usr/local/bin/python
                这样 yum 就能找到 python 这个可执行文件的路径了
                • ln -s /usr/local/bin/python2.7 /usr/bin/python

                现在 yum 还是不正常的! 因为还有一个地方要修改.
                type yum          找出yum 的真实路径 /usr/bin/yum

                • vi /usr/bin/yum  
                    #!/usr/bin/python
                    import sys
                    try:
                    ...
                看yum这个文件的内容第一行 你会发现yum文件 其实是一个python脚本
                现在的 #!/usr/bin/python 其实是个指向2.7.9版本的python可执行文件.
                但是 yum 只能用 python2.6.6 的python 可执行文件.
                • 把 #!/usr/bin/python 改成 #!/usr/bin/python2.6.6 就可以了

                现在 yum --version 命令就正常了 是yum 3.2.29版本




        ⦿ pip 2.7
            用python 少不了用pip命令.首先要安装pip.
            安装很简单. 下载后运行脚本就可以.
            要让python2.7 正常使用pip.  就必须下载并安装 pip2.7
            这个脚本它会自动根据你当前的python版本 选择对应的pip版本

            • wget https://bootstrap.pypa.io/get-pip.py && python get-pip.py

                现在 pip -V 就显示 pip 9.0.1 ... (python2.7) 了



            • 特殊情况
                上面情况是 centos6 x86 没有自带pip的情况.
                如果你系统默认自带pip的那么 和 yum 一样有点麻烦.

                    首先你必须知道一个python版本 有一个对应的pip版本.
                系统自带python2.6 . 所以系统自带的pip 也是pip2.6
                ➜  ~ whereis pip
                pip: /usr/bin/pip /usr/bin/pip2.6

                要让python2.7 正常使用pip.  就必须下载并安装 pip2.7
                wget https://bootstrap.pypa.io/get-pip.py && python get-pip.py
                它会自动根据你当前的python版本 选择对应的pip版本

                get-pip.py 只是自动帮你安装对应的pip版本.
                安装好后你还需要 手动创建链接.  选择一个系统默认使用的pip版本

                ➜  ~ whereis pip
                pip: /usr/bin/pip /usr/bin/pip2.6 /usr/local/bin/pip /usr/local/bin/pip2.7
                发现有三个...pip.. 
                其实pip 运行也比较傻. 也只会去/usr/bin 文件夹下找的.
                我们把 /usr/bin/pip 快捷方式到 /usr/local/bin/pip2.7 就可以了.
                注意 /usr/bin/ 下是有个pip文件的.
                你要创建快捷方式.就得先把这个文件删除.或者重命名.
                文件肯定不能乱删的.那就重命名成 pip.back把.
                mv pip pip.back

                然后再创建快捷方式.
                ln -s /usr/local/bin/pip2.7 /usr/bin/pip

                ➜  bin pip --version
                pip 9.0.1 from /usr/local/lib/python2.7/site-packages (python 2.7)
                看 丫的  好了吧.... 
                不容易啊!!!!  


        ⦿ Python 3.6

                • wget https://www.python.org/ftp/python/3.6.1/Python-3.6.1.tar.xz
                                    注意.如果新版本 就用新版本的网址. 免得以后升级
                • tar -Jxvf Python-3.6.1.tar.xz && cd Python-3.6.1
                • ./configure && make && make install

                这个安装很简单了. 执行上面三个命令就安装好了!!!
                要用python3 运行某文件: python3 xxx.py

                • python3 -V        查看python3 的版本: Python 3.6.1






    🔸 ENV 虚拟环境

        ⦿ virtualenv 简介
            必须学会使用虚拟环境.既然学技术.肯定要搭建很多环境.
            virtualenv 能让你“项目X使用版本1.x、项目Y使用版本4.x”、系统默认使用3.X.
            有的项目要只能用python 2.7  不能用python 3+;  有的只能用python 3+  但是不兼容python2+
            有的项目要只能用django 1.11 不能用django 1.8; 有的只能用django 1.8 但是不兼容django 1.11
            本文遇到的Django-cms就是第二种情况. 那就得用虚拟环境了!

        ⦿ virtualenv 安装: 🔅 pip install --upgrade virtualenv
                    先升级(更新)pip, 再安装virtualenv

        ⦿ virtualenv 使用流程:
            1. virtualenv env              用python2+创建名叫env的虚拟环境
               virtualenv -p python3 env   用python3+创建名叫env的虚拟环境
            2. source env/bin/activate     激活 venv 这个虚拟环境: 终端前缀多出(env)
            3. 安装项目依赖....
            4. deactivate                  退出虚拟环境.







到这里是最基础设置. 设置好后去备份服务器. 方便还原. 
帮瓦工的vps几秒就能系统还原.非常牛逼! 







⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️------⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️
🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵  TCP BBR 🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵
⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️------⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️
⦿ 加速软件

    锐速/net speeder 这类的加速软件.
    但是现在有了新的选择 TCP BBR 这个是google出的!极大的提高网速.
    首先选择BBR. 

⦿ BBR TCP

    极大的提高下载速度. 至少提高好几倍.
    BBR 目的是要尽量跑满带宽, 并且尽量不要有排队的情况, 效果并不比速锐差


    标准 TCP 协议不完美,特别是存在丢包情况的应对处理.
    国外的vps多多少少都有丢包的情况.导致访问很慢! 
    解决丢包的办法无非就是 用 


⦿ 标准TCP
    只要有万分之一的丢包率，标准 TCP 的带宽就只剩 30%；
    千分之一丢包率时只剩 10%；
    有百分之一的丢包率时几乎就卡住了。

⦿ TCP BBR 
    丢包率 5% 以下几乎没有带宽损失，
    丢包率 15% 的时候仍有 75% 带宽



⦿ Linux 4.9 内核

    2016.12.11  Kernel 4.9 正式发布,带来了一些令人激动的特性以及一些驱动的更新.
    自带了来自 Google 的 BBR (Bottleneck Bandwidth and RTT) TCP 拥塞控制 （congestion control）

    为了体验 BBR TCP, 需要将 CentOS 7 的内核升级至该版本。
    Centos7 自带的是内核版本 2.6 (uname -r 查看)



🔸 Google BBR 配置
    一键脚本 需要配置加速端口. 和 公网IP的网卡名

    端口配置: 端口开启后, 流量会先经过BBR处理. 再发送.
    网卡名字: 可能需要配置 “公网接口名称”，即你服务器上具有公网 IP 的接口名称。搬瓦工 OpenVZ 上默认都是 venet0，但是有朋友可能需要安装在其他服务器上，所以我加入了此选项。


🔸 OpenVZ BBR
    如果你服务器是 KVM. 等等的 那么你可以完全控制系统. 包括内核部分.
    如果你服务器是 OpenVZ . 你是修改不了主机内核的! 但是也有办法使用BBR
    主机就是母鸡. OpenVZ 就是小鸡.  OpenVZ 再虚拟个小小鸡出来. 
    在这个对这个小小鸡 我们是有完整的控制权限的. 我们在小小鸡上运行 BBR 
    当然. 性能有点损失.. 无所谓了.. 内存建议 256+




🔸 BBR一键脚本 (支持OpenVZ、) 
    其他类型vps ( KVM、Xen、VMware)  参考  https://91vps.club/2017/06/02/bbr/
    如果你是OpenVZ小鸡

    wget --no-check-certificate https://raw.githubusercontent.com/mmmwhy/LKL_BBR/master/lkl/install.sh && bash install.sh

    如果不想折腾建议直接安装 CentOS7 ， Debian8 和 Ubuntu16安装包只使用 64bit 的系统。
    默认的端口转发转发 1000-19999 的端口，可以直接搭配本站panel一键脚本。
    只适用 openvz




    加速软件.


    大概原理.. 
    网络就像水管,  服务器默认不会占用整根水管. 而是断断续续的发送. 这就造成了浪费. 也就是下载速度慢.
    就好像明明你汽车可以跑200km/h 但是一般你也就开50km/h.
    汽车有安全原因. 网络就无所谓了..
















⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️------⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️
⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️------⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️⬛️




🔸 user.ini

    ⦿ .htaccess 文件.
        分布式配置文件. 功能非常非常多.不必深入.. 
        http://www.jianshu.com/p/ddca040c8d48

        • 自定义错误页面   ErrorDocument 404 /error-pages/not-found.html
        • IP禁止   Deny from 123.45.67.8
        • 变更默认首页  DirectoryIndex homepage.html


    ⦿ .user.ini
        作用非常广泛. 不像.htaccess有局限性。
        不管是nginx/apache/IIS，只要是以fastcgi运行的php都可以用这个.
        php.ini 是php的默认配置文件.
        .user.ini 是一个可以由用户自定义的 php.ini
















