# 合作项目主题：  
综艺节目的金主爸爸们到底都是谁——不同行业赞助综艺节目的探究报告  
## Pythonanywhere url:http://yunru.pythonanywhere.com/  
# 技术文档描述：  
>- github仓库[整个项目的代码](https://github.com/SOMNUSLOCK/python_end/tree/master/hurun-20191122%20-%20%E5%89%AF%E6%9C%AC)    
>- html档描述：  
主要分两个页面，[第一个result2.html](https://github.com/SOMNUSLOCK/python_end/blob/master/hurun-20191122%20-%20%E5%89%AF%E6%9C%AC/templates/rank.html) 、 [第二个rank.html](https://github.com/SOMNUSLOCK/python_end/blob/master/hurun-20191122%20-%20%E5%89%AF%E6%9C%AC/templates/rank.html)  
1.运用了jinja2模板  
2.图的html档，用python档return render_template导进去  
3.result2.html属于主页面，放不同行业赞助综艺节目的相关数据；rank.html展示了十大赞助商赞助排行的数据。  
>- python档描述：
1.读取csv，实现每个页面均有表格且随着悬浮/点击选择筛选  
2.自定义函数，render_template -> 图表的显示  
3.flask框架的路由@app.route，自定义函数 -> 页面分别为响应前和后，响应前（即下拉框选择前）仅有表格，响应后带图表  
>- web app动作描述
1.左上角“排行榜”按钮，点击实现页面跳转  
2.每一张图鼠标悬浮、第二章图鼠标点击月份、第三张图鼠标悬浮，来实现交互功能。


