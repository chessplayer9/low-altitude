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
        {{< test margin="775px" bg="#ffffff" >}}

        ## 一、论坛介绍

        在国家发展战略版图里，低空经济的重要性正与日俱增。无人机、无人驾驶飞行器等低空飞行器技术日新月异，推动低空空域逐步跃升为城市管理革新与经济发展的全新增长点，智能感知技术正在成为保障低空空域活动安全、有序管理的关键。低空环境复杂、目标特性差异大，导致视觉、电磁等多模态感知数据杂，低空场景急需开展感知计算方法和关键技术研究，支撑空地海目标的精细识别和低空环境的精准理解。“低空智能感知计算与应用”论坛将涵盖空天遥感基础模型、开放世界目标检测跟踪、低空环境态势感知、低空智能服务应用实践等前沿议题，促进学术交流与产业合作，共同探索低空智能感知的新机遇与挑战。

        ## 二、论坛议程

        <style>
          .table-container {
            display: flex;
            justify-content: center;
            margin: 20px 0;
          }
          .schedule-table {
            width: 75%; /* 改为自适应宽度 */
            border-collapse: collapse;
            font-family: Arial, sans-serif;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
          }
          .schedule-table th,
          .schedule-table td {
            padding: 10px 15px; /* 适当增加内边距 */
            text-align: center;
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
            width: 180px; /* 固定时间列宽度 */
          }
          .schedule-table th:nth-child(2),
          .schedule-table td:nth-child(2) {
            width: 350px; /* 固定标题列宽度 */
          }
          .schedule-table th:nth-child(3),
          .schedule-table td:nth-child(3) {
            width: 150px; /* 固定报告人列宽度 */
          }
          .schedule-table th:nth-child(4),
          .schedule-table td:nth-child(4) {
            width: 150px; /* 固定单位列宽度 */
          }
        </style>

        <div class="table-container">
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
                <td>西北工业大学</td>
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
                <td>华中科技大学</td>
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
        </div>

        ## 三、组织者信息

        <!-- markdownlint-disable -->
        <div class="team-grid" style="
          display: grid;
          grid-template-columns: repeat(2, 1fr);
          gap: 20px;
          margin-top: 30px;
        "> 
          <!-- Member 1 -->
          <div class="member-card" style="
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            display: flex;
            align-items: flex-start;
          ">
            <img src="/test_temp/cutegirl.jpg" style="
              width: 120px;
              height: 150px;
              object-fit: cover;
              margin-right: 15px;
            ">
            <div>
              <h3 style="margin: 0 0 8px 0">王耀威</h3>
              <p style="margin: 0 0 10px 0; color: #000">哈尔滨工业大学(深圳)、鹏城实验室</p>
              <p style="margin: 0; color: #666; font-size: 14px;">哈尔滨工业大学(深圳)教授，鹏城实验室研究员，教育部长江学者特聘教授，鹏城实验室网络智能研究部副主任、感知智能研究所所长。致力于多模态模型学习方法、大规模视频智能感知等领域研究，构建特征流与模型流协同的技术体系，解决了大规模视频智能感知处理的系统难题。在国际期刊/会议发表高水平论文140余篇，获授权专利50余项。曾承担国家/省部级项目20余项，包括科技创新2030“新一代人工智能”重大项目，国家自然基金重点项目和广东省“新一代人工智能”专项等，获2017年国家技术发明二等奖、中国电子学会2022年科技进步一等奖和2015年技术发明一等奖、广东省科技进步奖特等奖。担任IEEE TCSVT副主编、IEEE数字视网膜系统工作组主席，牵头制定首个端边云协同技术国际标准IEEE 3161-2022、IEEE 3161.9-2023和团体标准T/AI 116.1-2021，获IEEE标准杰出贡献奖。</p>
            </div>
          </div>

          <!-- Member 2 -->
          <div class="member-card" style="
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            display: flex;
            align-items: flex-start;
          ">
            <img src="/test_temp/xz.jpg" style="
              width: 120px;
              height: 150px;
              object-fit: cover;
              margin-right: 15px;
            ">
            <div>
              <h3 style="margin: 0 0 8px 0">曾志刚</h3>
              <p style="margin: 0 0 10px 0; color: #000">华中科技大学</p>
              <p style="margin: 0; color: #666; font-size: 14px;">国家杰出青年科学基金获得者，教育部长江学者特聘教授，万人计划科技创新领军人才，IEEE Fellow，华中科技大学人工智能与自动化学院院长，图像信息处理与智能控制教育部重点实验室主任。2003年6月在华中科技大学获系统分析与集成博士学位。曾在香港中文大学和中国科技大学从事博士后研究。先后担任IEEE Transactions on Neural Networks；IEEE Transactions on Cybernetics；IEEE Transactions on Fuzzy Systems；Cognitive Computation；Neural Networks；Applied Soft Computing；自动化学报；控制工程；系统工程与电子技术；控制理论与应用的编委。曾获教育部自然科学奖一等奖、湖北省自然科学一等奖、湖北省科技进步一等奖、国家科学技术进步奖二等奖等奖励。</p>
            </div>
          </div>

          <!-- Member 3 -->
          <div class="member-card" style="
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            display: flex;
            align-items: flex-start;
          ">
            <img src="/test_temp/dy.jpg" style="
              width: 120px;
              height: 150px;
              object-fit: cover;
              margin-right: 15px;
            ">
            <div>
              <h3 style="margin: 0 0 8px 0">陈轲</h3>
              <p style="margin: 0 0 10px 0; color: #000">鹏城实验室</p>
              <p style="margin: 0; color: #666; font-size: 14px;">鹏城实验室副研究员、视觉智能研究所所长助理、新一代人工智能产业技术创新战略联盟--智慧低空标准工作组联络组长。长期致力于几何驱动的智能感知方法与关键技术研究。主持国家级、省部级纵向项目/课题及产业界横向课题多项，个人累计承担经费总计两千余万元。发表SCI期刊和EI会议论文百余篇，其中CCF-A类或中科院1区论文五十余篇；申请发明专利十余项。 </p>
            </div>
          </div>

          <!-- Member 4 -->
          <div class="member-card" style="
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            display: flex;
            align-items: flex-start;
          ">
            <img src="/test_temp/zqh.jpg" style="
              width: 120px;
              height: 150px;
              object-fit: cover;
              margin-right: 15px;
            ">
            <div>
              <h3 style="margin: 0 0 8px 0">项翔</h3>
              <p style="margin: 0 0 10px 0; color: #000">华中科技大学、鹏城实验室</p>
              <p style="margin: 0; color: #666; font-size: 14px;">华中科技大学长聘副教授、图像与视觉学习实验室（HAIVLab）负责人，鹏城实验室访问学者。近年面向低空研究开放世界感知，获得国家级海外青年人才基金，作为第一作者或通讯作者在含CVPR、ICCV、ECCV、IJCV、IEEE汇刊在内的顶会顶刊发表55篇论文，其中ACM MM长文单篇被引921次，授权或申请专利10项，被提名ICPR-22 T-CAP最佳论文奖，任JVCI副编，因对多媒体领域贡献两次被提名 AI 2000。</p>
            </div>
          </div>

          <!-- Member 5 -->
          <div class="member-card" style="
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            display: flex;
            align-items: flex-start;
          ">
            <img src="/test_temp/lyf.jpg" style="
              width: 120px;
              height: 150px;
              object-fit: cover;
              margin-right: 15px;
            ">
            <div>
              <h3 style="margin: 0 0 8px 0">Yifan Liang</h3>
              <p style="margin: 0 0 10px 0; color: #000">Huazhong University of Science and Technology</p>
              <p style="margin: 0; color: #666; font-size: 14px;">研究方向/个人简介可以放在这里</p>
            </div>
          </div>

          <!-- Member 6 -->
          <div class="member-card" style="
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            display: flex;
            align-items: flex-start;
          ">
            <img src="/test_temp/media/flower.jpg" style="
              width: 120px;
              height: 150px;
              object-fit: cover;
              margin-right: 15px;
            ">
            <div>
              <h3 style="margin: 0 0 8px 0">Ke Chen</h3>
              <p style="margin: 0 0 10px 0; color: #000">Huazhong University of Science and Technology</p>
              <p style="margin: 0; color: #666; font-size: 14px;">研究方向/个人简介可以放在这里</p>
            </div>
          </div>

          <!-- Member 7 -->
          <div class="member-card" style="
            background: white;
            padding: 20px;
            border-radius: 8px;

        ## 四、讲者信息

        {{< /test >}}
      design:
        spacing:
          padding: ["50px", "0px", "0px", "0px"]  # 垂直30px/水平0

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
