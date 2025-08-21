---
pageClass: home-page
# some data for the components

name: Wenjin Deng
profile: /profile4.jpg

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/WinstonDeng
  - title: zhihu
    icon: "/icons/zhihu.svg"
    link: https://www.zhihu.com/people/deng-wen-jin-36-27/posts
  - title: google scholar
    icon: "/icons/google-scholar.svg"
    link: https://scholar.google.com/citations?user=xi3HtBUAAAAJ&hl=zh-CN
  # - title: CSIG Member

# researchgate: https://en.wikipedia.org/wiki/Harry_Potter
# Student at Xiamen University 
bio: SSP = Strong + Smart + Professional 
# 本是尘世一蚍蜉，何须争与鹏高起
# 仰势乘风浮塔尖，自在静悟九万里
email: dengwenjin@stepfun.com / dengwenjin@stu.xmu.edu.cn  
---

<ProfileSection :frontmatter="$page.frontmatter" />

- CSIG Member

## About Me
<!-- (https://vcg.xmu.edu.cn/) -->
I'm currently an AI Researcher & Engineer at in [StepFun](https://www.stepfun.com/), focusing on Agentic Model, supervised by [Binxing Jiao](https://scholar.google.com/citations?user=tAAjbqgAAAAJ&hl=zh-CN&oi=ao) and [Chen Hu](https://scholar.google.com/citations?hl=zh-CN&user=z9SAY1UAAAAJ). Before that I served as R&D Engineer in [Momenta](https://www.momenta.cn/en/), working on perception group of MSD (Momenta Self-Driving).

I got my Master's degree and Bachelor's degree in the School of Informatics at Xiamen University. Especially, I spent wonderful time from 2019 to 2023 in the [Visual Computing and Graphics Lab](https://vcg.xmu.edu.cn/), supervised by associate professor [Ming Zeng](http://mingzeng.xyz/). In 2022.6 -2022.9, I served as a virutal human research intern at [Virtual Human Group](https://fuxivirtualhuman.github.io/) of [NetEase Fuxi AI Lab](https://fuxi.163.com/), working with [Zhimeng Zhang](https://scholar.google.com/citations?user=FGRtKVoAAAAJ&hl=zh-CN&oi=ao) and [Yu Ding](https://scholar.google.com/citations?hl=zh-CN&user=T9Vd-rcAAAAJ&view_op=list_works&sortby=pubdate).

My research interests lie at Computer Vision and Multi-modality LLM. I'm particularly interested in the areas of human-centric perception (pose estimation, restruction), generation and animation (speech audio or natural language driven).
## News
- [Oct. 2023] Our work on 3D Human Reconstruction has been accepted by Graphical Models.
- [Sep. 2023] Our two National Invention Patents from China have been officially granted.
- [Nov. 2022] Our work on singing head generation has been accepted by CVM2023 and CVMJ.
- [Nov. 2022] Our work on talking head generation has been accepted by AAAI2023.
- [Oct. 2022] I and my roommate [Yinglin Zheng](https://yinglinzheng.netlify.app/) won the National Scholarship for Graduate Students at the same time.
- [Aug. 2022] Our work on talking head generation has been submitted to AAAI2023.
- [Apr. 2022] Our work on multi-person pose estimation has been accepted by IJCAI2022.
- [Mar. 2021] Our work on maksed face revealing is accepted by ICME 2021 as oral presentation.
- [Feb. 2021] My [zhihu survey on human pose](https://mp.weixin.qq.com/s/PNcclVdReiay5LXvlgMEyA) is re-tweeted by several well-known AI WeChat accounts.
- [Oct. 2020] Our work on human pose estimation is accepted by PRCV 2020.

## Some of my paper co-authors
<!-- [Jing Liao](https://liaojing.github.io/html/), Assistant Professor with the Department of Computer Science, City University of Hong Kong <br> -->
[Ming Zeng](http://mingzeng.xyz/), Associate Professor at School of Informatics, Xiamen University <br>
[Yinglin Zheng](https://yinglinzheng.netlify.app/), Research Intern at Visual Computing Group, Microsoft Research Asia (MSRA) <br>
[Jinpeng Lin](https://github.com/JPlin), Researcher at AlibabaGroup <br>

## Publications

<ProjectCard hideBorder=true image="https://ars.els-cdn.com/content/image/1-s2.0-S1524070323000371-ga1_lrg.jpg">

  Vertex position estimation with spatial–temporal transformer for 3D human reconstruction

  Xiangjun Zhang, Yinglin Zheng, **Wenjin Deng**, Qifeng Dai, Yuxin Lin, Wangzheng Shi, Ming Zeng
  
  2023, Graphical Models

 [Paper](https://www.sciencedirect.com/science/article/pii/S1524070323000371)

</ProjectCard>


<ProjectCard hideBorder=true image="/musicface.png">

  MusicFace: Music-driven Expressive Singing Face Synthesis

  Pengfei Liu, **Wenjin Deng**, Hengda Li, Jintai Wang, Yinglin Zheng, Yiwei Ding, Xiaohu Guo, Ming Zeng
  
  2022, The Computational Visual Media Conference (CVM2023)

 [Paper](https://arxiv.org/pdf/2303.14044.pdf) [Data](https://vcg.xmu.edu.cn/datasets/singingface/index.html)

</ProjectCard>

<ProjectCard hideBorder=true image="/DINet.png">

  DINet: Deformation Inpainting Network for Realistic Face Visually Dubbing on High Resolution Video

  Zhimeng Zhang*, Zhipeng Hu*, **Wenjin Deng***, Changjie Fan, Tangjie Lv, Yu Ding*
  
  2022, Thirty-Seventh AAAI Conference on Artificial Intelligence. (AAAI2023)

 [paper](https://fuxivirtualhuman.github.io/pdf/AAAI2023_FaceDubbing.pdf) [Code](https://github.com/MRzzm/DINet) 

</ProjectCard>

<ProjectCard hideBorder=true image="https://s1.ax1x.com/2022/04/21/LyGJKK.png">

  I^2R-Net: Intra- and Inter-Human Relation Network for Multi-Person Pose Estimation

  Yiwei Ding*, **Wenjin Deng***, Yinglin Zheng, Pengfei Liu, Jianmin Bao, Meihong Wang, Xuan Cheng, Ming Zeng, Dong Chen
  
  2022, The 31st International Joint Conference on Artificial Intelligence (IJCAI2022)

 [Paper](https://arxiv.org/pdf/2206.10892.pdf) [Code](https://github.com/leijue222/Intra-and-Inter-Human-Relation-Network-for-MPEE)

</ProjectCard>

<!-- <ProjectCard hideBorder=true image="https://s1.ax1x.com/2022/08/26/v2cJMD.png">

  Improving Person Re-identification with Semantically Aligned Appearance Transformer

  Hui Li, Yinglin Zheng, Zhaodong Tan, **Wenjin Deng**
  
  2022, IJCNN at IEEE World Congress on Computational Intelligence Chairs (WCCI2022), Oral presentation.

</ProjectCard> -->

<ProjectCard hideBorder=true image="/projects/contrable.png">

  Controllable Facial Caricaturization with Localized Deformation and Personalized Semantic Attentions

  Ming Zeng, Yinglin Zheng, Jinpeng Lin,  Xuan Cheng, Jing Liao, Zizhao Wu, **Wenjin Deng**

  2021, IEEE Transactions on Multimedia (TMM2021).

  [Link](https://ieeexplore.ieee.org/document/9535294)

</ProjectCard>

<ProjectCard hideBorder=true image="/projects/mask_face.png">

  Real-time Masked Face Revealing for Video Conference

  Jinpeng Lin, Pengfei Liu, Yinglin Zheng, **Wenjin Deng**, Ming Zeng

  2021, IEEE International Conference on Multimedia and Expo (ICME2021), Oral presentation.

  [Link](https://ieeexplore.ieee.org/document/9428117)

</ProjectCard>


<ProjectCard hideBorder=true image="/projects/vh3d.png">

  VH3D-LSFM:Video-based Human 3D Pose Estimation with Long-term and Short-term Pose Fusion Mechanism

  **Wenjin Deng**, Yinglin Zheng, Hui Li, Xianwei Wang, Zizhao Wu, Ming Zeng

  2020, Chinese Conference on Pattern Recognition and Computer Vision (PRCV2020)

  [Link](https://link.springer.com/chapter/10.1007/978-3-030-60633-6_49)

</ProjectCard>



## Patents and Copyrights
<!--
<ProjectCard hideBorder=true >

 \[中国国家发明专利\] CN202111117800.8 一种感知环境的语音驱动虚拟人姿态合成方法 （已授权）  

  曾鸣;**邓文晋**;丁艺伟;刘鹏飞

</ProjectCard>

<ProjectCard hideBorder=true >

 \[中国国家发明专利\] CN202011092625.7 一种利用长短期信息融合的视频三维人体姿态估计算法 （已授权）

  曾鸣;**邓文晋**

</ProjectCard>

-->

<ProjectCard hideBorder=true>
 - \[中国国家发明专利\] CN202111117800.8 一种感知环境的语音驱动虚拟人姿态合成方法 （已授权）  

  曾鸣;**邓文晋**;丁艺伟;刘鹏飞

 - \[中国国家发明专利\] CN202011092625.7 一种利用长短期信息融合的视频三维人体姿态估计算法 （已授权）

  曾鸣;**邓文晋**
  
 - \[中国国家发明专利\] CN202110750794.3 一种利用语音信息的实时视频人脸区域时空一致合成方法 （已授权）

  曾鸣;刘鹏飞;**邓文晋**

 - \[中国国家发明专利\] CN202011408727.5 一种增强医患相互信任减少医患矛盾评估预警系统 （已授权）

  赵一麟;曾鸣;**邓文晋**;刘秋松;张红建;潘恒;丁艺伟;周旭;郭鹏;周媛媛;刘凤武

 - \[软件著作权\] 2019SR0447844 智能交互健身系统 （已授权）

  曾鸣,周熙盟,黄译嶙,陈梓豪,**邓文晋**

</ProjectCard>

<!-- <ProjectCard hideBorder=true>

 \[中国国家发明专利\] CN202011408727.5 一种增强医患相互信任减少医患矛盾评估预警系统 （公审中）

  赵一麟;曾鸣;**邓文晋**;刘秋松;张红建;潘恒;丁艺伟;周旭;郭鹏;周媛媛;刘凤武

</ProjectCard>

<ProjectCard hideBorder=true>

 \[软件著作权\] 2019SR0447844 智能交互健身系统 （已授权）

  曾鸣,周熙盟,黄译嶙,陈梓豪,**邓文晋**

</ProjectCard> -->


## Projects

<ProjectCard hideBorder=true image="/projects/case.png">

  A management system for case workflow

  Java Backend: **Wenjin Deng**, [Pengfei Liu](https://github.com/BlacksLiu)

  H5 frontend: [Yiwei Ding](https://github.com/leijue222), **Wenjin Deng**
  
  2021

</ProjectCard>

<ProjectCard hideBorder=true image="/projects/watermeter.png">

  Watermeter Reader Autonomous System for paper *Image-Based Automatic Watermeter Reading under Challenging Environments*

  Java Backend: **Wenjin Deng**, Jian Wang

  H5 frontend: [Yiwei Ding](https://github.com/leijue222)
  
  2020

  [Paper Link](https://www.mdpi.com/1424-8220/21/2/434)

</ProjectCard>

<ProjectCard hideBorder=true image="/projects/iFit.png">
  AI fitness coach in web(PC/Mobile) using our Human Pose Estimation Network. Benefit from our design, it infers well pose on user's local device with 25fps.

  Human Pose Estimation Algorithm & Website: [Zihao Chen](https://github.com/sppleHao), **Wenjin Deng**

  Team: Ximeng Zhou, [Zihao Chen](https://github.com/sppleHao), **Wenjin Deng**, Yilin Huang

  2018.08-2019.5

  [Media Report](https://www.sohu.com/a/315247559_685340)

</ProjectCard>

<ProjectCard hideBorder=true image="/projects/ooad.png">
  A course system in web(PC/Mobile) using Springboot and VUE.

  Java Backend: [Shiqi Wang](https://github.com/17Wang), **Wenjin Deng**

  H5 frontend: Tianyu Su, [Zihao Chen](https://github.com/sppleHao)

  2018.11-2019.1

  [Project Link](https://github.com/OOAD2-3/RBS)

</ProjectCard>



## Awards & Honors

- National Scholarship for Graduate Students, Xiamen University, China, 2022
- Cho Tak Wong Scholarship, Xiamen University, China, 2021
- **Outstanding prize (1st place)** of the 12nd "Intel Cup" national undergraduate software innovation competition, Shanghai, China, 2019.


## Education 

- **School of Informatics, Xiamen University, M.S.** <br/>
Sept. 2020 - Jun. 2023

- **School of Informatics, Xiamen University, B.S.** <br/>
Sept. 2016 - Jun. 2020

## Thanks
Great thanks to my friend [Yinglin Zheng](https://yinglinzheng.netlify.app/).
<!-- Custom style for this page -->


<a href="http://www.easycounter.com/">
<img src="http://www.easycounter.com/counter.php?whiteair" border="0" alt="stats counter">
</a>

<style lang="stylus">

.theme-container.home-page .page
  font-size 14px
  font-family "lucida grande", "lucida sans unicode", lucida, "Helvetica Neue", Helvetica, Arial, sans-serif;
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /* Override */
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
      img
        max-width 120px
        max-height 120px
    .card-content p
      -webkit-margin-after 0.2em

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img 
          width 100%
          max-width 400px

</style>

