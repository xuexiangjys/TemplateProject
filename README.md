# TemplateProject
模版空壳Android工程，快速搭建（添加了XUtil、XPage和XAOP)

## 使用方式

1.克隆项目

```
git clone https://github.com/xuexiangjys/TemplateProject.git
```

2.修改项目名（文件夹名），并删除目录下的.git文件夹（隐藏文件）

3.使用AS打开项目，然后修改`包名`、`applicationId`和`app_name`

* 修改包名

![](https://github.com/xuexiangjys/Resource/blob/master/img/templateproject/1.png)

![](https://github.com/xuexiangjys/Resource/blob/master/img/templateproject/2.png)

* 修改applicationId

![](https://github.com/xuexiangjys/Resource/blob/master/img/templateproject/3.png)

* 修改apk打包名

![](https://github.com/xuexiangjys/Resource/blob/master/img/templateproject/4.png)

* 修改app_name

![](https://github.com/xuexiangjys/Resource/blob/master/img/templateproject/5.png)

## 项目打包

1.修改工程根目录的`gradle.properties`中的`isNeedPackage=true`。

2.添加并配置keystore，在`versions.gradle`中修改`app_release`相关参数。

## Android Studio模版

[详情点击查看](https://github.com/xuexiangjys/AndroidStudioTemplates)