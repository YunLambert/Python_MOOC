# 2020nCov 爬虫通知
调用了可用的api接口，获取数据，并通过微信模板消息的方式发送给指定的微信用户。同时为了自身方便，增加了天气预报通知和2020年进度条通知两个内容。
定时发送的功能利用了crontab进行了设置，时长为3小时更新一次数据。
效果如下：
![result](./result.jpg)