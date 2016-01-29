# NightCAT-ChatRoom
基于NodeJS+Express模块+MongoDB数据库制作的多人聊天室
*目前只实现了基础功能, 欢迎ISSUES或者Pull Requests╰(●'◡'●)╮* 
*并且内含大量中文注释，适合入门初学者使用*
<br>
第一步:
-----
    先把文件下载下来，并且下载[mongodb](http://www.mongodb.org/downloads)
<br>
第二步:
------
    使用npm install下载所有必须模块
<br>
第三步:
-----
####mongodb的使用:<br>

######(1)使用cmd命令行工具链接到mongodb的bin目录下<br>
`> cd C:\\....\\bin`
#######(2)使mongodb连接到我们的data文件夹<br>
`> mongod --dbpath=C:\\....\\data`
#######(3)新开一个cmd命令行工具,并启动mongod <br>
`> mongo`
######(4)创建Users数据库<br>
`> use Users    //当然你也可以使用其他名字,但是需要在app.js :14行修改`
######(5)创建一个Collection<br>
`> db.createCollection('userdata')   //同上也可以改~ 但是需要在app.js :35行:62行修改`
<br>
第四步:
-------
    开始运行╰(●'◡'●)╮
    
    使用cmd命令行工具链接到我们的目录下  (也就是存放app.js的目录)
    
    然后运行 (๑¯ω¯๑)
    > node ./bin/www
    或者
    > npm start
    都可以~ 然后打开http://127.0.0.1:3000/就能看到登录界面啦~
    
    页面可以在view上修改~ 样式图片还有JS文件都放在public目录下~
    
    
