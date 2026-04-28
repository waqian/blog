清明节没出门，趁 openAI chatgpt3.5免费，开始折腾免费API，感谢X ＠geekbb 推荐。
# 1. kimi-free API 
这是4月初安装的，不用登录kimi就可以用。
https://github.com/LLM-Red-Team/kimi-free-api
https://github.com/LLM-Red-Team
LLM Red Team 意为 LLM大模型红队，大模型应用发展速度超乎了所有人的预料，在这样得表象下是日益严重的安全风险。
本组织成立的愿景是通过各厂商大模型应用中已公开的信息挖掘潜在的安全问题并公开一些技术细节，如果影响到您应用的正常运营请联系组织负责人，我们会及时下线相关仓库。
所有内容仅供研究禁止套壳对外服务对官方造成服务压力！！
以下是我们目前已公开的仓库：
Moonshot AI (Kimi.ai) 接口转API [kimi-free-api](https://github.com/LLM-Red-Team/kimi-free-api)
阶跃星辰 (跃问StepChat) 接口转API [step-free-api](https://github.com/LLM-Red-Team/step-free-api)
阿里通义 (Qwen) 接口转API [qwen-free-api](https://github.com/LLM-Red-Team/qwen-free-api)
ZhipuAI (智谱清言) 接口转API [glm-free-api](https://github.com/LLM-Red-Team/glm-free-api)
聆心智能 (Emohaa) 接口转API [emohaa-free-api](https://github.com/LLM-Red-Team/emohaa-free-api)
此外，我们提出一种可能的提高逆向成本的方案：[ban-free-api](https://github.com/LLM-Red-Team/ban-free-api)

# 2. freegpt3.5
https://github.com/missuo/FreeGPT35
接上one-api 可用。

# 3.  [aurora](https://github.com/aurora-develop/aurora)
支持高并发的freegpt 3.5.
docker 可以部署在 Render上（好像这个镜像被禁了）

# 4. [ FreeAskInternet](https://github.com/nashsu/FreeAskInternet)
perplexity 免费平替，结合和 chatGPT-next-web freegpt searxng
中文提问搜中文资源为主，建议用英文提示效果更好。 

# 5.  watchtower  
之前都是用 Unraid的自动升级插件，原生docker没有自动升级，watchtower 支持定时、指定（排除）images/containers 升级。