![十三组](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1540476601004&di=1836db18b117c2fada5324c06d62d2de&imgtype=0&src=http%3A%2F%2Fp8.qhimg.com%2Fdmsmty%2F350_200_%2Ft01b59f3c80d947c82d.jpg)  

## 软件工程13组
- - -
|Number| Id | Name | English | Tasks |
| :-: | :-: | :-: | :-: | - |
| 1 | SZ160110224 | 姜昊 | jianghao | 
| 2 | SZ160110231 | 但远琦 | danyuanqi | 
| 3 | SZ160110214 | 陈润泽 | chenrunze |
| 4 | SZ160110216 | 赵昕玥 | zhaoxinyue | 
| 5 | SZ160110205 | 许浚伟 | xujunwei | 服务器管理、数据库管理、可视化业务逻辑后台模块实现
- - -

## 项目的依赖环境、使用说明
- - -
### Server端
#### 硬件配置
|Item| Request |
| - | - |
| CPU核数 | 建议选择可以独占一核的CPU使用 |
| 系统位数 | 建议64位以上系统 |
| 操作系统要求 | 建议选用64位Linux系统 |
| 内存大小 | 建议内存大小在1GB以上 |
| 硬盘空间 | 建议40GB以上 |

#### 软件配置
|Item| Request |
| - | - |
| Python | 建议使用Python3.6以上的版本 |
| PHP | 建议使用PHP7.0+版本 |
| 数据库 | 建议使用MySQL5.7及更新的版本 |


### Client端

|Item| Request |
| - | - |
| CPU要求 | 建议CPU核数为双核或以上 |
| 内存大小要求 | 建议内存大小在1GB以上 |
| 网络协议 | 支持TCP/IP协议，以及HTTP协议 |
| 操作系统要求 | Windows版本：Windows 2000/XP/2003/Vista/7及以上 </br> Linux版本：内核要求Linux kernel - 2.2.14及以上，并且至少要安装glibc 2.2.4、gtk+ 2.0函数库 </br> Mac版本：Mac OS X 10.2.x 及以上
| 浏览器要求 | Internet Explorer：6.0及以上版本 </br> Chrome或Firefox浏览器 |
- - -

## 实现功能与实现技术
- - -
### 基本功能
|Number| Module | Implements | Remark | Files
| :-: | :-: | - | :-: | - |
| 1 | 登录 |  | 基础功能 |  | 
| 2 | 注册 |  | 基础功能 |  |
| 3 | 数据可视化 | 使用了 `echarts.js` 插件 | 基础功能 | 前端： </br>后台： jawnho.xyz/ControllerPost.php, jawnho.xyz/service/model.php |
| 4 | 图片存储 | 服务器使用MySQL无重复地存储图片数据 | 附加功能 | 前端： </br>后台： jawnho.xyz/ControllerPost.php, jawnho.xyz/service/model.php: imageStore |
| 5 | 生成报表 |  | 基础功能 | 前端：</br>后台： jawnho.xyz/ControllerGet.php, jawnho.xyz/service/model.php: imageLoad |
- - -
