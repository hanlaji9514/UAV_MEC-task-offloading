# UAV_MEC-task-offloading
[**Task Offloading and Trajectory Scheduling for UAV-Enabled MEC Networks: An Optimal Transport Theory Perspective**](https://ieeexplore.ieee.org/document/9585571)   
提出了一個適用於無人機啟用的MEC網絡的任務卸載框架。通過利用無人機的懸停和移動能力，可以向網絡的所有子區域中的設備提供任務卸載服務。為了延長無人機的運行時間和相關網絡的壽命，制定了一個優化問題，通過聯合區域劃分和無人機軌跡安排來最小化無人機的總能耗。將其分解為兩個獨立的子問題，區域劃分和無人機軌跡優化。對於第一個子問題將其建模為半離散最優運輸問題，考慮不同子區域之間的流量平衡，並提出一個迭代算法來實現最優解。然後，無人機軌跡優化子問題被建模為旅行推銷員問題，以確定最短路線。模擬結果顯示，所提出的方案可以顯著降低無人機的能耗，同時實現適當的負載平衡。  
Di Wang, Jie Tian, IEEE, Haixia Zhang, and Dalei Wu, "Task Offloading and Trajectory Scheduling for UAV-Enabled MEC Networks: An Optimal Transport Theory Perspective", IEEE WIRELESS COMMUNICATIONS LETTERS, VOL. 11, NO. 1, JANUARY 2022, pp. 150-154, 2022.    

[**Task Offloading in UAV-Aided Edge Computing: Bit Allocation and Trajectory Optimization**](https://ieeexplore.ieee.org/document/8607062)  
考慮了一個由多個移動用戶和一個UAV組成的MEC系統，其中UAV可以在空中移動並提供計算服務。作者將系統能耗最小化問題轉化為一個混合整數非凸優化問題，並提出了一種替代優化算法，該算法共同優化了任務卸載決策、傳輸期間的位元分配以及UAV的軌跡。數值結果顯示了所提方案的顯著節能效果。  
Jingyu Xiong , Hongzhi Guo , Member, IEEE, and Jiajia Liu, IEEE COMMUNICATIONS LETTERS, VOL. 23, NO. 3, MARCH 2019, pp. 538-541, 2019.  

[**UAV-Enabled Mobile Edge Computing: Offloading Optimization and Trajectory Design**](https://ieeexplore.ieee.org/document/8422277)  
研究了一個由多個移動用戶和一個UAV組成的MEC系統，其中UAV可以在空中移動並提供計算服務。作者將系統的總延遲最小化問題轉化為一個混合整數非線性規劃問題，並提出了一種基於分支定界法和粒子群優化算法的混合算法來求解。該算法可以聯合優化任務offloading決策和UAV軌跡。數值結果顯示，該算法可以有效降低系統的總延遲。  
Fuhui Zhou, Yongpeng Wu, Haijian Sun, Zheng Chu, ""UAV-Enabled Mobile Edge Computing: Offloading Optimization and Trajectory Design"", 2018 IEEE International Conference on Communications (ICC), 2018.  
> 這篇與上篇都沒有在地面上的Edge Server，直接由UAV當作MEC讓UAV擔任基地台的功能，感覺不太實際，因為UAV有電量和計算性能的問題沒辦法和有電力連結的Edge Server具有相同能力

[**Energy Consumption Minimization for Secure UAV-enabled MEC Networks Against Active Eavesdropping**](https://ieeexplore.ieee.org/document/10333674)
本文提出了一種新的能源消耗最小化方案，用於考慮對抗主動側聽的安全UAV啟用的MEC網絡。UAV服務器支持TUs完成他們的數據計算，主動UAV側聽者參與側聽TUs的機密數據並廣播攻擊信息以降低TUs的卸載品質。干擾產生器發出人工干擾信號以對抗主動UAV側聽者的側聽。通過考慮所有TUs數據的安全計算，通過設計動態UAV服務器軌跡，本地計算和卸載計算優化實現了安全UAV啟用的MEC網絡的能源消耗加權和(為UAV飛行與任務運算、卸載之加權和)最小化。
> 用干擾產生器對抗監聽攻擊有點怪，只有一台無人機，比較的baseline就是沒有進行路徑規劃(所以重點是在路經規劃嗎？)

[**Joint Trajectory-Task-Cache Optimization in UAV-Enabled Mobile Edge Networks for Cyber-Physical System**](https://ieeexplore.ieee.org/document/8883173)  
研究了一種無人機(UAV)支援的移動邊緣網路，其中UAV具有固定翼或旋翼，被派遣提供通信和移動邊緣計算(MEC)服務給地面終端(GTs)。為了最小化能耗以延長UAV的續航力，利用聯合優化其3D軌跡和GTs之間的任務緩存策略，以節省飛行推進和GT任務所花費的能量。這種聯合軌跡-任務-緩存問題難以被最優解決，因為它是非凸的，並涉及多個約束。為了解決這個問題，將任務卸載和緩存的優化重新表述為兩個可處理的線性規劃(LP)問題，並將UAV軌跡的優化分別分解為三個凸二次受限二次規劃(QCQP)問題，分別是水平軌跡、垂直軌跡和UAV的飛行時間。然後提出了一種基於塊坐標下降法的算法，通過一個連續凸優化(SCO)過程迭代地求解形成的子問題。在算法收斂到預定精度後，就可以得到聯合問題的一個高品質次優解。數值結果顯示，所提出的解決方案顯著優於基準解決方案。  
Haibo Mei, Kezhi Wang, Dongdai Zhou, Kun Yang, "Joint Task Offloading and Trajectory Optimization for UAV-Enabled Mobile Edge Computing," in IEEE Access, vol. 7, pp. 156476-156488, 2020.

# Aim to Energy Consumption or Energy Efficiency
[**Energy-saving Algorithmof UAVsinTaskOffloading of UAV-assisted Mobile EdgeComputing**](https://ieeexplore.ieee.org/document/9887499)  
提出了一種具有雙向偏好列表的匹配遊戲算法，根據卸載到UAV能節省的延遲和能源消耗的加權總和評分建立偏好列表，UAV根據評分由而低接受使用者請求藉此完成卸載配對，以最小化能量總成本。
> 這篇假設無人機跟使用者都不會動，沒有固定式MEC。(我覺得這篇原本看能不能delay跟energy兩者都贏，但最後只贏Energy而已因為他的加權總合評分有Delay跟Energy兩部分)

[**Maximizing Energy Efficiency in UAV-Assisted NOMA–MEC Networks**](https://ieeexplore.ieee.org/document/10214196) 
在5G物聯網（IoT）的環境下多使用非正交多路存取（NOMA）技術來實現大規模連接性並提高頻譜效率，無人機（UAV）作為移動用戶（MUs）的計算單元和中繼站。研究了一種UAV輔助的NOMA-MEC通信網絡架構，將複雜的非凸的混合整數非線性分數規劃（MINLFP）問題分解為數個子問題並迭代求解，優化了通信調度、任務分配、時槽(time-slot)調度、用戶的傳輸功率以及UAV的軌跡，這些都在包括用戶傳輸能力、UAV位置和飛行速度以及能源預算等幾個約束條件下進行，以最大化整個系統的EE。
> 這篇只有一台UAV。

# With Deep Learning
[**Unmanned-Aerial-Vehicle-Assisted Computation Offloading for Mobile Edge Computing Based on Deep Reinforcement Learning**](https://ieeexplore.ieee.org/document/9212373)   
提出了基於深度強化學習（UACODRL）的UAV輔助MEC計算卸載，以最小化總成本，該成本是延遲、能源消耗和頻寬成本的加權和。我們首先使用K-Means算法進行分類以降低動作空間的維度。隨後，使用UACODRL找到接近最優的卸載方案以最小化總成本。
> 這篇使用基於深度強化式學習的方式，但他假設只有一台MEC並且該MEC能夠完全覆蓋所有的使用者以及UAV的數量足夠覆蓋全部使用者，並從中去挑加權和最小的選擇，沒有考慮到MEC會有覆蓋不完整的情形，且無UAV的路徑規劃。

[**Task Offloading and Trajectory Control for UAV-Assisted Mobile Edge Computing Using Deep Reinforcement Learning**](https://ieeexplore.ieee.org/document/9395130)   
提出了一種深度強化學習模型來學習並優化任務卸載和UAV軌跡控制，讓Agent試圖在任務過期之前最大化處理的任務數量，並同時最小化能源和時間消耗。
> 和上篇一樣都是基於深度強化式學習(DRL)去做的，但是這篇沒有固定式MEC只有用一台UAV當作MEC設備的角色。

[**A Joint Trajectory and Computation Offloading Scheme for UAV-MEC Networks via Multi-Agent Deep Reinforcement Learning**](https://ieeexplore.ieee.org/document/10278822)   
提出了多代理聯合軌跡和計算卸載（MA-TACO）方案，該方案共同優化了UAVs的軌跡和計算卸載策略，並且藉由多代理深度強化學習方法（OMADRL）優化每個UAV可以自主學習軌跡決策以適應動態需求，減少動作空間維度，並使每個UAV更快地實現最佳策略。

[**UAV-Assisted MEC System Considering UAV Trajectory and Task Offloading Strategy**](https://ieeexplore.ieee.org/document/10279045)
設計了一種聯合優化算法來優化用戶的任務卸載策略和UAV的軌跡。採用差分演化（DE）算法，根據用戶位置和UAV位置獲得每個用戶在當前時隙的卸載策略。並使用樂觀演員-評論家（OAC）算法，該算法可以最小化系統的能源消耗和延遲的加權總和得出最優的UAV軌跡路徑。
> 這篇論文僅在所有使用者皆固定不動的情況下提出解決方案，但是這篇沒有固定式MEC只有用一台UAV當作MEC設備的角色。這篇論文的UAV會偏向在使用者密集的地方得出彎曲的路徑以增加UAV在這塊區域的時間、在稀疏的地方以較平滑的軌跡快速通過

# UAV Energy Harvesting
UAV Energy Harvesting可用於災害環境，斷電時若使用者UE的電量不足能夠以Energy Harvesting的方式發送能量灌溉到UE身上。

[**Dynamic Offloading and Trajectory Control for UAV-Enabled Mobile Edge Computing System With Energy Harvesting Devices**](https://ieeexplore.ieee.org/document/9814972)
考慮使用者有電量的問題，在電量為一定threshold下使用者就沒辦法進行local的計算，UAV除了有MEC設備的角色還能夠將能量灌溉到使用者上使其獲得能量以繼續進行計算，本論文提出的PLOT(perturbed Lyapunov optimization-based offloading and trajectory)採用了擾動Lyapunov優化方法降低問題的複雜度找到問題的可行解以降低UAV飛行推進的能源消耗和提高系統吞吐量而且還維持了UAV數據隊列(Queue)的穩定性。例如PLOT算法將指導UAV更頻繁地訪問能源率較低的UE，以平衡不均勻的能源水平。
> 目標只討論到UAV飛行推進能源消耗最小化，假設UAV用於Computing和Energy harvesting的能量都直接從再生能源取得(無限)，這感覺有點不切實際

[**Computational Efficiency Maximization for UAV-Assisted MEC Networks With Energy Harvesting in Disaster Scenarios**](https://ieeexplore.ieee.org/document/9814972)
考慮了一種具有能源收集（EH）的UAV輔助的MEC網絡將source能量分為能量灌溉及資訊傳輸兩部分，採用k-means聚類來確定UAV的最優位置並確定用戶與UAV的關聯連接。在第三階段，我們使用第一階段的最優UAV位置和第二階段的用戶關聯指標來確定UE的最優功率和卸載時間，然後進行線性化並使用內點方法來解決產生的線性優化問題。
> 提到加入EH能夠讓效果變好，但這種EH通常都沒有討論UAV的能量問題。

# The Main Opponent
[**Energy Efficient Task Caching and Offloading in UAV-Enabled Crowd Management**](https://ieeexplore.ieee.org/document/9804231)  
提出了一種由IoT設備、UAV-BS、邊緣雲和數據中心組成的能源高效的UAV啟用MEC網絡，並提出了一種Green-UAV-CoCaCo算法，以共同優化UAV的通信、緩存和計算以提高能源效率（EE）。基於貪婪算法設計了一個UAV軌跡模型，用於預測用戶的坐標並選擇適當的邊緣服務器進行任務卸載。然後，提出了UAV-CoCaCo算法，以極大化任務緩存和卸載的能源效率。模擬結果展示了所提算法的有效性。  
Gaoxiang Wu, Qiang Liu , Jinfeng Xu, Yiming Miao , and Matevž Pustišek, "Energy Efficient Task Caching and Offloading in UAV-Enabled Crowd Management", IEEE SENSORS JOURNAL, VOL. 22, NO. 18, 15 SEPTEMBER 2022, pp. 17565-17572, 2022.  
> 只有這篇有用到多台UAV，並且同時去探討UAV路徑規劃和task offloading，不過是每一台無人擴張，在Evaluation中分別為其兩篇論文的環境進行擴展，機分開去greedy出UAV路徑規劃並且去決定要offloading到哪一個Edge server做計算，預測User會移動到那一個ES附近，成為Markov Model(馬可夫模型)(這篇有多台Edge server)，在Evaluation主要比的是Energy Consumption

[**Vehicular Computation Offloading in UAV-enabled MEC Systems**](https://ieeexplore.ieee.org/document/9776115) 
該文提出了一種基於貪婪啟發式（GH）的動態排程框架（GHDSF），本文目標為最小化其目標函數為延遲與能量消耗的加權和，在排程過程中，每個任務都被安排到對目標函數貢獻最小的目的地。並與基於博弈理論的無人機輔助車輛計算成本優化（UVCO）算法進行比較。實驗結果顯示優於UVCO。主要原因可能是UVCO在安排任務時沒有考慮到分配出去的工作的工作負載。
> 這篇論文著重探討如何offloading，UAV路徑為固定繞圓形，但是這篇有固定式的MEC(只有一台)

論文環境主要為上兩篇論文的擴張，在Evaluation中分別為其兩篇論文的環境進行擴展，讓三篇論文的演算法能夠在相同的實驗環境下進行比較。
