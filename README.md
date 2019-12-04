# remConfig.js
px2rem  


## 适配Rem  
```
import Vue from 'vue'
import app from './../App.vue'
import RemConfig from './../js/remConfig.js'  

RemConfig(750,100)
```
第一个参数是图稿宽度(根据情况改变)，第二个是缩放比例建议固定100，元素大小可写成(稿件中px)/100 rem  
例：稿件中元素宽度测量为223px，实际样式代码中书写2.23rem
