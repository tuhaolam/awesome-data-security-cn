[TOC]

# awesome-data-security-cn
数据安全方法论与实践

## 方法论
只讲思路，不能开箱即用
### 规范标准
***
- [DSMM数据安全能力成熟度模型](https://www.dsmm.com.cn/)：国标GB∕T 37988-2019 信息安全技术 数据安全能力成熟度模型
- [DSM数据安全认证](https://blog.csdn.net/Chaincomp/article/details/125368036)：依据国标《GB/T 41479-2022 信息安全技术 网络数据处理安全要求》实施认证
- [数据安全治理应参考的国家标准](https://www.secrss.com/articles/49326)

### 建设思路
***
#### 通用指南
- [数据安全治理实践指南2.0](https://www.secrss.com/articles/50798)：信通院发布
- [数据安全治理白皮书4.0](https://www.wangan.com/p/7fy7f6062330a897)：中关村网络安全与信息化产业联盟发布
- [数据安全复合治理与实践白皮书](https://www.freebuf.com/articles/paper/317405.html)：中国评测联合国信中心、蚂蚁集团共同发布
- [数据安全治理能力评估方法](https://www.isc.org.cn/profile/material/2021/11/11/634610a0-fb9c-45c0-8372-7932cbf3c628.pdf)：中国互联网协会发布
- [awesome-zero-trust-cn](https://github.com/tuhaolam/awesome-zero-trust-cn)：聚焦国内零信任方法论与实践
- [awesome-cryptography](https://github.com/sobolevn/awesome-cryptography): A curated list of cryptography resources and links.
- [基于数据安全的沙盘推演体系](https://mp.weixin.qq.com/s/ldqIPYnG235syNVzk9kvNg)：框架上与传统安全沙盘推演流程相似，重点是在战技、战术与战略三个层面围绕数据安全CIA特性展开
- [基于数据安全网关的数据安全防护体系研究](https://mp.weixin.qq.com/s/0CqgircMQ_KquFaPWVeHaQ)：本质上是API网关，但融合了数据安全全场景，覆盖数据采集与共享等数据全生命周期，并集成常用的安全管控手段
- [腾讯安全发布的数据安全治理与实践白皮书](https://cloud.tencent.com/developer/article/2298382)：提供的三个案例来自腾讯云、腾讯游戏、微信三大核心业务，在框架性和实践性上有一定参考价值

#### 企业实践
- [数据安全的第一道坎](https://www.sec-un.org/数据安全的第一道坎/)：平安银行分享
- [data-security-google-cloud](https://cloud.google.com/blog/topics/developers-practitioners/data-security-google-cloud)：GCP数据安全白皮书
- [Google数据安全自动化建设之路（白皮书）](https://zhuanlan.zhihu.com/p/564689012)：GCP数据安全国内解读
- [跟着大公司学数据安全架构之AWS&Google](https://www.freebuf.com/articles/network/171547.html)：介绍aws、gcp的数据安全架构
- [互联网企业数据安全体系建设](https://tech.meituan.com/2018/05/24/data-security-system-construction.html)：美团安全负责人分享
- [将军令：数据安全平台建设实践](https://tech.meituan.com/2019/02/14/data-security-platform-construction-practice-jiangjunling.html)：美团数据安全平台分享
- [大型互联网公司数据安全实践](https://www.anquanke.com/post/id/190093)：美团数据安全负责人分享
- [京东数据安全的审计与治理](https://blog.csdn.net/weixin_45727359/article/details/126132613)：基于DCAP（Data-Centric Audit and Protection），关注京东内部全面推进的11个改造项
- [离职期员工的信息安全管控实践](https://mp.weixin.qq.com/s/hIIyFbx562WREErC9Ygw0Q)：权限回收、异常行为监控预警、继续教育与工作申请审批


### 数据识别与分类分级
***
- [基于关键词、数据字典和正则表达式敏感数据识别方法](https://cn-sec.com/archives/1364844.html)
- [好大夫数据安全分类分级实践探索](https://www.freebuf.com/articles/database/349036.html)：一种低成本、高效落地数据分级分类的思路
- [大规模数据安全分类系统架构实践](https://mp.weixin.qq.com/s/mRmDEuDKJSJ_xrYyBMn4Dw)：美团分类分级系统建设，结合了机器学习和传统指纹技术对所有数据进行分类

### 认证与授权
***
- [大数据应用安全研究报告（11家公司实践详解）](http://www.cbdio.com/BigData/2017-05/15/content_5519040.htm)
- [采用统一的零信任数据访问方法实现数据安全现代化](http://www.anquan419.com/news/18/1562.html)

### 数据加密与脱敏
***
- [CASB：一场镜花水月还是云安全的未来？](https://www.sec-un.org/casb：-一场镜花水月还是云安全的未来？/)
- [常用业务场景下的密码技术应用参考流程](https://blog.csdn.net/weixin_45303938/article/details/107523306)
- [万字详解数据安全关键技术之数据脱敏](https://www.freebuf.com/articles/database/348732.html)
- [货拉拉数据加密治理实践](https://mp.weixin.qq.com/s/hDs7vMlYrLhRuA_BU7yq0g)

### 数据防泄漏
***
- [GCP DLP](https://cloud.google.com/dlp/docs?hl=zh-cn)
- [企业云原生数据防泄漏（DLP）架构与运营实践指南](https://mp.weixin.qq.com/s/3MPdhLw12L9GLt_LDoswvQ)：万字长文，主要是思路和解决方案的列举
- [奇安信：数据泄露典型判例分析报告](https://www.qianxin.com/threat/reportdetail?report_id=37)：根据司法案例判断内部人员泄露占数据泄露角色分布的80%
- [南方都市报：超半数个人信息由行业“内鬼”泄露](https://epaper.oeeee.com/epaper/A/html/2021-11/01/content_22788.htm)：根据司法案例判断“内鬼”贩卖个人信息最多

### 隐私计算
***
- [awesome-data-privacy](https://github.com/yilmaztolga/awesome-data-privacy): A curated list of data privacy and security resources
- [awesome-privacy-chinese](https://github.com/international-explore/awesome-privacy-chinese)：国内隐私技术交流，梳理非常详细，值得学习

### 安全审计
***
- [从异常行为分析的视角重新审视数据安全场景](https://mp.weixin.qq.com/s/5svpMNihz7EyE9sKS3WD7g)：虽片言只语，但可窥见其中奥妙
- [UEBA架构设计之路](https://www.secrss.com/articles/12141)：连载10篇，美团数据安全负责人出品
- [UEBA案例分析系列之数据泄露检测](https://www.4hou.com/posts/3OQn)：结合实际案件分析UEBA如何检测，非常难得，可惜没有继续连载
- [UEBA资料汇总](https://ixyzero.com/blog/archives/4103.html)：内容比较散乱，亮点在于资料比较丰富
- [数据库审计产品进化史](https://www.sec-un.org/数据库审计产品进化史/)：对数据库审计这一传统领域的不错梳理

### 数据检测与响应
***
#### 产品
- [Cyberhaven DDR](https://venturebeat.com/security/cyberhaven-insider-threats/)及其[工作原理](https://www.cyberhaven.com/how-it-works/)介绍
- [Dig Security DDR](https://www.dig.security/product)及其[工作原理](https://www.dig.security/post/an-introduction-to-data-detection-and-response-ddr)介绍
- [青骓DDR](https://zhuanlan.zhihu.com/p/588632074)：国内为数不多的商业产品

#### 数据泄露事件应急
- [数据泄漏应急响应思路](https://blog.csdn.net/sycamorelg/article/details/123516930)：这篇文章最后也被写入奇安信的书里
- [数据安全事件应急及溯源分析实践案例](https://www.freebuf.com/articles/paper/328494.html)
- [数据泄露典型判例分析报告](https://www.qianxin.com/threat/reportdetail?report_id=37)：奇安信出品，数据相当具有参考价值
- [没有BAT3级的应急响应中心，互联网公司该如何应对数据泄露事件？](https://cloud.tencent.com/developer/article/1038728)
- [关于数据泄密事件排查的注意事项](https://toutiao.io/posts/3vfm6a5/preview)：梳理的很清晰
- [基于数据安全的应急响应体系建设](https://mp.weixin.qq.com/s/7mlBtdB9JAfTDGvjwyFN3g)：参照PDCERF应急响应模型，结合数据安全特点，形成准备、检测、抑制、根除、恢复与总结六个阶段，并提出量化的数据安全事件分级方案

### 书籍
***
- [数据安全架构设计与实战](https://weread.qq.com/web/bookDetail/5ed32a607198b78c5ed6a0b)：作者在鹅厂做过多年数据安全工作，目前在菊厂
- [数据安全领域指南](https://weread.qq.com/web/bookDetail/917323f0813ab7713g018417)：很详细的介绍了数据安全整体体系
- [微信读书书单：Awesome-Data-Security](https://weread.qq.com/)：作者维护的一份书单

### 分享
***
- [信息安全知识库vipread](https://vipread.com/library/tags/数据安全)：国内各种公开分享基本都收纳进来了
- [sec-wiki](https://www.sec-wiki.com/news/search?wd=数据安全)：每周一推送
- [awesome-security-weixin-official-accounts](https://github.com/DropsOfZut/awesome-security-weixin-official-accounts#数据安全类)：数据安全类微信公众号

### 个人成长
***
- [数据安全人员能力思考](https://iami.xyz/DSMM-Date-Security/)
- [CSDP数据安全认证专家](https://c-csa.cn/training/course-detail/i-1702.html)
- [数据安全工程技术人员国家职业标准](http://www.mohrss.gov.cn/xxgk2020/fdzdgknr/jcgk/zqyj/202301/t20230117_493635.html)
- [组织机构的数据安全人员能力要求](https://www.secrss.com/articles/8893)
- [数据安全人才强基计划](https://www.isc.org.cn/article/12511724820754432.html)

## 实践
只讲实际落地，以开源项目等形式提供
### 数据识别与分类分级
***
- [godlp](https://github.com/bytedance/godlp): 字节开源的敏感数据识别与脱敏工具
- [d18n](https://github.com/LianjiaTech/d18n): 链家开源的敏感数据识别与脱敏工具
- [DataDefender](https://github.com/armenak/DataDefender): Data Discovery and Anonymization toolkit
- [大数据安全--敏感数据识别和分级打标](https://blog.csdn.net/u014779378/article/details/103035474)

#### 数据加密与脱敏
- [maskdata](https://github.com/Sumukha1496/maskdata): a Node.js module to mask various kinds of data.
- [文字水印TextWatermark](https://mp.weixin.qq.com/s/hAZHUiPGmxyn20Lh2PTUpA)
- [图片明水印](https://github.com/dxcweb/watermark)
- [网页明水印](https://github.com/saucxs/watermark-dom)
- [网页盲水印](https://github.com/guofei9987/blind_watermark)

### 隐私计算
***
- [隐私计算开源](http://www.21jingji.com/article/20221008/herald/de7776ac8bf0e543d4dd7aeb32f6d68f.html)
- [同态加密开源框架整理](https://blog.csdn.net/OpenMpc/article/details/127901713)

### 安全审计
***
- [OpenUBA](https://medium.com/georgia-cyber-warfare-range/introducing-openuba-an-open-source-user-behavior-analytics-platform-powered-by-the-scientific-5d71bc50b808): an open source user behavior analytics platform powered by the scientific computing ecosystem
- [sqlaudit](https://www.freebuf.com/articles/database/289443.html)：mysql数据库审计

### 比赛
***
- [2021红明谷杯数据安全大赛](https://www.ichunqiu.com/hmgctf)
- [2021极客谷杯数据安全劳动和技能竞赛](https://www.aqniu.com/industry/78089.html)
- [2022首届全国数据安全大赛](https://bm.ichunqiu.com/ds-contest)
- [2023数字中国创新大赛网络数据安全赛道](https://www.dcic-china.com/competitions?raceId=32)

## 欢迎贡献
如果你希望为这个项目做贡献，只需fork，加入自己的修改并给这个项目发送一个PR，我很乐意采纳您的建议:)

## 联系作者
欢迎数据安全研究者、从业者添加微信交流，暗号：`你好世界`+`作者github账号名`