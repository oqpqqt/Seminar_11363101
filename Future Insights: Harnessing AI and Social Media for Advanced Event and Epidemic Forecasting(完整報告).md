### 學號：11363101 姓名：謝弘彥 日期：2025/06/03 講者：呂昌田教授 題目：Future Insights: Harnessing AI and Social Media for Advanced Event and Epidemic Forecasting

## 心得報告：

### 一、社群媒體疫情監測

傳統疫情監測主要依賴官方統計資料，存在時間延遲和精確度不足的問題。呂昌田教授的演講介紹如何透過AI技術和社群媒體資料，建立更即時、更精確的疫情預測系統。這種創新方法結合了計算流行病學的疾病機制理解與社群媒體的即時性優勢，為公共衛生監測開創了新的可能性。

在傳統的計算流行病學方法中，監測資料往往具有粗略的特性，僅能提供縣市級和週級的統計資訊，且存在至少一週的資料延遲。更重要的是，傳統方法難以追蹤動態的接觸網絡變化，例如因失業而搬家、突然請假等人員流動情況，這些都會影響疾病傳播模式的準確建模。相對地，社群媒體資料驅動的技術能夠提供即時的個人健康狀況監測，不僅能識別民眾對流感的反應行為（如主動避開人群、接種疫苗），更能追蹤個人疾病的完整進展過程。

社群媒體資料的最大價值在於其即時性和細緻度特性。相較於傳統監測資料的週級延遲，社群媒體能提供即時的健康狀況資訊，甚至能追蹤個人從感覺不舒服到康復的完整疾病進展過程。這種個人化的健康資訊挖掘，為疫情的早期預警和精準防控提供了重要支撐。然而，社群媒體資料也帶來了新的挑戰，包括高度非正式和不符合文法的表達方式、每日超過百萬筆的龐大資料量、動態變化的新標籤和話題，以及高達95%以上的雜訊內容，這些都需要透過先進的AI技術來克服。

### 二、文獻探討

演講中提及的EMBERS系統展現了多任務學習在時空事件預測中的重要性。透過整合監督式與非監督式學習，系統能夠利用歷史資料，並動態捕捉新興關鍵字和趨勢變化。這種模型融合策略有效解決了小地區資料不足和區域異質性的挑戰。

文獻[1]中的Facebook Prophet模型為COVID-19疫情相關社會影響的時間序列分析提供了有效工具。該模型特別適合處理具有季節性和趨勢變化的社會經濟資料，能夠自動識別疫情影響下社會行為的週期性模式，為政策制定者提供科學依據。Prophet模型的優勢在於其對異常值的魯棒性和對缺失資料的容忍度，同時具備自動模式識別能力和數據預處理功能，這些特性在分析疫情對社會經濟行為影響的資料中尤為重要，使其成為評估疫情長期社會影響的可靠分析工具。

文獻[2]探討的社群媒體流行度預測品質評估方法，為疫情相關資訊的可信度評估提供了技術基礎。在疫情資訊傳播中，如何區分真實的健康資訊與虛假訊息至關重要。透過巨量資料分析技術，系統能夠評估不同來源資訊的可靠性，提升疫情預測的準確性。

文獻[3]提出的基於使用者行為變化的事件檢測系統，為疫情等重大事件的早期發現提供了新想法。該系統透過分析COVID-19疫情期間使用者在線上社群網路中的行為模式變化，成功識別出疫情爆發的時間點和影響範圍。這種方法的創新之處在於不僅分析文字內容，更關注使用者行為的深層變化。

系統能夠檢測到的行為變化包括：發文頻率的異常變化、社交互動模式的轉變、關注話題的轉移等。這些行為指標往往比直接的文字表達更能反映真實的社會狀況，為事件檢測提供了更可靠的信號。

### 三、技術挑戰與解決方案

演講中強調的動態查詢擴展技術，有效解決了社群媒體內容的動態性和非正式性問題。傳統的關鍵字比對方法難以應對新興話題和非正式表達，而基於機器學習的動態擴展技術能夠自動學習和適應語言的變化，大幅提升了相關內容的召回率。

在處理巨量資料的6V特徵（Volume、Velocity、Variety、Veracity、Value、Visualization）時，系統採用了分層處理架構。邊緣運算負責即時資料收集，霧運算進行中間處理，雲端負責深度分析。這種分散式架構既保證了即時性，又確保了分析的深度和準確性。

### 四、未來發展與應用前景

AI與社群媒體結合的疫情監測技術正朝向更智慧化、更個人化的方向發展。未來的系統將能夠提供個人化的健康風險評估，基於個人的社交網路和行為模式預測疾病傳播風險。同時，多模態資料融合技術將整合文字、圖像、影片等多種社群媒體內容，提供更全面的疫情監測能力。

隱私保護和資料安全將是未來發展的重要考量。如何在保護個人隱私的前提下，充分利用社群媒體資料進行疫情監測，需要更先進的隱私保護技術和更完善的法規框架。

## 關鍵字
人工智慧(Artificial Intelligence)、社群媒體挖掘(Social Media Mining)、疫情預測(Epidemic Prediction)、時間序列分析(Time Series Analysis)、事件檢測(Event Detection)、機器學習(Machine Learning)、巨量資料分析(Big Data Analytics)、使用者行為分析(User Behavior Analysis)、計算流行病學(Computational Epidemiology)、動態查詢擴展(Dynamic Query Expansion)

## 參考文獻
[1] S. S, R. B, S. V and S. Premalatha, "Time Series Analysis of Impact of Covid-19 Using Facebook Prophet Model and Review of the Machine-Learning Algorithm," 2023 International Conference on Advanced & Global Engineering Challenges (AGEC), Surampalem, Kakinada, India, 2023, pp. 151-155

[2] S. R. N and R. R, "Quality Assessment Approaches in Popularity Prediction of Social Media Using Big Data Analytics," 2024 2nd International Conference on Sustainable Computing and Smart Systems (ICSCSS), Coimbatore, India, 2024, pp. 737-743

[3] R. L. Rosa et al., "Event Detection System Based on User Behavior Changes in Online Social Networks: Case of the COVID-19 Pandemic," in IEEE Access, vol. 8, pp. 158806-158825, 2020
