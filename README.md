#### HM-RxPermissions


#### 功能介绍

使用RXJava进行权限请求

#### 安装

在工程根目录的build.gradle文件里添加如下maven地址：

```gradle
allprojects {
    repositories {
        ...
        maven { url 'file:///Users/syl/.m2/repository/' }
        ...
    }
}
```

在项目模块的buile.gradle文件里面加入如下依赖：

```gradle
    compile 'com.heima.iou:hmrxpermissionlocal:1.0.0'
```

外部引用：

```gradle
    compile 'io.reactivex.rxjava2:rxjava:2.0.6'
    compile 'io.reactivex.rxjava2:rxandroid:2.0.1'
```

#### 使用说明

支持的路由

路由文件


#### 集成说明

- 需要保证各个模块之间RXJava的版本一致

#### Author

syl