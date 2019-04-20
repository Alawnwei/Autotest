
一、框架结构：

Business:业务相关公共模块，如登录

Common：业务无关公共模块，如读取文件

PageObject:页面元素封装

TestCase：测试用例层

TestData:测试数据

TestSuite:测试套件

browser.ini:运行浏览器配置文件

run.py:运行文件


二、部署：

1、部署 Python

2、部署 Pycharm

3、安装第三方模块：pip install -U 模块名称

    pip install -U selenium
    
    pip install htmlreport
    
    pip ddt
    
4、将浏览器驱动放入浏览器安装目录下

5、将浏览器安装目录放入环境变量 path 中




三、测试用例

1、打开了浏览器

2、输入网址

3、点击请登录链接

4、输入{账号}

5、输入{密码}

6、点击登录

7、{断言}

8、关闭浏览器


断言类型：

1、成功

2、用户名为空

3、用户名不为空，密码为空

4、密码错误

数据：

用户名|密码|断言类型

admin|123456|1

|123|2

291||3

291|1234|4

