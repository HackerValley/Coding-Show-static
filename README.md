# Coding-Show-static
静态页面版本的Coding-Show。  
所有的页面 [在线图片](http://www.processon.com/diagraming/582a93cbe4b00c4fc8ae282f)

## 目标
1. 创建静态页面
2. 将页面连接(vue-router)
3. 数据绑定(mock 数据)
4. 与后端对接(待定)

##1.创建静态页面
1. 确定文件夹结构  
文件或文件夹名字须修改
```
  主目录
    assets/
      js/
      css/
        style.css
      img/
    pages/
      admin/  后台管理
        request.html 项目审核页面，申请加入项目
        skill.html  技能审核页面
        professor.html 专家审核页面
      user/  用户管理
        profile.html 个人信息页面
      add.html 添加页面
      modi.html 修改页面
      publish.html 我发布的项目
      develop.html 我开发的项目
    index.html
    
```    
2. 分拆页面  
  确定各个页面的 布局 和 功能  
  [详细见 word 文档](https://github.com/HackerValley/Coding-Show-prototype-readme/blob/master/prototype/11-7%E5%8E%9F%E5%9E%8B%E5%92%8C%E5%BC%80%E5%8F%91%E6%96%87%E6%A1%A3/%E5%BC%80%E5%8F%91%E8%AF%B4%E6%98%8E%E4%B9%A6.docx)  
  //TODO: doc 转化为 md ，按页面拆成多个md文件  
 
##2. 将页面连接(vue-router)
1. 使用 \<a\> 标签创建超链接跳转  
   *此处不修改页面*
2. 改写 vue-router  

##3. 数据绑定(mock 数据)
1. 约定变量名
```
  根据页面上的数据内容
```
2. 使用rap.taobao.com

##4. 与后端对接(待定)
