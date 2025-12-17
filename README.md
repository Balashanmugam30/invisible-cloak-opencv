# 🪄 Invisible Cloak — Harry Potter-Style Magic with OpenCV

> *Turn a red cloth into a real-time invisibility cloak using computer vision.*

[![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)](https://www.python.org)
[![OpenCV](https://img.shields.io/badge/OpenCV-Enabled-5C3EE8?style=for-the-badge&logo=opencv)](https://opencv.org)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)](https://github.com/Balashanmugam30/invisible-cloak-opencv)
[![Live Demo](https://img.shields.io/badge/Live_Demo-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/posts/balashanmugams_futurix2025-invisiblecloak-harrypottervibes-activity-7370684897872613376-GlDC)

This project uses **Python and OpenCV** to create a real-time *invisibility cloak effect* inspired by the Harry Potter universe. A colored cloth (commonly red) appears invisible by intelligently replacing its pixels with the captured background using computer vision techniques.

---

## 🎥 Live Demonstration

Watch the invisibility effect in action:

🔗 https://www.linkedin.com/posts/balashanmugams_futurix2025-invisiblecloak-harrypottervibes-activity-7370684897872613376-GlDC

---

## 🧠 How It Works

The invisibility illusion is achieved through a simple but powerful computer vision pipeline:

1. The webcam captures a static background frame.
2. A specific color range (cloak color) is detected using the HSV color space.
3. A mask is created to isolate the cloak region.
4. The masked region is replaced with the background pixels.
5. The final frame is rendered in real time, creating the illusion of invisibility.

---

## ⚡ Key Concepts Used

- 📸 Real-time video capture with OpenCV  
- 🎨 HSV color space masking  
- 🧠 Pixel-level background replacement  
- ⏱️ Frame-by-frame processing  

---

## 🛠 Technologies Used

- **Python 3.x**
- **OpenCV (cv2)**
- **NumPy**

---

## 📂 Project Structure

```

invisible-cloak-opencv/
├── main.py               # Core invisibility logic
├── requirements.txt      # Python dependencies
└── README.md

````

---

## 🚀 Run Locally

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Balashanmugam30/invisible-cloak-opencv.git
cd invisible-cloak-opencv
````

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Program

```bash
python main.py
```

Make sure your webcam is connected. Hold a **solid-colored cloth** in front of the camera to see the effect.

---

## 🧪 Tips for Best Results

* Use a **bright, solid color cloth** (red works best)
* Avoid patterned or reflective fabrics
* Keep the background static while capturing it
* Ensure good lighting for accurate color detection

---

## 🎯 Why This Project Matters

This project demonstrates:

* Practical application of computer vision
* Real-time image processing skills
* Creative use of OpenCV for visual effects
* Strong Python fundamentals

It’s a great showcase project for **AI / ML / Computer Vision portfolios**.

---

## 👨‍💻 Author

**Balashanmugam S**

* GitHub: [https://github.com/Balashanmugam30](https://github.com/Balashanmugam30)
* LinkedIn: [https://www.linkedin.com/in/balashanmugams/](https://www.linkedin.com/in/balashanmugams/)
* Instagram: [https://www.instagram.com/balaxxh](https://www.instagram.com/balaxxh)

> *Where code meets illusion.*

```
```
