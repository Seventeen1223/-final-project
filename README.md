### 项目：看图识景

[Powerpoint链接](https://gitee.com/Seventeen1223/PPT/blob/master/%E7%9C%8B%E5%9B%BE%E8%AF%86%E6%99%AF.pptx)

| 发布日期  | 2019年12月17日|  
  | --------   | -----:   | 
| 项目  | 看图识景|  
 | 项目负责人  | 孔秋虹|  
 | 项目进度  | 已完成|  
|项目迭代|3.0版本|
### 一、价值主张设计
####  1.产品定位
本产品旨在构建一个可以帮助人们上传照片即可获取景点信息的平台。
####  2.目标用户
游客/学生/ 导游
####  3.功能使用场景描述
- 用户在社交软件浏览到某一个很有意思或者非常漂亮吸引人的景观，想要知道它在哪里，打开“看图知景”APP，上传图片即可返回景点大致信息。
- 用户在景区游览时，对某一个自己感兴趣的景点拍一张照片，自动识别出景点的信息。
- 用户在使用APP识别出景点信息后不想要看文字版本的话，可以选择“语音播放”功能进行语音播放识别结果。
####  4.加值宣言
我们时常会在被某个好看的景点图片惊艳到，但倘若图片本身并没有文字说明的话，我们通常会向他人求助“这是哪里”，或者使用谷歌地图等功能，上传图片后可以查到一些位置信息，但必须要原图。本产品致力于帮助用户透过图片识别景点，用户上传图片，经过通用物体和场景识别返回景点信息，选择“语音播放”功能则可以通过语音合成返回语音播放结果。
- 优先级：依托百度可识别出10万+物体及场景标签，并在不断丰富中，持续提供更精细的识别服务的强悍能力，通过通用物体和场景识别API，对用户上传的照片进行检测和识别，支持识别绝大部分等景观景点景物的识别，并对仅获取到局部景点照片这类情况进行专项优化。

- 次优先：语音播报服务对返回的文字内容进行语音分析，输出语音版本的景点搜索结果。通过在线语音合成API，对文字内容进行语音播报。

####  5.核心价值（最小可行性产品）
为满足用户的知悉需求，解决用户想要知道景点信息的问题，在返回景点信息的同时为用户提供可选择的语音播放结果。
####  6.用户痛点
- 用户看到好看的景点图片，想要知道它在哪里，图片附近却没有文字说明。
- 在景点游览的时候不想要跟着导游后面，想要自己参观。
- 游览景点不想要文字介绍，想要解放眼睛。
####  7.人工智能概率性与用户痛点
优势：
- 准确性高：基于百度海量数据，利用深度学习技术及高精度算法不断迭代模型，准确率业界领先。
- 标签体系丰富：可识别出10万+物体及场景标签，并在不断丰富中，持续提供更精细的识别服务。
- 简单易用：支持标准化接口封装，调用简单，只需上传单张图片，即可获取识别结果。

劣势：
- 直接使用百度图片里面的图片URL时会显示“图片URL无效”，无法进行识别。
- 用户上传照片光线不足、过于模糊时无法识别。
- 用户对某一景点极具体部分进行照片而无全貌时图片识别失败。
####  8.需求列表与人工智能API加值
| 用户想要知道景点在哪里  | 通用物体和场景识别|
  | --------   | -----:   | 
| 用户对语音播放景点内容有需求  | 语音合成|  

### 二、原型
####  1.产品原型
([点击此处查看完整原型链接](http://seventeen1223.gitee.io/scene))

首页界面设计

![首页](https://upload-images.jianshu.io/upload_images/9404387-89b2abdf255971f7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


上传照片界面设计

![上传照片](https://upload-images.jianshu.io/upload_images/9404387-181b4f0663fc2455.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


识别结果界面设计

![识别结果](https://upload-images.jianshu.io/upload_images/9404387-4fb16d709731417b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

识别失败界面设计

![识别失败](https://upload-images.jianshu.io/upload_images/9404387-9f7c5276a32fb1b2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

识别历史界面设计

![识别历史](https://upload-images.jianshu.io/upload_images/9404387-cd073d4bdc883723.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

识别详情界面设计

![识别详情](https://upload-images.jianshu.io/upload_images/9404387-6f3b6b7414d1773a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


语音播报界面设计

![语音播报](https://upload-images.jianshu.io/upload_images/9404387-d005f9cdf6c4bf6b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

我的界面设计

![我的](https://upload-images.jianshu.io/upload_images/9404387-086f48f8220344d4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

####  2.产品架构图

![产品架构图](https://upload-images.jianshu.io/upload_images/9404387-28a7f4cb898b45a8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

####  3.产品功能结构图

![产品功能结构图](https://upload-images.jianshu.io/upload_images/9404387-8261609a9b061c01.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

####  4.产品信息结构图
![产品信息结构图](https://upload-images.jianshu.io/upload_images/9404387-40bc0e6bfa51ff28.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

####  5.产品流程图
![产品流程图](https://upload-images.jianshu.io/upload_images/9404387-10bc041e2730e730.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)




### 三、API 产品使用关键AI或机器学习之API的输出入展示
#### 1.使用水平
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

# encoding:utf-8

import requests
import base64

'''
通用物体和场景识别
'''

request_url = "https://aip.baidubce.com/rest/2.0/image-classify/v2/advanced_general"
# 二进制方式打开图片文件
f = open('C:/Users/ASUS/Desktop/museum.jpg', 'rb')
img = base64.b64encode(f.read())

params = {"image":img}
access_token = '24.805ba36f70a4d0e6d743401eb732d35c.2592000.1579537426.282335-18081781'
request_url = request_url + "?access_token=" + access_token
headers = {'content-type': 'application/x-www-form-urlencoded'}
response = requests.post(request_url, data=params, headers=headers)
if response:
    print (response.json())
```
- 输出代码示例:
```
{'log_id': 4366321357176858870, 
'result_num': 5, 
'result': [{'score': 0.462137, 'root': '自然风景-天空',
 'keyword': '天空'}, 
{'score': 0.335543, 'root': '建筑-传统建筑', 
'keyword': '宫殿'},
 {'score': 0.218333,
 'root': '非自然图像-彩色动漫', 'keyword': '卡通动漫人物'}, 
{'score': 0.114476, 'root': '建筑-传统建筑',
 'keyword': '城楼'}, 
{'score': 0.011721, 'root': '商品-绘画', 'keyword': '图画'}]}

```
（2）语音合成（使用百度API）
- 接口描述：基于该接口，开发者可以轻松的获取语音合成能力
- 接口地址:[百度语音技术之语音合成](https://ai.baidu.com/ai-doc/SPEECH/7k38y8ier)
- 输入代码示例
```
# coding=utf-8
import sys
import json

import os

import time

IS_PY3 = sys.version_info.major == 3
if IS_PY3:
    from urllib.request import urlopen
    from urllib.request import Request
    from urllib.error import URLError
    from urllib.parse import urlencode
    from urllib.parse import quote_plus
# else:
#     import urllib2
#     from urllib import quote_plus
#     from urllib2 import urlopen
#     from urllib2 import Request
#     from urllib2 import URLError
#     from urllib import urlencode

class DemoError(Exception):
    pass

class VoiceMerge():
    def __init__(self, apiKey='4mI1KB7u0CaCtR73Pd89DGbA', secretKey='S0cujdLjCZomNYkM0Pbp81FogAG9UoyO'):
        self.API_KEY = apiKey
        self.SECRET_KEY = secretKey

    def voiceMerge(self, text='', outFilePath='', per=1, spd=5, pit=5, vol=5, aue=3, cuid='', scope='audio_tts_post'):
        '''
        :param text: 需要转换为语音的文本内容
        :param outFilePath: 输出文件路径
        :param per: 发音人，0-普通女声，1-普通男生，3-情感合成-度逍遥，4-情感合成-度丫丫，默认为 0.
        :param spd: 语速，取值0-15，默认为5中语速
        :param pit: 音调，取值0-15，默认为5中语调
        :param vol: 音量，取值0-9，默认为5中音量
        :param aue: 下载的文件格式, 3 - mp3(default)，4 - pcm-16k，5 - pcm-8k，6 - wav
        :param cuid: 用户唯一标识，用来区分用户，填写机器 MAC 地址或 IMEI 码，长度为60以内
        :param scope: 有此scope表示有tts能力，没有请在网页里勾选
        :return:
            注意文件名称与 aue 要相匹配
        '''
        TTS_URL = 'http://tsn.baidu.com/text2audio'
        FORMATS = {3: "mp3", 4: "pcm", 5: "pcm", 6: "wav"}
        format = FORMATS[aue]

        cuid = str(cuid) if cuid else f"{int(time.time()*1000)}"


        token = self.getToken(scope)
        tex = quote_plus(text)  # 此处 text 需要两次 urlencode
        print(tex)
        params = {'tok': token, 'tex': tex, 'per': per, 'spd': spd, 'pit': pit, 'vol': vol, 'aue': aue, 'cuid': cuid,
                  'lan': 'zh', 'ctp': 1}  # lan ctp 固定参数

        data = urlencode(params)
        print('test on Web Browser' + TTS_URL + '?' + data)

        req = Request(TTS_URL, data.encode('utf-8'))
        has_error = False
        try:
            f = urlopen(req)
            result_str = f.read()

            headers = dict((name.lower(), value) for name, value in f.headers.items())

            has_error = ('content-type' not in headers.keys() or headers['content-type'].find('audio/') < 0)
        except  URLError as err:
            print('asr http response http code : ' + str(err.code))
            result_str = err.read()
            has_error = True

        # save_file = "error.txt" if has_error else f'result_{per}_{spd}.' + format
        flt = outFilePath.split('.')
        save_file = f"{flt[0]}_error.txt" if has_error else f'{outFilePath}'
        with open(save_file, 'wb') as of:
            of.write(result_str)

        if has_error:
            if (IS_PY3):
                result_str = str(result_str, 'utf-8')
            print("tts api  error:" + result_str)

        print("result saved as :" + save_file)


    def getToken(self, scope):
        TOKEN_URL = 'http://openapi.baidu.com/oauth/2.0/token'
        print("fetch token begin")
        params = {'grant_type': 'client_credentials',
                  'client_id': self.API_KEY,
                  'client_secret': self.SECRET_KEY}
        post_data = urlencode(params)
        if (IS_PY3):
            post_data = post_data.encode('utf-8')
        req = Request(TOKEN_URL, post_data)
        try:
            f = urlopen(req, timeout=5)
            result_str = f.read()
        except URLError as err:
            print('token http response http code : ' + str(err.code))
            result_str = err.read()
        if (IS_PY3):
            result_str = result_str.decode()

        print(result_str)
        result = json.loads(result_str)
        print(result)
        if ('access_token' in result.keys() and 'scope' in result.keys()):
            if not scope in result['scope'].split(' '):
                raise DemoError('scope is not correct')
            print('SUCCESS WITH TOKEN: %s ; EXPIRES IN SECONDS: %s' % (result['access_token'], result['expires_in']))
            return result['access_token']
        else:
            raise DemoError('MAYBE API_KEY or SECRET_KEY not correct: access_token or scope not found in token response')



if __name__ == '__main__':
    text = "沈阳故宫博物院欢迎您"
    rpath = os.getcwd()
    outFilePath = os.path.join( 'test3.mp3')
    vm = VoiceMerge()
    vm.voiceMerge(text=text, outFilePath=outFilePath)
```
- 输出代码示例
```
fetch token begin
{"access_token":"24.5d0b729702b768bb91ad33f3c470939f.2592000.1579539688.282335-17537140","session_key":"9mzdDtaDwbOhk2UNyNCEW57DKKwcVYJqciD7HjBHMcj4ykLsMPZcoNrqcYRkoKeB75wgwgyDYDvgvwJ4x1VGjTa9yeWlew==","scope":"audio_voice_assistant_get brain_enhanced_asr audio_tts_post public brain_all_scope picchain_test_picchain_api_scope wise_adapt lebo_resource_base lightservice_public hetu_basic lightcms_map_poi kaidian_kaidian ApsMisTest_Test\u6743\u9650 vis-classify_flower lpq_\u5f00\u653e cop_helloScope ApsMis_fangdi_permission smartapp_snsapi_base iop_autocar oauth_tp_app smartapp_smart_game_openapi oauth_sessionkey smartapp_swanid_verify smartapp_opensource_openapi smartapp_opensource_recapi fake_face_detect_\u5f00\u653eScope vis-ocr_\u865a\u62df\u4eba\u7269\u52a9\u7406 idl-video_\u865a\u62df\u4eba\u7269\u52a9\u7406","refresh_token":"25.bae875974408855b0982af03fcd9cb19.315360000.1892307688.282335-17537140","session_secret":"fc2c8b306d6d0cfdfbbabccf5abccc4d","expires_in":2592000}

{'access_token': '24.5d0b729702b768bb91ad33f3c470939f.2592000.1579539688.282335-17537140', 'session_key': '9mzdDtaDwbOhk2UNyNCEW57DKKwcVYJqciD7HjBHMcj4ykLsMPZcoNrqcYRkoKeB75wgwgyDYDvgvwJ4x1VGjTa9yeWlew==', 'scope': 'audio_voice_assistant_get brain_enhanced_asr audio_tts_post public brain_all_scope picchain_test_picchain_api_scope wise_adapt lebo_resource_base lightservice_public hetu_basic lightcms_map_poi kaidian_kaidian ApsMisTest_Test权限 vis-classify_flower lpq_开放 cop_helloScope ApsMis_fangdi_permission smartapp_snsapi_base iop_autocar oauth_tp_app smartapp_smart_game_openapi oauth_sessionkey smartapp_swanid_verify smartapp_opensource_openapi smartapp_opensource_recapi fake_face_detect_开放Scope vis-ocr_虚拟人物助理 idl-video_虚拟人物助理', 'refresh_token': '25.bae875974408855b0982af03fcd9cb19.315360000.1892307688.282335-17537140', 'session_secret': 'fc2c8b306d6d0cfdfbbabccf5abccc4d', 'expires_in': 2592000}
SUCCESS WITH TOKEN: 24.5d0b729702b768bb91ad33f3c470939f.2592000.1579539688.282335-17537140 ; EXPIRES IN SECONDS: 2592000
%E6%B2%88%E9%98%B3%E6%95%85%E5%AE%AB%E5%8D%9A%E7%89%A9%E9%99%A2%E6%AC%A2%E8%BF%8E%E6%82%A8
test on Web Browserhttp://tsn.baidu.com/text2audio?tok=24.5d0b729702b768bb91ad33f3c470939f.2592000.1579539688.282335-17537140&tex=%25E6%25B2%2588%25E9%2598%25B3%25E6%2595%2585%25E5%25AE%25AB%25E5%258D%259A%25E7%2589%25A9%25E9%2599%25A2%25E6%25AC%25A2%25E8%25BF%258E%25E6%2582%25A8&per=1&spd=5&pit=5&vol=5&aue=3&cuid=1576947687661&lan=zh&ctp=1
result saved as :test3.mp3
```
#### 2.使用比较分析 

![腾讯图片识别之场景识别](https://upload-images.jianshu.io/upload_images/9404387-ef71c16e29b8c86a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![百度图像识别之通用物体和场景识别](https://upload-images.jianshu.io/upload_images/9404387-39fff801cbc236bd.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###### （1）百度与腾讯AI的输出结果比较
百度通用物体和场景识别能够高精确度识别出景点名称并将其进行归类，输出结果附上文本信息，输出数据结果和腾讯的api对比更加精准，容许图片的模糊度较腾讯的场景识别高，识别图像能力也更强。

![腾讯场景识别调用次数](https://upload-images.jianshu.io/upload_images/9404387-6256b28fe6713185.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![百度场景识别调用额度](https://upload-images.jianshu.io/upload_images/9404387-baf3ca60e29ac2e6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###### （2）百度与腾讯AI的调用额度比较
百度图像识别下各个能力都具有免费调用额度，通用物体和场景识别每日的免费调用额度为500次；而腾讯的场景识别对不同用户有调用次数的不同划分，不同用户单接口的QPS（每秒请求次数）上限不同，如需更多还需自行联系QQ客服进行反馈。据此，较为推荐百度的场景识别。

#### 3.使用后风险报告 

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

#### 4. 容错性
- 通用物体和场景识别，用户可以编辑识别图片，进行修改。
- 语音合成，用户也可以编辑识别文字，进行修改。

