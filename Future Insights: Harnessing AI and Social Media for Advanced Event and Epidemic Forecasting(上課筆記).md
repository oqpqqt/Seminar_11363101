### 學號：11363101 姓名：謝弘彥 日期：2025/06/03 講者：呂昌田教授 題目：Future Insights: Harnessing AI and Social Media for Advanced Event and Epidemic Forecasting

### 1. 疫情建模的兩大類別

#### **類別1：計算流行病學**
**挑戰：**
- **粗粒度監測資料**：州級和週級資料精度不足
- **接觸網路動態追蹤困難**：人員流動（如失業搬家、突然請假）難以捕捉
- **重新訓練時效性差**：監測資料至少延遲一週

#### **類別2：社群媒體資料驅動技術**
**優勢：**
- **即時監測流行病**：時間精度細緻，無延遲
- **個人健康狀況挖掘**：
  1. 識別對流感的反應（如避開人群、施打疫苗）
  2. 追蹤個人疾病進展（從感覺不適到康復）

---

### 2. 社群媒體內容篩選技術

#### **動態查詢擴展**
**傳統解決方案：**
- 基於預定義字典的關鍵字比對
- 訓練分類器（如支援向量機SVM）
- 基於規則或決策樹

**Twitter資料評估挑戰：**
- 高度非正式和不符合文法
- 巨大資料量（每日超過100萬筆）
- 動態性（新標籤、新話題）
- 雜訊和不平衡（相關內容少於5%）
- 豐富的社群網路結構

---

### 3. 巨量資料特徵（6V）
- **Volume**（數量）
- **Velocity**（速度）
- **Variety**（多樣性）
- **Veracity**（真實性）
- **Value**（價值）
- **Visualization**（視覺化）

---

### 4. 評估系統

#### **MITRE獨立評估**
**評估指標：**
1. **品質**：0-4分評分
2. **提前時間**：預測提前多久
3. **召回率**：實際事件中被預測到的比例
4. **精確率**：預測事件中正確的比例
5. **機率**：預測的可信度

---

### 5. IARPA開源指標計畫
**目標：** 開發持續自動分析公開資料的方法，以**預測和/或偵測**人口層面事件：
- 政治危機、人道主義危機
- 大規模暴力、暴動、大規模遷移
- 疾病爆發、經濟不穩定
- 資源短缺、天然災害應變

---

### 6. 核心技術方法

#### **多任務學習用於時空事件預測**
- **輸入：** 推文
- **輸出：** 特定主題下的預測時空事件
- **模型類型：** 多任務學習

**挑戰：**
- 小地區推文資料不足
- 難以同時考慮不同地區間的異質性和相關性

#### **模型融合策略**
**解決的挑戰：**
- **監督式模型 + 非監督式模型**：充分利用歷史資料 + 捕捉動態關鍵字
- **一對一模型 + 一對多模型**：考慮獨特特徵 + 充足訓練資料

---

### 7. 方法論整合

#### **計算流行病學 + 社群媒體挖掘**
**互補優勢：**

| 計算流行病學 | 社群媒體挖掘 |
|-------------|-------------|
| ✅ 疾病進展機制 | ❌ 缺乏疾病進展機制 |
| ✅ 疾病傳播機制 | ❌ 缺乏疾病傳播機制 |
| ✅ 考慮干預措施 | ❌ 不考慮干預措施 |
| ❌ 時間粗粒度 | ✅ 時間細粒度 |
| ❌ 空間粗粒度 | ✅ 空間細粒度 |
| ❌ 社群接觸網路動態差 | ✅ 即時觀察社群接觸網路變化 |
| ❌ 一週延遲 | ✅ 無時間延遲 |


