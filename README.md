# xiaochengxu-module
小程序的一些文件暂存

## 1、md5.js   =>   小程序加密所需md5的JS文件




var MD5s = require('../../utils/md5.js')

Page({
  data: {},
  onLoad: function (options) {
    var md = MD5s.md5("这是一段要被加密的话");
    console.log(md);  //802909e380455122f72d652ffaa1a4dc
  }
})
