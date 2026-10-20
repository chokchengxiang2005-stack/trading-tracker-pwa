# Trading Tracker Mobile

可安装到 iPhone/iPad 主屏幕的 PWA。部署到 HTTPS 静态网站后，用 Safari 打开并选择“添加到主屏幕”。

- 行情与新闻：Finnhub API Key。
- 1 分钟 K 线：优先 Finnhub；若其拒绝访问，可填写 Twelve Data API Key 自动备用。
- K 线每 30 秒刷新，支持缩放与横向拖动；附 MACD (12,26,9)。
- 买入/卖出/观望为透明、非自动执行的研究信号，输入仅包含报价、开盘价、1 分钟 OHLC、MACD、相关新闻标题。它不使用订单簿、持仓、基本面或宏观资料。

密钥只写入设备浏览器本地存储，不应提交至公开代码库。
