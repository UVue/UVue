# UVue

> A MVVM framework for Unity3D based on slua



## Roadmap
- [ ] slua library [repo](https://github.com/zxc122333/slua_cmake)
  - [ ] windows
  - [ ] android
  - [ ] ios
  - [ ] osx
  - [ ] webgl

## NOTE
  1. 与一些UI框架不同的是，UVue专注于提供MVVM所需的基础设施，不是也不打算成为一个大而全的框架。

  例如UVue没有直接提供Panel概念，而是提供了更加抽象的UVComponent。通过UVComponent项目主程可以非常方便的定制出自己项目所需要的Panel概念

  - 预先编译好的lua链接库不包含任何第三方lua扩展。预先编译所使用的工程在这里[这里](https://github.com/zxc122333/slua_cmake)，使用cmake来简化跨平台编译，可以参考里面的说明和例子自行增减第三方库

  - lua版本只针对lua5.3.3，而不是slua默认的 ios+lua5.1.5 android+luajit

## [FAQ]()
## [how to]()
