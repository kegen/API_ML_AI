# 黑白照片美化APP-PRD

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

### 五、目标用户

- 需要黑白照片填色的用户

- 需要修复，美化照片的用户

### 六、用户需求列表

|用户案例|对应接口|重要程度|
|-|------|-|
|用户想把父母以前的旧黑白照片填上颜色|黑白图像上色|重要
|用户想将照片上的文字遮挡，物品遮挡去除|图像修复|重要
|用户想知道他和他父母的人脸相似度|人脸对比|次重要

#### 具体应用场景

- 小柯在抽屉里翻出了一张二十年前父母的合照，但当时的照相馆比较简陋，是黑白照片，小柯想要将这张照片放大后裱起来放在客厅，但是黑白照片挂起来并不好，这是小柯就打开**黑白照片美化APP**，将该照片上传上APP，APP经过识别后，快速的上好了颜色。

- 小方找出了一张和小柯的合照，但是上面之前用美颜软件加上了许多修饰物，现在她想将那些修饰物去掉，她马上打开**黑白照片美化APP**，选中照片中想要遮挡修饰物的区域，APP马上识别后，将修饰物去掉并填充上了背景相似的颜色。

- 小柯拿出父亲三十年前的照片，想知道现在的自己到底有多像那时候的父亲，他就把自己的照片和父亲年轻时的照片一起上传上**黑白照片美化APP**，APP马上给出99%的相似度。

### 七、人工智能概率性与用户痛点
- 黑白图像上色api

上色导致颜色混杂，脸上出现衣服的颜色

- 人脸对比api

背景颜色影响人脸相似度分析

- 图像修复api

一张照片多个区域想要遮挡

---------------

- 一张黑白战士照片

![image](https://note.youdao.com/ynoteshare1/index.html?id=40f6d2b1257f58c54e70d52442f75b33&type=note)
