---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "0rem"

sections:
  - block: markdown
    content:
      title: |
        {{< test margin="625px" bg="#ffffff" >}}
        <style>
          .no-wrap-center {
            white-space: nowrap; 
            text-align: center;
            font-size: 80px;    /* 字体大小（可调整） */
            color: #2b73af;     /* 蓝色（可替换为HEX/颜色名） */
            font-weight: bold;  /* 加粗（可选） */
          }
        </style>
        <div class="no-wrap-center">低空智能感知计算与应用</div>

        <style>.center {text-align: center;}.link {font-size: 20px;text-decoration: none;}.link:hover {color: red; /* 改变链接颜色 */font-weight: bold; /* 改变链接文本的粗细 */cursor: pointer; /* 鼠标悬停时显示手型指示链接可点击 */}.separator {font-size: 20px;color: black;}</style><div class="center"><a href="https://arxiv.org/abs/2502.20668" class="link">[paper]</a> <span class="separator">|</span> <a href="https://www.kaggle.com/datasets/xiangexiang/openearthsensing-oes" class="link">[dataset]</a></div>

        <style>.text {font-size: 18px;line-height: 1.6;}strong {font-weight: bold;color: red;}</style><div class="text">Home page of the large-scale fine-grained open-world remote-sensing datasets and benchmark <strong>OpenEarthSensing (OES)</strong> for various open-world remote-sensing downstream tasks, mainly including evaluating the ability of models to detect semantic shifts, adapt to covariate shifts, and continuously update the parameters without forgetting learned knowledge. OES includes 189 scene and object categories, covering the vast majority of potential semantic shifts that may occur in the real world. To provide a more comprehensive testbed for evaluating the generalization performance, OES encompasses five data domains with significant covariate shifts, including two RGB satellite domains, one RGB aerial domain, one multi-spectral RGB domain, and one infrared domain.  </div>

        {{< /test >}}
      text: |-
      design:
        spacing:
          padding: ["40px", "0px", "0px", "0px"]  # 垂直30px/水平0


---
