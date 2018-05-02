# 博客园
[个人博客园](http://www.cnblogs.com/guotianbao/) 
# Windows7下安装运行  
把ackblog文件下载下来  
1. 打开cmd窗口输入：pip install virtualenv 创建虚拟环境（前提是你已经安装好pip）  
2. 桌面新建一个名为Test的文件夹,进入该文件夹Shift+鼠标右键打开cmd输入：virtualenv testenv  
3. Test的文件夹内生成了testenv文件夹，进入testenv文件夹的Scripts文件夹中，Shift+鼠标右键打开cmd输入：activate激活虚拟环境  
4. 把下载的ackblog文件夹拖入Scripts文件夹中，在cmd中进入ackblog文件夹：cd ackblog  
5. requirements.txt所在ackblog文件夹内，在cmd输入：pip install -r requirements.txt 回车    
6. 安装完所有的环境依赖后，在cmd中再输入：python manage.py runserver  
7. 不要关闭cmd窗口，去浏览器打开：127.0.0.1:8000 看看是否可以访问。
# 功能
1. 支持Markdown语法发表文章  
2. 游客评论  
3. 分页  
4. RSS订阅  
5. 最热文章、标签云  
