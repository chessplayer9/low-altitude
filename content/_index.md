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
            margin-right: -300px; /* 向右偏移量 */
          }
        </style>

        <div class="title-container">
          <div class="main-title">低空智能感知计算与应用</div>
          <div class="sub-forum">———2025中国多媒体大会分论坛</div>
        </div>
      design:
        spacing:
          padding: ["100px", "0px", "0px", "0px"]  # 垂直30px/水平0

  - block: markdown
    content:
      text: |
        {{< test margin="825px" bg="#ffffff" >}}

        ## 一、论坛介绍

        在国家发展战略版图里，低空经济的重要性正与日俱增。无人机、无人驾驶飞行器等低空飞行器技术日新月异，推动低空空域逐步跃升为城市管理革新与经济发展的全新增长点，智能感知技术正在成为保障低空空域活动安全、有序管理的关键。低空环境复杂、目标特性差异大，导致视觉、电磁等多模态感知数据杂，低空场景急需开展感知计算方法和关键技术研究，支撑空地海目标的精细识别和低空环境的精准理解。“低空智能感知计算与应用”论坛将涵盖空天遥感基础模型、开放世界目标检测跟踪、低空环境态势感知、低空智能服务应用实践等前沿议题，促进学术交流与产业合作，共同探索低空智能感知的新机遇与挑战。

        ## 二、论坛议程

        <style>
          .schedule-table {
            width: 100%;
            border-collapse: collapse;
            font-family: Arial, sans-serif;
            margin: 20px 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
          }
          .schedule-table th,
          .schedule-table td {
            padding: 10px 12px;
            text-align: center; /* 所有单元格内容居中 */
            vertical-align: middle;
            border-bottom: 1px solid #e0e0e0;
          }
          .schedule-table th {
            background-color: #2b73af;
            color: white;
            font-weight: bold;
          }
          .schedule-table tr:nth-child(even) {
            background-color: #f8f9fa;
          }
          .schedule-table tr:hover {
            background-color: #e9f5ff;
          }
          .break-row {
            background-color: #fff8e6 !important;
            font-style: italic;
            color: #666;
          }
          .header-row {
            background-color: #f0f7ff;
            font-weight: bold;
          }
          /* 列宽设置 */
          .schedule-table th:nth-child(1),
          .schedule-table td:nth-child(1) {
            width: 15%;
          }
          .schedule-table th:nth-child(2),
          .schedule-table td:nth-child(2) {
            width: 45%;
          }
          .schedule-table th:nth-child(3),
          .schedule-table td:nth-child(3) {
            width: 20%;
          }
          .schedule-table th:nth-child(4),
          .schedule-table td:nth-child(4) {
            width: 20%;
          }
        </style>

        <table class="schedule-table">
          <thead>
            <tr>
              <th>时间</th>
              <th>报告题目</th>
              <th>报告人</th>
              <th>单位</th>
            </tr>
          </thead>
          <tbody>
            <tr class="header-row">
              <td>14:00 ~ 14:30</td>
              <td colspan="3">领导致辞与技术发布</td>
            </tr>
            <tr>
              <td>14:30 ~ 15:00</td>
              <td>待定</td>
              <td>张艳宁</td>
              <td>西工大</td>
            </tr>
            <tr>
              <td>15:00 ~ 15:30</td>
              <td>待定</td>
              <td>李世鹏</td>
              <td>IDEA</td>
            </tr>
            <tr class="header-row">
              <td>15:30 ~ 15:45</td>
              <td colspan="3">茶歇</td>
            </tr>
            <tr>
              <td>15:45 ~ 16:15</td>
              <td>待定</td>
              <td>王涛</td>
              <td>航天宏图</td>
            </tr>
            <tr>
              <td>16:15 ~ 16:45</td>
              <td>分布式空天遥感解译基础模型研究新进展</td>
              <td>孙显</td>
              <td>空天院</td>
            </tr>
            <tr>
              <td>16:45 ~ 17:15</td>
              <td>面向无人机遥感的开放世界感知</td>
              <td>项翔</td>
              <td>华科</td>
            </tr>
            <tr>
              <td>17:15 ~ 17:45</td>
              <td>基于多模态基础模型的鲁棒视频目标跟踪与分割技术</td>
              <td>李鑫</td>
              <td>鹏城实验室</td>
            </tr>
            <tr class="header-row">
              <td>17:45 ~ 18:00</td>
              <td colspan="3">总结发言</td>
            </tr>
          </tbody>
        </table>

        ## 三、组织者信息

        ## 四、讲者信息

        {{< /test >}}
      design:
        spacing:
          padding: ["100px", "0px", "0px", "0px"]  # 垂直30px/水平0

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
