# wechat_shop_health_product
保健品微信商城(公众号商城微信支付)

开发框架: 后台Play框架2.3.8版本 https://www.playframework.com/documentation/2.3.x/Home, 前台AngularJS+JQuery
数据库:   MySql5.5以上

部署流程:

1. 安装Java8以上, 设置环境变量, 命令行输入javac可以看到信息. (可下载下方网盘的Java一键安装配置包)
2. 安装MySql, 连接配置位于 /conf/application.conf, 新建库(编码utf8_unicode_ci), 并导入db文件夹内的sql脚本
3. 下载代码, 命令行在代码文件夹内直接输入命令即可下载依赖以及运行 (Windows下命令: Activator run) (Linux下: Bash Activator run), 系统会运行在 http://localhost:9000 
4. 若输入以上指令后下载依赖报错, 估计是由于依赖被墙所引起. 则下载下方网盘的依赖包, 复制到 C:\Users\你的用户名\.ivy2\cache 目录下, 重新输入命令即可.


Java及依赖安装:
百度网盘: https://pan.baidu.com/s/10H82J6i0uuWcucs4CGjYtg 提取码: 57nq


有问题可报Issue或联系:
微信 ly17040643
邮箱 17040643@QQ.com
