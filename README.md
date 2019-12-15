# m3u8Dowload
java下载m3u8视频，解密并合并ts
<pre>
 M3u8DownloadFactory.M3u8Download m3u8Download =  M3u8DownloadFactory.getInstance(M3U8URL);
//设置生成目录
m3u8Download.setDir("F://m3u8JavaTest");
//设置视频名称
m3u8Download.setFileName("test");
//设置线程数
m3u8Download.setThreadCount(100);
//设置重试次数
m3u8Download.setRetryCount(100);
//设置连接超时时间（单位：毫秒）
m3u8Download.setTimeoutMillisecond(10000L);
m3u8Download.start();
</pre>