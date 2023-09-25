# UAV_MEC-task-offloading
[**Task Offloading and Trajectory Scheduling for UAV-Enabled MEC Networks: An Optimal Transport Theory Perspective**](https://ieeexplore.ieee.org/document/9585571)   
提出了一個適用於無人機啟用的MEC網絡的任務卸載框架。通過利用無人機的懸停和移動能力，可以向網絡的所有子區域中的設備提供任務卸載服務。為了延長無人機的運行時間和相關網絡的壽命，制定了一個優化問題，通過聯合區域劃分和無人機軌跡安排來最小化無人機的總能耗。將其分解為兩個獨立的子問題，區域劃分和無人機軌跡優化。對於第一個子問題將其建模為半離散最優運輸問題，考慮不同子區域之間的流量平衡，並提出一個迭代算法來實現最優解。然後，無人機軌跡優化子問題被建模為旅行推銷員問題，以確定最短路線。模擬結果顯示，所提出的方案可以顯著降低無人機的能耗，同時實現適當的負載平衡。  
Di Wang, Jie Tian, IEEE, Haixia Zhang, and Dalei Wu, "Task Offloading and Trajectory Scheduling for UAV-Enabled MEC Networks: An Optimal Transport Theory Perspective", IEEE WIRELESS COMMUNICATIONS LETTERS, VOL. 11, NO. 1, JANUARY 2022, pp. 150-154, 2022.    
  
[**Energy Efficient Task Caching and Offloading in UAV-Enabled Crowd Management**](https://ieeexplore.ieee.org/document/9804231)  
提出了一種由IoT設備、UAV-BS、邊緣雲和數據中心組成的能源高效的UAV啟用MEC網絡，並提出了一種Green-UAV-CoCaCo算法，以共同優化UAV的通信、緩存和計算以提高能源效率（EE）。基於貪婪算法設計了一個UAV軌跡模型，用於預測用戶的坐標並選擇適當的邊緣服務器進行任務卸載。然後，提出了UAV-CoCaCo算法，以極大化任務緩存和卸載的能源效率。模擬結果展示了所提算法的有效性。  
Gaoxiang Wu, Qiang Liu , Jinfeng Xu, Yiming Miao , and Matevž Pustišek, "Energy Efficient Task Caching and Offloading in UAV-Enabled Crowd Management", IEEE SENSORS JOURNAL, VOL. 22, NO. 18, 15 SEPTEMBER 2022, pp. 17565-17572, 2022.  
> 只有這篇有用到多台UAV，並且同時去探討UAV路徑規劃和task offloading，不過是每一台無人機分開去greedy出UAV路徑規劃並且去決定要offloading到哪一個Edge server做計算，預測User會移動到那一個ES附近，成為Markov Model(馬可夫模型)(這篇有多台Edge server)，在Evaluation主要比的是Energy Consumption

[**Task Offloading in UAV-Aided Edge Computing: Bit Allocation and Trajectory Optimization**](https://ieeexplore.ieee.org/document/8607062)  
考慮了一個由多個移動用戶和一個UAV組成的MEC系統，其中UAV可以在空中移動並提供計算服務。作者將系統能耗最小化問題轉化為一個混合整數非凸優化問題，並提出了一種替代優化算法，該算法共同優化了任務卸載決策、傳輸期間的位元分配以及UAV的軌跡。數值結果顯示了所提方案的顯著節能效果。  
Jingyu Xiong , Hongzhi Guo , Member, IEEE, and Jiajia Liu, IEEE COMMUNICATIONS LETTERS, VOL. 23, NO. 3, MARCH 2019, pp. 538-541, 2019.  

[**UAV-Enabled Mobile Edge Computing: Offloading Optimization and Trajectory Design**](https://ieeexplore.ieee.org/document/8422277)  
研究了一個由多個移動用戶和一個UAV組成的MEC系統，其中UAV可以在空中移動並提供計算服務。作者將系統的總延遲最小化問題轉化為一個混合整數非線性規劃問題，並提出了一種基於分支定界法和粒子群優化算法的混合算法來求解。該算法可以聯合優化任務offloading決策和UAV軌跡。數值結果顯示，該算法可以有效降低系統的總延遲。  
Fuhui Zhou, Yongpeng Wu, Haijian Sun, Zheng Chu, ""UAV-Enabled Mobile Edge Computing: Offloading Optimization and Trajectory Design"", 2018 IEEE International Conference on Communications (ICC), 2018.  
> 這篇與上篇都沒有在地面上的Edge Server，直接由UAV當作MEC讓UAV擔任基地台的功能，感覺不太實際，因為UAV有電量和計算性能的問題沒辦法和有電力連結的Edge Server具有相同能力

[**Joint Task Offloading and Trajectory Optimization for UAV-Enabled Mobile Edge Computing**](https://ieeexplore.ieee.org/document/8883173)  
研究了一種無人機(UAV)支援的移動邊緣網路，其中UAV具有固定翼或旋翼，被派遣提供通信和移動邊緣計算(MEC)服務給地面終端(GTs)。為了最小化能耗以延長UAV的續航力，利用聯合優化其3D軌跡和GTs之間的任務緩存策略，以節省飛行推進和GT任務所花費的能量。這種聯合軌跡-任務-緩存問題難以被最優解決，因為它是非凸的，並涉及多個約束。為了解決這個問題，將任務卸載和緩存的優化重新表述為兩個可處理的線性規劃(LP)問題，並將UAV軌跡的優化分別分解為三個凸二次受限二次規劃(QCQP)問題，分別是水平軌跡、垂直軌跡和UAV的飛行時間。然後提出了一種基於塊坐標下降法的算法，通過一個連續凸優化(SCO)過程迭代地求解形成的子問題。在算法收斂到預定精度後，就可以得到聯合問題的一個高品質次優解。數值結果顯示，所提出的解決方案顯著優於基準解決方案。  
Haibo Mei, Kezhi Wang, Dongdai Zhou, Kun Yang, "Joint Task Offloading and Trajectory Optimization for UAV-Enabled Mobile Edge Computing," in IEEE Access, vol. 7, pp. 156476-156488, 2020.
