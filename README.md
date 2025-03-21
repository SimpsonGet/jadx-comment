

## 介绍

使用jadx时，对代码添加注释不实时显示

使用 **JLabel** 在原提示框基础上显示输入内容


![image-20250321204246857](https://github.com/user-attachments/assets/89c1ce74-5304-4b39-bd84-71a572559fff)

![image-20250321202452708](https://github.com/user-attachments/assets/e0570466-34d4-4ffa-a253-a63dff257bd7)


## 构建

### 1、源码构建

下载**CommentDialog.java**替换到**jadx-master\jadx-gui\src\main\java\jadx\gui\ui\dialog**下，重新编译jadx

```shell
git clone https://github.com/skylot/jadx.git
cd jadx
./gradlew dist
```

```shell
#windows
build/jadx/bin/jadx-gui.bat

#linux
./jadx-gui
```



### 2、release下载

直接运行build/jadx/bin/**jadx-gui.bat**
