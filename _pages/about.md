---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
# 下面是你新加的 "selected publications" 列表数据
# 这里的每一项对应单独一篇论文，“image_path”代表左边的缩略图
selected_papers:
  - image_path: "fd-deeploc.jpg"
    alt: "paper thumbnail"
    title: "<a href='https://www.nature.com/articles/s41592-023-01775-5'><span style='font-size: 0.8em;'>Field-dependent deep learning enables high-throughput whole-cell 3D super-resolution imaging</span></a>"
    excerpt: >
      **Fu, S.<sup>#</sup>**, Shi, W.<sup>#</sup> et al. *Nat Methods* 20, 459–468 (2023). <br>
      We model the **spatially variant PSF** of a large FOV (180 × 180 × 5 μm<sup>3</sup>) and develop a **field-dependent** deep-learning method to precisely localize single molecules for 3D SR imaging.
    # url: "https://www.nature.com/articles/s41592-023-01775-5"
    # btn_label: "Read Paper"
    # btn_class: "btn--primary"

  - image_path: "dmo-psf.png"
    alt: "paper thumbnail"
    title: "<a href='https://doi.org/10.1364/OL.460949'><span style='font-size: 0.8em;'>Deformable mirror based optimal PSF engineering for 3D super-resolution imaging</span></a>"
    excerpt: >
      **Fu, S.** et al. *Opt. Lett.* 47, 3031–3034 (2022). <br>
      We **maximize the PSF information content** within the modulation space of a deformable mirror to achieve better 3D localization precision.
  
  - image_path: "liteloc.jpg"
    alt: "paper thumbnail"
    title: "<a href='https://doi.org/10.1038/s41467-025-62662-5'><span style='font-size: 0.8em;'>Scalable and lightweight deep learning for efficient high accuracy single-molecule localization microscopy</span></a>"
    excerpt: >
      Fei, Y.<sup>#</sup>, **Fu, S.<sup>#</sup>**, Shi, W.<sup>#</sup> et al. *Nat Commun* 16, 7217 (2025). <br>
      We propose a **competitively parallel** data analysis framework with a **lightweight network** to massively increase the SMLM data analysis throughput.

ongoing_projects:
  - image_path: "lunar.png" # 换成你新项目的预览图名字
    alt: "project thumbnail"
    # 这里依然可以嵌入调整字体或加入超链接
    title: "<a href='https://www.biorxiv.org/content/10.1101/2025.02.16.638552v2'><span style='font-size: 0.8em;'>Aberration-aware 3D localization microscopy via self-supervised neural-physics learning</span></a>"
    excerpt: >
      **Fu, S.** et al. *bioRxiv* (2026). <br>
      We develop a blind 3D localization framework that can handle overlapping single-molecule data with unknown aberrations. By jointly learning **a physical PSF model** and **a localization network**, our method enhances SMLM with much improved robustness, achieving **calibration-free volumetric nanoscopy** in complex biological samples.
---

Hi, I am Shuang Fu(傅爽). 

I am currently a Postdoc at [Yiming Li's Lab](https://li-lab-sustech.github.io/), [Southern University of Science and Technology](https://www.sustech.edu.cn/en/), Shenzhen, China. 

My previous research focused on developing tools for single-molecule localization microscopy (SMLM), especially **AI4SMLM**, where I developed a series of physics-informed deep learning methods to make SMLM more robust under complex imaging conditions. I’m also fascinated by **Intelligent Optical Systems** and **Computer Vision**. My philosophy is simple: combine physics knowledge with the power of data-driven AI to build tools that actually work in the real world. I’m always looking for opportunities to participate in projects that don't just sound cool, but are truly useful for researchers and engineers.

**I am currently looking for Postdoctoral/Research positions starting as early as August 2026, with flexibility extending into early 2027.** If you are interested, feel free to contact me at `fus@sustech.edu.cn`.

## Selected Publications
<!-- 这是用来召唤你上面在 YAML 中配置的数据的组件，这里的 id 必须对应你在上面写的 'selected_papers' -->
{% include feature_row id="selected_papers" type="left" %}

## Ongoing Projects
<!-- 修改 id="ongoing_projects" 来匹配你刚才在上面新建的 YAML 名字 -->
{% include feature_row id="ongoing_projects" type="left" %}