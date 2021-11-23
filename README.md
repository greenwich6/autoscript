# autoscript

## windows端图像识别自动化python脚本

#### 1. 安装python3.4以上版本，并配置环境变量
教程：<https://www.runoob.com/python3/python3-install.html>
#### 2. 安装依赖包
   在cmd中（win+R  输入cmd  回车）输入

    pip install pyperclip
    pip install xlrd
    pip install pyautogui==0.9.50
    pip install opencv-python
    pip install pillow

#### 3. 把每一步要操作的图标、区域截图保存至本文件夹  png格式（注意如果同屏有多个相同图标，回默认找到最左上的一个，因此怎么截图，截多大的区域，是个学问，如输入框只截中间空白部分肯定是不行的，宗旨就是“唯一”）
#### 4. 在cmd.xls 的sheet1 中，配置每一步的指令，如指令类型1234  对应的内容填截图文件名，指令5对应的内容是等待时长（单位秒） 指令6对应的内容是滚轮滚动的距离，正数表示向上滚，负数表示向下滚
#### 5. 保存文件
#### 6. 双击waterRPA.py打开程序，按1表示excel中的指令执行一次，按2表示无限重复执行直到程序关闭
#### 7. 开始程序后请将程序框最小化，不然程序框挡住的区域是无法识别和操作的
#### 8. 如果程序开始后因为你选择了无限重复而鼠标被占用停不下来，alt+F4吧~
#### 9. pyautogui库其他用法 <https://blog.csdn.net/qingfengxd1/article/details/108270159>
