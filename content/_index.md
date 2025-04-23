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
      text: |
        <style>
          .title-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            position: relative;
            margin: 20px 0;
            gap: 10px; /* 控制主副标题间距 */
          }
          .main-title {
            white-space: nowrap;
            font-size: 80px;
            color: #2b73af;
            font-weight: bold;
          }
          .sub-forum {
            font-size: 40px;
            color: #666;
            white-space: nowrap;
            align-self: flex-end; /* 右对齐 */
            margin-right: -400px; /* 向右偏移量 */
          }
        </style>

        <div class="title-container">
          <div class="main-title">低空智能感知计算与应用</div>
          <div class="sub-forum">2025中国多媒体大会分论坛</div>
        </div>
      design:
        spacing:
          padding: ["100px", "0px", "0px", "0px"]  # 垂直30px/水平0

  - block: markdown
    content:
      text: |
        {{< test margin="625px" bg="#ffffff" >}}

        ## 一、论坛介绍

        在国家发展战略版图里，低空经济的重要性正与日俱增。无人机、无人驾驶飞行器等低空飞行器技术日新月异，推动低空空域逐步跃升为城市管理革新与经济发展的全新增长点，智能感知技术正在成为保障低空空域活动安全、有序管理的关键。低空环境复杂、目标特性差异大，导致视觉、电磁等多模态感知数据杂，低空场景急需开展感知计算方法和关键技术研究，支撑空地海目标的精细识别和低空环境的精准理解。“低空智能感知计算与应用”论坛将涵盖空天遥感基础模型、开放世界目标检测跟踪、低空环境态势感知、低空智能服务应用实践等前沿议题，促进学术交流与产业合作，共同探索低空智能感知的新机遇与挑战。

        ## 二、论坛议程

        ## 三、组织者信息

        ## 四、讲者信息

        {{< /test >}}
      design:
        spacing:
          padding: ["200px", "0px", "0px", "0px"]  # 垂直30px/水平0

  # - block: markdown
  #   content:
  #     title: |
  #       {{< test margin="625px" bg="#ffffff" >}}
  #       <style>
  #         .no-wrap-center {
  #           white-space: nowrap; 
  #           text-align: center;
  #           font-size: 80px;    /* 字体大小（可调整） */
  #           color: #2b73af;     /* 蓝色（可替换为HEX/颜色名） */
  #           font-weight: bold;  /* 加粗（可选） */
  #         }
  #       </style>
  #       <div class="no-wrap-center">低空智能感知计算与应用</div>

  #       <style>.text {font-size: 18px;line-height: 1.6;}strong {font-weight: bold;color: red;}</style><div class="text">在国家发展战略版图里，低空经济的重要性正与日俱增。无人机、无人驾驶飞行器等低空飞行器技术日新月异，推动低空空域逐步跃升为城市管理革新与经济发展的全新增长点，智能感知技术正在成为保障低空空域活动安全、有序管理的关键。低空环境复杂、目标特性差异大，导致视觉、电磁等多模态感知数据杂，低空场景急需开展感知计算方法和关键技术研究，支撑空地海目标的精细识别和低空环境的精准理解。“低空智能感知计算与应用”论坛将涵盖空天遥感基础模型、开放世界目标检测跟踪、低空环境态势感知、低空智能服务应用实践等前沿议题，促进学术交流与产业合作，共同探索低空智能感知的新机遇与挑战。</div>

  #       {{< /test >}}
  #     text: |-
  #     design:
  #       spacing:
  #         padding: ["100px", "0px", "0px", "0px"]  # 垂直30px/水平0


---
