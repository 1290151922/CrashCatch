本文来自 ：http://blog.csdn.net/baiyuliang2013/article/details/51657443

应用中的崩溃问题对于APP开发者是最头疼的问题了，虽然应用上线前会经过严格测试，
但总会有漏网之鱼，使用过程中冷不丁的弹出一个“xxx已停止运行或xxx无响应是否关闭”甚是恼人，
不但用户体验差，而且异常还难以捕获，对bug修复带来难度！虽然市面上有不少第三方的崩溃分析sdk，
但集成后会带来额外增加安装包大小，应用稳定性等问题，因此若能自己写一个全局异常捕获并在出现崩溃时跳转到
自定义友好界面，岂不是更好？

之前参考网上资源写过一篇自定义异常处理的文章，虽说能用，不过体验并不好，而且存在兼容性问题，
而本篇文章将会解决以上的种种问题，先来看个效果：