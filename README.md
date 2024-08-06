
# Portfolio

## 👋🏻👋🏻 Hello, I'm Ken !!
我是一個喜歡旅遊、跑步和看劇的人。這些興趣不僅讓我保持身心健康，還讓我擁有豐富的生活經驗和開闊的視野。在大學生活中，雖然我沒有擔任社團幹部，但我參加了很多比賽，培養了團隊合作和時間管理的能力。

## Work experience
我曾在升大學時的暑假在一家鑄造耗材公司打工，也在大一時在咖啡廳的內場工作過。雖然我的工作經驗不多，但我對不同的工作環境適應性高。

---
## Education 
- Eletrical Engineering | National Taiwan University of Science and Technology

---
## GPA
![image](/assets/img/gpa.png){: width="700" }
 
---
## Course
![image](/assets/img/CourseGpa.png){: width="400" }

---
## Project
### Global Routing (2-pin nets)

在此項目中，我使用 Dijkstra 演算法來解決 2-pin nets 的路由問題。Dijkstra 演算法是一種經典的最短路徑算法，能有效地找到從起點到終點的最短路徑。具體步驟如下：

1. 初始化：將所有節點的距離設為無限大，起點的距離設為0。

2. 選擇節點：從未訪問的節點中選擇距離最小的節點作為當前節點。

3. 更新距離：對於當前節點的每個鄰居，計算從起點經過當前節點到鄰居的距離，如果這個距離小於鄰居的當前距離，則更新鄰居的距離。

4. 標記訪問：將當前節點標記為已訪問。

5. 重複步驟2-4：直到所有節點都被訪問過或目標節點的距離已確定。

### Soft Block Floorplanning (Software Development for Electronic Design Automation #PA2)

在這個專案中，我使用 Sequence Pair 的 Positive/Negative Locus 來表示各 block 的位置，並運用 Simulated Annealing 進行迭代以尋找最佳解。此過程包含三個操作：

- Op1: 重塑 block 並執行 Op2
- Op2: 交換同一序列中的兩個節點
- Op3: 交換兩個序列中的節點

在成本評估階段，我使用 LCS（Longest Common Subsequence）來獲取垂直與水平方向的最長路徑（最大邊長），並根據總面積來判斷結果是否符合預期。

**詳細步驟**
1. 初始化：首先，為每個 block 分配初始位置，並計算初始成本。

2. 迭代過程：在每次迭代中，隨機選擇一個操作（Op1、Op2 或 Op3）來改變 block 的位置。

3. 成本計算：使用 LCS 計算新的布局的垂直與水平方向的最長路徑，並根據總面積來評估新布局的成本。

4. 接受新解：根據 Simulated Annealing 的接受準則，決定是否接受新布局。如果新布局的成本更低，則接受新布局；如果成本更高，則根據一定的概率接受新布局，以避免陷入局部最優解。

5. 溫度更新：逐漸降低系統的溫度，以減少接受較差解的概率，最終收斂到全局最優解。

![image](/assets/img/EDA_PA2_image.png){: width="550" }

### ICCAD Problem D, Chip Level Global Router

- [x] Parser file：讀取和解析輸入文件中的設計數據(3rd party)。

- [x] 單位轉換與計算：統一不同輸入的單位，並計算gcell大小及數量。

- [x] 旋轉變換：使用旋轉矩陣來計算新的坐標。

- [x] 視覺化圖形：使用python來顯示設計中的各個block和gcell的分佈情況，便於分析和調試。

- [x] 射線法判斷各block涵蓋哪些gcell：利用射線法計算每個block所覆蓋的gcell，確保路由過程中的準確性。

- [x] A\*star routing : 實現了A*star演算法，進行高效的路由尋徑。

- [ ] ripup and reroute：用於解決路由衝突和優化路由結果。

- [ ] Evaluation : 評估布線的分數

### Implement a 5-stage pipelined processor with forwarding and hazard detection (Computer Organization #Final)



### Inertial navigation with MPU6050



### LeNet-5 with quatilization, augmentation, early exit



### yolo v4 real time detection

---
## Contest

### 上銀機械手臂競賽
- 智慧撞球  亞軍
- 智慧創作  亞軍
- 智慧拼圖  季軍

### ICCAD
- Problem D (推廣題)	Chip Level Global Router (尚未結束)

### 桃園虎頭山自走車 
- 未得名

### 黑克松 
- 未得名
