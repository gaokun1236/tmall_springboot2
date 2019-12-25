# tmall_springboot2

演示链接：
http://how2j.cn/tmall
http://how2j.cn/tmall/admin


1.使用到的技术：
springboot,hibernate,shiro,redis,rest接口开发,前后端分离，vue.js


2. java源代码包结构
pojo 实体
config 配置
es elasticsearch dao类
exception 异常处理
realm shiro相关
dao DAO类
interceptor 拦截器
web 控制层
service Service层
test 测试类
util 工具类
comparator 比较类


3. webapp 目录
css css文件
img 图片资源
js js文件
4. templates
thymeleaf 模板文件



实现的功能：
1. 购物车
立即购买 加入购物车 查看购物车页面 购物车页面操作

2. 订单状态流转
生成订单 确认支付 后台发货 确认收货 评价

3. CRUD
后台各种功能

4. 分页
后台各种功能

5. 一类产品多属性配置
属性管理

6. 一款产品多图片维护
产品图片管理

7. 产品展示
前台首页 前台产品页

8. 搜索查询-基于elastic search
搜索

9. 登录、注册 - 基于 shiro
注册 登录 退出

10. 登录验证 - 基于 shiro
登录状态拦截器

11. 事务管理
ForeRESTController.对createOrder进行事务管理
等等 。。。

12. 缓存处理
全站数据通过 redis 进行了缓存


imags文件夹只放了项目成功运行的截图。以下只放两张
![image](https://github.com/gaokun1236/tmall_springboot2/blob/master/images/%E8%AE%A2%E5%8D%95%C2%B7.png)

![image](https://github.com/gaokun1236/tmall_springboot2/blob/master/images/%E5%90%8E%E7%AB%AF.png)



启动项目：
1.sql文件放在other文件夹里面
2.redis_elasticsearch 解压后，先按照顺序运行，然后再启动项目
