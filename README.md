# AI 智能皮影机器人
<video width="640" height="360" controls>
        <source src="demo.mp4"  type="video/mp4">
        您的浏览器不支持 HTML5 video 标签。
</video>
<video width="640" height="360" controls>
        <source src="video_01.mp4"  type="video/mp4">
        您的浏览器不支持 HTML5 video 标签。
</video>
<video width="640" height="360" controls>
        <source src="video_02.mp4"  type="video/mp4">
        您的浏览器不支持 HTML5 video 标签。
</video>

（演示视频需要启动项目才能查看）

## 项目背景

1. 创意来源

皮影戏(Shadow Puppets)，又称“影子戏”或“灯影戏”，作为我国的第一批世界非物质文化遗产，是一种以兽皮或纸板做成的人物剪影以表演故事的民间戏剧。其构造一般的皮影由头、躯干（上下两部分），2条腿（每条腿从膝盖分两节）、2只胳膊（大臂和小臂2部分）、2只手组成。皮影模型的肢体结构与人体构造结构基本一致，其模型控制点位置与人体关节点分布具有极大的重合性。由此可以得出皮影戏的动作表演控制与人关节活动控制肢体动作也具有着极大的相似性。而目前基于深度学习的人体骨架识别技术可以获取图像中人体的关节位置，我们可以通过算法将人体关节位置解析人体肢体动作，再通过机器人（关节控制）对应皮影模型的肢体动作表演，从而可以实现一种新的皮影戏表演方式。

