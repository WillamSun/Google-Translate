# 谷歌翻译生草机介绍：

:monkey_face::monkey_face::monkey_face:  
***
## 原作者：  
<a title="bilibili" target="_blank" href="https://space.bilibili.com/551409211"><img src="https://img.shields.io/badge/dynamic/json?color=353940&labelColor=f27596&label=Bilibili&suffix=%20followers&query=%24.data.totalSubs&url=https%3A%2F%2Fapi.spencerwoo.com%2Fsubstats%2F%3Fsource%3Dbilibili%26queryKey%3D551409211&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGAAAABgCAYAAADimHc4AAAD7ElEQVR4nO2dW9WrMBCFK6ESkFAJSKiESqgEHCABCZWAhEpAAhL2ecik5dDc/pXLBDLfWnlqy0xmJ5BMQnq5CIIgCIIgCIIgCIIgCEIBAHQAemYfrgCunD6wAKAHsEKxALgx+bCQD8/S9tmgVqeDr1lLigDgZvDhXso+K9TyTBQRwRJ8AHjntl0Flh5QRAQK/mKxPeayWx2OXpBNBKiHvi34b7T2MC4pAvW6twR/RwkRKPizBN8CgEcuESj4Lwm+BwBjahEk+H8EwJRKhOaCDzW8e1JLfkUUH1NgmR3XmHffHR1l+72BSs8d7w8U+JDAnZERQMcV+CtUi7dNqFqibB4J7vtrq7xKCuAasbTMXCL4T+5aVk6+2xHUrWdhruAR6HIJcOeu2UHI8zyAe2ytWfEdWz9PVvQ8YAmIQ5dDAB9LFsMVAv8oMO2zAGrC5WNIarRiAuKR9jYEd9pY08aa6uUzIHGRdkgKd8pY0yc1WjEBAqypDYoAG0QAZkQAZkQAZkQAZk4vANQenjsSzS3I/wcSbXU5jQBUkRtdf4Rar90v8kSv3+I3ffCCSpk8I/w+lgDkdI/v2rEp2CaiWm1AsDQLlDAD+dlFXLMeAaCSeLZdaSFE5VUQNot38cKuEeBgAsSuG0flVZBmEanbXfNQAsS0fgBYIn2fIu3/BBMHEyBmDXlFfA8IzeHb+Ems4WAChKykrVA9ZfsQTL57jXzRg4A5wC/A8N4ADiZAZwm2XjW75Qh2KOTfA0p4kygPw28OJcCVgn3nDnYo2EwEYRgGH0qAMyICMCMCMCMCMCMCMCMCMCMCfP3qwHDOQ4AAUekTk8FaBRihJnZdYbvtCGC7LvmkM63GjVDINPFrQgCq5ETXfmMzI90FXzPvfqt7x4rEu/ZaEcCUxFvgz2zO+BUn6UkoaEEAsptiMSX5e8FoRYCN7cVgb4Vq7U/H50Pq4JNP7Qiw8UFnJwcK+tXy+Wj6PLEvPgHSHv5UgwA1IQIwwyFAyLJin9RoxYgAzAQIkPwNmf26busC+OIx5TDqo5nDT+F/SS/9CYzwb+No49zNy2evkYv0LywGGAXUvp6eSneycqOic0w20k7CNgKE7jJunSGLACTCxF27ylmQc98T5MQUH49swd+I0HPXslLKnT0N+wnkrTKi9JZL/L9i1SorMmdeQ4TQQ7OFMxIMzGD45w8nUL1im7efENZLJpgPSw0pfz0cdt4U3230Td/Tvx2R6d2FrHhEWLkq5PELOMsRPHCPnAZGv1xJteL7jbJiaW3sB2nDvPC/osSYvjRQz4cJ6n7KO3rYQL7M+L6nVtfDVRAEQRAEQRAEQRAEIZ5/SAXmdfXaoQsAAAAASUVORK5CYII=&longCache=true" ></a>  
__@MC着火的冰块__，传送门：[空降至Bilibili](https://space.bilibili.com/551409211 "点击空降")
__（已授权搬运）__
***
## 简介：  
> 最近谷歌翻译在网上火了，因为谷歌翻译是机器翻译，所以如果只是翻译一次，大体还是有九成九的准确度的，但是当使用谷歌翻译选择小语种，然后小语种再翻译到另一个小语种，重复翻译多遍后，内容就会疯狂失真，然后准确度也会随着翻译次数开始偏离原来的真正的意思。  
  
__可如果手动翻译效率极低，于是就有了这款自动翻译机__  
本项目是由`Bilibili` ***@MC着火的冰块***用`Python`制做的谷歌自动翻译机，可以自动翻译内容**几十甚至几百遍**~~*（就是翻译太多变会卡）*~~  
***
## 更新日志：
### 2.0：
- 全新的GUI界面，告别控制台，操作更简单
- 优化算法，由逐条翻译换成整体翻译，大幅提高速度
- 从输入文件路径换成直接输入内容，操作更方便
  
### 2.1：
- 更新一键复制，方便快捷，再也不用选中在复制了！

### 2.2:  
- 更新一键粘贴，输入也变得方便起来
- 更新进度条，再也不用干等了，立马知道进度！
- 翻译使用多线程，窗口再也不会未响应了！

### 2.3:
- 翻译时使用随机语言翻译，每次翻译语言顺序不同，结果更生草！
***
## 使用说明：
引用库：`tkinter` `googletrans` `threading` `pyperclip`  
**已将需要安装的库放入*requirements.txt*，批量安装请使用命令行命令：**  
```
pip install -r requirements.txt
```  

### 1.0：  
1. 创建**2**个**文本文档**
2. 在**第一个文本文档**里输入**要翻译的内容**
3. **第二个文本文档留空**
4. **运行程序**
5. 输入**第一个文本文档**的**路径**，*可以是绝对也可以是相对*
6. ***按下Enter***
7. 输入**第二个文本文档**的**路径**，同上，可以是绝对也可以是相对
8. ***按下Enter***
9. 输入**翻译次数**
10. 程序会**加载一会儿**，随后将**翻译结果**放入**第二个文本文档中**
11. **按下Enter**退出
12. 打开**第二个文本文档**就可以看到**翻译结果**了
  
### 2.0：  
1. 运行后会出现窗口，在**上方输入框**中输入**要生草的内容**  
2. 在**中间的输入框**中输入**要翻译的次数**（翻译次数建议**不要超出40**，会卡）  
3. ~~**随后窗口会未响应一会，纯属正常现象！！**~~***（2.2已修复）***  
4. 稍等一会儿在**下方输入框**中会出现**翻译结果**  

*__使用2.0时请勿关闭后方控制台__*
***
## 翻译结果：  
|输入|翻译次数|输出|
|:---|:---:|:---|
|小猪佩奇|30|猪肉页|
|你tm故意找茬是吧|25|您故意发现失败，对吗？|
|我宣布个事，我是个烧饼|15|我宣布的是芝麻蛋糕|
|我是神里绫华的狗|15|我在n中去fs和n，|
|举头望明月，低头思故乡|40|看着混蛋，低下头，想着你的家乡|
