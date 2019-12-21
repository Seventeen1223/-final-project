
 | 项目  | 看图知景|  
 | --------   | -----:   | 
 | 项目负责人       | 孔秋虹      |
### 项目：看图知景
####  产品定位
本产品旨在构建一个可以帮助人们上传照片即可获取景点信息的平台。
####  目标用户
游客/学生/ 导游
####  功能使用场景描述
- 用户在社交软件浏览到某一个很有意思或者非常漂亮吸引人的景观，想要知道它在哪里，打开“看图知景”APP，上传图片即可返回景点大致信息。
- 用户在景区游览时，对某一个自己感兴趣的景点拍一张照片，自动识别出景点的信息。
- 用户在使用APP识别出景点信息后不想要看文字版本的话，可以选择“语音播放”功能进行语音播放识别结果。
####  加值宣言
我们时常会在被某个好看的景点图片惊艳到，但倘若图片本身并没有文字说明的话，我们通常会向他人求助“这是哪里”，或者使用谷歌地图等功能，上传图片后可以查到一些位置信息，但必须要原图。本产品致力于帮助用户透过图片识别景点，用户上传图片，经过通用物体和场景识别返回景点信息，选择“语音播放”功能则可以通过语音合成返回语音播放结果。
- 优先级：依托百度可识别出10万+物体及场景标签，并在不断丰富中，持续提供更精细的识别服务的强悍能力，通过通用物体和场景识别API，对用户上传的照片进行检测和识别，支持识别绝大部分等景观景点景物的识别，并对仅获取到局部景点照片这类情况进行专项优化。

- 次优先：语音播报服务对返回的文字内容进行语音分析，输出语音版本的景点搜索结果。通过在线语音合成API，对文字内容进行语音播报。

####  核心价值（最小可行性产品）
为满足用户的知悉需求，解决用户想要知道景点信息的问题，在返回景点信息的同时为用户提供可选择的语音播放结果。
####  用户痛点
- 用户看到好看的景点图片，想要知道它在哪里，图片附近却没有文字说明。
- 在景点游览的时候不想要跟着导游后面，想要自己参观。
- 游览景点不想要文字介绍，想要解放眼睛。
####  人工智能概率性与用户痛点
优势：
- 准确性高：基于百度海量数据，利用深度学习技术及高精度算法不断迭代模型，准确率业界领先。
- 标签体系丰富：可识别出10万+物体及场景标签，并在不断丰富中，持续提供更精细的识别服务。
- 简单易用：支持标准化接口封装，调用简单，只需上传单张图片，即可获取识别结果。
劣势：
- 直接使用百度图片里面的图片URL时会显示“图片URL无效”，无法进行识别。
- 用户上传照片光线不足、过于模糊时无法识别。
- 用户对某一景点极具体部分进行照片而无全貌时图片识别失败。
####  需求列表与人工智能API加值
- 用户想要知道景点在哪里（通用物体和场景识别） 
- 用户对语音播放景点内容有需求（语音合成）

