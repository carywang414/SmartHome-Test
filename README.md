# 🚪 Face Recognition Access Control System

本專案為一個簡易的人臉辨識門禁系統，使用 OpenCV 搭配 FaceNet 模型進行臉部比對，辨識白名單中的人物是否可以進入。

## 📸 功能說明

- 使用攝影機即時擷取畫面
- 自動偵測人臉並進行人臉辨識
- 可從 `white/` 資料夾建立允許進入的臉部資料庫
- 辨識結果會顯示於畫面上（允許進入 / 拒絕進入 / 沒有找到人臉）

## 🖥️ 執行畫面

![](![alt text](image.png)) *(你可以擷圖放這裡)*

---

## 🛠️ 環境需求

- Python 3.8+
- OpenCV
- TensorFlow
- keras-facenet
- mediapipe

