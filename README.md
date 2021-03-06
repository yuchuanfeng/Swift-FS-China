# SwiftFS China

![截图](http://chuantu.biz/t6/62/1506231350x3072129954.png)

-------

### 项目概述

* 一个运行在SwiftWeb上的基于Perfect的BBS系统。
* 主要页面直接采用了ruby on china的样式
* 采用的MySQL，文件本地存储
* 本项目只是骨架,未完全完成。



### 运行环境
* Swift 4
* Mysql 5.76+ (最新版即可)

### 安装
#### 第一部分 
##### 在mac
1. 需要安装Xcode9
2. Swift 4.0+
###### 在linux
1. 需要安装语言环境
2. 可参考 [perfect](https://www.perfect.org/docs/) 或 [vapor](https://docs.vapor.codes/2.0/getting-started/install-on-ubuntu/) 官网
3. 本项目在Linux直接使用 vapor (Install Toolbox)[https://docs.vapor.codes/2.0/getting-started/toolbox/]
4. 执行swift build 或 vpaor build 时会提示 未安装的环境，按提示安装即可

#### 第二部分
* 安装redis
* 将仓库中提供的SQL文件导入
* 修改文件目录下PerfectChina/ApplicationConfiguration 配置信息，有数据库连接，白名单等
* webroot/avatar 为图片本地地址
* 日志输出在更目录 ./webLog.log"


## TODO
* [x] 用户相关
  * [x] 用户注册
  * [x] 用户登录
  * [x] 用户退出登录
  * [x] 找回密码
  * [x] 邮箱验证
  * [x] github登录
  * [x] 个人主页
  * [x] 个人资料修改
  * [x] 修改密码
  * [x] 用户关注
  * [x] 通知阅读
  * [x] 图片上传
  * [x] 通知单条删除和全部删除
* [ ] 后台系统 打算用 antdesign or next.js?
  * [ ] 管理用户
  * [ ] 管理帖子
  * [ ] 管理评论
* [ ] GraphQL接口
* [ ] Build & CI
  * [ ] MakeFile
  * [ ] Docker
* [ ] 其他
  * [x] 全文索引
  * [x] ajax改成模板渲染
  * [ ] 优化UI
  * [ ] openresty
  * [ ] redis

 
 



#### License
[MIT](https://github.com/sumory/openresty-china/blob/master/LICENSE)



