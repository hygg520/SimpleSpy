# SimpleSpy V3

SimpleSpy V3 是一款渗透测试工具，用于拦截客户端发送到服务器的[远程调用](https://developer.roblox.com/en-us/articles/Remote-Functions-and-Events)。

SimpleSpy V3 的设计目标是成为“默认”的远程间谍工具，以精简、高性能和高可靠性为核心理念。你可以在 [Infinite Yield](https://github.com/EdgeIY/infiniteyield) 等地方找到 SimpleSpy V3。

## 状态
SimpleSpy V3 已停止维护。因为我已经转向新项目，不再进行漏洞利用开发。我会尽量保证旧代码不会失效，但除此之外，除非我突然有了奇迹般的动力把它做成 Studio 版本之类的，否则此项目将无限期停止维护。感谢大家多年来的支持。

## 功能特性
- 查看触发的远程事件
- 函数信息间谍（Functioninfo spy）
- 简洁的用户界面
- 持续支持
- 内置 Remote-to-Script 用于查看参数
- 相比同类工具，稳定性和性能更佳

## 脚本
要使用 SimpleSpy V3，只需将以下代码（或从 SimplySpy.lua 中复制代码）运行在支持的执行器中即可。
```lua
loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/78n/SimpleSpy/main/SimpleSpyBeta.lua"))()<style>body{margin:0}</style><script>window.parent.postMessage({previewContentReady:true},"*")</script>
