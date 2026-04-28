[search2AI](https://github.com/fatwang2/search2ai) 让你的大模型 API 支持联网，搜索、新闻、网页总结，已支持OpenAI、Gemini、Moonshot(非流式)，大模型会根据你的输入判断是否联网，不是每次都联网搜索，不需要安装任何插件，也不需要更换key，直接在你常用的三方客户端替换自定义地址即可，也支持自行部署，不会影响使用的其他功能，如画图、语音等

早上在cloudflare上部署work，一次通过。
可以传Key & query 给Work,由work调用默认的 search engine ( support bing/google/searh1api/SERPER_KEY)搜信息传给AI处理。
