# cordova

既然是跨平台的app 开发 少不了的android和ios开发环境 在这里就不叙述了 因为已经写过了

大概意思就是android-stadio 然后换一下国内镜像 ios好说了

> npm

``` bash
npm install -g cordova
```

> 官方教程
``` bash
cordova help
```

> 初始化工程

``` bash
cordova create 文件夹名称自己命名
```

> 运行在浏览器
``` bash
cordova platform add browser
cordova run browser
```

> 运行在android
``` bash
cordova platform add android 
cordova run android
```

> 遇到的问题

1 在运行在android 的过程中会下载gradle 还需要配置gradle的环境变量 
过程中会出现 下载不下来的情况和解压失败的情况
解决方式就是手动去下载gradle.x.x.all.zip 放到命令窗口提示的文件夹中就可以成功了


截图没有了 以后记得保存截图 这个问题耽误了我3个小时28分钟