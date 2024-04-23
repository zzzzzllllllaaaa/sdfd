---
{"dg-publish":true,"permalink":"/multitts1.1.9/","noteIcon":""}
---


[[tts\|tts]]，[[t2s\|t2s]]，[[multitts1.3.2\|multitts1.3.2]]，[[常用机器人下面的还没整理\|常用机器人下面的还没整理]]

#tts #作者 #multitts #3zh #资源

简介::超级棒！上班累死累活，全靠听书续命。这个版本的简单清晰。

[软件备份1.1.9](https://wwp.lanzoup.com/iV8100vq9eja)，提取码 : 3qw2
[vioce.zip](https://www.123pan.com/s/P8mKVv-kDUaH.html)， 里面包含发音人。（导入慢可以自己自己解压移动到voice文件夹）
### 增加新引擎（适用1.1.9版本）
新引擎每个发音人需要两个文件，在xxxxxvoicedata目录（百度导航语音下载）的子目录下提取。
1. 一般将体积最大的那个文件（文件名由数字和-组成）命名为xxx.voc.dat。
2. 次大的（文件名由纯数字组成）命名为xxx.res.dat。（注：如果只有一个文件的话，就命名为xxx.voc.dat）
3. 然后把更改的文件移至acoustic目录下。（/org.nobody.multitts/files/voice/bdetts/90013/acoustic/）
4. 最后在config.yaml文件中加上声音的配置，你模仿其他地图声音的格式写就行了

格式：
```
- avatar: null（放图片）
  code: zuobaozi（改的名字的xxx）
  desc: zuobaozi（右边的显示什么女声啥的）
  gender: 0
  name: 猪宝子（显示的声音名字）
  param: 90013（不改）,com.baidu.BaiduMap,
  sampleRate: 24000
  speed: 1.2
  type: 0
  volume: 1.0
```
