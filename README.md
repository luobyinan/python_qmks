# python_qmks
## 技术文档
### HTML档
* 在这次的期末项目的HTML文档上，我在网页的选择您感兴趣的图表处，用了轮播图跳转，点击轮播图就能跳转到相应的交互数据页面。代码如下：
```div id="wrapper">
  <div id="slider-wrap">
             <ul id="slider">
               <li >
                 <a href="/total_people" type='submit'><img class="i" src="static/entry/img/全国男女人口数对比.png" /></a>
               </li>

               <li>
                  <a href="/GDP" type="submit"><img class="i" src="static/entry/img/中国各省2016-2018年GDP情况.png" /></a>
               </li>

               <li >
               <a href="/unmarried_people" type="submit"><img class="i" src="static/entry/img/中国各省单身人口情况.png" /></a>
               </li>

               <li>
               <a href="/junior_college_people" type="submit"><img class="i" src="static/entry/img/2018年各省6岁及以上大专学历以上总人数.jpg" /></a>
               </li>

               <li>
               <a href="provice_people" type="submit"><img class="i" src="static/entry/img/各省总人口数男女人口数对比.png" /></a>
               </li>

            </ul>
             <!--控制按钮-->
            <div class="btns" id="next"><i class="fa fa-arrow-right"><img src="static/entry/img/right.png" /></i></div>
            <div class="btns" id="previous"><img src="static/entry/img/left.png" /><i class="fa fa-arrow-left"></i></div>
            <div id="counter"></div>

            <div id="pagination-wrap">
              <ul>
              </ul>
            </div>
            <!--控制按钮-->
  </div>
    ```
