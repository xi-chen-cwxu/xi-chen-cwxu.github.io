---
permalink: /
title: "个人简介 About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<br>
[无锡学院](https://www.cwxu.edu.cn/)传媒与艺术学院院长助理，博士，副教授，[英国剑桥艺术学院](https://www.aru.ac.uk/arts-humanities-education-and-social-sciences/cambridge-school-of-art)访问学者，工信部产业互联网人才能力评价国家标准委员会专家，教育部产教融合协同育人项目专家委员会成员（[完美世界](http://www.wmupd.com/)），中国科学院计算技术研究所高级虚拟现实设计师，全国高等院校电子竞技专业委员会委员，长三角电竞教育联盟委员，完美世界数字文化创意产业学院副院长，美国[ACM SIGGRAPH](https://www.siggraph.org/)计算机图形专业委员会成员，参与和主持多项国家级省部级项目，在CEED, SUIC, Neural Computing and Applications, ICME等国际学术会议中发表论文，获得[ICDI](https://icdi.cmu.ac.th/Home.aspx)国际创新学者称号。<br>
<p style="font-size:16px">Dr. Xi CHEN is currently assistant dean and associate professor of the School of Media and Arts of Wuxi University. He is also a visiting professor at Cambridge School of Art, Anglia Ruskin University, United Kingdom. He is the expert of the National Standard Committee for Industrial Internet Talent Capacity Evaluation of the Ministry of Industry and Information Technology, member of the Expert Committee of the Industry-Education Integration Collaborative Education Project of the Ministry of Education (Perfect World), senior virtual reality designer of the Institute of Computing Technology of the Chinese Academy of Sciences, member of the National Higher Education E-sports Professional Committee, member of the Yangtze River Delta E-sports Education Alliance, vice president of Perfect World Digital Culture and Creative Industry College, member of the ACM SIGGRAPH United States, participated in and presided over many national, provincial and ministerial projects. He published papers in international academic conferences such as CEED, SUIC, Neural Computing and Applications, ICME, and was awarded the title of ICDI International Innovation Scholar.</p>

研究专长：人工智能数字人、电竞跨文化传播。<br>
<p style="font-size:16px">Research interests: Digital human technology, Cross-cultural communication of e-sports.</p>

<hr>

代表成果 Achievements
======
<html>
<head>
    <style>
        /* 基础样式 */
        .github-details {
            max-width: 900px;
            margin: 20px auto;
            border: 1px solid #d0d7de;
            border-radius: 6px;
            padding: 12px;
            background: #ffffff;
        }

        /* 标题区域 */
        summary {
            list-style: none;
            cursor: pointer;
            padding: 8px;
            display: flex;
            align-items: center;
            font-family: -apple-system, BlinkMacSystemFont, sans-serif;
            font-size: 16px;
            color: #2f363d;
        }

        /* 禁用默认三角符号 */
        summary::-webkit-details-marker {
            display: none;
        }

        /* 自定义三角图标 */
        .triangle {
            width: 16px;
            height: 16px;
            margin-right: 12px;
            transform: rotate(90deg); /* 初始向右 */
            transition: transform 0.25s ease;
            transform-origin: center;
        }

        /* 展开状态样式 */
        [open] .triangle {
            transform: rotate(180deg);
        }

        /* 内容区域 */
        .content {
            padding: 16px;
            border-top: 1px solid #d0d7de;
            margin-top: 12px;
            background: #f6f8fa;
            border-radius: 4px;
        }

        /* 交互动画 */
        .content {
            animation: fadeIn 0.3s ease;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-10px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>
    <!-- 第一个折叠面板 -->
    <details class="github-details">
        <summary>
            <svg class="triangle" viewBox="0 0 16 16" fill="#2f81f7">
                <path d="M8 0L14.9282 12H1.0718L8 0Z"/>
            </svg>
            <br><i><b>Holosync：融合ACR-MOS指标、情感共鸣与文化自适应的人工智能数字人直播效能评估框架</b></i><br>
        </summary>
        <div class="content">
         The research <i>"Development of New Methods for Assessing the Quality and Effectiveness of Live Broadcasts Using Digital Human Technologies" </i>pioneers a multidimensional evaluation framework that integrates technical performance metrics and audience psychological dynamics to redefine standards for virtual host-driven broadcasts. A groundbreaking contribution is the hierarchical assessment system, beginning with a technical quality module employing the <b>Absolute Category Rating (ACR) method</b>. <b>Mean Opinion Score (MOS)</b> is derived through the formula:
<html>
<head>
    <title>MOS Formula</title>
    <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
    <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
    <style>
        /* 精密字号控制 */
        .container {
            margin: 15px;
            font-size: 0.9em;  /* 基准字号14.4px */
            line-height: 1.6;
            color: #444;
        }
        .formula-label {
            font-size: 0.85em; /* 12.24px */
            letter-spacing: 0.05em;
            color: #666;
        }
        .formula-definition {
            font-size: 0.75em; /* 10.8px */
            color: #777;
            margin-top: 8px;
        }
        
        /* 数学公式缩放 */
        math {
            font-size: 0.9em !important;  /* 公式整体缩放 */
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="formula-label">The Mean Opinion Score (MOS):</div>
        
        <!-- 公式容器 -->
        <div style="text-align: center; margin: 8px 0;">
            \[ MOS = \frac{\sum_{i=1}^{n} R_i}{n} \]
        </div>

        <!-- 定义文字 -->
        <div class="formula-definition">
            where \( R_i \) = individual rating score, 
            \( n \) = total number of viewers.
        </div>
    </div>
</body>
</html>
This framework quantifies technical stability (video/audio quality) and viewer satisfaction correlations, while innovatively integrating <b>emotional resonance, social presence, and cognitive dynamics</b>. It bridges virtual hosts' attributes (realism, emotional expressiveness) with audience-specific variables (cultural context, motivations), establishing a new evaluation paradigm that unifies technical benchmarks with human-centric perceptions to optimize digital streaming authenticity.
        </div>
    </details>

    <!-- 第二个折叠面板 -->
    <details class="github-details">
        <summary>
            <svg class="triangle" viewBox="0 0 16 16" fill="#2f81f7">
                <path d="M8 0L14.9282 12H1.0718L8 0Z"/>
            </svg>
            技术细节
        </summary>
        <div class="content">
            <p><strong>浏览器兼容性：</strong></p>
            <table>
                <tr><th>浏览器</th><th>支持版本</th></tr>
                <tr><td>Chrome</td><td>≥ 12</td></tr>
                <tr><td>Firefox</td><td>≥ 49</td></tr>
                <tr><td>Safari</td><td>≥ 6</td></tr>
            </table>
        </div>
    </details>

       <!-- 第三个折叠面板 -->
    <details class="github-details">
        <summary>
            <svg class="triangle" viewBox="0 0 16 16" fill="#2f81f7">
                <path d="M8 0L14.9282 12H1.0718L8 0Z"/>
            </svg>
            技术细节
        </summary>
        <div class="content">
            <p><strong>浏览器兼容性：</strong></p>
            <table>
                <tr><th>浏览器</th><th>支持版本</th></tr>
                <tr><td>Chrome</td><td>≥ 12</td></tr>
                <tr><td>Firefox</td><td>≥ 49</td></tr>
                <tr><td>Safari</td><td>≥ 6</td></tr>
            </table>
        </div>
    </details>
</body>
</html>



