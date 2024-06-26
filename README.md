# “小胰宝 - 面向胰腺癌肿瘤患者的智能RAG平台”

## 【项目介绍】

小胰宝是由病友SamQin开发并上线的RAG应用，主旨为帮助每年**数十万**新增确诊病人以及幸存病人，克服专业医学和治疗的医患信息差。使用小胰宝，可7x24小时，帮助病患高效率，准确理解病情状态，治疗术语，规范治疗指南，以及综合治疗的复杂信息，克服慌乱情绪，选择科学和有效治疗路线，并最终获得更长的治疗收益，也即生命窗口。

小胰宝已经上线8个月，帮助了3000+患者稳定提供，并聚集了支持AI科技应用的专业医生，患者群，以及开源技术社区和社会公益人士。在2024年7月份明确了开源本项目，并感谢@RichardLin@开源社庄老师等大V，牵头本项目并推动开源社区的落地，组织建立，项目宣传和完善。

**小胰宝的上线，为全癌种肿瘤患者AI智能服务，开辟和验证了新模式。期待开源社区的伙伴们，动起手来，以”科技+AI+人文“的独有能力，推动本项目的复制，为数千万CA患者，快速提供更多类似应用。让他们获得选择的机会！**

优先推荐为肺癌/乳腺癌/甲状腺/肝癌/肠癌等五大癌肿患者，开发上线相关AI助手。请随时联系本项目组织者，交流相关信息，携手公益！ 也希望您主动传播本项目，让更多开发者知道和参与这个有价值有温度的科技应用。

## 体验地址

- 小胰宝 - 胰腺ca患者助手：https://aibot.samqin.asia
- 星妈爱聊 - ca心理安抚助手：https://xingma.samqin.asia

