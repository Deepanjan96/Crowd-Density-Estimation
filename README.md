# 🧠 Crowd Density Estimation using YOLOv5

This project uses a custom-trained YOLOv5 model to detect people in crowd images and estimate crowd density levels (Low / Medium / High) from video footage.

The model is trained on over 500 annotated images and applied to real-time video frames to provide visual insights into people count and density variation.

---

## 📊 Key Features

- 🏷️ Custom object detection using YOLOv5 (`best.pt`)
- 🧮 Frame-wise person counting
- 🌡️ Crowd density classification:
  - 0–10 people ➝ Low 🟢
  - 11–30 people ➝ Medium 🟡
  - >30 people ➝ High 🔴
- 📈 CSV export of results
- 📊 Graphs for people count and density trends
- 📸 Visualization of detected images and frames

---

## 🔗 Download Trained Model

Due to GitHub's file size restrictions, the trained YOLOv5 model (`best.pt`) is hosted externally:

👉 [Download `best.pt` from Google Drive](https://drive.google.com/file/d/1-1aqSgmrp5auVglkUawrKEZduDmGjyPM/view?usp=sharing)


---

## 🗂️ Files Included

| File                        | Description                           |
|-----------------------------|---------------------------------------|
| `Crowd_Detection_Deepanjan.ipynb` | Main Colab notebook (full pipeline)   |
| `check_detected_titled.jpg`       | Sample image with people detected     |
| `crowd_analysis_results.csv`      | Frame-wise people count + density     |
| `people_count_plot.png`           | Graph: People per frame               |
| `crowd_density_plot.png`         | Graph: Crowd density per frame        |

---

## 🛠 Tech Stack & Tools

- Python, OpenCV, Pandas, Matplotlib  
- YOLOv5 (Ultralytics)  
- Google Colab  
- Google Drive (for model hosting)

---

## 🧾 How to Use

1. Upload a video to the notebook
2. Frames are extracted automatically
3. The model detects persons and saves:
   - Annotated images
   - CSV file
   - Graphs of people & density
4. All results are downloadable or saved to Drive

---

## 🙋‍♂️ Author

**Deepanjan Kayal**  
🎓 B.Tech in Electrical Engineering  
📍 Kolkata, India  
📫 [officialdeepanjan4@gmail.com](mailto:officialdeepanjan4@gmail.com)

---

## 📎 License

This project is open-source under the [MIT License](LICENSE).

---

## ⭐ Star This Repo!

If you found this project helpful, feel free to star ⭐ it and share!
