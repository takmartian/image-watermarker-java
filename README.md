# 工具包描述

## imageutil
添加图片水印的工具包

## fileutil
- 添加数字水印的工具包
- 在文件尾加入数字水印
- 数字水印内容会经过对称加密才写入文件

## graphyutil
- 添加图片隐写的工具包
- 隐写内容不加密
- 隐写术介绍文档参考：https://blog.csdn.net/l8947943/article/details/127088875

# 工具包使用
运行package里的main，有图形界面
### 图片水印：
1. 选择图片
2. 选择填写水印内容
3. 设置水印大小透明度等
4. 生成水印图片
### 文件数字水印：
1. 选择文件
2. 填写数字水印内容
3. 输入加密密码
4. 生成水印文件
### 图片隐写：
1. 选择图片
2. 选择填写隐写内容
3. 生成隐写图片

# 使用顺序注意
由于文件数字水印是在文件尾写入数据，所以文件数字水印生成后，再进行图片水印或者图片隐写，会导致文件水印失效
