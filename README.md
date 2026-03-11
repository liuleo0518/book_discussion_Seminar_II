# book_discussion_Seminar_II
2026/03/03 中正大學 光機電所的葉志庭副教授 Mini/Micro LED Design and Challenges for Advanced Displays
-
![80.jpg](https://github.com/liuleo0518/book_discussion_Seminar_II/blob/main/80.jpg)
這次專題研討邀請到中正大學光機電所的葉志庭副教授，為我們探討 Mini/Micro LED 顯示技術的設計與挑戰。身為準碩士生，平時在資工領域較常接觸軟體與演算法，這次能從光學與硬體的角度切入，了解先進顯示技術的底層架構，讓我獲益良多。
演講中葉教授清楚界定了 Mini 與 Micro LED 的差異，並點出「觀看距離」與「解析度（PPI）」的絕對關聯。令我印象最深刻的是，在未來熱門的 AR/VR 設備應用上，因為螢幕距離眼睛極近，需要極高的 PPI 才能達到視網膜等級的體驗，這正是具備高亮度、高對比且壽命更長的 Micro LED 能夠大展身手的領域。
新技術也伴隨著嚴峻的製程挑戰。教授特別提到了良率與「巨量轉移（Mass Transfer）」的技術瓶頸，以及目前業界如何透過「藍光 Micro LED 搭配量子點（QD）色彩轉換」來大幅提升良率與色彩純度。
這次演講不僅讓我認識了下一代顯示技術的發展趨勢，也提醒了我，未來在設計 AR/VR 相關的應用程式或 AI 模型時，必須將底層硬體的顯示極限與色彩特性納入考量。這種跨領域的硬體思維，對於即將進入研究所階段的我來說，是非常寶貴的啟發。
![98.jpg](https://github.com/liuleo0518/book_discussion_Seminar_II/blob/main/98.jpg)
2026/03/10 臺中科技大學 資訊與流通學院 資訊工程系的陳永隆教授兼院長
這次專題研討邀請到臺中科大資訊工程系的陳永隆教授，分享了三個涵蓋物聯網與電腦視覺的實務專題研究。身為即將步入研究所的大四學生，這次演講讓我深刻體會到將資工理論落實於解決實際痛點的價值。

智慧魚缸
-
![100.jpg](https://github.com/liuleo0518/book_discussion_Seminar_II/blob/main/100.jpg)
第一個主題是「智慧系統設計與應用—智慧魚缸」。教授展示了如何結合 HomeAssistant、ESP32、MQTT 通訊協定以及 OpenCV 影像辨識，打造出一個完整的遠端監控系統。這套架構不單只是感測水溫或光照，還整合了自動餵食與抽水馬達控制。看到教授將複雜的感測與控制節點繪製成清晰的系統概念圖，對於未來我們在規劃大型系統架構時，是非常好的學習範本。

口罩檢驗管理系統
-
![104.jpg](https://github.com/liuleo0518/book_discussion_Seminar_II/blob/main/104.jpg)
第二個主題「口罩檢驗管理系統」則切入了工業界常見的產品瑕疵檢測。演講中探討了將影像預處理後，投入 ResNet、InceptionV3 與 Xception 等不同卷積神經網路（CNN）模型的成效。這讓我更明白，在真實場域中選擇深度學習模型，必須針對特定資料集的特徵來評估不同網路架構的萃取能力。
改良 YOLOv8 模型之遙測影像目標偵測

改良 YOLOv8 模型之遙測影像目標偵測
-
![108.jpg](https://github.com/liuleo0518/book_discussion_Seminar_II/blob/main/108.jpg)
第三個主題「改良 YOLOv8 模型之遙測影像目標偵測」則是我最有共鳴的一段。演講中比較了原版與改良後的 YOLOv8n-Bi、YOLOv8n-TFBi 模型，能在維持參數量（Parameter）與推論時間（Inference time）變動不大的前提下，穩步提升 mAP 與 Precision。這讓我回想起之前在實作 YOLOv8 步行安全偵測裝置專案時，也曾遇到模型輕量化與辨識精準度之間的取捨難題。陳教授團隊透過調整網路結構來優化效能的思路，給了我很大的啟發。

這次的演講從 IoT 系統整合一路談到 AI 演算法的底層改良，層次分明且極具啟發性，為我接下來的碩士班研究提供了寶貴的參考方向。