####  产品原型
([点击此处查看完整原型链接](http://seventeen1223.gitee.io/scene))

*首页界面设计

![首页](https://upload-images.jianshu.io/upload_images/9404387-89b2abdf255971f7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


*上传照片界面设计

![上传照片](https://upload-images.jianshu.io/upload_images/9404387-181b4f0663fc2455.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


*识别结果界面设计

![识别结果](https://upload-images.jianshu.io/upload_images/9404387-4fb16d709731417b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

*识别失败界面设计

![识别失败](https://upload-images.jianshu.io/upload_images/9404387-9f7c5276a32fb1b2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

*识别历史界面设计

![识别历史](https://upload-images.jianshu.io/upload_images/9404387-cd073d4bdc883723.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

*识别详情界面设计

![识别详情](https://upload-images.jianshu.io/upload_images/9404387-6f3b6b7414d1773a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


*语音播报界面设计

![语音播报](https://upload-images.jianshu.io/upload_images/9404387-d005f9cdf6c4bf6b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

*我的界面设计

![我的](https://upload-images.jianshu.io/upload_images/9404387-086f48f8220344d4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###  产品架构图

![产品架构图](https://upload-images.jianshu.io/upload_images/9404387-28a7f4cb898b45a8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###  产品功能结构图

![产品功能结构图](https://upload-images.jianshu.io/upload_images/9404387-8261609a9b061c01.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###  产品信息结构图
![产品信息结构图](https://upload-images.jianshu.io/upload_images/9404387-40bc0e6bfa51ff28.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###  产品流程图
![产品流程图](https://upload-images.jianshu.io/upload_images/9404387-10bc041e2730e730.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)





#### API1.使用水平
（1）通用物体和场景识别（使用百度API）
- 接口描述：该请求用于通用物体及场景识别，即对于输入的一张图片（可正常解码，且长宽比适宜），输出图片中的多个物体及场景标签。
- 接口地址:[百度图像识别之通用物体和场景识别](https://ai.baidu.com/ai-doc/IMAGERECOGNITION/Xk3bcxe21)
- 请求方式：POST
- 请求URL： https://aip.baidubce.com/rest/2.0/image-classify/v2/advanced_general
- 输入代码示例
```
# encoding:utf-8

import requests
import base64

'''
通用物体和场景识别
'''

request_url = "https://aip.baidubce.com/rest/2.0/image-classify/v2/advanced_general"
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
- 输出代码示例:
```HTTP/1.1 200 OK
x-bce-request-id: 73c4e74c-3101-4a00-bf44-fe246959c05e
Cache-Control: no-cache
Server: BWS
Date: Tue, 18 Oct 2016 02:21:01 GMT
Content-Type: application/json;charset=UTF-8
{
	"log_id": 327863200205075661,
	"result_num": 5,
	"result": [{
		"score": 0.967622,
		"root": "公众人物",
		"baike_info": {
			"baike_url": "http://baike.baidu.com/item/%E6%96%B0%E5%9E%A3%E7%BB%93%E8%A1%A3/8035884",
			"image_url": "http://imgsrc.baidu.com/baike/pic/item/91ef76c6a7efce1b27893518a451f3deb58f6546.jpg",
			"description": "新垣结衣(Aragaki Yui)，1988年6月11日出生于冲绳县那霸市。日本女演员、歌手、模特。毕业于日出高中。2001年，参加《nicola》模特比赛并获得最优秀奖。2005年，因出演现代剧《涩谷15》而作为演员出道。2006年，参演校园剧《我的老大，我的英雄》；同年，她还出版了个人首本写真集《水漾青春》。2007年，她从日出高校毕业后开始专注于演艺发展，并发表个人首张音乐专辑《天空》；同年，新垣结衣还主演了爱情片《恋空》，而她也凭借该片获得了多个电影新人奖项。2010年，主演爱情片《花水木》。2011年，主演都市剧《全开女孩》。2012年，相继参演现代剧《Legal High》、剧情片《剧场版新参者：麒麟之翼》。2013年，主演都市剧《飞翔情报室》。2014年，她主演了剧情片《黎明的沙耶》。2016年，主演爱情喜剧《逃避虽可耻但有用》，并凭借该剧获得了多个电视剧女主角奖项。2017年，主演爱情片《恋爱回旋》，凭借该片获得第60届蓝丝带奖最佳女主角；同年11月，她还凭借医疗剧《Code Blue 3》获得第94届日剧学院赏最佳女配角。"
		},
		"keyword": "新垣结衣"
	},
	{
		"score": 0.716067,
		"root": "人物-人物特写",
		"keyword": "头发"
	},
	{
		"score": 0.421281,
		"root": "商品-穿戴",
		"keyword": "围巾"
	},
	{
		"score": 0.22347,
		"root": "商品-五金",
		"keyword": "拉链"
	},
	{
		"score": 0.028031,
		"root": "商品-穿戴",
		"keyword": "脖套"
	}]
}
```
（2）语音合成（使用百度API）
- 接口描述：基于该接口，开发者可以轻松的获取语音合成能力
- 接口地址:[百度语音技术之语音合成](https://ai.baidu.com/ai-doc/SPEECH/7k38y8ier)
- 输入代码示例
```result  = client.synthesis('你好百度', 'zh', 1, {
    'vol': 5,
})

# 识别正确返回语音二进制 错误则返回dict 参照下面错误码
if not isinstance(result, dict):
    with open('auido.mp3', 'wb') as f:
        f.write(result)
```
- 输入代码示例
```// 成功返回二进制文件流
// 失败返回
{
    "err_no":500,
    "err_msg":"notsupport.",
    "sn":"abcdefgh",
    "idx":1
}
```
#### API2.使用比较分析 

![腾讯图片识别之场景识别](https://upload-images.jianshu.io/upload_images/9404387-c505a937afa21b29.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![百度图像识别之通用物体和场景识别](https://upload-images.jianshu.io/upload_images/9404387-39fff801cbc236bd.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

##### 百度与腾讯AI的输出结果比较
百度通用物体和场景识别能够高精确度识别出景点名称并将其进行归类，输出结果附上文本信息，输出数据结果和腾讯的api对比更加精准，容许图片的模糊度较腾讯的场景识别高，识别图像能力也更强。

#### API3.使用后风险报告 

###### 产品使用可行性

（1）技术方面可行性
*   在市面上现有的场景识别API产品中，我们选择了精准度高，识别度较腾讯等场景识别API更为准确的百度通用物体和场景识别API。
*   百度通用物体和场景识别API仍然存在图片过于模糊难以分辨的技术风险，但是这样的识别结果不会时常发生，对用户来讲是小概率风险，给用户带来的负面体验较少，不会压过正面影响的机率。
（2）市场方面可行性
*   市场需求大，可实施性强。
*  一款轻量级别APP，不会消耗过多内存，调用API成本也并不高昂。
###### 输入输出限制及API使用定价表
- 通用物体和场景识别
[百度场景识别价目表来源](https://ai.baidu.com/tech/body/num)

![免费VS付费](https://upload-images.jianshu.io/upload_images/9404387-c95620335be30e75.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- 语音合成
[百度语音合成价目表来源](https://ai.baidu.com/tech/speech/tts)

![免费VS付费](https://upload-images.jianshu.io/upload_images/9404387-0a01c7f4f067c230.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
