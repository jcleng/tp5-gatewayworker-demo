# tp5整合workerman/gatewayworker开发demo
#安装扩展
composer require workerman/workerman
启动
/www/server/php/54/bin/php server.php
守护启动执行php server.php start -d


worker配置文件在application/extra目录下

逻辑操作在application/push/controller/Event.php中，参考workerman官方demo即可
