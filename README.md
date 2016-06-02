# ViewSupport

[![License](https://img.shields.io/badge/license-Apache%202-green.svg)](https://www.apache.org/licenses/LICENSE-2.0)
![](https://img.shields.io/badge/Support-7%2B-green.svg)
[![](https://jitpack.io/v/GcsSloop/ViewSupport.svg)](https://jitpack.io/#GcsSloop/ViewSupport)

### 微博: [@GcsSloop](http://weibo.com/GcsSloop)

View支持包，可以帮助你快速的自定义View。

*****

## 工具列表

工具            | Wiki |简介
----------------|------|----------------------------
CanvasAidUtils  | 查看 | Canvas辅助工具，你可以用它绘制坐标系来帮助你检查视图的位置，并在完成之后移除该坐标系。
CanvasUtils     | 查看 | Canvas绘图工具，封装了一些Canvas没有提供的方法，目前只能用来画一条线。
DensityUtils    | 查看 | 密度工具， 根据设备进行如下单位转换: sp -> px, px -> sp, dp -> px, px ->dp
MathUtils       | 查看 | 数学工具， 封装一些数学算法，例如: 获取两点只见距离，获取线段上某一点的位置， 获取线段与水平线夹角 等
ViewUtils       | 查看 | 视图工具， 封装了一些与视图相关等内容，如 手动测量视图大小， 为视图动态设置margin 等



## 如何添加该开源库

#### Gradle:

**Step 1. 添加JitPack仓库**

在当前项目等根目录下的 `build.gradle` 文件中添加如下内容:

``` gradle
	allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
```

**Step 2. 添加项目依赖**

``` gradle
	dependencies {
	        compile 'com.github.GcsSloop:ViewSupport:v1.0.3'
	}
```

## About Me

### 微博: [@GcsSloop](http://weibo.com/GcsSloop)

<a href="https://github.com/GcsSloop/README/blob/master/README.md" target="_blank"> <img src="http://ww4.sinaimg.cn/large/005Xtdi2gw1f1qn89ihu3j315o0dwwjc.jpg" width=300 height=100 /> </a>

## License

```
Copyright (c) 2016 GcsSloop

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
