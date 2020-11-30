# Google浏览器翻译插件(扩展程序)
>支持多种语言翻译  
>可收藏翻译结果, 翻译结果可以导入导出  
>可播放翻译前的语音

翻译1.0版使用翻译前的字符作为localstorage的key, 翻译后的字符作为localstorage的value
`localStorage.setItem(input.value, output.value)`

翻译版2.0使用数组保存单词列表, 数组中包含对象  
对象的k属性为翻译前的字符, 对象的v属性为翻译后的字符 
speakUrl属性为翻译前的发音url地址

数据格式:
```json
[
    {
        "k": "document",
        "v": "n. 文件，公文；[计] 文档；证件\nvt. 记录，记载",
        "speakUrl": "http://openapi.youdao.com/ttsapi?q=document&langType=en&sign=8049C3D33725F4BC304B54F097359A6E&salt=1606716826274&voice=4&format=mp4&appKey=2423360539ba5632&ttsVoiceStrict=false"
    }
]
```

代码只给出了2.0版本  

如何在Google Chrome里使用该插件请参考: https://www.cnblogs.com/zp106/p/12700114.html

程序截图:  
[1](./程序截图/1.png)
[2](./程序截图/2.png)
[3](./程序截图/3.png)
[4](./程序截图/4.png)
