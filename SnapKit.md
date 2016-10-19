# [SnapKit](https://github.com/SnapKit/SnapKit)
SnapKit is a DSL to make Auto Layout easy on both iOS and OS X.

 - SnapKit提供的方法只能操作通过它添加的LayoutConstraint。
  + 系统的NSLayoutConstraint和SnapKit的LayoutConstraint不应该共存。
  + 建议只在客户强烈要求手写UI布局代码的情况下使用。
