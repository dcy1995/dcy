<p align="center">
# 虚拟仿真技术在SFX实验教学中的应用
  </p>
                                作者：董朝阳  尹智鹏  汪悦
## 1.作品的设计思路、科学性以及先进性<br/>
虚拟仿真实验室的研究首先分析了目前课题组内“一锅法”制备SFX及其衍生物的实验教学需求和难题，继而探讨了虚拟仿真技术在现代教学中的应用，并结合有机合成实验教学的现状，针对SFX的“一锅法”实验教学做了以下研究与开发：<br/>
（1）虚拟仿真实验系统设计。基于传统有机合成实验教学的诸多弊端，研究报告从有机合成实验教学实际出发，结合“一锅法”制备SFX的实验过程，完整还原了有机合成实验室的场景，在老师的指导下，设计了适用于SFX实验教学的虚拟仿真教学系统，对虚拟仿真实验教学系统的架构做了具体规划，定义了不同的功能模块，生动形象的描绘了实验教学各项活动的开展流程。<br/>
（2）有机合成虚拟仿真实验室开发。虚拟仿真实验室的开发是本研究报告的重点工作，工程采用以软件代替硬件的思想，利用3ds Max软件和基于Unity3D的万维引擎平台，在计算机上构建了与传统有机合成实验室具有相同功能的场景型、交互式的虚拟仿真实验室，模拟2, 3′,6′-TBrSFX的制备与表征过程。<br/>
   工程的开发拓展了传统有机合成实验教学的深度与广度，使有机合成实验教学不受时间、空间的限制，满足实验教学的需要。采用开放条件的拓展思维训练模式，让学生真正的接触到创新所在的精髓，对化学类相关专业所面向的有机电子、信息材料、存储器等专业创新型人才所需要的知识、技能、和素质目标的达成起支撑。同时，该实验项目打破了传统的固定实验内容的教学模式，节省了大量的教学资源，初步形成了化学实验教学的新模式，在医学、航空、建筑等其他教学领域中也有着广阔的应用。<br/>
## 2.SFX合成实验相关综述<br/>
   SFX（螺芴氧杂蒽）是一种螺环结构，2004年，本课题组在使用芴酮与苯酚尝试变换反应条件制备9,9-二(4-羟苯基)芴(FDPO)的过程中，将Easton试剂替代为MeSO3H和P2O5(3:1)的过量混合物作为反应条件，偶然发现了一种极性比芴酮小的副产物。之后又改变反应条件将反应时间延长至24h，得到一种不同于FDPO的未知化合物。出于好奇心，课题组收集此副产物进行表征，最终，经过核磁共振波谱、气相色谱-质谱、单晶衍射解析证明是SFX结构。这次偶然的发现引起了课题组的关注，随后经过不断改变反应条件(如改变MeSO3H和P2O5的投量比或者将苯酚换为苯醚等)，多次重复实验后证实了9,9-二(4-羟苯基)芴（FDPO）为动力学产物，而螺芴氧杂蒽（SFX）为热力学产物，这就表明芴酮合环形成SFX的过程经历了一步三键，最后还发现该过程与荧烷中氧杂蒽环的形成过程相似。“一锅法”合成螺环的偶然发现获得了业内同行的高度赞赏，Timothy和Swager在Synfact 发表的文章特地对此发现进行了评述。该方法不仅可以制得高产率的SFX母体结构及其衍生物，而且还可以拓展到其他螺环芳烃的制备(图1.1)。正是“一锅法”的贡献，SFX在化学品商业化目录中的价格明显低于通过邻卤二芳基法合成的SBF，因此SFX类的有机半导体具有很大的商业化潜力。<br/>
 ![](https://raw.githubusercontent.com/dcy1995/dcy/master/5.png)<br/> 
<p align="center">            
  “一锅法”合成SFX及其衍生物
  </p>
   SFX 虚拟仿真合成项目是一个典型的科研成果转化为教学成果的案例，来源于科研成果。2006 年 SFX 的一锅法被发表在《有机化学通讯, Organic Letters》上（Organic Letters 2016, 18 (24), 6220-6223. 亮点报道，Timothy. M. Swager et al. Synfacts 2006, 9, 0904.），历经十二年的努力，不仅推进了科学研究的进程，实现从实验室到产业化的跨越，今年被烟台某公司量产，出口韩国，有望进入三星显示屏，而且实现了教学成果的转化，应用于“本硕博互动”培养模式，成为教研一体的优质素材，还作为典型案例被引入到《有机合成综合实验》课程、《有机功能材料与器件》课程中。在此期间形成了获 1 项国家自然科学奖二等奖（2013 年， 3/5）、2 项省级奖励和一项省奖教学成果奖（2/10）。<br/>
![](https://raw.githubusercontent.com/dcy1995/dcy/master/4.png)<br/> 
<p align="center">        
  SFX 合成实验与各类化学类课程的联系
  </p>
## 3.作品简介：<br/>
   1.本项目在详细分析虚拟现实技术的基础上，结合“一锅法”制备SFX实验教学的特点，设计了一个有机合成虚拟仿真实验室。<br/>
   2.本作品借助杭州浙大旭日科技开发有限公司的万维引擎平台，采用虚拟仿真技术的3ds Max进行场景建模，在指导老师的指导下，探究了SFX的制备过程及其交互功能，并运用基于Unity3D的万维引擎平台可视化编程语言完成开发。<br/>
   3.学生通过本作品不但能够充分理解和掌握专业理论基础知识，而且保障了一个相对安全、可靠的实验教学环境，为学生提供一个不受时间、空间限制的虚拟仿真实验环境。<br/>
   4.学生可以通过虚拟仿真实验室模拟真实实验，仔细观察实验的过程和细节，完成各种预定的实验教学项目，因此实验教学的灵活性和交互性大大增强。<br/>
 ![](https://raw.githubusercontent.com/dcy1995/dcy/master/2.png)<br/> 
 ![](https://raw.githubusercontent.com/dcy1995/dcy/master/1.png)<br/>
 ![](https://raw.githubusercontent.com/dcy1995/dcy/master/3.jpg)<br/>
