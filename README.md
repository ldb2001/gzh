# 公众号天气&纪念日推送教程
## 1.微信开放平台注册

首先我们需要注册一个微信开放平台的测试号

http://mp.weixin.qq.com/debug/cgi-bin/sandboxinfo?action=showinfo&t=sandbox/index 

![image-20240817090808893](C:\Users\86152\AppData\Roaming\Typora\typora-user-images\image-20240817090808893.png)

![image-20240817090925725](C:\Users\86152\AppData\Roaming\Typora\typora-user-images\image-20240817090925725.png)

![image-20240817091031585](C:\Users\86152\AppData\Roaming\Typora\typora-user-images\image-20240817091031585.png)

![image-20240817091131028](C:\Users\86152\AppData\Roaming\Typora\typora-user-images\image-20240817091131028.png)

模板内容如下（模板内容能做修改，不过需要根据代码自己修改，不做过多赘述了）：

{{date.DATA}} 

地区：{{region.DATA}} 

天气：{{weather.DATA}} 

气温：{{temp.DATA}} 

风向：{{wind_dir.DATA}} 

今天是我们恋爱的第{{love_day.DATA}}天 

{{birthday1.DATA}} 
{{birthday2.DATA}}

## 2.和风天气API key获取

因为涉及到天气，我们需要搞个API来获取天气数据，注册一个和风天气

https://id.qweather.com/

![image-20240817091614667](C:\Users\86152\AppData\Roaming\Typora\typora-user-images\image-20240817091614667.png)

![image-20240817091723670](C:\Users\86152\AppData\Roaming\Typora\typora-user-images\image-20240817091723670.png)

![image-20240817091900253](C:\Users\86152\AppData\Roaming\Typora\typora-user-images\image-20240817091900253.png)

![image-20240817092003604](C:\Users\86152\AppData\Roaming\Typora\typora-user-images\image-20240817092003604.png)

## 3.配置

找到代码中的config.txt文件

![image-20240817092531290](C:\Users\86152\AppData\Roaming\Typora\typora-user-images\image-20240817092531290.png)
