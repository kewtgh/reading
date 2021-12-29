---
title: 从面相分析全球第一家量产AI芯片的企业——寒武纪
excerpt: "寒武纪以其“全球第一家量产AI芯片的半导体企业”的名声响彻世界，那么其实力到底如何？从其团队的面相上能看出什么？"
header:
  teaser: /assets/img/page-header-image-tech5-teaser.jpg
  overlay_image: /assets/img/page-header-image-tech5.jpg # Add image post (optional)
  overlay_filter: 0.5
categories:
  - 阅相识人
  - 企业剖析
  - 芯片半导体
tags: 
  - 芯片
  - 半导体
  - IC
  - EDA
  - CEO
  - AI
  - 人工智能
  - COO
  - CTO
  - CFO
  - 封装与测试
  - 寒武纪
  - 陈天石
  - 陈云霁
toc: true
last_modified_at: 2021-12-29T22:25:52-05:00
---

&emsp;&emsp;芯片半导体领域是目前国内最为火热的产业之一，也是政府举国兴办的产业，像极了洋务运动时举国上下筹办制造业的局面。虽然国内的芯片领域曾经出过不少乌龙，有天下哗然的“汉芯”事件，也有盛极一时的“弘芯半导体”，但仍然有许多企业逐渐树立了自己的市场地位。那么这些企业到底如何？

&emsp;&emsp;从本期开始，我们将分析国内几家初上市，或者仍为独角兽的芯片半导体企业，了解行业的境况和企业的实情。

&emsp;&emsp;首先简单介绍一下芯片半导体领域：

---

## 一、芯片半导体行业简介

&emsp;&emsp;芯片半导体可以按照制造流程可以简单分为以下三个方面：

### 一）芯片设计

1. **EDA（Electronic Design Automation）**：即电子设计自动化，以高度智能化的软件模拟实际场景，帮助进行芯片设计。该领域目前几乎被国际三大EDA厂商垄断，三家企业分别为Synopsys、Cadence、Mentor Graphics。
   
   - **电子电路设计与仿真工具**：即电路模拟。
   
   - **PCB设计软件**：即布局布线。
   
   - **IC设计软件**：即集成电路的设计，其中包括设计输入、设计仿真、综合、布局布线、物理验证、模拟电路仿真等综合性工具。
   
   - **PLD设计工具**：主要用于构造芯片的逻辑功能，目前包括CPLD(Complex PLD)和FPGA(Field Programmable Gate Array)两大类。
   
   - 其他EDA软件：包括VHDL语言工具和VerilogHDL等。

2. **芯片设计企业**：指具体负责设计的企业，部分企业不但自己设计，还自己生产，这类企业大部分会在芯片制造介绍。该领域中，国内的知名企业包括：海思半导体、汇顶科技、华大半导体、中兴微电子等，国际的知名企业包括：高通、博通、英伟达、超威半导体等。

3. **IP**：这里专门提IP是因为之后很多时候介绍企业时会用到，也是芯片领域常用的概念。IP即**Intellectual Property，知识产权，就是芯片中他人已经设计好的、具有知识产权的模块，在设计芯片时可以直接嵌入到产品中**。

### 二）芯片制造

1. **制造设备**：主要为芯片制造提供设备，国内企业包括中电科电子设备、北方华创、中微半导体设备等；国际企业包括东京电子、阿斯麦、应用材料、尼康等企业。
   
   - **硅片设备**
   
   - **热处理设备**
   
   - **光刻设备**
   
   - **刻蚀设备**
   
   - **离子注入设备**
   
   - **薄膜沉积设备**
   
   - **抛光设备**
   
   - **清洗设备**
   
   - **检测设备**

2. **制造材料**
   
   - **硅片制造**
   
   - **辅料**：包括电子特种气体、光刻胶、CMP抛光材料、高纯湿电子化学品、靶材等。

3. **制造企业**：国内企业包括中芯国际、华润微电子、华虹半导体、长江存储等，国际企业包括英特尔、台积电、三星电子、SK海力士、西部数据等。

### 三）芯片封装与测试

1. **封测设备**

2. **封测材料**

3. **封测厂**：国内企业包括通富微电、长电科技、华天科技等，国际企业包括日月光半导体、安靠（Amkor）、力成科技（PTI）等。

