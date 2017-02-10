# buptskills#
作者：
https://github.com/Forec/scripts-for-bupt/tree/master/get-your-gpa
环境配置：用pip安装：BeautifulSoup、pytesseract
         安装PIL：官网下载安装程序或者用pip安装pillow代替PIL
         tesseract-ocr：下载安装程序（注意安装时候选择添加path，安装路径尽量不要改变）

BUG：
1.因tesseract-ocr导致的WindowsError:[Error2]的解决方案：
https://github.com/madmaze/pytesseract/issues/18
2.中文文字乱码或者无法正确print：注意编码类型，程序中默认使用的是GBK编码
