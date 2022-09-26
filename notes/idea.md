# 新插件的想法

## FFI
### ffi (C-API)

允许从 baltam 中动态加载并调用 C 接口的库。

直接接入 libffi
- https://github.com/libffi/libffi

通过 LuaJit+ffi 中转
- https://luajit.org/ext_ffi.html


### ffi (polyglot)

通过插件系统加载其他语言的脚本程序
- https://github.com/metacall/core


### ffi (RPC)

使用管道、套接字、其他网络协议进行通信
- https://github.com/RonIovine/pshell


### ffi (Component Object Model, COM)

使用语言、编译器无关的 COM 技术


## 插件开发辅助
### cling 接口测试环境
- 以解释执行的形式编写插件
- 允许在 cling REPL 中动态测试 bex 的插件接口

### lua 接口测试化境
- 以解释执行的形式编写插件
- 允许在 lua REPL 中动态测试 bex 的插件接口
