
# 二、知识图谱项目
<img src="https://github.com/Shunli-Wang/Basic_Knowledge_of_KG/blob/main/imgs/KG_projects.png" width = "500" alt="知识图谱项目" align=center >

**1、按照时代划分**
- 早期知识库项目：[Cyc](https://cyc.com/)、[WordNet](https://wordnet.princeton.edu/)、[ConceptNet](http://www.conceptnet.io/)
- 互联网时代的知识图谱：[Freebase](http://www.freebase.com/)、[Wikidata](https://www.wikidata.org/)、[DBpedia](https://www.dbpedia.org/)、[Yago](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research/yago-naga/yago/)、[BabelNet](http://live.babelnet.org/)、[NELL](http://rtw.ml.cmu.edu/rtw/)、[Microsoft ConceptGraph](https://concept.research.microsoft.com/)
- 中文知识库：[OpenKG](http://www.openkg.cn/)、[Zhishi.me](http://openkg.cn/dataset/zhishi-me)（目的是将繁体维基+百度百科+互动百科融合在一起形成中文的维基百科）、[cnSchema.ORG](https://schema.org.cn/)

**2、按照领域划分**
- 通用型KG：[Freebase](http://www.freebase.com/)、[DBpedia](https://www.dbpedia.org/)、[Yago](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research/yago-naga/yago/)
- 知识建模与概念建模：[Schema.org](https://schema.org/)
- 特定领域：Herbnet（中草药）、linked-life-data（生命科学）、LinkedGeoData.org（地理）、[WordNet](https://wordnet.princeton.edu/)（语言学）
- 中文KG：[Zhishi.me](http://openkg.cn/dataset/zhishi-me)、CN-DBpedia、XLORE、PKU Base
- 人工构建：[Wikidata](https://www.wikidata.org/)
- 自动抽取：[NELL](http://rtw.ml.cmu.edu/rtw/)、WEB KB、WEB CHILD

**3、详细介绍**
- [Cyc](https://cyc.com/)：目的是构建人类最大的常识知识库。50万条属于和700万条断言。知识库由术语（Term）和断言（Assertion）组成。特点是基于形式化的知识表示方法刻画知识。
- [WordNet](https://wordnet.princeton.edu/)：最著名的词典知识库。普林斯顿大学认知实验室1985年开创。主要定义了名词、动词、形容词和副词之间的语义关系。WordNet3.0已经包含超过15万个词和20万个语义关系。
- [ConceptNet](http://www.conceptnet.io/)：源自MIT媒体实验室的OMCS项目，此项目由Marvin Minsky于1999年创建。ConceptNet5已经包含2800万关系描述。采用了非形式化、更加接近自然语言的描述。较为侧重于词和词之间的关系。

- [Freebase](http://www.freebase.com/)：基于RDF三元组模型，底层采用图数据库进行存储。2005年由MetaWeb启动语义网项目，2010年谷歌收购Freebase，2016年谷歌宣布Freebase并入Wikidata并正式关闭Freebase。
- [DBpedia](https://www.dbpedia.org/)：指数据库版本的Wikipedia，早期语义网项目，是从Wikipedia抽取出来的链接数据集。采用RDF语义数据模型，总共包含30亿个RDF三元组。
- [Wikidata](https://www.wikidata.org/)：目的是构建全世界最大的免费知识库，具有众包协作机制，采用CC0完全自由许可协议。支持以三元组为基础的知识条目的自由编辑。已经超过5000万个知识条目。
- [Schema.org](https://schema.org/)：2011年开始由各大搜索引擎公司共同支持的语义网项目，支持各个网站采用语义标签的方式将语义化链接嵌入到网页中。本质是采用互联网众包的方式生成和收集好质量的知识图谱数据。
- [BabelNet](http://live.babelnet.org/)：类似于WordNet的多语言词典知识库，目的是解决WordNet在非英语语种中数据缺乏的问题。BabelNet3.7包含271种语言、1400万个同义词组、36.4万个词语关系和3.8亿个从Wikipedia种抽取的链接关系，总计超过19亿个RDF三元组。
- [NELL(Never-Ending Language Learner)](http://rtw.ml.cmu.edu/rtw/)：由CMU开发，采用互联网挖掘方法从Web种自动抽取三元组知识。目前已经抽取了300万+条三元组知识。
- [Yago](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research/yago-naga/yago/)：由德国马普所研制的链接数据库。集成了Wikipedia、WordNet、GeoNames三个数据库，具有更加丰富的实体分类体系。还考虑了时间和空间知识，增加了时空维度的属性描述。包含1.2亿条三元组知识，是IBM Watson的后端知识库之一。
- [Microsoft ConceptGraph](https://concept.research.microsoft.com/)：以概念层次为中心的KG，以概念定义和概念之间的IsA关系为主，可以用于短文本理解和语义消歧。V1.0包含超过540万个概念、1255万个实体和8760万个关系。
- [LOD(Linked Open Data)](https://lod-cloud.net/)：为了实现Tim Berners-Lee于2006年发表的有关链接数据（Linked Data）作为语义网的一种实现的设想。使用URI表示万物、使用RDF和SPARQL标准。LOD已经有1143个链接数据集。

- [OpenKG](http://www.openkg.cn/)：面向中文域开放知识图谱的社区项目，聚集了大量开放的中文知识图谱数据、工具和文献。对百科数据进行了链接计算和融合工作，并提供开放Dump和API。涵盖的中文知识图谱包括：
    - [Zhishi.me](http://openkg.cn/dataset/zhishi-me):狗尾草科技、东南
    - [CN-DBpedia](http://openkg.cn/dataset/cndbpedia):复旦
    - [XLore](http://openkg.cn/dataset/xlore):清华
    - [Belief-Engine](http://openkg.cn/dataset/belief-engine):中科院自动化所
    - [PKUPie](http://openkg.cn/dataset/pku-pie):北大
    - [ZhOnto](http://openkg.cn/dataset/zhonto):狗尾草科技  
    工具包括：知识建模-Protégé、知识融合-Limes、知识问答-YodaQA、知识抽取-DeepDive。
- [cnSchema.ORG](https://schema.org.cn/)：由OpenKG发起和完成的开放的知识图谱Schema标准，词汇集包含上千种概念分类、数据类型、属性和关系等常用概念定义。
- [OpenBase.AI](http://openbase.openkg.cn/)：是OpenKG实现的类似于Wikidata的开放KG众包平台。以中文为中心，更加突出ML与众包的协同。
