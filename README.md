# 图美APP-PRD

|发布时间|2019年12月5日|
|-|------|
|产品名称|图美|
|完成进度|进行中|
|设计者|柯根|
|测试者|柯根|

# 目录

- [价值主张设计](#价值主张设计)
	- [背景](#背景)

	- [加值宣言](#加值宣言)

	- [核心价值](#核心价值)
	
	- [用户痛点](#用户痛点)
	
	- [目标](#目标)
	
	- [目标用户](#目标用户)
	
	- [需求列表与人工智能API加值](#需求列表与人工智能API加值)
	
	- [人工智能概率性与用户痛点](#人工智能概率性与用户痛点)

- [原型](#原型)

- [使用水平](#使用水平)

	- [百度黑白图像上色API](#百度黑白图像上色API)
	- [百度人脸对比API](#百度人脸对比API)
	- [百度图像修复API](#百度图像修复API)

- [使用比较分析](#使用比较分析)

- [使用后风险报告](#使用后风险报告)

## 价值主张设计
-----
### 一、背景
- 在这个日新月异的年代，科技快速的发展，各种事物也都在迅速改变，许多人回到旧时居住的地方，发现物是人非，怀旧风每十年就会轮回一次，拿出许久以前拍的照片，发现是黑白的，是残缺的，是不清晰的，或是有许多遮挡物破坏了图片的美观度，这些都让大家十分苦恼。

### 二、加值宣言
- 本产品通过人工智能对图像进行美化、修复来帮助用户实现黑白照片的修缮。

- 核心

运用百度AI中的**黑白图像上色**功能来将用户上传的黑白照片填上颜色

- 辅助

运用百度AI中**人脸对比**和**图像修复**功能来为用户提供自己照片与父母旧照片的相似度对比，以及修复遮挡物，让图片更美观。

### 三、核心价值

- 黑白图像上色：最小可用为识别黑白图像内容并填充色彩，使黑白图像变得鲜活。

### 四、用户痛点

- 黑白照片想要修复填色，却不懂PS等软件技术，自身无法填色和修复，网络上和现实中的照片修复服务价格过高。

### 五、目标

- 上传黑白照片，应用识别后，自动填上颜色

- 上传照片后，选中想要修复的地区，应用自动修复

- 上传两张照片可以对比人脸相似度

### 六、目标用户

- 需要黑白照片填色的用户

- 需要修复，美化照片的用户

### 七、需求列表与人工智能API加值

|用户案例|对应接口|重要程度|
|-|------|-|
|用户想把父母以前的旧黑白照片填上颜色|黑白图像上色|重要
|用户想将照片上的文字遮挡，物品遮挡去除|图像修复|重要
|用户想知道他和他父母的人脸相似度|人脸对比|次重要

#### 具体应用场景

- 小柯在抽屉里翻出了一张二十年前父母的合照，但当时的照相馆比较简陋，是黑白照片，小柯想要将这张照片放大后裱起来放在客厅，但是黑白照片挂起来并不好，这是小柯就打开**图美APP**，将该照片上传上APP，APP经过识别后，快速的上好了颜色。

- 小方找出了一张和小柯的合照，但是上面之前用美颜软件加上了许多修饰物，现在她想将那些修饰物去掉，她马上打开**图美APP**，选中照片中想要遮挡修饰物的区域，APP马上识别后，将修饰物去掉并填充上了背景相似的颜色。

- 小柯拿出父亲三十年前的照片，想知道现在的自己到底有多像那时候的父亲，他就把自己的照片和父亲年轻时的照片一起上传上**图美APP**，APP马上给出99%的相似度。

### 八、人工智能概率性与用户痛点
- 黑白图像上色api

上色导致颜色混杂，脸上出现衣服的颜色

- 人脸对比api

背景颜色影响人脸相似度分析

- 图像修复api

一张照片多个区域想要遮挡

---------------

- 一张黑白战士照片

- 1-1

![image](https://github.com/kegen/API_ML_AI/blob/master/11.png)

- 经过上色之后

- 1-2

![image](https://github.com/kegen/API_ML_AI/blob/master/1.png)

- 可见各方面颜色清晰，对比度高，无颜色混乱现象

- 两张网友说五官相似的明星照片进行相似度识别

- 1-3

![image](https://github.com/kegen/API_ML_AI/blob/master/22.png)

- 黄渤的两张不同照片

- 1-4

![image](https://github.com/kegen/API_ML_AI/blob/master/2.png)

- 这三张照片的背景颜色都比较鲜明和强烈，并没有影响到人脸对比的识别，由此可见，人脸识别的准确度还是很高的。

- 一张自拍上有许多修饰物

- 1-5

![image](https://github.com/kegen/API_ML_AI/blob/master/3.png)

- 选中想要遮挡的修饰物

- 1-6

![image](https://github.com/kegen/API_ML_AI/blob/master/33.png)

- 修复后

- 1-7

![image](https://github.com/kegen/API_ML_AI/blob/master/333.png)

- 图像修复可以同时遮挡多个区域。

--------

## 原型

### 交互及界面设计

- 点击蓝色文字可以跳转[原型](http://nfunm037.gitee.io/api_ml_ai)页面，若交互效果点击无效，可刷新页面再次点击。

- [下载产品原型文档](https://github.com/kegen/API_ML_AI/blob/master/api%E5%8E%9F%E5%9E%8B.rp)

- API运用情况
1、黑白图像上色功能运用了**黑白图像上色api**。
2、图像修复功能运用了**图像修复api**。
3、人脸对比功能运用了**人脸对比api**。

- 口头操作说明

>用户进入**图美**，有**黑白图像上色**、**图像修复**和**人脸对比**三个功能可供用户选择，随机点击一个功能进入之后，可在本地图库找到自己想要上色/修复/对比的图片，其中对比需要两张图片，修复需要选中修复区域，之后点击马上上色/修复/对比，即可立即生成上色/修复/对比后的图片，用户可以将其保存在本地图库。


- **使用流程图**

- 2-0

![image](https://github.com/kegen/API_ML_AI/blob/master/%E6%B5%81%E7%A8%8B%E5%9B%BE1.png)

![image](https://github.com/kegen/API_ML_AI/blob/master/%E6%B5%81%E7%A8%8B%E5%9B%BE2.png)

-------

- **载入页**

- 2-1

![image](https://github.com/kegen/API_ML_AI/blob/master/%E8%BD%BD%E5%85%A5.png)

- **功能选择页**

- 2-2

![image](https://github.com/kegen/API_ML_AI/blob/master/%E5%8A%9F%E8%83%BD.png)

- **功能主页面**

- 2-3

![image](https://github.com/kegen/API_ML_AI/blob/master/%E9%BB%91%E7%99%BD%E4%B8%8A%E8%89%B2.png)

- 2-4

![image](https://github.com/kegen/API_ML_AI/blob/master/%E4%BF%AE%E5%A4%8D.png)

- 2-5

![image](https://github.com/kegen/API_ML_AI/blob/master/%E5%AF%B9%E6%AF%94.png)

- **图库选择页**

- 2-6

![image](https://github.com/kegen/API_ML_AI/blob/master/%E9%BB%91%E7%99%BD%E4%B8%8A%E8%89%B2%E5%9B%BE%E5%BA%93.png)

- 2-7

![image](https://github.com/kegen/API_ML_AI/blob/master/%E5%AF%B9%E6%AF%94%E5%9B%BE%E5%BA%93.png)

- **选择成功页**

- 2-8

![image](https://github.com/kegen/API_ML_AI/blob/master/%E9%BB%91%E7%99%BD%E5%8A%9F%E8%83%BD.png)

- 2-9

![image](https://github.com/kegen/API_ML_AI/blob/master/%E5%AF%B9%E6%AF%94%E5%8A%9F%E8%83%BD.png)

- 2-10

![image](https://github.com/kegen/API_ML_AI/blob/master/%E4%BF%AE%E5%A4%8D%E5%8A%9F%E8%83%BD.png)

- **功能实现成功**

- 2-11

![image](https://github.com/kegen/API_ML_AI/blob/master/%E4%BF%AE%E5%A4%8D%E6%88%90%E5%8A%9F.png)

- 2-12

![image](https://github.com/kegen/API_ML_AI/blob/master/%E5%AF%B9%E6%AF%94%E6%88%90%E5%8A%9F.png)

- 2-13

![image](https://github.com/kegen/API_ML_AI/blob/master/%E9%BB%91%E7%99%BD%E6%88%90%E5%8A%9F.png)


----

## API 产品使用关键AI或机器学习之API的输出入展示

--------

### 使用水平

--------

#### 百度黑白图像上色API

- 接口描述：智能识别黑白图像内容并填充色彩，使黑白图像变得鲜活。

- 输入

```
# encoding:utf-8

import requests
import base64

'''
黑白图像上色
'''

request_url = "https://aip.baidubce.com/rest/2.0/image-process/v1/colourize"
# 二进制方式打开图片文件
f = open('[本地文件]', 'rb')
img = base64.b64encode(f.read())

params = {"image":img}
access_token = '[调用鉴权接口获取的token]'
request_url = request_url + "?access_token=" + access_token
headers = {'content-type': 'application/x-www-form-urlencoded'}
response = requests.post(request_url, data=params, headers=headers)
if response:
    print (response.json())
```

- 输出

```
{
	"log_id": "6876747463538438254",
	"image": "处理后图片的Base64编码"
}
```

- 测试

- 3-1

![image](https://github.com/kegen/API_ML_AI/blob/master/%E9%BB%91%E7%99%BD.png)

- 3-2

![image](https://github.com/kegen/API_ML_AI/blob/master/11.png)

- 3-3

![image](https://github.com/kegen/API_ML_AI/blob/master/1.png)


#### 百度人脸对比API

- 接口说明：用于比对多张图片中的人脸相似度并返回两两比对的得分，可用于判断两张脸是否是同一人的可能性大小。

- 输入

```
# encoding:utf-8

import requests

'''
人脸对比
'''

request_url = "https://aip.baidubce.com/rest/2.0/face/v3/match"

params = "[{\"image\": \"sfasq35sadvsvqwr5q...\", \"image_type\": \"BASE64\", \"face_type\": \"LIVE\", \"quality_control\": \"LOW\"},
 {\"image\": \"sfasq35sadvsvqwr5q...\", \"image_type\": \"BASE64\", \"face_type\": \"IDCARD\", \"quality_control\": \"LOW\"}]"
access_token = '[调用鉴权接口获取的token]'
request_url = request_url + "?access_token=" + access_token
headers = {'content-type': 'application/json'}
response = requests.post(request_url, data=params, headers=headers)
if response:
    print (response.json())
```

- 输出

```
{
    "score": 44.3,
    "face_list": [  //返回的顺序与传入的顺序保持一致
        {
            "face_token": "fid1"
        },
        {
            "face_token": "fid2"
        }
    ]
}
```

- 测试

- 3-4

![image](https://github.com/kegen/API_ML_AI/blob/master/22.png)

- 3-5

![image](https://github.com/kegen/API_ML_AI/blob/master/2.png)


#### 百度图像修复API

- 接口说明：去除图片中不需要的遮挡物，并用背景内容填充，提高图像质量。

- 输入

```
# encoding:utf-8

import requests

'''
图像修复
'''

request_url = "https://aip.baidubce.com/rest/2.0/image-process/v1/inpainting"

params = "{\"inpainting_type\":\"rectangle\",\"rectangle\":[{\"width\":92,\"top\":95,\"height\":36,\"left\":543}],\"image\":\"图片base64编码\"}"
access_token = '[调用鉴权接口获取的token]'
request_url = request_url + "?access_token=" + access_token
headers = {'content-type': 'application/json'}
response = requests.post(request_url, data=params, headers=headers)
if response:
    print (response.json())
```

- 输出

```
{
     "log_id": "6876747463538438254",
     "rect_image": ”处理后图片的Base64编码“
}
```

- 测试

- 3-6

![image](https://github.com/kegen/API_ML_AI/blob/master/33.png)

- 3-7

![image](https://github.com/kegen/API_ML_AI/blob/master/333.png)

- 3-8

![image](https://github.com/kegen/API_ML_AI/blob/master/%E4%BF%AE%E5%A4%8D%E6%B5%8B%E8%AF%95.png)

--------

### 使用比较分析

#### 百度黑白图像上色API

- 市面上的各大平台除**百度**外，还没有其他平台的**黑白图像上色API**，因此百度黑白图像上色API无其他竞品。

- 所以选择百度的**黑白图像上色API**

#### 百度图像修复API

- 市面上的各大平台除**百度**外，还没有其他平台的**图像修复API**，因此百度图像修复API无其他竞品。

- 所以选择百度的**图像修复PI**

#### 百度人脸对比

- 4-1

- ![image](https://github.com/kegen/API_ML_AI/blob/master/%E7%99%BE%E5%BA%A6%E4%BB%B7%E6%A0%BC%E8%A1%A8.png)

##### face++人脸比对API：

- 4-2

- ![image](https://github.com/kegen/API_ML_AI/blob/master/face%2B%2B%E4%BB%B7%E6%A0%BC%E8%A1%A8.png)

##### 阿里人脸比对API：

- 4-3

- ![image](https://github.com/kegen/API_ML_AI/blob/master/%E9%98%BF%E9%87%8C%E4%BB%B7%E6%A0%BC%E8%A1%A8.png)

-------

### 使用后风险报告

- 黑白图像上色API

黑白图像上色API是百度AI的新品，价格与常规API价格相同，在上色方面**准确率高达90%**，不足的是，在面对**全黑/全白** 图片时，如果图片无明显特征或对比度鲜明，会出现上色紊乱的现象。

- 图像修复API

图像修复API是百度还在邀请测试的产品，价格为正常价格，对图片上遮挡物的清除为**100%清除**，不足之处在于，清除之后会对背景出现一些色块混杂，导致背景不太自然。

- 人脸对比API

价格：FACE++>百度>阿里云。百度每天有500次免费调度的额度，而阿里云只有5次。

准确度及功能：百度>FACE++>阿里云。百度的准确度是最高的，并且相较于其他两家，百度会返回提供给用户具体相似度的百分点，让用户更清晰的看得出区别。

- 因此我们三个API都选择百度AI。
