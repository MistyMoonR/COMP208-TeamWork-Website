# COMP208-Group41
 
`2.16` - `V0.1`   

|Group members|JS|GX|HH|JK|LH|ZQ|
|---|---|---|---|---|---|---


## **工作流程介绍**

Meeting Note 在word里多人共同完成并检查，因为这个是文档类型，占分高，最好用office的Word来处理，最后转成PDF放到学校网站。一周提交一次

23号DDL： Requirement analysis  五页PDF，**最好提前设计一下排版，统一风格。**     

文档和代码之类的记录在 [Github](https://github.com/MistyMoonR/COMP208-Group41) 上，大家刚开始别嫌麻烦哈，等到了后期版本管理可以给大家省去不少不必要的麻烦。

聊天：Wechat 或者 Teams (Teams起码能装装样子应付学校)       



-----------
### DDL 安排        
- [x] MEETING NOTES (REWIEW WORTH 8%)  
- [ ] REQUIREMENT ANALYSIS (REWIEW WORTH 12%) *23 Feb 2021*
- [ ] DESIGN (REVIEW WORTH 15%) *19 Mar 2021*
- [ ] IMPLEMENTATION (DEMO WORTH 15%) *4 May 2021*
- [ ] FINAL DOCUMENTATION (ASSESSMENT WORTH 30%) *14 May 2021*      
- [ ] Individual Submission (ASSESSMENT WORTH 20%) *14 May 2021*    

-----------



### 推荐网站:     
[报告查一查](http://report.seedsufe.com/#/report) 方便查资料(copy and paste梭哈)        
[Draw.io](draw.io) 画流程图，UML，啥图都行，关键免费        

搭建网站要用的东西      
[Caddy](https://caddyserver.com/)       
[Matter.js](https://brm.io/matter-js/)      
[P5.js](https://p5js.org/)       
[Mathjs](https://mathjs.org/)  
[Threejs](https://threejs.org/)     

-----------

### Git教程 (还未完成，先不急)
没有Github账号建议注册一个哈，学会这个技能这个将会对你以后学习或者工作都有很大帮助！(不懂为啥学校不教这个玩意)      

下面网站介绍Git的用处            
[Git教程](https://www.liaoxuefeng.com/wiki/896043488029600)     
[Git魔法书](http://www-cs-students.stanford.edu/~blynn/gitmagic/intl/zh_cn/ch01.html)

#### macos部分 -未完成
打开终端        
先安装brew，如果已经安装可以跳过        
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
如果不行的话换国内源
```
/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"
```

brew安装后可以直接安装git，并且检查是否安装完毕
```
brew install git

git --version 
```

创建一个全局用户名、全局邮箱作为配置信息，这里的name和email替换为你的Github的name和邮件，注意双引号不要去掉
```
git config --global user.name "your_name"  

git config --global user.email "your_email@youremail.com"
```
生产SSH key(这里解释下你的电脑和github服务器连接，需要有一个私钥来确认身份)
```
ssh-keygen -t rsa -C "your_email@youremail.com"
```
然后把id_rsa.pub里面全部内容复制粘贴到Github上SSH keys