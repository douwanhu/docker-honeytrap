# dockerized honeytrap


[honeytrap](https://github.com/armedpot/honeytrap) 是一个低交互蜜罐，主要抓取利用TCP UDP网络协议<br>
的攻击。所有捕获到的威胁数据存储至/data/honeytrap/ <br>
/data/honeytrap/log/attackers.json 记录所有攻击过程<br>
/data/honeytrap/attacks 下保存网络包文件<br>
/data/honeytrap/downloads 保存下载的恶意文件<br>
为避免磁盘空间占用过大，多蜜罐系统默认24小时重启一次，且重启后清除<br>
/data/下的数据，并在清除之前将所有数据导入到已部署的MySQL数据库中<br>

附在公网上90天Honeytrap捕获到的威胁数据统计报告dashboard<br>
![Honeytrap Dashboard]((https://github.com/liyihoohoolab/hotpot/blob/master/docker-honeytrap/doc/dashboard.png)

