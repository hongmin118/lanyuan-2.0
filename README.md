lanyuan-2.0
===========

蓝缘系统版本2.0

预览地址：http://www.lanoss.com
    
多谢群友们的支持，该网站是用到啊里云服务+香港主机，希望大家继续支持捐

助！群主支付账号 mmm333zzz520@163.com 捐助时，记得备注！谢谢！

关于新版本的说明：
说明：
这个版本主要是对原有的蓝缘系统更换UI界面,功能上基本一致, 但此还在开发当中..... 关于以前版本,不再维护,致力于新版本的开发和维护.
优化：
此版本不再使用前版本在dao层创建session方法来进行数据CRUD, 用mapper来代替dao,由mybaits自动管理各事务的操作,大大减少代码开发时间.
此版本开发采用了maven管理工具,不再使用传统的web方式,所有jar所由maven管理!
技术要点：
1：此版本采用ajax+js分页,js完成是群主自己写的,有点模仿ligerui的分页实现 
2：列表的表头固定,兼容IE,firefox,google,360的浏览器,其他暂没有测试.
3：表格排序功能
4：解决dialog窗口拖动时,阴影变大问题
5：加入druid技术,对sql语句的监控.
6：自定义注解导出excel
7：使用了ehcache缓存机制
8：新增支持oracle分页实现
9：........
