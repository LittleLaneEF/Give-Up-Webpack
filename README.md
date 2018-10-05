关于本次分享的萌芽有三个导火索：

首当其冲的是 `Webpack` 作为现阶段模块化打包的宠儿，受到大量开发者的追捧，与此同时我的日常开发也和它密不可分。虽然用得很多，但是对于他的认知还是很零碎、散乱，也希望借此机会整理 `Webpack` 的知识点，让自己对它的认识愈加深刻！

其次是源于我最近看的胜洪宇大神分享的关于 `Webpack`  的技术博客。博客里面文字和视频混排，从简单到复杂的分享了关于 `Webpack3.0+` 的知识点。我也是从头到尾跟着博客坚持学习完的，学完感觉自己收获颇丰，于是整理出来分享给大家！

最后一点是看到吴浩麟编写的《深入浅出 Webpack》，里面的知识点写得很丰富，从浅入深的讲解了关于 `Webpack` 的用法和特性，我在这里也是结合自己的实践做个总结吧，以加强自己的理解！

相应的，对于每个知识点的讲解，我也会编写对应的 `demo`，`demo` 会针对同一个 `plugin` 或 `loader` 在不同`webpack` 版本的使用，也就是说可能会给出不同 `webpack` 版本对应的 `plugin` 或 `loader` 的用法，还请大家自己动手编码，多多尝试。对于 `demo`  我一定会在实践中跑通才放上来的，可能由于读者安装的 `node 版本` 、`npm` 版本 、`Webpack` 版本不同，存在跑不通的情况！还请大家按照我指定的版本操作，这样也可以很好地避免大家在学习中少走弯路，影响大家的学习兴趣！

小弟不才，由于我也是带着学习的心态来分享的，可能文章里面可能有很多错误，望大家多多指正！但是我也会努力不让自己出错。

这是分享的环境



![环境.png | center | 177x143](https://cdn.nlark.com/yuque/0/2018/png/114852/1538231007379-fea8da0f-7585-43ed-a0d7-071e6ce92b56.png "")


本分享启发自：

* [Webpack3.X版 成神之路](http://jspang.com/post/webpack3x.html)
* [深入浅出 Webpack](http://webpack.wuhaolin.cn/)

