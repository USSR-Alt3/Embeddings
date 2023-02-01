  # 重要事项注意！(Important!)：
 ## 简短声明，幸运点进来的人最好看一下：
  
 1. 私炉古法炼丹，现在正在整LoRa，主要供AI绘画同好以及群友交流使用，应该...大概持续更新？
    本人企鹅号2481436585，如非交流炼丹经验请勿骚扰。
    
 2. 注意文件大小，在本仓库内KB级pt文件均为EMB模型，MB级safetensors文件均为LoRa模型，使用方式有所区别。

 3. EMB模型的使用：

    放入`...\stable-diffusion-webui\Embeddings`目录下，使用`XXX.pt`模型时对应的要输入的提示词就是`XXX`。

 4. LoRa模型的使用：

    首先，确定自己的Webui为最新的2023稳定版本。

    然后，在“扩展”页面中安装`sd-webui-additional-networks`,或在`...\stable-diffusion-webui\Embeddings\extensions`目录下执行以下命令进行安装：

     `git clone https://github.com/kohya-ss/sd-webui-additional-networks.git`

    之后，将下载的LoRa模型放入`.\stable-diffusion-webui\extensions\sd-webui-additional-networks\models\lora`下。

    使用`XXX~xxx.safetensors`模型时,确保正确安装上述扩展打开Webui，在`Additional Networks`中选择需要使用的模型，并调整权重，且务必记得勾选`Enable`，输入模型对应文件名中`xxx`作为提示词可增强角色还原度。

 5. 如需用于发表的作品，请于简介附上本工程链接。
   
 6. 所有文件禁止转载！更不能无耻地偷去赚小白的米！
 
 7. 没了，谁想到能叠的甲联系我一下。
   
 ## A terse statement,for those lucky to come to this project：
   
 1. Anime and game characters‘ embeddings and LoRas developed by USSR,are used for AI painting and communicating in our group.I'll contine updating this project in idle time,maybe?

 2. Take care to the size of files.In this responsibility,`XXX.pt` means this file an Embedding model,and `XXX~xxx.safetensors` means a LoRa model.
 
 3. How to use Embeddings:

     Put Embedding models like `XXX.pt` into folder `...\stable-diffusion-webui\Embeddings`,when using,input `XXX` to use `XXX.pt`.

 4. How to use LoRas:

    First,make sure your Webui is the latest stable version of 2023.

    Then,open the page `Extensions` to install the extension `sd-webui-additional-networks`.

    Next,put LoRa models like `XXX~xxx.safetensors` into folder `.\stable-diffusion-webui\extensions\sd-webui-additional-networks\models\lora`.

    At last,make sure you correctly install the extension,so that you can enable models at `Additional Networks`,and you can input `xxx` in the corresponding model name `XXX~xxx.safetensors`,to enhance the characters' similarity.
   
 5. If you wanna use these files to publish artwork on webs like Pixiv or Twitter,please indicating this project's link.
   
 6. All files of this project are forbidden to be reproduced!Also can't be used for profit or defrauded those new guys!

  # 懒人下载(Download directly):
  
 ## `git clone https://github.com/USSR-Alt3/Embeddings.git`

  # 更新日志(Update)：
 <details>
 - <summary>2023/2/1</summary>
   + 更新 游戏王-芙莉西亚之虫惑魔(YGO-OCG-Traptrix Rafflesia)
   + 上传 游戏王-阿蒂普丝之虫惑魔(YGO-OCG-Traptrix Atypus)
   + 上传 游戏王-阿洛美勒丝之虫惑魔(YGO-OCG-Traptrix Allomerus)
   + 上传 游戏王-阿特拉之虫惑魔(YGO-OCG-Traptrix Atrax)
   + 上传 游戏王-蒂奥之虫惑魔(YGO-OCG-Traptrix Dionaea)
   + 上传 游戏王-基诺之虫惑魔(YGO-OCG-Traptrix Arachnocampa)
   + 上传 游戏王-库拉莉亚之虫惑魔(YGO-OCG-Traptrix Cularia)
   + 上传 游戏王-兰卡之虫惑魔(YGO-OCG-Traptrix Mantis)
   + 上传 游戏王-莉塞之虫惑魔(YGO-OCG-Traptrix  Genlisea)
   + 上传 游戏王-普蒂卡之虫惑魔(YGO-OCG-Traptrix Pudica)
   + 上传 游戏王-塞拉之虫惑魔(YGO-OCG-Traptrix Sera)
   + 上传 游戏王-特莱恩之虫惑魔(YGO-OCG-Traptrix Myrmeleo)
   + 上传 游戏王-西托莉丝之虫惑魔(YGO-OCG-Traptrix Pinguicula)
 </details>
 - 2023-1-23
   + 上传 游戏王-吉娜之虫惑魔(YGO-OCG-Traptrix Vesiculo)
 - 2023-1-22
   + 上传 游戏王-芙莉西亚之虫惑魔(YGO-OCG-Traptrix Rafflesia)
 - 2023-1-21
   + 上传 明日方舟-星熊(Arknights-Hoshiguma)
   + 上传 明日方舟-星熊(Arknights-Hoshiguma-TempestSeries)
 - 2023-1-20
   + 上传 明日方舟-夜莺(Arknights-Nightingale)
   + 上传 明日方舟-夜莺-挽歌(Arknights-Nightingale-WitchFeast)
 - 2023-1-19
   + 上传 明日方舟-闪灵(Arknights-Shining)
   + 上传 明日方舟-闪灵-静谧午夜(Arknights-Shining-CoralCoast)
 - 2023-1-18
   + 上传 明日方舟-安洁莉娜-质素访客(Arknights-Angelina-Bloodline of Combat)
   + 上传 明日方舟-安洁莉娜-夏卉(Arknights-Angelina-CoralCoast)
 - 2023-1-17
   + 上传 明日方舟-能天使(Arknights-Exusiai)
   + 上传 明日方舟-推进之王(Arknights-Siege)
   + 上传 明日方舟-伊芙利特(Arknights-Ifrit)
   + 上传 明日方舟-伊芙利特-日晒(Arknights-Ifrit-CoralCoast)
   + 上传 明日方舟-艾雅法拉(Arknights-Eyjafjalla)
   + 上传 明日方舟-艾雅法拉-夏卉(Arknights-Eyjafjalla-CoralCoast)
   + 上传 明日方舟-安洁莉娜(Arknights-Angelina)
   + 上传 游戏王-魔女术名匠·玻璃女巫(YGO-OCG-Witchcrafter Madame Verre)
   + 上传 游戏王-白银城的拉比林斯(YGO-OCG-Labrynth of the silver castle)
   + 上传 碧蓝航线-奥古斯都(AzurLune-August)
   + 上传 碧蓝航线-奥古斯都-女仆魔女(AzurLune-August-MaidWitch)
 
  # 以下是预览图(Preview)：
 
 <details>
 <summary>明日方舟(Arknights)</summary>

 <details>
 <summary>六星干员(Rare 6)</summary>

 <details>
 <summary>能天使(Exusiai)</summary>  

 ![]()
 </details>

 <details>
 <summary>推进之王(Siege)</summary> 
 
 ![]()
 </details>

 <details>
 <summary>伊芙利特+伊芙利特-日晒(Ifrit)</summary>  

 ![]()
 ![]()
 </details>

 <details>
 <summary>艾雅法拉+艾雅法拉-夏卉(Eyjafjalla)</summary>

 ![]()
 ![]()
 </details>

 <details>
 <summary>安洁莉娜+安洁莉娜-质素访客+安洁莉娜-夏卉(Angelina)</summary>   

 ![]()
 ![]()
 ![]()
 </details>

 <details>
 <summary>闪灵+闪灵-静谧午夜(Shining)</summary>

 ![]()
 ![]()
 </details> 

 <details>
 <summary>夜莺+夜莺-挽歌(Nightingale)</summary> 

 ![]()
 ![]()
 </details>

 <details>
 <summary>星熊+星熊-狩标浪人(Hoshiguma)</summary> 

 ![]()
 ![]()
 </details>

 </details>

 </details>


 <details>
 <summary>游戏王(YGO-OCG)</summary>
 
 <details>
 <summary>白银城的拉比林斯(Labrynth of the Silver Castle)</summary>
    
 ![]()
 </details>
 
 <details>
 <summary>虫惑魔(Traptrix)</summary>

 <details>
 <summary>游戏王-芙莉西亚之虫惑魔(Traptrix Rafflesia)</summary>
    
 ![]()
 </details>

<details>
 <summary>游戏王-吉娜之虫惑魔(Traptrix Vesiculo)</summary>
    
 ![]()
 </details>

 </details>

 <details>
 <summary>魔女术名匠·玻璃女巫(Witchcrafter Madame Verre)</summary>
    
 ![]()
 </details>
 
 </details>
 

 <details>
 <summary>碧蓝航线(AzurLune)</summary>
 
 <details>
 <summary>奥古斯都+奥古斯都-女仆魔女(August)</summary>
 
 ![]()
 ![]()
 </details>
 
 </details>
