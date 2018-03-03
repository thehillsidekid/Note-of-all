# MicroPython Notes
## Key words
- lexer  词法解析器
- parser 语法解析器

## Modules
- 一些硬件相关的功能可以以模块的形式加入到MicroPython中，关注源码中以“**Mod**”开头的文件，比如通用的硬件模块有“machine”，针对Pyboard有专用的“Pyb”模块。
- 这里以machine模块为例，machine中包含的硬件相关的操作，可以在“**Modmachine.c**”的[machine_module_globals_table](https://github.com/micropython/micropython/blob/a275cb0f487cd6517760271dc01d369c32600c63/ports/stm32/modmachine.c#L526)中找到具体操作，如果需要添加功能，可以参考其他功能，如ADC来在对应位置完成。






未完待续。。。。    
---

欢迎关注我的微信公众号：**墨意MOE**    
![](../Pic/Misc/qrcode_for_gh_a64f54357afb_258.jpg)