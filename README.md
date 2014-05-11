![easyItem](https://raw.github.com/hoosin/easyItem/master/Static/images/logo.png)

**easyItem**，是基于PHP。定位为项目跟踪管理，BUG管理的一款开源web开源项目。


##环境要求

- php5.3


##浏览器要求

- Chrome
- FireFox
- IE9 IE10 不支持IE6-8


##安装

- 修改`Config/Config_Common.php` 中的配置，应用名称和数据库名
		
```php
	<?php
	class Config_Common {
	
	    const APP_NAME = 'WORK_TIME';
	
	    public static $db = array(
	        'host' => 'host', //主机
	        'username' => 'username', //用户名
	        'password' => 'password', //密码
	        'pnet' => port, //端口
	        'dbname' => 'dbname', //数据库
	    );
	}
```

- 修改`upload`文件夹的可写权限，用来保存上传的图片
- 在浏览器中访问 `http://.../worktime/index.php`
- 执行安装操作
- 初始账户：`admin`
- 初始密码：`123456`

##更新记录

1. 2014/1/10 17:04:16 兼容chrome；
2. 2014/1/12 17:04:31 完善编辑器bug；
3. 2014/1/14 17:05:00 加入[easyBtn](https://github.com/hoosin/easyBtn "easyBtn") UI组件；


##开源许可

 [easyItem](https://github.com/hoosin/easyItem "easyItem") 基于 [MIT License](http://zh.wikipedia.org/wiki/MIT_License "MIT License") 开源，使用代码只需说明来源，或者引用 [license.txt](https://github.com/hoosin/easyItem/blob/master/LICENSE.txt "license.txt")  即可。

##提交BUG

[![](https://raw.github.com/hoosin/lite/master/img/btn.png)](https://github.com/hoosin/easyItem/issues)
