## Charles抓包设置 

>抓包：就是抓取http和https请求,以及响应。其中http都是以明文的形式传输，抓包就可以看到内容。但是https抓包，则需要安装相应的证书，而且要选择监听对应的url和443端口。

### 1.Charles安装 

官网下载安装Charles:

https://www.charlesproxy.com/download/

***

### 2.添加证书 

使用的时候,如果先要抓https的包,那么需要添加证书。

- 2-1 PC下载证书：HELP->SSL Proxying->Install Charles Root Certificate->安装证书。

- 2-2 手机下载证书：HELP->SSL Proxying->Install Charles Root Certificate on a Mobile Device or Remote Browser（根据提示安装证书）。

1. i.

2. ii.

***

设置-->通用-->关于本机-->证书信任设置

把里面的那个Charles的证书设置为信任就可以了

![搜索框页面](https://github.com/yukuai0117/Pisces/blob/master/attachments/%E6%90%9C%E7%B4%A2%E6%A1%86%E9%A1%B5%E9%9D%A2.png)