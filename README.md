# taotao
淘淘商城（仿淘宝）

所用技术：
分布式程序设计
该项目采用了分布式程序设计,把整个项目分成若千个可独立执行的程序模块，解决了传统集中式
中存储服务器的瓶颈问题，提高了项目的可靠性、可用性和拓展性,方便后期增加新的功能和模
块。

SSM框架
使用了SSM作为底层框架,对数据库进行CRUD操作。

Redis存储
使用Redis作为缓存，缓存秒杀、主页商品，减少用户等待时间，优化用户体验。

Nginx反向代理
保护了真实的web服务器，减轻了web服务器的负担，加速了对网站访问速度,优化用户体验,同
时节约了有限的IP地址资源。

MySQL
关系型数据库管理系统

Dubbo框架
面向接口的远程方法调用，智能容错和负载均衡，以及服务自动注册和发现。

zookeeper
zookeeper为分布式应用提供一致性服务的软件， 提供的功能包括:配置维护、域名服务、分布式
同步、组服务等。

                           _ooOoo_
                          o8888888o
                          88" . "88
                          (| -_- |)
                          O\  =  /O
                       ____/`---'\____
                     .'  \\|     |//  `.
                    /  \\|||  :  |||//  \
                   /  _||||| -:- |||||-  \
                   |   | \\\  -  /// |   |
                   | \_|  ''\---/''  |   |
                   \  .-\__  `-`  ___/-. /
                 ___`. .'  /--.--\  `. . __
              ."" '<  `.___\_<|>_/___.'  >'"".
             | | :  `- \`.;`\ _ /`;.`/ - ` : | |
             \  \ `-.   \_ __\ /__ _/   .-` /  /
        ======`-.____`-.___\_____/___.-`____.-'======
                           `=---='
        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
                 佛祖保佑       永无BUG
