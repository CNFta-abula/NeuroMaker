---
title: "測試文章：我的第一個 NeuroMaker 專案紀錄"
date: 2026-03-10T18:00:00+08:00
draft: false
tags: ["測試", "專案紀錄"]
categories: ["教學筆記"]
---

這是一篇用來測試 Hugo 排版與圖片顯示的文章！未來可以直接拿這篇當作寫作範本。

## 專案動機與目標
記錄這次專案的核心目標，例如探討如何將硬體實作（如 Arduino）結合心理學概念。

## 圖片排版測試
下面是一張測試圖片。只要把圖片放在 `static/images/` 底下，就能輕鬆引用，我還加了圓角跟淡淡的陰影讓它看起來更有質感。

<div align="center">
  <img src="/images/test-image.jpg" width="80%" alt="請在 static/images 放一張名為 test-image.jpg 的圖片" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
  <p style="color: gray; font-size: 0.9em;">圖 1：這是我加了自訂效果的圖片</p>
</div>

## 程式碼顯示測試
如果是開發筆記，放上 C++ 或 Python 程式碼，PaperMod 主題會自動幫我們做語法高亮：

```cpp
void setup() {
  Serial.begin(115200);
  Serial.println("Hello, NeuroMaker! 網站部署測試成功！");
}