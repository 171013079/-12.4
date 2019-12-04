# -12.4
发布名称|发布时间|发布人
---|:--:|---:
毕业相册设计|2019.11.21|吴惠怡
<br> 

 #### 第一部分
<br> 
#####一、价值设计 
**市场调查**：经过对市面上一些现有的毕业相册类或是回忆类产品调查研究发现，这些产品大都是起到一个整合毕业相片，以此做成毕业电子相册的形式。其一并不系统，没有整合成一个可以自主使用的产品；其二，没有附加价值，只是单纯的照片幻片灯形式；其三，调查中也没有发现有组织正使用着类似产品。从上可知，市场目前没有此类产品的出现与使用，我认为此类市场是还没有被发掘的，我们目前的产品开发正好填补了这个空缺。且随着现在api技术的成熟，模块化使用的范围越来越广，我们调用api来整合、完成产品是可行并由市场价值的。
<br>
**目前我们的设想是**：1.调用语音识别（需查证）api，收录并且可以语言翻译每位登陆使用者的毕业赠言及其他想要留言的话。2.调用人脸识别api，通过摄像头对人脸信息的采集进行信息的记录，可以通过照片查找与其的共同合照，以及找到自己班级等更多利用人脸识别可以完成的人像查找。3. 地图，调用地图api。①在开启实时定位权限，可以在地图上不同地点进行打卡，上传自己的照片。②其中，照片可以公开或是选择隐藏，公开时可以点赞留言，带有一定的社交功能。③，认识的人可以开启共享定位，分享自己的位置，寻找最佳的聚会地点。


#####二、价值主张/最小可行性产品
完成语音识别和地图api调用①与②的功能设计。使用户可以完成基本的毕业相册的留念以及设计需求。

#####三、背景
目前市面上的暂无此类产品，而庞大的毕业生人群有此类留念与聚会安排需求。

#####四、目的
做一个能够符合毕业生留念需求的小程序/app
#####五、目标
**前期目标：**
1.导入地图实现定位功能，让用户可以打卡及上传照片。
2.调用语音识别api，让用户可以录入留言
3.调用人脸api，用户用摄像头或者上传照片识别毕业生，寻找与其合照且公开的照片
**后期目标（加值）：**
地点定位，事人们可以通过彼此的位置寻找最合适的聚会地方。
#####六、用户
应届毕业生 往届毕业生 在读大学生
#####七、用户痛点
1.毕业后用于纪念/留念
2.毕业时想要留言，社交
2.毕业后聚会找不到合适的地点
#####八、1.用户需求
用户案例|对应标题|重要程度
---|:--:|---:
用户想要在校园打卡，上传照片|校园打卡|重要
用户想要留言毕业祝福|留言祝福|重要:
用户想要寻找与朋友的合照|照片识别|重要
用户想要定位，寻找聚会地点|聚会推荐|次重要:

2.具体场景分析
①小一在毕业时，想要在图书馆门前拍照留念，并且想和大家分享。
②小二在毕业过后感觉非常想念他的同学们，听听大家的声音并且想要给同学毕业祝福。
③小三在毕业典礼上拍摄了许多照片，他想要公开照片并且能够快速找到与她某个朋友的所有合照
④毕业过后到了校庆，同学们组织着想要聚会，但是同学们天南地北找不到合适的地点。
