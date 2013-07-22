此项目为一个Android程序，可作为CloudBaaS的SDK。

用户使用CloudBaaS来作为Android程序后端时可基于此项目开发。

此项目和CloudService配合使用，其中CloudService作为服务端，本项目作为Client端的SDK。

需要注意的是在使用SDK接口时候，需要先调用CloudClient.init(context,appname,ak,sk)来初始化。
