# API_智能毕业纪念册
| 史诗      | 毕业纪念册 |
| ------------ | ------------- |
| 发布日期     | 2019年12月    |
| 文件状态     | 进行中        |
| 文件主人     | 林梓仪        |

## 背景
毕业纪念册记录着同学们校园时光的点点滴滴，是同学们友情、爱情最好的见证。但现如今市面上的毕业纪念册就两种，一种是纸质版的毕业纪念册，另一种是通过H5，功能单一，这两种就是属于仅为照片记录，且易丢失。目前市面上没有可以实时更新纪念册同学们的信息的纪念册，因此市场竞争压力小，且空间潜力大。

## 目标人群
在校学生，已毕业的群体

## 加值主张设计
### 加值宣言
#### 一句话版本
这个小程序将通过face++的人脸搜索API和百度AI中的词义相似度API帮助用户找到失散多年的同学。

#### 一分钟版本
我们将在微信上开发一款毕业纪念册小程序。这个电子毕业纪念册小程序将会与各大学校合作，把每张毕业照以及毕业照上同学们对应的名字上传到这个小程序上，用户会通过这个小程序将使用face++人脸识别里的人脸搜索API和百度AI中的词义相似度API帮助用户找到他想要找到的同学。此外，当用户找到他想要找到的同学的时候，用户可以在这个同学的主页进行语言留言（这个留言只有用户以及同学可以听到）。每个用户也可以在这个小程序上发布自己的信息和动态，以便别的同学查找。
### 核心价值（最小可行性）
该小程序的核心价值是用户可以通过人脸搜索和词义相似度的功能，找到多年未联系且不知道其联系方式的同学。

### 核心价值与用户痛点
- 当用户想要回忆过往青春，却找不到其毕业纪念册。
- 当用户在偶然看到一张照片，感觉很熟悉却想不起来照片中的人的名字。
- 当用户这记得同学的名字，却忘了他的脸和联系方式。

### 人工智能概率性与用户痛点
- face++称其人脸搜索API的准确度高达98%。虽然准确度很高，但如果刚好有两个同学长得很相像，也会存在找错的可能性。
- 百度AI的词义相似度API虽然准确度高，但当有同学的名字相似度高，也会存在找错/识别的人数太多的可能性。

### 需求列表与人工智能API加值


| 需求                     | 重要程度 | API               |
| ------------------------ | -------- | ----------------- |
| 用户只有一张照片，想找到此照片里的同学| ♥♥♥♥♥   | 人脸识别-人脸搜索API |
| 用户只记得同学的名字，想要找到叫这个名字的同学 | ♥♥♥♥   | 词义相似度API  |
