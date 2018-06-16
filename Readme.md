# Curtain
## 简介
一款基于JQuery的列表滚动插件
## 使用方法
首先要用HTML编写一个列表
```
<div class="w_table" id="w_table3">
                             <ul class="yl_ul">
                                 <!--<li>
                                     <div class="ylInf">
                                         <div>1.华阳小区</div>
                                         <div>0.01m</div>
                                     </div>
                                 </li>
                                 <li>
                                     <div class="ylInf">
                                         <div>1.华阳小区</div>
                                         <div>0.01m</div>
                                     </div>
                                 </li>
                                 </ul>
 </div>
```
使用js进行初始化
```
$("#w_table3").Scroll({ line: 1, speed: 500, timer: 5000 });
```