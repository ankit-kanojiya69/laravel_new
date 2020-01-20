## 关于

[Laravel](https://github.com/laravel/laravel)本地化(中文化)项目模板，带[Laravel-Admin](https://github.com/z-song/laravel-admin)、[Config](https://github.com/laravel-admin-extensions/config)、一键安装/更新，已安装[dingo/api](https://github.com/dingo/api)扩展包以及部分其他辅助扩展包，目前[Laravel](https://github.com/laravel/laravel)版本是6.x版本。


同步[github.com](https://github.com/asundust/laravel_new)和[gitee.com](https://gitee.com/asundust/laravel_new)


## 使用

内置了vendor环境，如不需要，请去`.gitignore`内添加`/vendor`即可。


一键安装/更新命令 `php artisan system install`，`php artisan system update`。

`php artisan system install`会在项目根目录产生`install.lock`文件，如果无权限，请自行更改命令代码。

建议查看一下`app/Console/Commands/System.php`(`php artisan system`)逻辑，以便更好的使用该命令。

目前问题：在`production`环境下无法正确执行询问形命令，目前尚无解决方法。

其他命令`php artisan`查看。

## 许可证
[MIT](https://opensource.org/licenses/MIT)
