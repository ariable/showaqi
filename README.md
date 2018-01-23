利用 aqicn.org 的 widget 做的一个小工具 本来就打算放自己博客上的

根据访客的 ip 地址显示其城市的 AQI IP 对应城市是用新浪的 API 获取的

因为使用了汉字转拼音，所以只能支持国内的城市

用法就是将几个 PHP 文件都放到同一目录下

前端只需要`<script src="yoursite.com/aqijs.php?size=xxx"></script>`

即可使用

size 有 small large xsmall xlarge xxl 这几种 按自己需求使用即可

当然你的服务器需要支持 PHP 我也不知道兼容性怎么样

有兴趣的话自己改改代码也很简单，很多代码是从百度复制的，有些代码好几个网站上都是一样的，所以也搞不清楚版权

Demo : <a href="https://ariable.github.io/aqijs.htm" target="_blank">演示页面</a>
