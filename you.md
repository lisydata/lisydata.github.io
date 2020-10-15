## 一、启动软件

先启动Fiddler 4 ，再启动模拟器。

模拟器一定是启动多开器中Android5那个。



## 二、 通过模拟器抓取数据

- 必要参数说明

![](https://gitee.com/lisydataforwork/imagesforwork/raw/master/images/20201015123853.png)

是否保存搜索用户：设置为1代表在模拟器搜索用户时即保存数据；设置为0代表在模拟器用户时不保存数据到数据库。

是否在进入主页时进行采集：设置为1代表点击进入用户主页时，采集用户信息，并将该用户设置为视频主；设置为0代表点击进入用户主页时，不保存数据。

是否在浏览时采集平台：设置1时在浏览器评论时，自动保存评论和评论涉及的用户。



## 三、 自动采集数据

- 保存视频主：先进入视频主的主页，然后点击右上角三个点，点击分享，点击复制链接。在浏览器打开连接，复制“sec_uid=”到最近的“&”之间的字符，该字符即用户id。进入后台，点击“客户记录”，点击添加，填入复制的用户id。在列表中找到刚刚添加的用户，点击立即采集即可。

![image-20201015125127959](https://gitee.com/lisydataforwork/imagesforwork/raw/master/images/20201015125128.png)

![image-20201015125223727](https://gitee.com/lisydataforwork/imagesforwork/raw/master/images/20201015125223.png)

![image-20201015125419863](https://gitee.com/lisydataforwork/imagesforwork/raw/master/images/20201015125420.png)



![image-20201015125702149](https://gitee.com/lisydataforwork/imagesforwork/raw/master/images/20201015125702.png)

![image-20201015125740082](https://gitee.com/lisydataforwork/imagesforwork/raw/master/images/20201015125740.png)

