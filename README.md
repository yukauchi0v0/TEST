<p align="center">
  <a href="https://ixd.ntut.edu.tw/" target="_blank" rel="noopener noreferrer">
    <img src="螢幕擷取畫面 2026-05-18 151214.png" alt="國立臺北科技大學 互動設計系 Logo" width="50%">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/NTUT-IXD-red?style=for-the-badge" alt="NTUT IXD">
  <img src="https://img.shields.io/badge/Course-FoPDAI-blue?style=for-the-badge" alt="FoPDAI">
  <img src="https://img.shields.io/badge/Platform-Unity%20%2F%20C%23-green?style=for-the-badge" alt="Unity">
  <img src="https://img.shields.io/badge/Input-MIDI%20Keyboard-orange?style=for-the-badge" alt="MIDI">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge" alt="License">
</p>

# 🎹🎵 Interactive Generative Art with MIDI Keyboard
> **113_FoPDAI_課程教材與專案** —— 結合 MIDI 鍵盤、程式設計與視覺互動藝術的教學實踐與成果展示。本專案引導學生透過數位連結（Digital Engagement）探索沉浸式音樂互動景觀化體驗。

---

## 📑 目錄 (Table of Contents)
- [👨‍🏫 課程指導團隊](#-課程指導團隊)
- [🌟 教學宗旨與核心理念](#-教學宗旨與核心理念)
- [📺 教材示範影片](#-教材示範影片)
- [🛠️ 核心技術與學習重點](#️-核心技術與學習重點)
- [🌟 2026 最新學生成果展示](#-2026-最新學生成果展示)
- [📦 歷屆／往期成果回顧 (Archive)](#-歷屆往期成果回顧-archive)
- [🚀 開發與實作指南](#-開發與實作指南)

---

## 👨‍🏫 課程指導團隊
- **指導老師**：[韓秉軒 Han Ping-Hsuan](https://ixd.ntut.edu.tw/p/406-1089-110727,r1713.php?Lang=zh-tw) 副教授
- **開課單位**：國立臺北科技大學 互動設計系 (IxD, NTUT)

---

## 🌟 教學宗旨與核心理念
本課程旨在引導學生透過互動式視覺與聽覺的結合，增強特定舞台（如舞蹈、音樂劇、戲劇、科技藝術或遊戲體驗等）之表現力。課程內容涵蓋程式語言的基本語法、人工智慧與外部硬體（如 MIDI 控制器）的應用，帶領學生將音樂與空間、程式碼邏輯融為一體，實踐音樂互動式景觀化（Music-Interactive Scenographization）的完整創作。

---

## 📺 教材示範影片
<p align="center">
  <a href="https://youtu.be/I_TfnCPqWdc" target="_blank" rel="noopener noreferrer">
    <img src="螢幕擷取畫面 2026-05-18 151728.png" alt="教材示範影片" width="80%">
  </a>
</p>

---

## 🛠️ 核心技術與學習重點
本專案在實作過程中融合了多項關鍵技術，各模組的功能與參數對應如下：

| 模組分類 | 核心技術 / 工具 | 說明與應用 |
| :--- | :--- | :--- |
| **互動硬體整合** | `MINIS (RtMidi)`, `MIDI Keyboard` | 讀取外部 MIDI 鍵盤/控制器訊號，即時抓取數值並進行 0-1 參數映射。 |
| **輸入系統** | `Unity New Input System` | 採用事件驅動（Event-based）架構，靈活設定 Action Maps 與對應綁定。 |
| **物理與動態控制** | `Rigidbody`, `Update()`, `Time.time` | 賦予物件真實物理特性，透過每幀更新與精準時間軸控制實現流暢動態。 |
| **聲光視覺融合** | `Particle System`, `AudioSource` | 將音樂頻率與節奏對應至視覺粒子與特效，建構動態生成藝術（Generative Art）。 |

---

## 🌟 2026 最新學生成果展示

<table align="center">
  <tr>
    <td width="33.3%" align="center">
      <a href="https://youtu.be/VU8c3B2G0Lo" target="_blank" rel="noopener noreferrer">
        <img src="https://img.youtube.com/vi/VU8c3B2G0Lo/0.jpg" alt="2026 Result 1" width="100%"><br>
        🎬 2026 成果作品 1
      </a>
    </td>
    <td width="33.3%" align="center">
      <a href="https://youtu.be/k7JCcOx8mJo" target="_blank" rel="noopener noreferrer">
        <img src="https://img.youtube.com/vi/k7JCcOx8mJo/0.jpg" alt="2026 Result 2" width="100%"><br>
        🎬 2026 成果作品 2
      </a>
    </td>
    <td width="33.3%" align="center">
      <a href="https://youtu.be/ULoKU4VA0to" target="_blank" rel="noopener noreferrer">
        <img src="https://img.youtube.com/vi/ULoKU4VA0to/0.jpg" alt="2026 Result 3" width="100%"><br>
        🎬 2026 成果作品 3
      </a>
    </td>
  </tr>
  <tr>
    <td width="33.3%" align="center">
      <a href="https://youtu.be/q8dl5AEDBTs" target="_blank" rel="noopener noreferrer">
        <img src="https://img.youtube.com/vi/q8dl5AEDBTs/0.jpg" alt="2026 Result 4" width="100%"><br>
        🎬 2026 成果作品 4
      </a>
    </td>
    <td width="33.3%" align="center">
      <a href="https://youtu.be/tLvHPs3-GSg" target="_blank" rel="noopener noreferrer">
        <img src="https://img.youtube.com/vi/tLvHPs3-GSg/0.jpg" alt="2026 Result 5" width="100%"><br>
        🎬 2026 成果作品 5
      </a>
    </td>
    <td width="33.3%" align="center">
      <a href="https://youtu.be/roGEjevqmqs" target="_blank" rel="noopener noreferrer">
        <img src="https://img.youtube.com/vi/roGEjevqmqs/0.jpg" alt="2026 Result 6" width="100%"><br>
        🎬 2026 成果作品 6
      </a>
    </td>
  </tr>
</table>

---

## 📦 歷屆／往期成果回顧 (Archive)
> 收錄早期（2025 與 2024 年）之精選學生期末互動成果與示範。

### 📅 2025 Spring 學生成果
<table align="center">
  <tr>
    <td width="33.3%" align="center">
      <a href="https://youtu.be/EtXDwIwOYJc" target="_blank" rel="noopener noreferrer">
        <img src="https://img.youtube.com/vi/EtXDwIwOYJc/0.jpg" alt="2025 Result 1" width="100%"><br>
        🎬 2025 作品 1
      </a>
    </td>
    <td width="33.3%" align="center">
      <a href="https://youtu.be/d0j2c98tNHg" target="_blank" rel="noopener noreferrer">
        <img src="https://img.youtube.com/vi/d0j2c98tNHg/0.jpg" alt="2025 Result 2" width="100%"><br>
        🎬 2025 作品 2
      </a>
    </td>
    <td width="33.3%" align="center">
      <a href="https://youtu.be/QMvLnIeeIQ4" target="_blank" rel="noopener noreferrer">
        <img src="https://img.youtube.com/vi/QMvLnIeeIQ4/0.jpg" alt="2025 Result 3" width="100%"><br>
        🎬 2025 作品 3
      </a>
    </td>
  </tr>
  <tr>
    <td width="33.3%" align="center">
      <a href="https://www.youtube.com/watch?v=mIzLXEtFybc" target="_blank" rel="noopener noreferrer">
        <img src="https://img.youtube.com/vi/mIzLXEtFybc/0.jpg" alt="2025 Result 4" width="100%"><br>
        🎬 2025 作品 4
      </a>
    </td>
    <td width="33.3%" align="center">
      <a href="https://youtu.be/fz2pVe5SybU" target="_blank" rel="noopener noreferrer">
        <img src="https://img.youtube.com/vi/fz2pVe5SybU/0.jpg" alt="2025 Result 5" width="100%"><br>
        🎬 2025 作品 5
      </a>
    </td>
    <td width="33.3%" align="center">
      <a href="https://www.youtube.com/watch?v=Ftr2pT1rtDo" target="_blank" rel="noopener noreferrer">
        <img src="https://img.youtube.com/vi/Ftr2pT1rtDo/0.jpg" alt="2025 Result 6" width="100%"><br>
        🎬 2025 作品 6
      </a>
    </td>
  </tr>
</table>

### 📅 2024年經典回顧
<div align="center">
  <table>
    <tr>
      <td align="center">
        <a href="https://youtu.be/9hfCIWBD0oU" target="_blank" rel="noopener noreferrer">
          <img src="https://img.youtube.com/vi/9hfCIWBD0oU/0.jpg" alt="Archive 2024 Result" width="220px"><br>
          📽️ 2024 經典作品回顧
        </a>
      </td>
    </tr>
  </table>
</div>

---

## 🚀 開發與實作指南
1. **階段一：互動舞台與情境定義**
   - 選擇特定的冒險舞台（如科技藝術、互動遊戲、舞蹈視覺等），確立 MIDI 互動與視覺設計的主軸。
2. **階段二：MIDI 訊號與程式邏輯**
   - 設定 Unity New Input System 與 MINIS 插件，編寫 C# 腳本接收 MIDI 鍵盤訊號，處理即時數值映射。
3. **階段三：生成藝術與景觀整合**
   - 結合 Particle System 與 Prefab（預製物件）進行模組化佈署與視覺生成，完成最終的聲光互動展演。

---
<p align="center">🛠️ 113_FoPDAI_CourseProject | 國立臺北科技大學 互動設計系</p>
