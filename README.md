# 个人项目汇总  
### 学院 北京大学新闻与传播学院 姓名 沈攸晋  
  
> ## 1.人物共现关系图（Python-Pyecharts）  
  
* 在上一次作业中，我统计了《红楼梦》中各个人物的出现次数。这一次，我同样分析了《红楼梦》，使用jieba的词性功能，统计出现一百次以上的人名，并进一步统计了他们共同出现的次数。因为jieba词库会将一些动词如“明白”分析为名字，所以我将这些出现次数多的非人名添加进了ignore_list；同样，它会把一些“xx道（此处的道意为‘说’）”分析为人名，所以我讲这些词手动替换成了“xx”；而一些jieba词库识别不出的人名如“周瑞家的”，我加入了“userdict.txt”，导入了词库中。  
* 在分析完他们的共现次数之后，我在csv文档中加入了“category”一项，用1-5的数字对应了贾史王薛无，将人物根据归属家族进行分类，制作了有分类的人物共现关系图。  
  
[《红楼梦》人物共现关系图（分类）](https://shuanx2.github.io/cate_honglou.html)  
  
> ## 2.搜索引擎（HTML）  
  
* 我利用bootstrap官网提供的示例模板，制作了博客式网站，以搜索集合作为主界面，分了“搜索引擎”、“社交平台”、“学术写作”和“百科搜索”四个版面，可以在分类下直接点击进入搜索界面，也可以点击下方的详情进入。出于个人喜好，我将搜索界面的背景颜色改为了淡紫色，嵌入了网站logo，更改了搜索框的大小，内置了“请输入搜索内容”的文字，并用空行将不同的网站搜索框分隔开了。  
  
[搜索集合](https://shuanx2.github.io/search.html)  
> ## 3.网页设计（HTML）  
  
* 在bootstrap模板基础上，我设计了一个集合网站来整合“shuanx2在北京”这一主题的六个板块，用户可以通过主界面各个版块的“View”键来进入具体分类。在主界面的设计中，我替换了背景图片，将文字预览窗口改为了图片，丰富界面色彩。在分类中，用户可以通过左上角的“shuanx2在北京”返回主界面，左侧的标签也可以快速进入其他分类。在每一个分类的主图下，都有简短的介绍语，为了与正文区分，我用css更改了文字的颜色和样式；同时出于美观考虑，我更改了小标题为斜体，对必要的文字进行了加粗处理。  
  
[网页设计](https://shuanx2.github.io/design.html)   
> ## 4. 人物词频统计图（Python-Pyecharts）
* 基于《红楼梦》的人物词频统计结果，制作三种词频统计图  
  
[《红楼梦》人物词频统计-词云](https://shuanx2.github.io/name_count_wordcloud.html)  
[《红楼梦》人物词频统计-柱状图](https://shuanx2.github.io/name_count_bar.html)  
[《红楼梦》人物词频统计-象形柱状图](https://shuanx2.github.io/name_count_pictorialbar.html)  
> ## 5. 地理连线图（Python-Pycharts）
* 构想了一个环球路线，在世界地图中呈现。  
  
[shuanx2的环球旅行](https://shuanx2.github.io/worldtravel.html)  
> ## 6. 中国地图、世界地图（Python-Pyecharts）
* 根据2020中国GDP总量统计结果，制作附色阶的全国GDP总量数据图。（注：港澳台数据为预测数据）  
统计了从2016到2020年商品A在世界市场的销量情况。  
  
[2020全国GDP总量数据图](https://shuanx2.github.io/GDP2020.html)  
[2016-2020商品A全球销量](https://shuanx2.github.io/mapworld.html)  
> ## 7. 组合图表（Python-Pyecharts）
* 集合2010-2020的中国内地GDP总量数据，制作分年统计图、占比饼图，以及2010-2020的变化折线图。  
  
[2010-2020全国GDP总量数据统计](https://shuanx2.github.io/china_gdp_from_2010_to_2020.html)  
> ## 8. 时空数据可视化（Python-Pyecharts/Matplotlib）  
* 对图书情报有关文献数据做处理与可视化。  
  
[不同学报文章的参考文献时间跨度甘特图](gantt.jpg)  
[2001-2010高频关键词变化图](https://shuanx2.github.io/timeline.html)  
[地名在文献标题中出现次数地图](https://shuanx2.github.io/titlemap.html)  
[不同学报之间的引证关系地理连线图](https://shuanx2.github.io/line.html)  
> ## 9. 文本数据可视化（Python-Pyecharts/Matplotlib）  
* 对推特的发布者信息、地点、内容、话题等详情做数据处理，输出可视化结果。  
  
[出现频率最高的话题词云](https://shuanx2.github.io/hashtagscnt.html)  
[每小时热度前十的话题变化时间线](https://shuanx2.github.io/hashtagtimeline.html)  
[发推语言统计饼图](langcnt.jpg)  
[不同时间段发帖数变化曲线](twinum.jpg)  
[点赞转推双维度散点分布](scatter.jpg)
