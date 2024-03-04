#自动获取酒店源#

使用方法：

1.电视亭

  在看电视直播软件中直接输入以下任一地址即可：
  
      https://ghproxy.net/https://raw.githubusercontent.com//zdwj3674/123/main/itvlist.txt
      https://raw.githubusercontent.com//zdwj3674/123/main/itvlist.txt
  
2.想自己获取电视直播地址的可采用以下方法：

  windows电脑：
  
      1.1 电脑安装最新的chrome，同时执行文件目录下健对应版本的chromedriver.exe，
      1.2 下载windows目录下的itv.exe及itvtest.exe,
      1.3 首先运行itv.exe，完成后再运行itvtest.exe，
      1.4 运行完成后在当前目录下生成电视直播文件itvlist.txt。
  
  已安装python的电脑：
  
      2.1 电脑安装chrome，下载对应版本的chromedriver
      2.2 下载itv.py cctv.py weishi.py qita.py
      2.3 pip install selenium 请求 futures eventlet
      2.4 依次运行itv.py cctv.py weishi.py qita.py
      2.5 运行完成后在当前目录下生成电视直播文件itvlist.txt。
      
  
2024.02.17更新，增加时间标签；因频道太多，cctv、卫视及其他小时频道均修改为单独的文件运行；为每四运行，更新更及时。

2024.02.11更新，修复部分频道错误。

2024.02.07更新，增加生成m3u文件。因手边无电脑，仅python文件更新，windows文件夹下文件未更新。

2024.02.04更新，可以每日自动运行了。每日早4点运行。

2024.02.01更新，增加单步执行的文件。itv_all.py及在window目录下的itv_all.exe。因频道太多，总运行时间大概50分钟。

2024.01.31更新，整理所有代码，更新如下：

1.推荐在本地电脑运行，不推荐在github。因为github运行服务器不在本地运行，获取的数据不准确，测速不准。
2. windows目录下为可在win10独立运行的文件，无需python，只需要电脑安装最新的chrome(121.0.6167.85)，同时执行文件目录下的对应版本的chromedriver.exe即可运行，否则报错。
3.以前的文件全部归到temp。
4.最终生成的itvlist.txt文件只取频道相同测速最快的前5个，即可最终使用。
5.生成的全部频道文件，如itv.txt及itv_speed.txt不建议使用，因为频道太多，在diyp或派大星等软件中使用时播放会卡顿。此卡顿与频道的播放速度无关，是因为频道太多导致。

2024.01.26更新，对获取的ip第四地址位从1~255均尝试获取，能获取到的酒店源。采用了多线程，速度有很大的提升。
