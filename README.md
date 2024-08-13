# 雾凇拼音-plus

雾凇拼音-plus是雾凇拼音的增强版本，在原生雾凇拼音的基础a上n增加了下面的功能。
这些功能使用纯lua + curl命令的方式实现，不依赖c库和lua的socket库，避免lua版本不一致导致的问题。

## 云输入法功能
  - 通过 Ctrl + t 触发百度云输入（快捷键可定制）
  - 依赖curl，所运行的系统必须安装有curl
  - Android 端暂时不支持
## 翻译增强
调用谷歌翻译API，实现翻译功能
- 汉译英 通过 Ctrl + e 触发
- 英译汉 通过 Ctrl + h 触发   

## 安装
安装方法请参考 https://github.com/iDvel/rime-ice