# 计算水费的说明

## 一、水费计算标准

### 1、普通居民用水情况如下：

![](https://gitee.com/lisydataforwork/imagesforwork/raw/master/images/20200924110147.png)

### 2、非居民用水情况如下：

![image-20200924110600182](https://gitee.com/lisydataforwork/imagesforwork/raw/master/images/20200924110919.png)

## 二、计算

![image-20200924112640636](https://gitee.com/lisydataforwork/imagesforwork/raw/master/images/20200924112640.png)

1、 总用水1000，前5免费，待付用水量995，收费方式上面的“一”中的1所示，144 * 4.2 + 144 * 5.6 + (995-144-144) * 9.8 = 8339.8

2、 总用水量200，应该缴过一次费了，所以没有计算前5，待付用水量200，收费方式上面的“一”中的1所示，144 * 4.2 + （200-144） * 5.6 = 918.4

3、总用水量49， 看记录没有缴过费，前5免费，待付用水量44，没有超过144，收费方式上面的“一”中的1所示，44 * 4.2 = 184.8

4、总用水量10，缴过一次费了，待付用水量10，没有超过144，收费方式上面的“一”中的1所示，10 * 4.2 = 42

5、 总用水量1，缴过一次费了，待付用水量1，没有超过100000，收费方式上面的“一”中的2所示，1 * 6.05 = 6.05



附缴费历史：

![image-20200924115328846](https://gitee.com/lisydataforwork/imagesforwork/raw/master/images/20200924115328.png)



## ***<u>三、特别说明</u>***

**如果计算方式就是用立方数乘以单价，就*不要设置采用阶梯计价*。因为采用阶梯计价不同用水立方数价格不一样，而且如果有跨月会求每个月的平均值用水量，再计算，可能有精读损失。** 我看每一个都设置了采用阶梯计价，请根据需求**核对这部分设置是否正确**。

**计费方式对于计算水费特别重要，请仔细设置核对。**