![](https://ai-studio-static-online.cdn.bcebos.com/11dc27629de4486cbaf5bc608e51e24683eedd962891439897467f650336c007)
![](https://ai-studio-static-online.cdn.bcebos.com/908e89cdc13e427dace7b3e95fa3748183d9620f75804d8892409a3532ad847e)

2. 产生背景

“十四五”时期是开启全面建设社会主义现代化国家新征程、向第二个百年奋斗目标进军的第一个五年，也是全面提高我国非遗保护能力和水平的重要时期。皮影作为第一批被列入国家级非物质文化遗产名录的文化，一方面见证了中华文明的绵延传承，连结着民族情感，承载着我们中华民族许多优秀的传统文化；另一方随着时代的发展，新的技术和新的传播方式对传统艺术进行了无情的碾压，让皮影戏几乎面临失传。
近年来，人工智能领域快速发展，各种技术层出不穷，并能够与多种应用场景深度融合。其中人体骨骼关键点检测(Pose Estimation)是计算机视觉的基础性算法之一，在诸多计算机视觉任务起到了基础性的作用，如行为识别、人物跟踪、步态识别等相关领域。目前人体姿态估计的研究已取得显著进展；早期的MPII Benchmark，现在的COCO人体关键点挑战赛发展更快，如2016年冠军PAF（openpose，mAP=60.5）和2017年冠军CPN（mAP=72.1）；当然这期间也还有很多优秀的人体姿态方法，如Hourglass等。其中OpenPose是第一个用于多人2D姿态检测的开源实时系统，包括身体，脚，手和面部关键点。以人体骨骼关键点检测的深度学习技术已经得到了跳跃式的发展。
在此背景下，人工智能迅速发展与传统文化、非物质文化遗产深度融合，迎来了“人工智能+非遗”的新发展模式。

3. 推广前景

中国优秀传统文化是中国特色社会主义时间的独特优势，也是新时代坚持和发展中国特色社会主义的深厚历史底蕴和强大前进定力，特别是进入“十四五” 时期后，国家对文化的发展愈加重视。自 2004 年以来，国家每年都会出台文件， 聚焦“非物质文化遗产”，研究帮助文化的发展，近年来更是提出要加快文化与科技的结合，实现智能化、数字化发展。但我国目前的机械技术和人工智能技术大多应用在农业、工业上，传统文化的创新大多仍局限在艺术设计的层面上。对于皮影戏来说，目前主要还是依靠人工操作表演，但随着时代的发展，从事皮影戏表演的人员逐渐减少，在从业人员逐年减少的情况下，采用先进技术对皮影戏的表演进行创新显得极为重要。对于皮影戏的表演形式来说，人工智能化能够增强观众与皮影的互动，有助于帮助皮影走到日常生活中去，因此，AI 皮影机器人势必能够为皮影文化打开新时代的市场。

![](https://ai-studio-static-online.cdn.bcebos.com/846268a1f9904d35ba4ec20c89d06d1787ee1027836e448cb048a01f9b62cc4f)

目前，我们设计的AI皮影机器人已经在中小学及文化体验馆上得到了应用落地，得到很好的反响。通过基于人体骨架识别技术实现皮影戏的极具现实意义的人机交互功能，同时还可以捕获人体的动作姿态。我们将这项技术不仅应用在AI皮影机器人上，把它应用到戏剧表演上，通过人体骨骼识别技术识别标准戏剧动作解析记录保存，当有演员学习其戏剧表演时，将学习者的动作姿态信息与事先保存解析记录的动作信息对比，以此矫正学习者动作不足处。而这项技术不仅有利于普通的动作表演的发展，对于传统宝贵濒临失传戏剧的保护传承更具体巨大意义。同时对于医院等场所安全行为检测等也具有重大意义。

![](https://ai-studio-static-online.cdn.bcebos.com/8bb9e79d8a3a4c079a42bccf1928a23cf0aa208d70bc4624837bff0a0ad351f4)
![](https://ai-studio-static-online.cdn.bcebos.com/efa1e056a9024e0ea99bc2d87f6dca8273e8dc09806f48b69eb486a6fc915193)

4. 主要功能与特色

- 拟人表演

本项目用到目前较为主流的人体关键点检测深度学习模型，能够非常精确的提取出头部、肩膀、手脚等等16个人体关键点，关键点坐标预处理后传输到stm32主控板解析，将数据转化为舵机控制信号，最后实现皮影机器人模仿人体动作的模拟表演。

- 拟人结构

本项目开创性的提出类人体关节的皮影机器人结构。通过设计皮影机器人按人体关节模型进行控制关节排布，将皮影模型的每个控制关键点与机器人的旋转舵机一一映射，形成了类人体的机械结构。改变了传统皮影复杂的多杆一手操作方式，实现了皮影的多关节的控制，简化了皮影的控制方式，也简化了控制算法，让皮影舞台戏上动作表演丰富。

- 交互式表演

本项目皮影机器人设计了其他2种人机交互的表演方式，基亚博智能科技提供的基于LD3320和内部MCU的AI语音识别模块控制模式以及基于 MediaPipe Hands 的手势控制模式，这两种控制模式为用户提供了更加友好的操控方式，进一步的加深了皮影机器人的互动性、娱乐性，让皮影表演形式更加多样化和多场景化。

- 自动表演

采用 stm32 单片机作为皮影机器人硬件控制底层，能够接受上位机发生的信息，并解析成皮影机器人的运动控制信息驱动其肢体运动表演。因此可以通过上位机程序编程好皮影戏剧的动作编排，实现皮影机器人的自主表演。

## 问题描述

AI皮影机器人实现拟人表演的主要任务是首先实时检测摄像头或视频图像中的人，检测人体各个关节特征点的坐标，实现对人物的目标追踪，然后输出检测出目标的位置姿态信息给底层运动模块，进行相应计算后，控制电机进行输出，从而控制皮影完成动作模仿，达到人机交互效果。

**拟人视觉交互皮影机器人框图**

![](https://ai-studio-static-online.cdn.bcebos.com/1d66df3aa72b4db8970563438958a8ef35a3a0ccd8464a9c8757088d2da1dc86)

系统主要由图像视觉处理、机械结构、运动控制模块三大部分组成。视觉图像处理受数据采集速度与准确率影响，机械结构模型决定了皮影机器人的物理响应以及系统的控制方法，运动控制模块决定了机器人运行的平稳性、动作准确性、运行速度响应的快慢的好坏等。

### 图像处理模型

想要获取人体姿态前首先需要适合的模型，考虑到实际使用时所需要的检测速度快、关键点提取精准、整体程序足够小，对于设备的性能要求尽可能的低等需求，我们查阅了目前较为主流的各种人体检测模型，我们选取的第一代模型具有部署简单的特点，基于paddle便能简单部署起来，但模型大小达到了1G以上，对于设备的要求非常高，于是在完成第一代模型后我们便选择了openpose模型，相比于第一代模型大小缩减到了300M，同样设备性能上识别速度提升了80%，虽然得到了提升但是性能需求任然非常高，因此在第三代模型我们选择了更加轻量的google mediapipe模型，模型整体大小只有30M，在i5cpu的笔记本电脑上用纯cpu跑出了15帧的识别速度，这个模型的大小已经完全可以使项目部署到任何一台市场上主流的笔记本上面了。

**图像识别**

![](https://ai-studio-static-online.cdn.bcebos.com/1f91268b732f4ca49c9d01c226c4d2a85cd71c86bced42d8a940375a11ef1764)

### 机械结构模型

想要实现人体骨架技术对于皮影表演前首先需要有作为硬件载体的皮影机器人。现阶段皮影机器人大多采用3R机械臂控制模型（如图），机械臂控制三个控制杆，通过模拟人传统以手动控制皮影操的方式实现皮影戏表演。这种结构只能控制皮影模型1~3个控制支点，能够实现的皮影动作单一，机械结构不灵活较为固定、同用性不强，这种皮影机器人控制算法往往较复杂、通用性不高，不能适用多种不同皮影模型的控制，针对不同的皮影戏表演需要设计不同控制方法。因此这种模型目前尚未得到广泛的推广，且不适合我们人体骨架识别模型。

**3R机械臂结构皮影机器人**

![](https://ai-studio-static-online.cdn.bcebos.com/ccb60e9ea4db4330ba45691016fff0666f2216efd79e49cf9e7bbec0b4b53c73)
![](https://ai-studio-static-online.cdn.bcebos.com/eaa133beda374fd6b26b829526366f359aeb3868c4d24799b7132400a1a83ca7)

为此，我们自主设计了类人体关节的皮影机器人结构，采用人体关节点与皮影模型控制点相适应的拟人机械结构，通过多关节控制皮影模型控制支点，使皮影戏的动作表演可以通过多关节的控制，丰富了皮影戏的动作表演。这种模型大大简化了控制算法的复杂，提高了算法的通用性，同时很好拟合了人体骨架识别的深度学习模型。

**类人体关节结构皮影机器人**

![](https://ai-studio-static-online.cdn.bcebos.com/73509d36c6314d839fbdb33ec42e87ab5bc0a23681b54b7796d1dda8de1d208b)

### 运动控制模型
在满足人体骨架模型对于皮影机器人控制的机械结构后，对于皮影机器人驱动需要设计一定的硬件驱动系统，需要考虑驱动电机的类型，使关节响应实时迅速、准确。我们使用运输速度快的stm32单片机作为底层硬件驱动，采用能够实现360°精确控制的DS3230数字舵机，底盘这采用可以实现闭环控制的带编码器的直流电机控制。同时上位机下位机之间需要进行大量的数据参数，为此需要选择可靠实时的通信。此外皮影机器人系统涉及多舵机系统，为此需要考虑系统负载，应涉及电压驱动保护电路，保证皮影机器人系统安全运行。

**DS3230舵机性能**

![](https://ai-studio-static-online.cdn.bcebos.com/50b0ae6f563a4774b013901a401abcf86ab81b866eee4078942bc87b3a787bc1)

## 技术方案

本项目涉及上位机皮影机器人的数据处理、皮影机械结构的设计以及下位机硬件电路模块的搭建。应用人工智能技术、机器人结构技术、嵌入式技术来实现皮影机器人的智能化与自动化。系统通过摄像头模块向Jetson agx（上位机）导入实时视频流（hls）或本地视频（MP4）流后，使用opencv模块，通过VideoCapture函数指定视频流的数据源，将每一帧图像分别输入到终端，使用Mediapipe的深度学习卷积神经网络框架对摄像头获取的人体图像信息进行人体关键点检测和关键点聚类，然后将人体骨骼关键点进行连接，获取到人体的肢体骨骼，再在骨骼肢体上标注连接进行可视化处理，通过正运动学方程的推导和逆运动学解的求取机器人的关节运动，并通过几何算法计算关节肢体的旋转角度，从而实现人体姿势估计和跟踪。在获取各个关节点的旋转信息后，Jetson agx使用串口模块将旋转指令发送给下位机stm32单片机进行数据处理，然后驱动皮影机器人关节舵机、底盘直流电机运动，从而实现皮影机器人模仿人的姿态运动。同时，为了减低深度学习模型对于硬件性能的要求，系统开发了云服务器计算模式，以腾讯云、ai studio作为数据处理平台，nginx-rtmp作为数据中转站，为用户提供公网ip实现内网穿透功能。在数据中转中使用rtmp推流将视频传输到nginx服务器上，腾讯云、ai studio再将从nginx服务器上面获取识别数据进行运算识别，在服务器上识别完成后将数据通过socket发送到Jetson agx上面，再通过usb串口将数据传输到stm32主控板，由stm32板控制驱动皮影机器人运动，以此来实现拟人表演的功能。
此外，本系统设计语音控制模式、手势识别模和自主编程表演模式三种功能。可通过串口或蓝牙连接皮影机器人，在app上调节皮影机器人的每个关节的角度信息，控制皮影机器人展现用户显要实现的动作。语音模式为将各语音对应的动作或姿势预先写入皮影机器人中，进入语音模式时，通过AI智能语音识别模块识别到特定语音后，让皮影机器人表演出特定动作或姿势。手势识别模则基于MediaPipe Hands神经网络实现用户手势识别，机器人再根据手势表演特定动作或姿势。自主编程模式为实现自动化表演皮影戏的模式，在实现皮影戏的自动化表演之前，需要先记录皮影戏表演所需要的动作。将人工皮影戏表演的每个动作按顺序分解各个关节对应需要的角度，并通Keil软件平台写入到stm32单片机中驱动皮影机器人，表演时皮影机器人会自动按照预先编程好的动作按顺序表演，从而实现皮影戏的自动化表演。

**系统流程图**

![](https://ai-studio-static-online.cdn.bcebos.com/c366cec4ab8b475682e0b2ccc2d51582777b651eafbf4f7381d61d0e9009287a)

**系统模式**

![](https://ai-studio-static-online.cdn.bcebos.com/0819629a54f84ada8e55c70120bea6c97077824e2d6649b9b59aaeb76c3ebc94)

**硬件系统框图**

![](https://ai-studio-static-online.cdn.bcebos.com/fffebb86afb946ba81e814ffb6dcef45e9dcdf3f3967477cac2b324e3191b647)

**软件系统框图**

![](https://ai-studio-static-online.cdn.bcebos.com/cb712a4f0d7c472a8d74e0e64356a21512e826fc987e42d19503fc26e2651cc6)

### 人体姿态检测系统

人体解析(HumanParsing)是细粒组成部分（例如，身体部位和服装）。ACE2P通过融合底层特征，全局上下文信息和边缘细节，端到端地训练学习人体解析任务。人体骨骼的语义分割任务，其旨在识别像素级别的人类图像的项目基于深度学习框架搭建，通过PaddleHub、openpose、mediapipe提供的人体骨骼关键点检测预训练模型，我们就可以快速实现皮影戏的效果。PaddleHub可以便捷地获取PaddlePaddle生态下的预训练模型，完成模型的管理和一键预测。配合使用Fine-tuneAPI，可以基于大规模预训练模型快速完成迁移学习，让预训练模型能更好地服务于用户特定场景的应用。在PaddleHub获取到人体骨骼关键点模型之后，就可以对这些关键点进行连接，从而形成了人体姿态。然后我们将皮影素材映射到人体姿态身上，让皮影跟随人体姿态进行运动，就达到“皮影戏”的效果，如图。

**人体骨骼关键点检测**

![](https://ai-studio-static-online.cdn.bcebos.com/5587fe78dc35435180eb6450dfb188c330f2e010c5034c6daa84d558940c6dee)       
![](https://ai-studio-static-online.cdn.bcebos.com/3be6e7ed91914fc2848ea94e6e4eec90ecf0dbf4e25b4d9f9cab0fe1ecbe2169)

### 本项目已经迭代了三个模型

（1）初代模型：human_pose_estimation_resnet50_mpii
我们的初代模型基于human_pose_estimation_resnet50_mpii搭建，通过paddle框架完成代码的编写，该模型使用 MPII 数据集训练完成。本网络模型的SimplePose并没有构建复杂的金字塔特征结构，它Resnet网络模型进行改造，取Resnet最后残差模块输出特征层，再通过设计反卷积模块，即在后面接上3个反卷积模块，其中每个模块由Deconv + batchnorm + relu三个数据处理块组成，对输出的特征矩阵进行上采样处理，实现输出热力图，最后将结果映射到原图片上面最后将关键点反映到原图片上。

**human_pose_estimation_resnet50_mpii效果图**

![](https://ai-studio-static-online.cdn.bcebos.com/1252e87bd636463094cbc4eefdcbec5a53743611fad048ed9518776f15871030)

（2）第二代模型：PAF（openpose）
OpenPose是第一个用于多人2D姿态检测的开源实时系统，包括身体，脚，手和面部关键点，本模型的PAFs使用Bottom-Up的方法，即先检测图像中人体关键点，然后将图像中多人的人体关键点分别分配到不同的人体实例上。具体实施过程为首先预测一组图像中人体部位位置的2D置信图S，以及一组表示部位相似性的2D矢量场L，它们表示部位之间的关联程度。

**openpose效果图**

![](https://ai-studio-static-online.cdn.bcebos.com/5204f93db7424c97bdf538fdb7fc62bdfed980ef54ad484d9c09ae94d0c332ee)

（3）第三代模型：MediaPipe Holistic
目前我们使用第三代模型MediaPipe Holistic，MediaPipe Holistic管道集成了姿态、面部和手部组件的单独模型，每个模型都针对特定领域进行了优化。但由于它们的专长不同，对一个组件的输入并不适合其他组件。例如，姿态估计模型以较低的、固定分辨率的视频帧（256×256）作为输入。但如果要从图像中裁剪手部和面部区域以传递给各自的模型，图像分辨率会过低，无法准确表达。所以，谷歌将MediaPipe Holistic设计为一个多级管道，使用一个区域适配图像分辨率来处理不同的区域。
首先，MediaPipe Holistic通过BlazePose的姿态检测器和随后的关键点模型估计人体姿态。然后，使用推断出的姿态关键点，为每只手（2x）和面部导出三个感兴趣区域（ROI；Region of Interest）裁剪，并使用重新裁剪模型来提升ROI。然后，管道将全分辨率输入帧裁剪到ROI之中，并应用特定于任务的面部和手部模型来估计它们的对应关键点。最后，将所有关键点与姿态模型的关键点合并，并得到完整的540+个关键点。

**MediaPipe Holistic识别效果图**

![](https://ai-studio-static-online.cdn.bcebos.com/273a35b7502d4c308d5a8e9fed9e0cf2576f682c787c4ed9b91a518d05638ab3)

（4）第四代模型：PP-TinyPose
PP-TinyPose是PaddleDetecion针对移动端设备优化的实时姿态检测模型，可流畅地在移动端设备上执行多人姿态估计任务。借助PaddleDetecion自研的优秀轻量级检测模型PicoDet,我们同时提供了特色的轻量级垂类行人检测模型。

**PP-TinyPose识别效果图**

![](https://ai-studio-static-online.cdn.bcebos.com/0e0e21439b1044a4a99d7933853e6966a8a87954c4154d688d51aefa395d808a)

### 其他相关介绍

1. 手势识别

基于摄像头模块，我们采用了基于2D摄像头的二维手势识，同时使用了动态手势识别技术。手势有三个主要特征：手型，方向，运动轨迹，一个基于视觉手势识别系统的构成应包括：图像的采集，预处理，特征提取和选择，分类器的设计，以及手势识别。而识别系统的关键在于预处理时手势的分割，特征提取和选择，手势跟踪，以及手势识别算法。
而手势识别的实现我们采用了MediaPipe Hands的深度学习手势识别框架，使用由多个协同工作的模型组成的 ML 管道：一个手掌检测模型，对整个图像进行操作并返回一个定向的手部边界框。一种手部地标模型，该模型对手掌检测器定义的裁剪图像区域进行操作，并返回高保真 3D 手部关键点。

**手势识别框架步骤**

![](https://ai-studio-static-online.cdn.bcebos.com/627ce68b9470445dad7fa401f1f9287c2d58088dcec64606a6b0d37c9127866b)

**手势识别控制点**

![](https://ai-studio-static-online.cdn.bcebos.com/165887d807f145e092976b76f1be786070973fd4f3cf471bae60b65741c52e01)

2. 实时监测和实时传输视频

皮影表演检测具有实时性的特点，RTMP是一种设计用来进行实时数据通信的网络协议，主要用来在 Flash/AIR 平台和支持 RTMP 协议的流媒体/ 交互服务器之间进行音视频和数据通信，适合实时性高的应用场景；使用腾讯云轻量应用服务器，它是一种易于使用和管理、适合承载轻量级业务负载的云服务器，由于带有公网 ip 所以可以实现内网穿透功能，在此基础上搭建 nginx web 服务器进行 rtmp 推流工作；由于受到网络信号、app 权限、数据处理的影响，agx到服务器上的通信会有一定的延迟，故采用多进程技术并行处理来加快处理的速度以减少延迟。开设三个进程，一个用来接收数据，一个用来处理数据，一个用来显示结果。此外使用队列数据结构存储数据，以避免数据堵塞，进一步降低通信延迟，此外在图像采集部分，将采用生产者消费者模式，摄像头采集图像作为生产者，将采集到的图像放入循环队列缓冲区，图像处理进程则作为消费者不断从缓冲区获取图像进行处理。

3. MP4格式视频检测：

在本地预先存下一段MP4格式的视频，使用cv2模块对视频进行帧提取，使用网络模型对图像帧进行关键点特征提取。

**通过视频检测**

![](https://ai-studio-static-online.cdn.bcebos.com/a459e28247364e8b870c9fa892ad052e2526b7718bdd459caf35863c26fdc689)

4. 摄像头检测：

通过摄像头获取相应的视频数据流，通过opencv模块对视频进行帧提取，使用openpose、mediapipe等网络模型对图像进行检测，最后提取图片中人体的关键点特征。

**摄像头检测示例**

![](https://ai-studio-static-online.cdn.bcebos.com/87c60ef5ddde4c99997dd14104c6836b687c36e1e9ca4a5b8de19de3d1291c74)


5. 1.7hls格式rtmp推流检测：
   当数据源不在本地时，数据源端可以通过rtmp协议推流的方式将视频数据推流到nginx-rtmp服务器，识别终端使用opencv模块通过rtmp协议拉流将视频从nginx服务器上面拉取到程序里面，再进行相对应的图像检测。


**hls 数据流**

![](https://ai-studio-static-online.cdn.bcebos.com/5f2445824c624cfda4602e8c178c3bad65a4dfe706dd44239646921f206c24b7)


6. 腾讯云：

腾讯云是腾讯公司旗下的产品，为开发者及企业提供云服务、云数据、云运营等整体一站式服务方案。
具体包括云服务器、云存储、云数据库和弹性web引擎等基础云服务；腾讯云分析（MTA）、腾讯云推送（信鸽）等腾讯整体大数据能力；以及 QQ互联、QQ空间、微云、微社区等云端链接社交体系。这些正是腾讯云可以提供给这个行业的差异化优势，造就了可支持各种互联网使用场景的高品质的腾讯云技术平台。
在项目中服务器作为运算终端，用于图像关键点的提取。

7. 百度AI Studio：

百度AI Studio是针对AI学习者的在线一体化学习与实训社区. 本平台集合了AI教程, 深度学习样例工程, 各领域的经典数据集, 云端的超强运算及存储资源, 以及比赛平台和社区.
从而解决学习者在AI学习过程中的一系列难题, 例如教程水平不一, 教程和样例代码难以衔接, 高质量的数据集不易获得, 以及本地难以使用大体量数据集进行模型训练.


8. 皮影机器人运动学正解与反解

为了对皮影及人进行运动模拟和控制，需对机器人进行运动学分析。从机构学角度来看．关节型非移动机器人操作机是由一系列用关节连在一起的构件所组成的具有多个自由度的开链型空间连杆机构。所以对机器人进行运动学、动力学分析时，可将机器人简化成由各连杆和末端执行器首尾相接，并通过关节相连而构成的一个开式连杆系。据此将机器人简化为连杆机构，并在底座上建立基坐标系，每个关节上建立一相对运动坐标系。
当机器人操作机的结构参数和运动参数确定后，便可由机器人运动学方程来确定机器人末端执行器在机座坐标系中的位姿。根据连杆系统变换矩阵T的通式，将连杆参数代人通式中，可得到连杆变换矩阵，然后将连杆变换矩阵代入运动方程中，即可解得机器人末端参考点在基坐标系中的位姿矩阵T，完成整解。
若已知机器人操作机的末端位姿(n，0。a，p)。通过齐次坐标变换，即可求出末端执行器在基坐标系中的位置和方向。经推导可求出其几个关节变量的运算公式。

9. 皮影机器人坐标系

![](https://ai-studio-static-online.cdn.bcebos.com/ebd67526276740a18cc3d6154108bc6beb54925c3d0044bbab12e69d1dfb810d)

在过程控制中，按偏差的比例（P）、积分（I）和微分（D）进行控制的PID控制器（亦称PID调节器）是应用最为广泛的一种自动控制器。有原理简单，易于实现，适用面广，控制参数相互独立，参数的选定比较简单等优点。
我们对皮影机器人底盘移动直流电机采用PID算法，使用位置闭环控制，根据编码器的脉冲累加测量电机的位置信息，并与目标值机械比较，得到控制偏差，然后通过对偏差的比例、积分、微分进行控制，使偏差趋向零，从而实现皮影机器人底盘的精确移动。

**PID控制直流电机框图**

![](https://ai-studio-static-online.cdn.bcebos.com/c874001e6a1e4587b277f12defcd48560bc45067b0b5476083a4bb4c50570f4e)

### 机械设计

1. 拟人体结构：

对于皮影机器人的结构设计，我们不同于以往的用机械臂操作皮影的结构设计，而是采用骨架识别人体骨骼关键点和皮影控制点相适应的拟人机械结构。将皮影的控制结构与人体骨骼关键点一一相对应，并按人体的关节位置排列方式分布，形成了类人体的机械结构。这种机械结构改变了传统需要复杂多变手势操作皮影表演的方式，大大简化了皮影戏的控制算法，使皮影戏自动化智能化操控成为了可能。

#### 拟人体结构

![](https://ai-studio-static-online.cdn.bcebos.com/edb5151e02d5427ab7581dd856f8a0bf9fad9c9911c14430a4e3987dbff1b673)

2. 多关节控制设计：

对于皮影机器人的支点控制，我们采用了多关节控制设计，不同于以往传统手工操作的皮影戏只能同时实现皮影模型3个点的控制，而是能够实现皮影机器人背板上的2个肩关节、2个髋关节关节的控制，同时设计了肢体装置，拓展了对皮影模型肘关节、膝关节的控制，而根据皮影模型的需要，可以实现人体所有肢体关节的舵机控制，增加了皮影机器人的关节控制自由度。

#### 肢体装置

![](https://ai-studio-static-online.cdn.bcebos.com/e59351dad98946e5a381c3235e4d2a32675e44e632ab44038d3e6b9ac46de047)


3. 关节旋转驱动控制设计：

对于皮影模型动作的驱动方式，我们使用可以360°旋转的舵机作为关节控制，舵机与皮影控制关节通过传动直杆连接，采用连杆杠式的连接方式、回转型的控制方式，舵机轴转动部与活动关节一一对应安装。舵机旋转便可以直接带动皮影模型关节的旋转，同时带动皮影模型肢体关节的旋转，即舵机角度直接决定皮影模型的姿态，这种关节控制的方式大大简化了皮影机器的运动模型，可以实现更多的复杂动作。

4. 水平移动设计：

皮影机器人底部安装了滑块，滑块安装在导轨上，通过控制导轨上的滑块左右运动可以实现皮影机器人的水平左右移动，进而满足皮影戏表演的舞台需要。

#### 水平移动导轨

![](https://ai-studio-static-online.cdn.bcebos.com/5197f6e592ec4848956dd9470aad0f2ad86901cc456141f6940747f77e32927c)

5. 可替换式皮影机器人：

为了兼容多种不同皮影模型控制，我们将皮影机器人背板设计为可拆式，针对不同皮影模型，只需要根据皮影模型关节排布设计对应的皮影机器人背板，在使用不同的皮影模型时，更换不同的皮影背板即可，从而使皮影机器人兼容性强，适用的模型丰富。

### 硬件设计

1. 数据处理模块

（1）Jetson agx：
上位机深度学习人体骨架识别在Jetson agx上进行数据处理，Jetson agx作为世界领先的 AI 迷你超级计算机。它性能强大，外形小巧，节能高效，适合机器人、无人机、智能摄像机和便携医疗设备等智能终端设备，能够快速训练和部署神经网络。可以实时提取摄像头获取的图像，使用opencv模块，通过VideoCapture函数指定视频流的数据源，输入到PAF骨架识别神经网络进行人体骨骼特征点提取，同时通过几何算法、运动学正逆解算法求解皮影机器人的关节、位置运动信息。

#### Jetson agx

![](https://ai-studio-static-online.cdn.bcebos.com/bd6e2704f36e4d22bfb8099cf761cf02cafd0777effe4891af22d1c5d024831c)

（2）Nano：
NVIDIA® Jetson Nano打开了嵌入式物联网应用程序的新世界，包括入门级网络视频录像机 (NVR)、家用机器人和具有完整分析功能的智能网关。 Jetson Nano 还是在现实环境中开始学习 AI 和机器人技术的完美工具，拥有随时可用的项目，并得到活跃而热情的开发者社区的支持。
在项目中nano主要作为数据接收终端，图像经由腾讯云或ai studio等云服务器进行处理后解析得到的角度数据通过socket发送到nano端，nano再将这些数据通过串口传输到stm32主控板。

#### Nano外观图

![](https://ai-studio-static-online.cdn.bcebos.com/da13f9de491a4911954f1f3aacd14b8835a4d56234c54a64bdf0e961f3d36e1b)

2. 下位机硬件部分

（1）图像采集模块
图像采集模块主要由USB摄像头组成，USB摄像头通过实时拍摄获取人体姿态估计检测所需要的数据。其分辨率为720P，传输速率每秒为30帧，能够满足实时检测估计人体姿态深度学习神经网络的需要。

#### 摄像头

![](https://ai-studio-static-online.cdn.bcebos.com/449ee80d07344b49b1ad5d03cb70659b452cfaf8c67b4a158d14156df1cb4768)


（2）通信模块：
通信模块采用USB转TTL串口模块或蓝牙BLE4.0，能够将上位机Jetson agx处理获得的人体骨骼关键点的旋转角度通过串口协议发送到下位机stm32上。具有稳定可靠的特定，不容易受外界无线电信号干扰，能够确保传输数据的可靠性。

（3）控制模块：
控制模块是由嵌入式设备stm32主控板组成的，能够接收串口模块传输过来的中央处理器发送的人体关节旋转信息，进行数据解析再发送控制驱动信号给驱动模块，使皮影机器人准确运动。
图3-31 关节控制流程图

（4）驱动模块：
驱动模块由16路PWM Servo舵机驱动板以及L298N组成。16路PWM Servo舵机驱动板内置了PWM驱动器和时钟，接收主控通过I2C协议发送的舵机驱动信号，实现多路PWM输出，驱动皮影机器人舵机运动。L298N则接收到主控发送的PWM信号驱动皮影机器人底盘移动。

（5）运动模块：
运动模块由六个DSD3230舵机和一个直流电机组成，在舵机、直流电机驱动器的驱动下，皮影机器人的6个关节移动旋转由6个360°舵机驱动旋转，而皮影机器人的水平移动通过1个直流电机旋转衔接履带带动机器人底盘平移移动。从而实现皮影机器人的仿人姿态与水平移动。

#### 皮影机器人运动流程图

![](https://ai-studio-static-online.cdn.bcebos.com/df4a0609c0cf4e15a9032c098de1611d93e351e0fcc34547bb08cfae097f4d94)

#### 皮影机器人舵机细图

![](https://ai-studio-static-online.cdn.bcebos.com/46308e0f1e8a43d68effb2b67d37ee390d53beedce044c5ca2efa738e7736ecd)

（6）语音模块
语音模块采用LD3320语音识别模块。LD3320能够记录设定接收到人的中文语音信息，最多可以记录50条中文语音信息，识别范围为2米。开启识别模式时，能够识别人声中文语音特定信息，从而实现语音识别的功能。
（7）电源模块
皮影机器人电源主要驱动底盘的减速直流电机和关节上的高扭力舵机，直流减速电机的驱动电压为12V，舵机的工作电压为4.8->6.8V，原电源方案考虑工作电流较大使用3S锂电池供电使用BUCK电路降压驱动舵机工作，后续由于机械结构的调整决定将电源部分分开，关节舵机部分和底盘直流电机部分的供电分开。
在皮影机器人关节舵机工作的过程中，由于电池需要给五个高扭力的舵机，在运行时出现机械设计问题时还会出现舵机堵转的情况，会在瞬间拉高电流，使电池发生过流现象，会对电池造成损坏，同时舵机需要电池有较大的放电能力，在实际工作中也可能会发生电池过放的情况，造成安全隐患，为了针对这个问题，我们设计了电源保护板
电源保护板我们使用了常见的DW01配合MOS管8205A方案进行设计，当锂电池电压在2.5->4.3V时 DW01的1脚 3脚均为高电平，第二脚位0V。此时DW01的1、3脚分别加压到8205A的5脚和4脚，8205A内的两个MOS管的G极接收到电压处于导通状态，此时电池的负极与保护板的P-端相当于接通，保护板有电压输出。

#### 电源模块原理图

![](https://ai-studio-static-online.cdn.bcebos.com/3ea2e03c58df4eea88a4f21be655d6097e8da99d10d940ac95d7f42cb046cbdd)

1.过放保护
电池外接负载放电，电压降低，DW01内部将R2电阻检测电池电压，当电池电压下降到2.3V左右DW01判定电池处于过放状态，断开1脚地输出电压，使1脚电压变为0V，8205A内地开关管关闭，此时B-与P-之间处于断开状态，停止放电。
2.过流保护
8205A内的mos管存在内阻，当G极电压小于0.7V一下时，开关管的导通内阻很大，相当于开关闭合，8205A的导通电阻与放电电流产生的电压在负载电流增大时增大，上升到0.2V时负载电流到极限，停止1脚的输出电压，使1脚电压变为0V、8205A的放电控制关闭，切断放电电路，实现了过流保护。

#### 3D图

![](https://ai-studio-static-online.cdn.bcebos.com/78bc5632d8c74123a8d6f9cf41b2305ecc54b9acc7b743fcb11322e5ffd950d7)

#### 电源保护电路PCB图

![](https://ai-studio-static-online.cdn.bcebos.com/2978c78d4f504a4083012f4268986356e435673ef2454ea9be29f1791a1e856e)


## 最终效果

![](https://ai-studio-static-online.cdn.bcebos.com/a565d678a75048b08c2081db937cd60b061bcced34dc4e3189c84ad5da515d2d)
![](https://ai-studio-static-online.cdn.bcebos.com/1dea3c582ca449b3a8b3914ee1abac36fbe251b3e3444955b7e812237f58d09f)
![](https://ai-studio-static-online.cdn.bcebos.com/881ed8750d3348eaba18d8b2c71c29fa63c5aafb3fb147cd904df84e50a5910b)
![](https://ai-studio-static-online.cdn.bcebos.com/c91eca0fd23b4d0bbde47e2622a32d8884eec756ff2c46648ca9954656449435)
![](https://ai-studio-static-online.cdn.bcebos.com/46ae61bbf1b14665b7ff02d7778b16c96bb8ab7900584ea2bc8c01ca77eb7884)

## 作品总结

我们从最初有皮影机器人的想法,到分工合作分别搭建机器人组件与算法,机械结构设计，再到软硬件相结合的调试改进,最后成功搭建出一个能投入到实际应用中使用的皮影机器人, 我们付出了汗水也收获了成功的喜悦。

回首望去，我们已实现了：

1)配置了由舵机与亚克力板为主的皮影硬件模型。

2)利用 rtmp 等传输协议，通过云端传送的视频流远程进行数据分析。

3)在角度转化中，使用 三角函数，向量计算等 对人体关键点坐标进行转化。

4)关于人体关键点检测,我们选择了 paddlepaddle，openpose，
mediapipe 等网络模型 对人体关键点特征进行提取。

5)在数据云存储中,实现了基于七牛云的二次开发,使其符合我们初期的
设想。

经过这次项目开发，我们认识到要想实现一个机器人是需要软硬件
的相互配合，需要考虑诸多因素，实现许多功能才能满足人们的需求从
而完成所需的任务，这也说明了机器人领域是一个复杂多变，影响因素
众多但值得人们进行探索的领域。且目前我国机器人领域发展迅猛、需
求巨大，值得引起我们的关注。在之后的开发中，我们会不断完善该项
目，使其能真正的运用到实际生活中，从而大大改善人们的生活。

## 核心代码
```python
import cv2
import paddlehub as hub
import serial
import math
# 导入sympy
from sympy import *


# ------------- 串口操作 --------------------- start
# 串口打开函数
def open_ser():
    port = '/dev/ttyUSB1'  # 串口号
    baudrate = 9600  # 波特率
    try:
        global ser
        ser = serial.Serial(port, baudrate, timeout=0.5)
        if (ser.isOpen() == True):
            print("串口打开成功")
    except Exception as exc:
        print("串口打开异常", exc)


# 数据发送
def send_msg(the_data):
    try:
        # send_datas = input("请输入要发送的数据\n")
        send_datas = str(the_data)

        ser.write(str(send_datas).encode("gbk"))
        print("已发送数据:", send_datas)
    except Exception as exc:
        print("发送异常", exc)


# 接收数据
def read_msg():
    try:
        print("等待接收数据")
        while True:
            data = ser.read(ser.in_waiting).decode('gbk')
            if data != '':
                break
        print("已接受到数据:", data)
    except Exception as exc:
        print("读取异常", exc)


# 关闭串口
def close_ser():
    try:
        ser.close()
        if ser.isOpen():
            print("串口未关闭")
        else:
            print("串口已关闭")
    except Exception as exc:
        print("串口关闭异常", exc)


# ------------- 串口操作 --------------------- end


# ---------- 关键点转换角度 --------------- start
def fun(y1, y2):
    return solve([y1, y2], ['x', 'y'])


def init(A, B, C):
    if A[0] - B[0] == 0:
        return -1
    k1 = (A[1] - B[1]) / (A[0] - B[0])
    k2 = -1 * k1
    b1 = A[1] - k1 * A[0]
    b2 = C[1] - k2 * C[0]

    x = Symbol('x')
    y = Symbol('y')
    y1 = k1 * x + b1 - y
    y2 = k2 * x + b2 - y

    return fun(y1, y2)


def to_angle(A, B, C):
    '''
        cosA = (b^2+c^2-a^2)/(2bc)
        A = arcos((b^2+c^2-a^2)/(2bc))
    '''
    a = ((B[0] - C[0]) ** 2 + (B[1] - C[1]) ** 2) ** 0.5
    b = ((A[0] - C[0]) ** 2 + (A[1] - C[1]) ** 2) ** 0.5
    c = ((A[0] - B[0]) ** 2 + (A[1] - B[1]) ** 2) ** 0.5
    # print(a,b,c)
    if (2 * b * c) == 0:
        return -1
    resual = (b ** 2 + c ** 2 - a ** 2) / (2 * b * c)
    if resual > 1:
        resual = 1
    elif resual < -1:
        resual = -1

    return math.degrees(math.acos(resual))


def to_left_shoulder(resual):
    left_elbow = resual['left_elbow']
    left_shoulder = resual['left_shoulder']
    A = left_shoulder
    B = left_elbow
    C = [left_shoulder[0], left_shoulder[1] + 100]
    the_data = to_angle(A, B, C)

    return the_data


def to_right_shoulder(resual):
    left_elbow = resual['right_elbow']
    left_shoulder = resual['right_shoulder']
    A = left_shoulder
    B = left_elbow
    C = [left_shoulder[0], left_shoulder[1] + 100]
    the_data = to_angle(A, B, C)

    return the_data


def to_right_elbow(resual):
    right_elbow = resual['right_elbow']
    right_shoulder = resual['right_shoulder']
    right_wrist = resual['right_wrist']
    A = right_shoulder
    B = right_elbow
    C = right_wrist
    # print(A,B,C)
    x = Symbol('x')
    y = Symbol('y')
    # print(init(A, B, C))
    if init(A, B, C) == -1:
        return 0
    if init(A, B, C) == []:
        return 0
    # print(init(A, B, C))
    B = [init(A, B, C)[x], init(A, B, C)[y]]
    the_data = to_angle(A, B, C)

    return the_data


def to_left_elbow(resual):
    right_elbow = resual['left_elbow']
    right_shoulder = resual['left_shoulder']
    right_wrist = resual['left_wrist']
    A = right_shoulder
    B = right_elbow
    C = right_wrist

    x = Symbol('x')
    y = Symbol('y')
    B = [init(A, B, C)[x], init(A, B, C)[y]]
    the_data = to_angle(A, B, C)

    return the_data


def to_right_foot(resual):
    left_elbow = resual['right_knee']
    left_shoulder = resual['right_hip']
    A = left_shoulder
    B = left_elbow
    C = [left_shoulder[0], left_shoulder[1] + 100]
    the_data = to_angle(A, B, C)

    return the_data


def to_left_foot(resual):
    left_elbow = resual['left_knee']
    left_shoulder = resual['left_hip']
    A = left_shoulder
    B = left_elbow
    C = [left_shoulder[0], left_shoulder[1] + 100]
    the_data = to_angle(A, B, C)

    return the_data


# ---------- 关键点转换角度 --------------- end


def out_points(img):
    '''
        全部肢体位置的键
        踝:'left_ankle','right_ankle'
        膝盖:'left_knee','right_knee'
        髋:'left_hip','right_hip'
        骨盆:'pelvis',胸部:'thorax',上颈:'upper_neck',头顶:'head_top'
        手腕:'right_wrist','left_wrist'
        肘:'right_elbow','left_elbow'
        肩膀:'right_shoulder','left_shoulder'
    '''
    pose_estimation = hub.Module(name="human_pose_estimation_resnet50_mpii")
    result = pose_estimation.keypoint_detection(images=[img], visualization=True)
    points = result[0]['data']
    return points


def standardization(data):
    data = str(int(data+0.5))
    if len(data) == 1:
        data = '00'+data
    elif len(data) == 2:
        data = '0' + data
    else:
        pass

    return data


if __name__ == "__main__":
    is_send = False  # 是否发送数据到stm32机器人

    if is_send is True:
        open_ser()  # 打开串口
        send_msg('a000b000c000d000e000f000Z')  # 为机器人复位

    capture = cv2.VideoCapture("test01.mp4")  # 读取视频, 0: 从摄像头

    count_frame = 0
    while capture.isOpened():
        ret, image = capture.read()

        if count_frame < 1:
            count_frame+=1
            continue
        count_frame = 0

        '''
        识别人体关键点坐标数据格式： 
        resual: OrderedDict([
            ('left_ankle', [243, 790]), 
            ('left_knee', [243, 700]),
            ('left_hip', [232, 580]), 
            ('right_hip', [294, 590]), 
            ('right_knee', [294, 710]),
            ('right_ankle', [289, 800]),
            ('pelvis', [260, 580]),
            ('thorax', [260, 430]), 
            ('upper_neck', [260, 400]), 
            ('head_top', [266, 280]),
            ('right_wrist', [136, 580]), 
            ('right_elbow', [175, 510]),
            ('right_shoulder', [209, 430]), 
            ('left_shoulder', [323, 430]),
            ('left_elbow', [334, 510]),
            ('left_wrist', [323, 590])
        ])
        '''
        resual = out_points(image)
        print(resual)

        '''
        # 关键点坐标转化为角度
        a_angle = standardization(to_left_elbow(resual))  # 肩膀到手肘方向与手肘到手腕方向上的夹角（左）
        b_angle = standardization(to_left_shoulder(resual))  # 肩膀到手肘方向与肩膀竖直方向上的夹角（左）
        c_angle = standardization(to_left_foot(resual))  # 盆骨到膝盖方向与盆骨竖直方向上的夹角（左）
        d_angle = standardization(to_right_foot(resual))  # 盆骨到膝盖方向与盆骨竖直方向上的夹角（右）
        e_angle = standardization(to_right_shoulder(resual))  # 肩膀到手肘方向与肩膀竖直方向上的夹角（右）
        f_angle = standardization(to_right_elbow(resual))  # 肩膀到手肘方向与手肘到手腕方向上的夹角（右）
        print("---------- send data -------------")
        print(f'a{a_angle}b{b_angle}c{c_angle}d{d_angle}e{e_angle}f{f_angle}Z')
        print("----------------------------------")

        if is_send is True:
            send_msg(f'a{a_angle}b{b_angle}c{c_angle}d{d_angle}e{e_angle}f{f_angle}Z')  # 发送数据到机器人
        '''

        # cv2.imshow("image", cv2.resize(image, (720,480)))
        # cv2.waitKey(1)

    if is_send is True:
        close_ser()  # 关闭串口通讯
    # 释放摄像头
    capture.release()
    # 关闭所有窗口
    cv2.destroyAllWindows()
```