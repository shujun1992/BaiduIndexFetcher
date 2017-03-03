# BaiduIndexFetcher
##使用说明：
1. BaiduIndexFetcher依赖的包包括：numpy, scipy, pillow, selenium, opencv-python，可用如下命令安装：pip3 install 包名  
建议安装前先更新pip：  
`pip3 install --upgrade pip`
2. [下载安装ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/)，并将ChromeDriver所在路径添加到环境变量
3. 打开项目文件夹，在resource目录下找到account.txt文件，输入百度账号的用户名，回车后输入密码
4. 运行test目录下的baiduindex.py，并按提示操作  

注意：
- 程序运行中途在登录界面需要手动输入验证码
- 输入查询关键字后，程序将自动获取指数，此过程中切勿移动鼠标
