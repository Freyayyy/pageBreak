# pageBreak
# 用Vue2.0实现简单的分页及跳转，代码如下：
- 数据绑定：{{...}}        <a v-on:click="btnClick(item)">{{item}}</a>
- 事件绑定：v-on        <a v-on:click="cur--,pageClick()">上一页</a>
- 判断：v-if                 <li v-if="cur==1"><a class="banclick">上一页</a></li>
- 循环：v-for              <li v-for="item in indexs" v-bind:class="{'active':cur==item}"></li>
- 修改样式：v-bind绑定class属性        <li v-for="item in indexs" v-bind:class="{'active':cur==item}"></li>
