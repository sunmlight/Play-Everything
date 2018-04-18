#### ubuntu安装ss图形化客户端
> sudo add-apt-repository ppa:hzwhuang/ss-qt5 ;sudo apt-get update;sudo apt-get install shadowsocks-qt5
- 连接成功无法上网:
    - 安装pip : sudo apt-get install python-pip 
    - 安装genpac : sudo pip install genpac
    - 打开并连接ss
    - 执行genpac -p "SOCKS5 127.0.0.1:1080" --output="autoproxy.pac"
    - 点击桌面右上角--网络设置--网络代理--选择自动代理模式配置URL:file:///home/username/autoproxy.pac
        - 注意url中username填入当前用户名
    
    

#### Ubuntu一键安装ss-ssr服务端
> 