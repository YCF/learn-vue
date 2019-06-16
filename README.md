# Vuejs 学习笔记

通过写一些有意思的例子来理解使用 Vue.js

1. vCard-Qrcode 

   初试数据绑定，实现输入框随动的二维码名片（手机可扫加入联系人），利用中文名的长度简单判断了复姓，简化处理了 firstName 和 lastName的录入。例子中使用了 Vuejs 的[输入绑定](https://cn.vuejs.org/v2/guide/forms.html#文本)和[计算属性](https://cn.vuejs.org/v2/guide/computed.html#计算属性)。

   同时本例子中使用了 [http://livejs.com/](http://livejs.com/)实现在开发时浏览器自动刷新。只要在HTML中引用 `live.js`和使用`python -m SimpleHTTPServer 8000`启动一个http服务就可以在编辑器保存时自动刷新网页。

   这个例子没用到 npm ，入门简单。

   

