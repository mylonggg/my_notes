# cloudflare建私有笔记

1.创建 **Workers** 

2.创建 **D1 SQL数据库** ，名字随意

3.[SQL代码](https://github.com/mylonggg/my_notes/blob/main/src/D1%E5%88%9D%E5%A7%8B%E5%8C%96.md)

4.编辑代码 [输入代码](https://github.com/mylonggg/my_notes/blob/main/src/worker.md)

5.保存部署

6.绑定D1数据库，变量名称`DB`，数据库选择自己新建

7.绑定AI,变量名`AI`

8.绑定自定域，然后添加一个环境变量（密码用于绑定数据库）类型：密钥，变量名`ADMIN_KEY`,值设置成你想要的密码

9.新建Pages 连接github账号，选项目名称，然后绑定自定域
