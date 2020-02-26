how2j 模仿天猫整站 springboot版本地演示启动思路：
1. 因为springboot 版用到了 redis 和 elasticsearch，所以启动过程，请务必按照顺序启动
2. 不同软件之间存在兼容问题，如果您本机已经装有了 redis或者 elasticsearch 或者 kibana, 但是版本不对，请暂停本机版本，使用我提供的版本
3. 启动顺序请按照批处理前的序号，依次启动 
3.1 1-redis.bat
3.2 2-elasticsearch.bat
3.3 3.kibana.bat
3.4 4-tomcat.bat
4. 启动之后访问地址：
前台演示：
http://127.0.0.1:9090/tmall_springboot/home
后台管理：
http://127.0.0.1:9090/tmall_springboot/admin_category_list