具体内容如下图（大图请[点击](https://cdn.jsdelivr.net/gh/kewtgh/PicSunflowers@main/2021/12/27-21-09-08-%E8%8A%AF%E7%89%87%E5%8D%8A%E5%AF%BC%E4%BD%93%E6%B5%81%E7%A8%8B%E5%88%86%E7%B1%BB.jpg)）：

<img src="https://cdn.jsdelivr.net/gh/kewtgh/PicSunflowers@main/2021/12/27-21-09-08-%E8%8A%AF%E7%89%87%E5%8D%8A%E5%AF%BC%E4%BD%93%E6%B5%81%E7%A8%8B%E5%88%86%E7%B1%BB.jpg" title="" alt="芯片半导体流程分类.jpg" data-align="center">

&emsp;&emsp;上面即是芯片半导体行业的简单介绍，下面我们来分析企业，先来看被称为全球第一家量产商业人工智能芯片的企业——寒武纪。

---

## 二、企业简介

&emsp;&emsp;寒武纪成立于2016年，由中科大出身的陈天石教授创立，主要专注于人工智能芯片产品的研发与技术创新，目前已于2020年7月份在科创板上市。

&emsp;&emsp;我们先了解一下寒武纪的产品，其目前产品主要有五个类别：

1. **智能加速卡**：主要应用于云端，解决在搜索引擎、云计算、网络游戏等场景中，对数据、图片和视频等的处理时，超高运算能力的需要。
   
   - 思元270：面向高能效比云端AI推理，支持视觉、语音、自然语言处理以及传统机器学习等多样化的人工智能应用。
   
   - 思元290：寒武纪首颗AI训练芯片，提供AI训练中所需的高内存带宽，帮助实现云端虚拟化及容器级的资源隔离。
   
   - 思元370：国内第一款公开发布支持LPDDR5内存的云端AI芯片，

2. **智能加速系统**：把加速卡、内存、网络接口等集成到一起，可以更加方便的使用，类似于购买的Apple电脑等组装好的机器。
   
   - 玄思1000智能加速器：AIDC的基础构建单元。**AIDC即自动识别和数据采集，主要指不需键盘输入的数据，比如条形码、磁条、语音识别、指纹识别和人脸数据等**。

3. **智能边缘计算模组**：**边缘是指最接近用户端或者数据源的一端**；对应的则是云端，就是处理这些数据的一端。比如智能驾驶汽车的汽车，自动送货的机器人等，主要价值在于降低延迟、分散算力。
   
   - 思元220：一款专门用于边缘计算应用场景的AI加速产品。

4. **终端智能处理器IP**：
   
   - 寒武纪1H/1M：寒武纪推出的高性能、低功耗的深度学习处理器IP系列，可广泛应用于各类智能终端，包括智能手机、智能摄像头、机器人、自动驾驶设备等。

5. **软件开发平台**：
   
   - 寒武纪人工智能开发平台（Cambricon NeuWare®）：寒武纪专门针对其云、边、端的智能处理器产品打造的软件开发平台。
   
   - 寒武纪推理加速引擎 MagicMind：**软件领域的引擎就是指核心代码，用户利用引擎只需要做简单的操作就可以实现需求，比如搜索引擎**。用户使用MLU、GPU或者CPU训练好的算法模型，借助MagicMind仅需投入极少的开发成本，即可将推理业务部署到寒武纪全系列产品上。

&emsp;&emsp;**目前寒武纪的战略是，做独立、中立的芯片公司，不直接参与具体的应用解决方案，类似于Android。所以其芯片是通用型的，便于应用于各种领域。**

---

## 三、寒武纪核心团队

&emsp;目前寒武纪的高管包括六位：创始人、董事长兼CEO陈天石先生，COO王在先生，CTO梁军先生，CFO叶淏尹女士，副总经理叶淏尹先生，副总经理刘少礼先生，另外还包括其未在公司介绍中署名的联合创始人，陈天石的哥哥，陈云霁。下面我们就逐一分析其核心团队成员。

### 1、创始人、董事长兼CEO  [陈天石](https://cdn.jsdelivr.net/gh/kewtgh/PicSunflowers@main/2021/12/29-00-25-24-%E9%99%88%E5%A4%A9%E7%9F%B3-4.jpg)

&emsp;&emsp;陈天石先生1985年生于江西南昌，2005年毕业于中国科学技术大学少年班，获得数学与应用数学学士学位；2010年毕业于中国科学技术大学计算机学院，获得计算机软件与理论专业博士学位；同年进入中国科学院计算技术研究所工作，历任助理研究员、副研究员和研究员，研究方向为计算机体系结构和计算智能。陈天石先生曾获ASPLOS、MICRO等多个最佳论文奖，并入选中科院计算所百星计划，主持国家自然科学基金青年基金项目、面上项目、优秀青年基金项目）。

&emsp;&emsp;2016年，陈天石先生与其胞兄陈云霁先生共同创立寒武纪。目前，陈天石先生担任寒武纪董事长兼CEO。

&emsp;&emsp;陈天石先生的性格特点有三点：

1. **谦卑朴实**：**陈天石先生性格非常谦卑，他在寒武纪这份事业上抱着非常真诚的态度，并且愿意躬身奉献来使这件事成功**。这也如同追求更高目标的韩信，在面对胯下之辱时，也能躬身承受。**这证明陈天石先生对成就事业的决心和期冀！**

2. **实干**：陈天石先生也非常实干，重视事情的结果，所以做事也非常扎实。

3. **刚直**：相较其胞兄，陈天石先生在人情世故方面就略弱一些，行为一般比较单纯。因而**他努力靠成果去证明自己，而非靠各种关系**，这倒也有些像曾国藩。

&emsp;&emsp;最后简单谈谈陈天石性格中比较隐晦的特点：他在家中排行老二，而他哥哥则学习优异、成就斐然，所以他一直活在哥哥的光环之下，**一方面对哥哥充满崇拜之情，另一方面也希望超越他哥哥。这也是他拥有强烈的成就心的来源！**

---

### 2、COO兼副总经理  [王在](https://cdn.jsdelivr.net/gh/kewtgh/PicSunflowers@main/2021/12/29-00-28-36-%E7%8E%8B%E5%9C%A8-3.jpg)

&emsp;&emsp;王在先生出生于 1984 年，拥有中国科学技术大学计算机应用技术博士学位。2011年至 2015 年就职于郑州商品交易所并任核心交易系统工程师，2015 年至 2016 年就职于中原银行并任信息科技部电子银行系统主管，2016 年至2018 年就职于中科院计算所从事科研工作。
&emsp;&emsp;2016 年，王在先生作为寒武纪创始团队成员加入公司，现任公司董事、副总经理兼首席运营官。

&emsp;&emsp;王在先生的性格有三个特点：

1. **博而不精**：王在先生对问题的认知上有一定的理解力，他对很多事物都有观察和思考，因而对事物的方向也有一定的判断力；但他的这些理解主要基于自己的观察和思考，而非实证或者经检验的理论，所以能知道大方向，却又很难道出具体的方法。

2. **圆而不通**：因为善于观察和思考的关系，他对人性也有一定的体察，所以在处理人际关系上有一定的能力；但是也因为不及根本、不求精细的原因，很难擅长。

3. **虽躬实傲**：因为他宏观上的思考和认知，会觉得自己在认知方面高于他人，与众不同；因而对很多问题较难躬身学习或者采取行动。虽然平时也显得很谦逊，但在心底却是带有高傲的，因而不太利于其学习和认知方面的完善。

---

### 3、CTO兼副总经理  [梁军]()

&emsp;&emsp;梁军先生出生于 1976 年，拥有中国科学技术大学通信与信息系统硕士学位。梁军先生曾于2000年至2003年，就职于华为技术有限公司北京研究所，任工程师；2003 年至 2017 年，就职于华为技术有限公司基础业务部、深圳市海思半导体有限公司，历任工程师、高级工程师、主任工程师、技术专家、高级技术专家。

&emsp;&emsp;2017年，梁军先生加入寒武纪，现任公司副总经理兼首席技术官。

&emsp;&emsp;暂时没有找到梁军先生公开的照片，无法具体评价，日后如有机会，再做更新。

---

### 4、CFO兼副总经理  [叶淏尹](https://cdn.jsdelivr.net/gh/kewtgh/PicSunflowers@main/2021/12/29-00-30-22-%E5%8F%B6%E6%B7%8F%E5%B0%B9-2.JPG.jpg)

&emsp;&emsp;叶淏尹女士出生于1988 年，拥有北京大学西方经济学硕士学位。叶淏尹女士曾于2012年至2016年就职于中国高新投资集团公司，并任投资经理、高级投资经理；2016年至2019年就职于国投创业投资管理有限公司，并任投资副总裁。

&emsp;&emsp;叶淏尹女士于2019年加入寒武纪，现任公司董事、副总经理、CFO、董事会秘书。

&emsp;&emsp;叶淏尹女士的性格有两个特点：

1. **聪明有余**：指她的智商很高，对很多事情和道理都非常明晰的判断，对业务方面也较专长，具体沟通过程中，也能感觉到她的思维敏捷！

2. **慧力不足**：这方面主要指**她对于理解他人的情绪和情感方面略弱**，所以在两个方面可能会有问题：**一是在带团队时，因为不能很好地懂下属，所以领导力就偏弱；二是在工作中，她能知道一件事该怎么做，当兼顾做对一件事和满足他人对结果的期望时就会略显不足。** 这在其财报上就能表现出来，公司的财报内容非常丰富，但是略显杂乱，而且有些需要展示的结果却没能清晰展示。

---

### 5、副总经理  [刘少礼](https://cdn.jsdelivr.net/gh/kewtgh/PicSunflowers@main/2021/12/29-00-32-05-%E5%88%98%E5%B0%91%E7%A4%BC-2.jpg)

&emsp;&emsp;刘少礼先生出生于1987年，拥有中科院计算所计算机系统结构博士学位。刘少礼先生2014年至2019年就职于中科院计算所，并任副研究员。

&emsp;&emsp;刘少礼先生也是寒武纪创始团队成员，于2016年加入，现任公司董事、副总经理。

&emsp;&emsp;刘少礼先生的两张照片也略显不同，上面的照片是其正面照，但这张照片是年轻时的照片。这张照片体现的性格是：**好胜心和功利心较强，聪明也较喜欢社交，** 因而在成绩上就会有一两个方面很突出，而其他方面则多属于中等或者偏上的情况。

&emsp;&emsp;后面这张[Photo](https://cdn.jsdelivr.net/gh/kewtgh/PicSunflowers@main/2021/12/29-20-46-18-%E5%88%98%E5%B0%91%E7%A4%BC-3.jpg)，则年纪比上一张要大十岁左右，性格则有些不同：**实干性比之前提升很多，但好胜心仍然还有，不过已经磨砺得弱了不少，仍然很懂得处理关系，但也不会那么活跃。**

---

### 6、副总经理  [刘道福](https://cdn.jsdelivr.net/gh/kewtgh/PicSunflowers@main/2021/12/29-00-34-19-%E5%88%98%E9%81%93%E7%A6%8F-6.jpg)

&emsp;&emsp;刘道福先生出生于1988年，拥有中科院计算所计算机系统结构博士学位。刘道福先生曾于2015年至2019年就职于中科院计算所，历任助理研究员、高级工程师。

&emsp;&emsp;2016年，刘道福先生作为寒武纪创始团队成员加入公司，现任公司副总经理。

&emsp;&emsp;刘道福先生目前在寒武纪具体负责哪些方面没有明确介绍，不过根据其过往经历，很有可能也是在研发，或者在与实施相关领域。其性格也比较符合该方向，有一个非常明显的特点：

1. 扎实：**他在自己所做的业务上非常扎实，理论、技术以及经验上都有非常成熟的能力；** 不仅如此，他在自己所有接触的领域都有成熟且自洽的理解，**包括生活中，因而他的同事都能感受到，他在介绍东西时往往能侃侃而谈**。

&emsp;&emsp;从其性格特点上来看，担当COO的角色也是很适合的。

---

### 7、联合创始人 [陈云霁](https://cdn.jsdelivr.net/gh/kewtgh/PicSunflowers@main/2021/12/29-00-35-25-%E9%99%88%E4%BA%91%E9%9C%81-1.jpg)

&emsp;&emsp;陈云霁先生1983年生于江西南昌，目前为中国科学院计算技术研究所研究员，博士生导师；同时，他担任了中国科学院脑科学卓越中心特聘研究员，以及中国科学院大学岗位教授。陈云霁先生曾获得首届国家自然科学基金“优秀青年基金”、首届国家万人计划“青年拔尖人才”、中国计算机学会青年科学家奖以及中科院青年人才奖，并曾先后负责或参与了多款龙芯处理器的设计。

&emsp;&emsp;陈云霁先生虽然同陈天石先生一同创立了寒武纪，但是目前并未在寒武纪履职。他以合作的方式，带领其实验室，研制寒武纪系列深度学习处理器。

&emsp;&emsp;相较于其胞弟，陈云霁先生更适合做企业的一把手，主要基于三个方面：

1. **深谙人性**：陈云霁先生非常善于琢磨他人心理，这在管理职位上则是必须的。

2. **善谋能断**：他也是一位思考者，善于观察事情并思考其根本逻辑，从而能做出正确判断，因而决策能力会比较强。

3. **厚重**：厚重的性格则易能包容那些真正有能力的人才，既能吸引人才，也敢于放权。

&emsp;&emsp;此外，陈云霁先生也**非常实干，看重成果**。他可能比较乐于研究，或者是看重中科院的地位和成就，否则他出任企业的一把手则对寒武纪来说，是更好的选择。

---

## 四、如何评价寒武纪？

### 一）业务方向

&emsp;&emsp;目前我简单将寒武纪的产品和服务分为三个方面：

1. **智能加速卡、智能加速系统及边缘计算模组**：主要应用方向为四类，云端、智能手机终端、物联网应用和智能汽车端。
   
   + **云服务**：这是智能加速方面最核心的应用领域，云计算的需求越来越高，因而对智能加速卡的需求也越来越强烈。市场潜力很大，但是可替代性的产品和技术也有很多，这完全在于寒武纪的市场能力，以及采用其产品时的替换成本。
   + **智能汽车、物联网及其他智能终端**：这是边缘计算模组的主要应用领域，甚至也包括智能手机端，这方面的潜力巨大。但是其产品的市场竞争力目前很难讲，因为除了之前与华为有过合作外，再没有知名的合作企业。**目前工业领域和安防监控等领域的需求可能是最直接也最强烈的，但并未见其有多大斩获**。

2. **终端智能处理器IP**：自从不再和华为合作后，目前已经很难有大的成长点，大多数手机厂商基本都采用高通芯片，而高通与其合作的可能性微乎其微。市场前景不明朗。

3. **软件开发平台**：这是两个寒武纪硬件产品的应用辅助软件平台，软件平台能否建立，需要足够的用户数，目前其用户数量还太少，短期内难有成长。
   
   + 寒武纪人工智能：
   + 推理加速引擎：

&emsp;&emsp;总体评价，**寒武纪目前选择的市场方向潜力巨大，但是可能因为产品实力的原因，也可能是因为市场能力的不足，其完全没有打开市场**。

&emsp;&emsp;

### 二）财务情况

<img src="https://cdn.jsdelivr.net/gh/kewtgh/PicSunflowers@main/2021/12/28-20-19-52-%E5%AF%92%E6%AD%A6%E7%BA%AA%E8%B4%A2%E5%8A%A1%E6%95%B0%E6%8D%AE.png" title="" alt="寒武纪财务数据.png" data-align="center">

&emsp;&emsp;**因为2020年的上半年正是疫情高发期，所以2021年和2020年的上半年度报告不具有可比性，我们只比较2021年的第三季度和2020年的第三季度。** 相较而言，2021年第三季度的营收同比2020年第三季度增长20.2%，属于尚可；但是同期的亏损额却增加了一倍还多，而且毛利率也在下降，因而未必是良好的表现，极有可能是竞争的激烈以及IP业务的缩水导致。

&emsp;&emsp;此外，根据其招股书及财报中披露，2018、2019和2020年三年中，**前五大客户的销售金额营收占比分别为100%、93.59%和82.10%；其中，第一大客户在营收中的占比分别为：98.37%、46.88%、57.86%，其经营风险极高**；对单一客户的依赖度如此之高，较为少见。

&emsp;&emsp;另外，2018年，其毛利润中畸高的99.90%是因为当时的产品只有IP，而客户则正是华为，用于其手机芯片中；之后华为成立海思，二者则由合作变为竞争关系，所以之后的**毛利率降幅明显，且逐年递减，能否保持有很大难度**。

&emsp;&emsp;再从几项核心业务的收入占比来看：

<img src="https://cdn.jsdelivr.net/gh/kewtgh/PicSunflowers@main/2021/12/28-23-29-01-%E5%AF%92%E6%AD%A6%E7%BA%AA2021-1-6-%E4%BA%A7%E5%93%81%E6%94%B6%E5%85%A5%E5%8D%A0%E6%AF%94.png" title="" alt="寒武纪2021-1-6-产品收入占比.png" data-align="center">

&emsp;&emsp;**边缘智能芯片和加速卡**是其最为核心的业务，这类主要是智能终端的应用，这方面因为目前的产品并不完善，寒武纪的市场空间很大，但是竞争对手也只需要半年至一年就可以赶上其相应的技术，所以时间窗口并不大。而训练整机的需求不知是具体哪个大客户在采用，因为这方面的需求并不稳定；依照其对前五大客户的依赖程度来看，甚至几乎都难以分析其产品的潜力，因为一家客户的大量需求并不能代表市场的普遍需求。

  从现金流来看，其期末现金余额为38.6亿，现金流很充分，且大部分为筹资及投资活动获得，证明**投资人对其的信心仍然很坚定**。

&emsp;&emsp;目前仅从财务数据来看，其应该在市场中还有一到两年的时机：**如果其财务数据能有更好的表现，市场风险度明显降低，则投资者会保持对其信心；但如果这段时间中不能有好的表现，类似前五大客户营收占比畸高的情形依然存在，则市场对其信心会大幅降低，其目前账面的现金流是否能应付这样的风险则未可知**。

&emsp;&emsp;仅从其上市之后的股价走势，就证明最初的估值明显偏高；目前寒武纪的股价已经从高点的超过250元人民币跌到现在不足100元；而且以其面临的挑战，现在的股价我认为仍然偏高。

<img src="https://cdn.jsdelivr.net/gh/kewtgh/PicSunflowers@main/2021/12/28-20-36-14-%E5%AF%92%E6%AD%A6%E7%BA%AA%E8%82%A1%E4%BB%B7.png" title="" alt="寒武纪股价.png" data-align="center">

&emsp;&emsp;**最后稍稍吐槽一下，寒武纪的财报，是我看过最累的！** 需要的数据不列举，还都得翻好几个财报才能算出来！怕不是认为财报不好看，股东们时间又很紧，要是看起来费精力，就去看其他家了吧？！希望其对产品的底气也能放在财报上！

&emsp;&emsp;下面评价其团队:

### 三）团队评价

&emsp;&emsp;整体看非常不乐观，其核心团队成员均是中科院出身，且以技术为主。我相信Google的拉里·佩吉和谢尔盖·布林如果没有**施密特**的帮助，Google的墓志铭上已经写着“卒于××年”的铭文了；如果Facebook的扎克·伯格最初没有**肖恩·帕克**助其执掌公司，Facebook现在的标志也是“已卒”！因为没有经验丰富的经理人，寒武纪的企业核心管理层的设置、岗位人员的任命，都可以说是灾难性的。

&emsp;&emsp;其市场和营销负责人、人力资源负责人，以及隐身的CTO，还有让我看财报看到发狂的CFO，这些职位都不称职！

&emsp;&emsp;**虽然陈天石的领袖魅力、实干性和决策力都不错，但是却非常缺乏企业治理经验！从这方面来说，其投资机构也是失职的，并未给予合适的帮助。按照其目前的团队配置，用不了多久，寒武纪也会成为另一家“弘芯”！**

&emsp;&emsp;我认为陈天石极有可能是被吹捧宣扬的媒体的声音误导了，他和其胞兄的经历被一众怀揣望子成龙的人奉为传奇，从而可能就真的自认为是传奇了！技术方面，他的确可能在国内树立领先地位，但是经营和管理上仍有许多需要潜心学习的，否则到头来也只是一场空欢喜！

&emsp;&emsp;整体评价，寒武纪的团队评分为：

![寒武纪团队评分.png](https://cdn.jsdelivr.net/gh/kewtgh/PicSunflowers@main/2021/12/29-00-40-50-%E5%AF%92%E6%AD%A6%E7%BA%AA%E5%9B%A2%E9%98%9F%E8%AF%84%E5%88%86.png)

---

&emsp;&emsp;寒武纪的分析就到这里，下一期我们来聊聊汇顶科技。相对于年轻的寒武纪，汇顶科技则正值壮年，成立于2002年，并于2016年于上证所上市，而且是真正的实力派，2020年的营收高达66亿元人民币，净利润接近14亿？那么汇顶科技哪些地方实力突出，又有什么短板呢？下一期详细介绍。