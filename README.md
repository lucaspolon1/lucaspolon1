# Lucas Poloni – Engineering Portfolio

## 👋 About Me
Hi, I’m Lucas Poloni (@lucaspolon1).  
I’m interested in computer vision and robotics, with a focus on applying machine learning to real-world sensing and perception problems.  
I’m currently learning probabilistic systems for machine learning models.

I'm looking for an entry level role working with robotics or sensors.
---

## 🚀 Featured Projects

### 🔹 Trash Detection Along Streams using Deep Neural Networks

Custom-trained trash detection model for annual stream assessments; real-time processing from drone aerial imagery.

---

#### Why does it matter?

- Stream pollution monitoring traditionally requires hours of manual field surveys that are costly, spatially limited, and difficult to scale across watersheds  
- Automated aerial detection reduces assessment time by **10–100×**, while enabling geolocalized debris maps for quantitative environmental management  

---

#### What did I do?

- Benchmarked **15+ YOLO models** to identify optimal speed-accuracy tradeoff, selecting **YOLOv26-medium** for embedded deployment on UAV platforms  
- Trained a custom detection model via transfer learning on **132 field-collected images + TACO public dataset**, achieving robust detection across multiple trash categories despite challenging stream conditions (vegetation occlusion, water reflections, variable lighting)  
- Deployed model in a **real-time video processing pipeline**, demonstrating operational capability for autonomous stream monitoring missions  

---

#### Tech Stack
Python, PyTorch, Ultralytics YOLO, OpenCV, Roboflow, NVIDIA H100 GPU  

---

#### Results
- Benchmark tradeoff analysis across 15+ YOLO models  
- Successful real-time detection of stream debris in aerial imagery  
- Demonstrated feasibility for autonomous environmental monitoring deployment  

📌 *Insert images:*
- Benchmark speed vs accuracy plot  
- Example detection output frame  

---

#### Link
Private repository (available upon request) | Competition submission / Poster presentation

---

### 🔹 Personal Finance Tracker
I wanted a way to track my finances, so I made a web application that allows me to upload statements from my bank, brokerage firms, and credit cards.

**Why does it matter?**  
- Unified dashboard for tracking spending, income, and savings goals across 7+ accounts that previously required juggling multiple banking apps
- Travel fund calculator shows exactly when I can afford trips based on my savings allocation and current spending patterns

**What did you do?**  
- Built full-stack web app with Python/Streamlit handling multi-format CSV parsing, duplicate detection, and SQLite database management
- Engineered intelligent parser that automatically detects column formats, cleans currency data, and categorizes transactions across different bank formats

**Link:** https://github.com/lucaspolon1/personal-finance-tracker.git

---

## 🛠️ Skills & Tools
- Programming: [Python, C, MATLAB, etc.]
- Tools/Frameworks: [PyTorch, OpenCV, Arduino, etc.]
- Areas: [Computer Vision, Robotics, Embedded Systems, etc.]

---

## 📫 Contact
- Email: ldpoloni@memphis.edu  
- [ADD: LinkedIn or other link if you want]

---

<!---
lucaspolon1/lucaspolon1 is a ✨ special ✨ repository because its `README.md` appears on your GitHub profile.
--->
