
1、必须先自行安装adb以及appium，如何安装请自行搜索，并确保能在cmd命令中使用所有命令，可参照https://blog.csdn.net/L_201607/article/details/78150107  
2、程序运行前需先用数据线连接手机，并保证手机的usb调试已经打开，在cmd使用命令adb devices查看是否连接成功  

3、启动appium并连接手机，具体如何配置请参照 https://www.guru99.com/introduction-to-appium.html  

4、启动程序，按ctrl + c 结束程序

---

autolike_with_yeshenVirtual.py 需要与sortout_database.py一起连用，将在pc使用夜神模拟器爬取souler发布的瞬间信息，点赞功能取消以加快爬取效率，自动筛选带有地点信息的瞬间，不带地点信息的瞬间不爬取。