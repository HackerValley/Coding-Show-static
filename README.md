# Coding-Show-static
静态页面版本的Coding-Show。  
所有的页面 [在线图片](https://www.processon.com/view/link/584a3a04e4b031ce542d2a5a) 点击查看    
DOCS_[页面预览](./docs/allpages.md)  
BootStrap的 [编码规范](http://codeguide.bootcss.com/) 有点长，先看完吧。着手写的时候有犹豫的地方，就想得到回来查。  

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
      admin/            后台管理
        request.html      项目审核页面，[胜利] 
        skill.html        技能审核页面  [yiran]
        professor.html    专家审核页面  [ruichu]
      user/             用户管理
        profile.html      个人信息页面  [eyea] 
        log.html                       [eyea] 
      add.html          添加页面        [larry]
      modi.html         修改页面        [larry]
      publish.html      我发布的项目    [yaojiang]
      develop.html      我开发的项目    [yaojiang]
      detail.html       项目详情页面    [eyea]
    index.html        首页            [suhanyu]
```    
 文档跳转：  
   - [doc 后台管理页面](./docs/page-admin.md)  
   - [doc 注册相关页面](./docs/page-reg.md)  
   - [doc 列表相关页面](./docs/page-list.md)  
   - [doc 详情修改页面](./docs/page-detail-and-curd.md)  

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
