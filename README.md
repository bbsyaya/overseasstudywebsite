英国留学网站
===========
***********
### 网址：[海外留学官网](http://119.23.11.226:8082/)                                                           
### 管理员帐号和密码均为：admin
***********
该网站是本人的毕业设计，具体需求是提供一个良好的交互界面，展示该公司的英国本科、研究生、中学生留学服务。网站分为前台和后台，前台是一列居中布局，从上到下每一部分分别是：
1. 登录条（包含logo和注册登录操作）
2. 导航条
3. 图片轮转
4. 学校板块
5. 留学流程板块
6. 英国本科留学板块
7. 研究生留学板块
8. 中学留学板块
9. 能力培训板块
10. 教师阵容板块
11. 联系方式、地址
12. 底部链接、版权

后台语言为Node.js，利用Express框架和其他一些模块：<br>
* body-parser:处理浏览器post提交的数据
* cookies:保存浏览器登录信息
* mongoose:用来管理mongodb的数据
* swig:模版引擎，用于解决前后端分离
