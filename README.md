# bilibili_fans_record
一个可以同时记录多个用户粉丝数变化为特定格式的txt文档的python程序。
<h3>具体用法</h3>
安装好依赖库后直接运行即可。
<h3>相关参数</h3>
<h5>基础</h5>
jump：每轮爬取的间隔，单位为秒。不建议太低以免被ban。请注意，默认每个用户抓取时间间隔为1s，因此实际jump=目标jump-抓取的用户数量+1。<br>
uids：目标用户的id号，格式参照示例即可。<br>
<h5>进阶</h5>
wait：一轮爬取中，每个目标数据的爬取间隔。若目标较少，且jump较大，则可以wait值可以较小。若目标较多或jump较小时，则wait不宜过小，以防止IP被ban。<br>
可以将“文档”二字更改为你想要的文件夹名，该文件夹位于与主程序同级的目录上。<br>
<br>
其他内容不建议更改。

https://github.com/arktos-venture/docker-tdengine
https://github.com/dgiot/dgiot-dashboard/blob/master/.github/workflows/deploy.yml
