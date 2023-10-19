# Padavan-build说明
现在不需要新建Release了，已经更改了脚本，直接fork，修改好之后，点击右上角的 Star 星星按钮即可开始自动编译（自己点击才会编译）。

ork  https://github.com/chongshengB/Padavan-build 的云编译文件到自己的github库，打开里面的yml自动化执行文件，
1，修改第47行的路由器名字
2，修改第40行为自己star的源码地址，如https://github.com/你的github/xxx.git
3，继续删除60行到114行的配置文字，你要增删插件就到你fork的源代码xxx/trunk/configs/templates 相应的路由器里修改，添加就选Y，否则N。
4，返回云编译项目主页，点击star就开始编译了，点击下一行的Actions等待20几分钟就能看见生成的固件。

手机编辑，有点乱，悟者自悟！
