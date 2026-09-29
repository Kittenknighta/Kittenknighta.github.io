---
title: 清华大学免费Token领取方法以及使用指南
date: 2026-09-29 11:57:51
categories:
  - 时间暂停我偷电瓶
cover: /img/covers/时间暂停我偷电瓶.jpg
---

清华大学免费Token领取方法以及使用指南

学生认证登录https://easycompute.cs.tsinghua.edu.cn/home

登录自动领1000元算力劵，这个算力劵在并行智算云平台生成的秘钥可以用绝大部分国产模型（几乎所有），但是，它的官方文档说只支持三种主流工具：Chatbox、Cherry Studio、AnythingLLM，这三种工具并非主流，事实上，只要提供了秘钥和URL链接，就可以通过CCSwitch部署到真正的主流工具（比如claude）。官网中已经给出URL链接为API_URL/BASE_URL：https://llmapi.paratera.com

除了这个1000块之外，还可以领取智谱“3个月”编码套餐

在“清华大学计算机系高性能计算研究所”界面点击“点击使用”跳转到并行智算云平台

智谱3个月编码套餐在并行智算云平台的右上角点击“GLM编程套餐”即可领取

如果用智谱GLM，官方提供了非常详细的开发文档，支持把GLM接入claude等其他工具，当然，还是要通过CCSwitch配置（比较方便）

注意：如果通过CCSwitch配置GLM，记得供应商要找到并选择Zhipu GLM，而如果用上面的1000元算力劵，则自定义配置供应商，提供秘钥和URL即可

算力劵和套餐均有期限，过期会清零~

CCSwitch不是最新版本的时候，我记得似乎好像在“模型映射”中，填写的模型名称必须与官网提供的完全一致，包括大小写

比如使用并行智算云平台时必须填写DeepSeek-V4-Pro

而从Deepseek官网生成api就必须是DeepSeek-V4-pro

不然报错

但是最新版好像就对此无要求

如果无法下载或者更新CCSwitch，

微软商店下载Watt Toolkit，此软件免费加速github，十分好用

加速后可以下载或者更新CCSwitch

！！！因为知道了秘钥和URL链接，任何人都可以使用此api，而URL各官方是公开的，所以自己的秘钥需要完全保密

如果别人知道了你的秘钥，那ta就可以偷偷白嫖！！！
