# preperation4interview

前端面试：
https://github.com/azl397985856/fe-interview（或者https://lucifer.ren/fe-interview/#/）


ReactNative原理:
https://www.jianshu.com/p/038975d7f22d
https://blog.cnbang.net/tech/2698/

web components

svelter

小程序原理：
https://juejin.im/post/5afd136551882542682e6ad7
https://github.com/Lmagic16/blog/issues/31

webRTC:
https://developer.mozilla.org/zh-CN/docs/Web/API/WebRTC_API

装饰器模式：


serviceWorker：
1.Service worker运行在worker上下文，因此它不能访问DOM。
2.相对于驱动应用的主JavaScript线程，它运行在其他线程中，所以不会造成阻塞。它设计为完全异步，同步API（如XHR和localStorage）不能在service worker中使用。
3.出于安全考量，Service workers只能由HTTPS承载，毕竟修改网络请求的能力暴露给中间人攻击会非常危险。在Firefox浏览器的用户隐私模式，Service Worker不可用。
4.Service workers大量使用Promise，因为通常它们会等待响应后继续，并根据响应返回一个成功或者失败的操作。Promise非常适合这种场景。
注册-》下载-》安装-》激活
https://developer.mozilla.org/zh-CN/docs/Web/API/Service_Worker_API
http://www.alloyteam.com/2016/01/9274/
http://taobaofed.org/blog/2018/08/08/workbox3/

webpack

react redux react-router

nodejs