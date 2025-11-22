# 字体替换脚本问题说明
由于部分网页的 Shadow DOM 和 Content Security Policy（CSP）限制，如果想要字体生效就必须进行如下操作：
- **方式 1**：在**本地同步安装对应语种与字重的字体**，若问题仍未解决可尝试在浏览器的设置中**将``默认字体``设为想要替换的字体**再试。
  - 尽量安装完整的语种和字重，效果最好；
  - 如果不在乎各语种间的写法以及显示差异，也不在乎粗细的话只安装 ``Regular`` 常规体即可。
- **方式 2**：在篡改猴拓展中的 ``设置`` 处进行如下配置：
![config](/files/Snipaste_2025-11-23_00-13-26.png)

# 配套资源下载
- MiSans：[官方直链下载](https://hyperos.mi.com/font-download/MiSans_Global_ALL.zip)，[OneDrive 网盘下载](https://ztach-my.sharepoint.com/:u:/g/personal/fishp_fishp666_onmicrosoft_com/EckleGMCaSlAjMgSZo-HEIYBSkNGYbTHLHuWOB516Lq8DA?e=rKIBRe)
