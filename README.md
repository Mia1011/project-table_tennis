# 應用人工智慧分辨桌球運動員之熟練度 

## 動機
在運動項目的應用上，由於其包含複雜的身體運動和協調動作，目前的研究發展主要依舊集中在辨識粗粒度的動作上，傳統的分析方法往往難以捕捉到運動員的微妙動作和技術細節，但在某些情境下，分辨動作的細微差異才是主要訴求。
## 目標
建立一套能辨識桌球運動員揮拍動作的系統，以此評估運動員的技術水平，並將其分為初學和精熟兩種熟練度等級。  
## 技術
主要引用Temporal Score Network，結合卷積神經網絡(CNN)和殘差神經網路(Resnet)的架構，以我們自行開發的桌球動作資料集(Table Tennis Pose Dataset, TT Pose Dataset)進行訓練與測試。隨後，借鑒Grad-CAM技術，提供深度學習黑盒子的可視化解釋。
