# Lucas Poloni – Engineering Portfolio

## 👋 About Me

Hi, I’m Lucas Poloni (@lucaspolon1).  
I’m interested in computer vision and robotics, with a focus on applying machine learning to real-world sensing and perception problems.  
I’m currently working on improving a trash detection model I developed through a robotics lab at my university.

---

## 🚀 Featured Projects

---

### 🔹 Trash Detection Along Streams using Deep Neural Networks

Custom-trained trash detection model for annual stream assessments; real-time processing from drone aerial imagery.

#### Why does it matter?

- Stream pollution monitoring traditionally requires hours of manual field surveys that are costly, spatially limited, and difficult to scale across watersheds  
- Automated aerial detection reduces assessment time by **10–100×**, while enabling geolocalized debris maps for quantitative environmental management  

#### What did I do?

- Benchmarked **15+ YOLO models** to identify optimal speed-accuracy tradeoff, selecting **YOLOv26-medium** for embedded UAV deployment  
- Trained a custom detection model via transfer learning on **132 field-collected images + TACO public dataset**, achieving robust detection across multiple trash categories under challenging conditions (vegetation occlusion, water reflections, variable lighting)  
- Deployed a real-time video processing pipeline for autonomous stream monitoring missions  

#### Tech Stack
Python, PyTorch, Ultralytics YOLO, OpenCV, Roboflow, NVIDIA H100 GPU  

#### Link
Private repository (available upon request) | Competition submission / Poster presentation  

---

### 🔹 Personal Finance Tracker

Web application for consolidating financial data across multiple accounts and tracking spending behavior.

#### Why does it matter?

- Unified dashboard for tracking spending, income, and savings goals across **7+ accounts**, replacing fragmented banking apps  
- Travel fund calculator estimates affordability of trips based on real-time savings and spending trends  

#### What did I do?

- Built a full-stack web application using Python and Streamlit  
- Implemented multi-format CSV parsing, duplicate detection, and SQLite-based transaction storage  
- Designed an intelligent parser that automatically detects bank formats, cleans currency data, and categorizes transactions across institutions  

#### Link
https://github.com/lucaspolon1/personal-finance-tracker  

---

## 🛠️ Skills & Tools

- **Programming:** Python, C, MATLAB  
- **Frameworks:** PyTorch, OpenCV, Streamlit  
- **Areas:** Computer Vision, Robotics, Embedded Systems  

---

## 📫 Contact

- Email: ldpoloni@memphis.edu  

---

<!---
lucaspolon1/lucaspolon1 is a ✨ special ✨ repository because its `README.md` appears on your GitHub profile.
--->
