# Google浏览器翻译插件(扩展程序)
>支持多种语言翻译  
>可收藏翻译结果, 翻译结果可以导入导出  

翻译1.0版使用翻译前的字符作为localstorage的key, 翻译后的字符作为localstorage的value
`localStorage.setItem(input.value, output.value)`

翻译版2.0使用数组保存单词列表, 数组中包含对象  
对象的k属性为翻译前的字符, 对象的v属性为翻译后的字符 

数据格式:
```json
[
    {
        "k": "name",
        "v": "n. 名称，名字；姓名；名誉\nvt. 命名，任命；指定；\nadj. 姓名的；据以取名的",
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
