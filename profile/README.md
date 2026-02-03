<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
# 唐图(rCoreOS)开源社区
探索基于Rust语言开发多构型操作系统内核框架和可组合内核组件，并可像拼七巧板（英文：Tangram，简称 tg；中文也称：唐图）那样，灵活组合出uni-kernel、monolithic-kernel、micro-kernel、hypervisor等各种构型的操作系统内核。帮助内核开发者像开发应用那样，快速搭建满足特定应用需求的定制化操作系统内核。
目前我们已经在[Rust组件汇聚地 crates.io](https://crates.io/)上发布（publish）了很多这样的内核组件，且还有不少是以** tg-CRATENAME **的名称表示的。同时，为便于大家学习，也构造了[七巧板化的rCore-Tuturial -- Tg-rCore](https://github.com/rcore-os/rCore-Tutorial-in-single-workspace/tree/test)。
## 起源
本社区起源于2017年底，清华大学计算机系操作系统课开始探索基于Rust语言的OS实验，并在2018年推出了教学操作系统rCore，并放到了github上。后续逐步开展科研探索，形成了rCore-Tutorial、rcore-in-single-workspace、zCore, ArceOS等一系列的教学科研操作系统。在对这些操作系统进行教学和研发的过程中，我们在进一步思考，能否以单个内核组件为可独立存在并运行的基本单元，并把这些单元组合在一起，形成不同形态和功能的操作系统内核。现在我们正在开发各种内核组件，并尝试组合出arceos、starry、axvisor等异构内核，欢迎大家一起加入我们这个社区！

- [想法来源：基于泛型独立组件构建各种领域OS](https://github.com/chyyuu/thoughts/blob/main/tangram-oskits.md)
- [2024年贾越凯博士论文的第四章:关于unikernel架构ArceOS内核的设计与实现](https://github.com/user-attachments/files/19867809/main-20240524-62-91.pdf)
- [2019-2025年与Rust写OS kernel相关的毕业论文列表](https://github.com/LearningOS/bachelor-thesis)

## 进一步扩展出的开源社区与项目
- [LearningOS开源社区](https://github.com/learningos)，培养操作系统专业人才
- [开源内核组件汇聚中心](https://github.com/kern-crates) 汇聚了各种各样的内核组件，并进行分析、测试和管理
- [rCore Tutorial Kernel：教学用内核组件化初步探索](https://github.com/rcore-os/rCore-Tutorial-in-single-workspace)
- [rCore Tutorial Kernel：教学用内核组件化进一步探索](https://github.com/crates-rcore-in-single-workspace)
- [多型态组件化操作系统：教学用内核组件化再进一步探索](https://opencamp.cn/os2edu/camp/2024fall/stage/3)
- [rCore Tutorial Kernel：教学用内核组件化再进一步探索](https://github.com/rcore-os/rCore-Tutorial-in-single-workspace/tree/test)
- [组件化Unikernel架构OS--ArceOS开源社区](https://github.com/arceos-org/arceos) 探索基于Unikernel ArceOS进一步开展多构型内核组件化设计
- [ArceOS: unikernel架构的组件化操作系统内核：科研用内核组件化的初步探索](https://github.com/arceos-org/arceos)
- [Starry-next: monolithic kernel架构的组件化操作系统内核：科研用内核组件化的进一步探索](https://github.com/oscomp/starry-next)
- [axVisor：Hypervisor架构的组件化操作系统内核：科研用内核组件化的进一步探索](https://github.com/arceos-hypervisor/axvisor)
  
## 新闻
- [2025开源之夏-唐图社区开源项目](https://summer-ospp.ac.cn/org/orgdetail/4169274d-0d8f-4836-96a4-cc9061ee7a24?lang=zh)
- [2025第二届中国研究生操作系统开源创新大赛2025.5.1~8月下旬](https://cpipc.acge.org.cn//cw/detail/2c9080178c7c917b018d1b1a0af61cd6/2c908018963934e10196865400e4360c) 
- [2025春夏季开源操作系统训练营：2025.3.30~2025.6.22](https://github.com/LearningOS/)
- [2025全国大学生OS比赛：2025.3~2025.8](https://github.com/oscomp/)

**注：上述训练营、比赛、实习等都有唐图开源社区的题目，欢迎大家报名参加！**

## 加入社区
对于感兴趣开发/改进内核模块/内核框架等或想使用/合作研发本社区提供的各种内核模块的OS内核开发者，请联系负责人（ 微信号 chyyuu 或 limingth），申请好友请说明“参加唐图开源社区”，加入唐图开源社区，一起参与探索并挑战未来。

## 进展中的实习项目
- [2025年春季清华计算机系本科生OS课大实验的选题和参考资源](https://github.com/LearningOS/os-lectures/blob/master/oslabs/biglab-relatedinfo-2025s.md)，欢迎感兴趣的同学和爱好者微信联系负责人（ 微信号 chyyuu 或 limingth），申请好友请说明“参加OS大实验”，加入兴趣小组，一起参与探索并挑战未来。
- [开源实验小项目招新](https://github.com/orgs/rcore-os/discussions/categories/ideas)，可作为本科或研究生毕设课题，欢迎报名并参加！请联系负责人（ 微信号 chyyuu 或 limingth），申请好友请说明“参加唐图社区开源实验项目”。
   - [2025春夏季开源操作系统训练营阶段四实习一项目](https://github.com/learningos#%E5%AE%9E%E6%88%981os-kernel-designimplementation)的[相关小项目](https://github.com/orgs/rcore-os/discussions/15)
   - [2025春夏季开源操作系统训练营阶段四实习二项目](https://github.com/learningos#%E5%AE%9E%E6%88%982hypervisor-design--implementation)的[相关小项目](https://github.com/orgs/rcore-os/discussions/13)
   - [2025春夏季开源操作系统训练营阶段四实习三项目](https://github.com/learningos#%E5%AE%9E%E6%88%983os-kerneldriver-based-on-the-asynchronous-mechanism-of-coroutines)的[相关小项目](https://github.com/orgs/rcore-os/discussions/36)

## 相关开源社区
- [syswonder开源社区](https://syswonder.org/)，面向泛在计算的操作系统探索
- [OS比赛开源社区](https://github.com/oscomp)，面向全国高校学生的OS比赛
- [智能网联汽车创新中心训练营:开源操作系统](https://github.com/cicvedu)，面向智能驾驶领域的系统软件开发培训