![小胰宝](https://www.freeimg.cn/i/2024/05/08/663ae77288263.png)

## 围绕综合治疗配套的“小胰宝一家人”

癌症治疗路线，包括 【医疗诊治】，【营养支持】和【心理支持】三个主要方面，也直接决定治疗效果的好坏：“生命窗口”的长短。

AI技术的患者应用，除了小胰宝类针对患者治疗过程的助手外，我们还尝试提供针对”心理支持“的【星妈爱聊- 胰腺ca患者心理安抚小助手】，以及【小食宝 - 患者营养和菜谱小助手】，形成三环合一的综合应用，帮助患者和家属高效率的获得信息。也请复制本项目，创建多癌肿应用的开发者注意这一点的必要性。

![星妈爱聊](https://github.com/PancrePal-xiaoyibao/PancrePal-xiaoyibao/blob/main/xingma.png)


![小胰宝新手宝典](https://github.com/samqin123/---RAG-/assets/103937568/4e1b2e11-38fe-4978-9660-d2761c2a0af1)

## 【项目开源原则和誓言】

使用小胰宝项目开源框架，包括基于本项目技术框架，产品框架，知识库数据全部或部分，默认自动接受如下原则和誓言：

1.  永不向病患和家属收费，不以“智能助手”做任何商业化引流。
2.  尊重知识贡献者所有权，不盗取知识库获利，公开知识库来源。
3.  一切立足“规范治疗”，“循证”为知识库准入第一原则。

**我们非常欢迎您使用本项目，并希望您能够给予反馈，以及基于开源共享精神的认可。您的一句谢谢和引用说明，也是我们付出努力的认可，很重要。**

----

## 【小胰宝1.0产品框架介绍】

<img width="1481" alt="image" src="https://github.com/PancrePal-xiaoyibao/PancrePal-xiaoyibao/assets/103937568/edcb6e3a-cccd-48c1-952a-b40274b9d9a1">


----
## 【小胰宝项目1.0版本使用开源组件】

小胰宝使用如下开源项目，也感谢这些项目大佬的付出，他们为患者创造了科技温情的价值。

1. [Fastgpt](https://github.com/labring/FastGPT): 为小胰宝1.0提供了核心RAG平台技术栈，，对万人级别患者提供了稳定和高效能服务，以及便捷高效的知识库搭建；<br>
2. [Chatgpt-on-wechat](https://github.com/zhayujie/chatgpt-on-wechat/tree/master): 作为微信机器人技术栈，提供了患者更便捷的使用和体验；<br>
3. [Dify](https://github.com/langgenius/dify): 为小胰宝2.0提供了RAG的扩展空间，包括LLMs的一站式接入，KB的体系扩展，以及最为重要的和全球化RAG能力对齐.<br>
4. [0-1 AI, one of LLM Large Language Model Leaders](https://01.ai)：零一万物团队，不仅全力支持本公益项目，而且慷慨提供了0-1API接口及Token消耗赞助，让数千患者享受到了科技福利。<br>
5. 同时，也感谢其它为小胰宝上线提供支持的开源社区人士 @v佬 -中国红客联盟 @Richard-开源社创始人，为小胰宝的技术和发展提供关键支持和引导
6. 在获悉小胰宝项目的进展后，[阶跃星辰](https://www.stepfun.com/)的小伙伴@Sunny付凯老师@simin主动联系项目，给予了慷慨的token捐赠，产品@陈雪丹和研发负责人@halo 帮助对prompt优化提供了技术支持。Stepchat的加入，不仅见证了开源世界的价值观，也代表一个重要的信息：
   ### 始终有一群人，愿意基于开源AI技术和人性温暖，制造出更多类似小胰宝的应用，帮助中国以及中国医疗捐助的国际肿瘤患者们，让他们有机会绕开信息鸿沟，选择科学规范治疗，获得生命收益。

----

## 【小胰宝项目延伸 - 知识库项目】

感谢@徐宇超老师的付出，为小胰宝和更多面向多癌肿的“小x宝”们，提供了一个知识库项目，方便非技术和医疗背景的贡献者，随时进行知识文档的汇总。<br>项目地址： https://xycjscs.github.io/KnowledgeBase-xiaoyibao/ 


---

## 【版本介绍和路线图】

参见[【版本介绍和路线图】](roadmap.md) 。

---
## 任务广场：需要开源社区大佬们的帮助工作项
### 开发类型

- [ ] 任务1：微信机器人优化：基于COW项目的微信机器人，降低掉线率，可以使用不同的魔改版本，欢迎测试后提交PR；
- [ ] 任务2：部署自动化：现在是需要3个项目的手工部署，希望能自动化部署，欢迎测试后提交PR；
- [ ] 任务3：dify/fastgpt使用multi-agent进行优化：dify/fastgpt目前只支持单agent和workflow，但肿瘤患者需要医学助理-营养助理-心理助理构成的至少3个agent联合服务，配合癌症患者的综合治疗效果。目前只能以3个应用来分解，患者则需要使用3个ai助手，很不方便; 需要熟悉RAG的大佬搭建demo，并提交PR；
- [ ] 任务4：微信小程序：越来越多的患者希望把微信小程序端开发出来，技术上小胰宝提供了api接口，但是需要前端开发者协助开发，欢迎测试后提交PR；建议使用git上的开源免费chatbot小程序框架。
- [ ] 任务5：优化fastgpt响应速度，实现流式输出：目前fastgpt的响应速度比较慢，大概要5-15秒，需要优化到2-3秒，欢迎测试后提交PR；


### 运营类型

- [ ] 任务6: 社区运营：目前小胰宝的社区运营团队刚刚成立，需要志愿者加入，增强“内容运营”，“病友社群运营”的运营能力，欢迎报名，请联系wx@m89989988m
- [ ] 任务7: 内容库运营：欢迎提交和胰腺癌治疗的内容（包括pdf文件，治疗方案，治疗药物，靶向方案，免疫方案，治疗方案的内容，经验。如果你可以去自行添加到[小胰宝知识库项目](https://xycjscs.github.io/KnowledgeBase-xiaoyibao/)，欢迎提交PR），或者可以申请加入志愿者群，联系wx@m89989988m
---
### 【开源合作招募】
1. 微信bot：
很多患者群聚集在微信生态，因此需要稳定的微信机器人，目前使用的免费开源工具包括Chatgpt-on-wechat, 存在2-3天掉线问题，因此严重影响病患的使用和小胰宝及类似应用服务十万级用户体量的要求。开源社区如有支持者，请联系本人。 
2. 知识库迭代
3. LLM能力增强
4. 诊疗协同
5. 公益组织协同


## 部署方式

### 配置环境建议

推荐服务器部署，配置建议2c2g3M40G起步（阿里云99元），建议4c8g-50G-5M。fastgpt和dify都需要稳定资源，否则增加运维压力。

### 【推荐】docker-compose安装

* 本项目的部署配置文件可以参考docker目录使用
* 模型部分以零一为例，可以随需修改，推荐Moonshot/Stepchat/Glm-4系列，不推荐openai，主要还是embedding和对话账号，openai国内使用不合法也不稳定。
* embedding推荐国产大模型，比如qwen的text-embedding-v2或者智谱的embedding模型

## 【联络方式】

- 作者联系邮箱 `qinxiaoqiang2002@hotmail.com`，微信：`qinxiaoqiang`
- 小胰宝公益组织负责人 RichardLin 微信：`OPQRichard`
