<p align="center">
  <a href="https://ixd.ntut.edu.tw/" target="_blank" rel="noopener noreferrer">
    <img src="螢幕擷取畫面 2026-05-18 151214.png" alt="國立臺北科技大學 互動設計系 Logo" width="50%">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/NTUT-IXD-red?style=for-the-badge" alt="NTUT IXD">
  <img src="https://img.shields.io/badge/Course-FoPDAI-blue?style=for-the-badge" alt="FoPDAI">
  <img src="https://img.shields.io/badge/Platform-Unity%20%2F%20C%23-green?style=for-the-badge" alt="Unity">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge" alt="License">
</p>

# 🎵 音樂互動式景觀化之教學成果 (Music-Interactive Scenographization)

> **113_FoPDAI_課程專案** —— 結合音樂、程式設計與視覺互動藝術的教學實踐與成果展示。本專案引導學生透過數位連結（Digital Engagement）探索沉浸式體驗[cite: 2]。

---

## 📑 目錄 (Table of Contents)
- [👨‍🏫 課程指導團隊](#-課程指導團隊)
- [🌟 教學宗旨與核心理念](#-教學宗旨與核心理念)
- [📺 教材示範影片](#-教材示範影片)
- [🌟 2025 Spring 學生成果展示](#-2025-spring-學生成果展示)
- [🛠️ 核心模組與技術架構](#️-核心模組與技術架構)
- [🚀 開發與實作指南](#-開發與實作指南)

---

## 👨‍🏫 課程指導團隊
- **指導老師**：[韓秉軒 Han Ping-Hsuan](https://ixd.ntut.edu.tw/p/406-1089-110727,r1713.php?Lang=zh-tw) 副教授[cite: 2]
- **開課單位**：國立臺北科技大學 互動設計系

---

## 🌟 教學宗旨與核心理念
本課程旨在引導學生透過互動式視覺與聽覺的結合，增強特定舞台（如舞蹈、音樂劇、戲劇、科技藝術或遊戲體驗等）之表現力[cite: 2]。課程內容涵蓋程式語言的基本語法、人工智慧的應用，並透過編程練習與跨域工具操作，帶領學生將音樂與空間、程式碼邏輯融為一體，實踐音樂互動式景觀化的完整創作。

---

## 📺 教材示範影片
<p align="center">
  <a href="https://youtu.be/I_TfnCPqWdc" target="_blank" rel="noopener noreferrer">
    <img src="螢幕擷取畫面 2026-05-18 151728.png" alt="教材示範影片" width="80%">
  </a>
</p>

---

## 🌟 2025 Spring 學生成果展示

<table align="center">
  <tr>
    <td width="33.3%" align="center">
      <a href="https://youtu.be/EtXDwIwOYJc" target="_blank" rel="noopener noreferrer">
        <img src="https://img.youtube.com/vi/EtXDwIwOYJc/0.jpg" alt="2025 Result 1" width="100%"><br>
        🎬 成果作品 1
      </a>
    </td>
    <td width="33.3%" align="center">
      <a href="https://youtu.be/d0j2c98tNHg" target="_blank" rel="noopener noreferrer">
        <img src="https://img.youtube.com/vi/d0j2c98tNHg/0.jpg" alt="2025 Result 2" width="100%"><br>
        🎬 成果作品 2
      </a>
    </td>
    <td width="33.3%" align="center">
      <a href="https://youtu.be/QMvLnIeeIQ4" target="_blank" rel="noopener noreferrer">
        <img src="https://img.youtube.com/vi/QMvLnIeeIQ4/0.jpg" alt="2025 Result 3" width="100%"><br>
        🎬 成果作品 3
      </a>
    </td>
  </tr>
  <tr>
    <td width="33.3%" align="center">
      <a href="https://www.youtube.com/watch?v=mIzLXEtFybc" target="_blank" rel="noopener noreferrer">
        <img src="https://img.youtube.com/vi/mIzLXEtFybc/0.jpg" alt="2025 Result 4" width="100%"><br>
        🎬 成果作品 4
      </a>
    </td>
    <td width="33.3%" align="center">
      <a href="https://youtu.be/fz2pVe5SybU" target="_blank" rel="noopener noreferrer">
        <img src="https://img.youtube.com/vi/fz2pVe5SybU/0.jpg" alt="2025 Result 5" width="100%"><br>
        🎬 成果作品 5
      </a>
    </td>
    <td width="33.3%" align="center">
      <a href="https://www.youtube.com/watch?v=Ftr2pT1rtDo" target="_blank" rel="noopener noreferrer">
        <img src="https://img.youtube.com/vi/Ftr2pT1rtDo/0.jpg" alt="2025 Result 6" width="100%"><br>
        🎬 成果作品 6
      </a>
    </td>
  </tr>
</table>

---

## 🛠️ 核心模組與技術架構
本專案在實作過程中融合了多項關鍵技術，各模組的功能與參數對應如下表：

| 模組分類 | 核心技術 / 參數 | 說明與應用 |
| :--- | :--- | :--- |
| **物理與動態控制** | `Rigidbody`, `Update()` | 賦予物件真實物理特性，透過每幀更新實現流暢動態[cite: 5]。 |
| **時間軸與觸發** | `Time.time`, `Instantiate` | 掌握精準時間軸控制，結合物件動態生成與回饋機制[cite: 5]。 |
| **數位舞台設定** | `Digital Engagement` | 結合舞蹈、音樂劇、遊戲體驗等場域，強化沉浸表現[cite: 2]。 |
| **聲光視覺融合** | Audio-Visual Mapping | 將音樂頻率與節奏對應至視覺動態，建構動態生態景觀。 |

---

## 🚀 開發與實作指南
1. **階段一：冒險舞台定義**
   - 選擇特定的冒險舞台（如科技藝術、互動遊戲、公眾螢幕等），並確立設計主軸[cite: 2]。
2. **階段二：基礎程式邏輯**
   - 運用 Unity C# 進行腳本編寫，處理變數、條件判斷與迴圈架構。
3. **階段三：視覺景觀整合**
   - 透過 Prefab（預製物件）進行模組化佈署與景觀生成，完成最終的聲光互動展演[cite: 5]。

---
<p align="center">🛠️ 113_FoPDAI_CourseProject | 國立臺北科技大學 互動設計系</p>
