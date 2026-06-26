---
title: Home
type: landing

sections:
  # 1. 메인 간판 (Navy)
  - block: markdown
    content:
      title: '' 
      text: |
        <div style="width: 1000px; max-width: 100%; margin: 0 auto; text-align: left;">
        <h1 style="color: white; font-size: 2.5rem; margin-bottom: 20px;">Statistical Learning Theory Lab</h1>
        <div style="font-size: 1.1rem; line-height: 1.8; color: white;">
        <p><strong style="color: white;">서울대학교 통계학과 통계적 학습이론 연구실에 오신 것을 환영합니다.</strong></p>
        <p>우리 연구실의 주요 연구 내용은 비정형 데이터 분석(non-standard data analysis)입니다. 구체적으로는 HDLSS(High-Dimension, Low-Sample-Size) problem, non-Euclidean data, data privacy 등을 다루고 있으며, 이를 대상으로 PCA, classification, multisource data integration 등의 연구를 진행하고 있습니다.</p>
        </div>
        </div>
    design:
      background:
        color: '#112240'
      columns: '1'
      spacing:
        padding: ['100px', '5%', '100px', '5%']

  # 2. Research Interests
  - block: markdown
    content:
      title: ''
      text: |
        <div id="research-section" style="width: 1000px; max-width: 100%; margin: 0 auto; text-align: left;">
        <h2 style="margin: 0 0 10px 0; font-size: 2rem;">Research Interests</h2>
        <hr style="border: 0; border-bottom: 2px solid #e5e7eb; margin-bottom: 40px; width: 100%;">
        
        <style>
        .research-img { width: 100%; height: 200px; margin-bottom: 20px; object-fit: contain; transition: transform 0.2s ease; display: block; }
        .research-img:hover { transform: translateY(-5px); }
        </style>

        <div style="display: flex; flex-wrap: wrap; justify-content: space-between; gap: 30px;">
        
        <div style="flex: 1; min-width: 280px; max-width: 310px;">
        <a href="/research/#hdlss">
          <img src="/research/hdlss.png" alt="High-dimension low-sample-size" class="research-img">
        </a>
        <h3 style="font-size: 1.25rem; margin: 0 0 10px 0;"><a href="/research/#hdlss" style="text-decoration: none; color: inherit;">HDLSS Problem</a></h3>
        <p style="font-size: 0.95rem; line-height: 1.6;">고차원 저표본(High-Dimension, Low Sample Size) 상황에서 발생하는 기하적, 통계적 현상에 대한 연구</p>
        </div>
        
        <div style="flex: 1; min-width: 280px; max-width: 310px;">
        <a href="/research/#non-euclidean">
          <img src="/research/non_euclidean.png" alt="Non-Euclidean" class="research-img">
        </a>
        <h3 style="font-size: 1.25rem; margin: 0 0 10px 0;"><a href="/research/#non-euclidean" style="text-decoration: none; color: inherit;">Non-Euclidean Data</a></h3>
        <p style="font-size: 0.95rem; line-height: 1.6;">다양체, 트리, 그래프 등 비유클리드 공간에 존재하는 데이터의 통계적 분석</p>
        </div>
        
        <div style="flex: 1; min-width: 280px; max-width: 310px;">
        <a href="/research/#privacy">
          <img src="/research/privacy.png" alt="Data Privacy" class="research-img">
        </a>
        <h3 style="font-size: 1.25rem; margin: 0 0 10px 0;"><a href="/research/#privacy" style="text-decoration: none; color: inherit;">Data Privacy</a></h3>
        <p style="font-size: 0.95rem; line-height: 1.6;">재현 자료(Synthetic Data)와 차등정보보호(Differential Privacy)를 기반으로 한 Data Privacy 연구</p>
        </div>
        
        </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['80px', '5%', '60px', '5%']

  # 3. 최근 뉴스
  - block: markdown
    content:
      title: ''
      text: |
        <div id="news-section" style="width: 1000px; max-width: 100%; margin: 0 auto; text-align: left;">
        <h2 style="margin: 0 0 10px 0; font-size: 2rem;">Recent News</h2>
        <hr style="border: 0; border-bottom: 2px solid #e5e7eb; margin-bottom: 30px; width: 100%;">
        <div style="line-height: 2; font-size: 1.05rem;">
        <div style="margin-bottom: 10px;">
          <strong>[2026-06-17 – 2026-06-18]</strong>
          IMS New Researchers Conference Asia: Presentations by 김용재 and 박재성
          (<a href="#news">More details in the News section</a>)
        </div>
      
        <div style="margin-bottom: 10px;">
          <strong>[2026-06-13 – 2026-06-16]</strong>
          IMS APRM: Presentations by 김민우, 이치훈, 김용재, 성기헌, 김규원, and 박재성
          (<a href="#news">More details in the News section</a>)
        </div>
        <div style="margin-top: 25px;">
        <a href="/news/" style="text-decoration: none; font-weight: bold;">➔ View all news</a>
        </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['40px', '5%', '60px', '5%']

  # 4. 연락처 (이 부분은 배경이 고정되어 있으므로 색상 하드코딩 유지)
  - block: markdown
    content:
      title: ''
      text: |
        <div style="width: 1000px; max-width: 100%; margin: 0 auto; text-align: left;">
        <h2 style="margin: 0 0 10px 0; font-size: 2rem; color: #112240;">Contact Us</h2>
        <hr style="border: 0; border-bottom: 2px solid #e5e7eb; margin-bottom: 30px; width: 100%;">
        <div style="display: flex; flex-direction: column; gap: 30px; color: #374151;">
        <div>
        <h3 style="margin: 0 0 5px 0; font-size: 1.25rem; color: #112240;">정성규 <span style="font-size: 1rem; color: #6b7280; font-weight: normal; margin-left: 5px;">| Professor</span></h3>
        <p style="margin: 0; font-size: 1.05rem;">Email: sungkyu@snu.ac.kr</p>
        </div>
        <div>
        <h3 style="margin: 0 0 5px 0; font-size: 1.25rem; color: #112240;">김규원 <span style="font-size: 1rem; color: #6b7280; font-weight: normal; margin-left: 5px;">| Lab Manager</span></h3>
        <p style="margin: 0; font-size: 1.05rem;">Email: kwkim1224@snu.ac.kr</p>
        </div>
        </div>
        </div>
    design:
      background:
        color: '#f8fafc' 
      columns: '1'
      spacing:
        padding: ['60px', '5%', '80px', '5%']
---
