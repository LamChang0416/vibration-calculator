# 專業振動測試參數計算器 | Professional Vibration Profile Calculator

[![GitHub Pages](https://img.shields.io/badge/Live-Demo-brightgreen)](https://LamChamg.github.io/vibration-calculator/)

## 📝 簡介 | Introduction

這是一個專為可靠度工程師 (Reliability Engineer) 設計的網頁版輔助工具，旨在簡化試驗前的規格驗證與參數計算。本工具整合了正弦振動與隨機振動的關鍵運算邏輯。

This is a web-based auxiliary tool designed specifically for Reliability Engineers to simplify specification verification and parameter calculation before vibration testing. It integrates key computational logic for both Sine and Random vibration.

---

## 🚀 核心功能 | Key Features

### 1. 正弦振動 (Sine Vibration)
* **自動交接頻率計算 (Automatic Crossover Calculation)**: 輸入位移與加速度，自動計算轉折頻率（例如 15.76 Hz）。
* **缺失值補全 (Missing Value Completion)**: 根據 $A = \omega^2 X$ 運動學公式自動補齊參數。
* **掃頻時間預估 (Sweep Time Estimation)**: 輸入掃頻速率 (Oct/min) 與次數，精確掌握測試進度。

### 2. 隨機振動 (Random PSD)
* **多點 PSD 輸入 (Multi-point PSD Input)**: 支援複雜頻譜的轉折點設定。
* **即時量值計算 (Real-time Metric Calculation)**: 自動算出 Grms、Peak 速度與 Peak-to-Peak 位移。
* **內建規範 (Predefined Standards)**: 內建 MIL-STD-810G, ISTA, NEBS 等常見規範範例。

---

## 🛠 技術棧 | Tech Stack
* **Frontend**: HTML5, CSS3 (Dark Mode Theme)
* **JavaScript**: Vanilla JS for kinematic logic
* **Visualization**: Plotly.js for interactive log-log charts

---

## 📖 使用說明 | Usage
1. 前往 [Live Demo 連結](https://LamChamg.github.io/vibration-calculator/)。
2. 選擇 **Sine** 或 **Random** 標籤頁。
3. 載入預設範例或手動輸入頻率點。
4. 點擊「自動計算」即可獲得完整曲線與預估值。

1. Visit the [Live Demo Link](https://LamChamg.github.io/vibration-calculator/).
2. Select the **Sine** or **Random** tab.
3. Load a preset or manually input frequency points.
4. Click "Calculate" to get the full profile and estimated values.

---

## 👨‍💻 作者 | Author
**Lam** 可靠度工程師 (Reliability Engineer)
專長：環境試驗、可靠度標準分析 (MIL-STD-810, IEC, ISTA)
