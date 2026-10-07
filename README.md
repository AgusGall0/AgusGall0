# Hi, I'm Juan Agustín Gallo 👋

Advanced **Informatics Engineering** student (4th year) at Universidad Nacional de Catamarca, Argentina, working on **computer vision, applied AI and relational databases**.

I like problems where a camera and a model can replace an expensive sensor — currently building a system that measures swimming technique from ordinary video. On the data side, I design relational databases with a focus on transactional integrity and role-based access control.

- 🔭 Working on: [swim-stroke-analyzer](https://github.com/AgusGall0/swim-stroke-analyzer) — biomechanical analysis of swimming strokes, from raw video to quantitative kinematics
- 🔬 Student member of **GSICAR** (Intelligent Systems and High-Performance Computing Research Group), FTyCA – UNCa
- 🌱 Learning: FastAPI, to pair my CV and data work with solid backend fundamentals
- 📫 Reach me: juanagustin09@gmail.com


---

## Selected projects

**[swim-stroke-analyzer](https://github.com/AgusGall0/swim-stroke-analyzer)** — *personal project, in progress (2026)*
Biomechanical analysis of swimming through computer vision. End-to-end pipeline from video to quantitative kinematics: landmark extraction with MediaPipe Pose persisted to Parquet with run metadata, signal processing (interpolation, Butterworth filtering with a cutoff frequency justified by residual analysis), joint-angle computation, stroke-cycle segmentation and a normalized mean curve.

`Python` · `MediaPipe` · `OpenCV` · `NumPy / SciPy` · `pandas` · `pytest` · `GitHub Actions`

**[sport-retail-inventory-db](https://github.com/AgusGall0/sport-retail-inventory-db)** — *course capstone project (2026)*
PostgreSQL database for multi-branch stock management in sportswear retail. I coordinated the project and owned the full data model (12 tables normalized to 3NF), the least-privilege role scheme, the PL/pgSQL business logic (procedures, functions and triggers), programmatic dataset generation and the reproducibility setup. It spins up with a single command on Docker, and CI validates the scripts and data consistency on every change. Includes a reproducible performance benchmark over 500,000 movements and 1.6 million detail rows, with execution-plan analysis that also documents when indexes *don't* help and why.

`PostgreSQL` · `PL/pgSQL` · `Docker` · `Python (pandas, NumPy)` · `GitHub Actions`

---

## Research & publications

**Development of a mobile application for livestock classification in the province of Catamarca**
Gallo, P. J., **Gallo, J. A.**, & Aranda, M. D. (2024). In *Memorias del XII Congreso Nacional de Ingeniería en Informática y Sistemas de Información (CoNaIISI 2024)*, pp. 1247–1250. Editorial Científica Universitaria, Universidad Nacional de Catamarca. Open Access, CC BY-NC-SA 4.0.

Trained a four-class image classifier — two cattle breeds (Angus, Criolla Argentina), sheep and goat — on a balanced 4,000-image dataset over 50 epochs. The model was converted to TensorFlow Lite and deployed to an Android application using MediaPipe for on-device inference, running without connectivity so it can be used in the field with no additional infrastructure.

`TensorFlow` · `TensorFlow Lite` · `MediaPipe` · `Python` · `Android` · `Jupyter / Colab`

**Computer Vision Applied to Precision Livestock Farming** — *oral presentation*
Gallo, P. J., **Gallo, J. A.**, & Aranda, M. D. X Jornadas Estudiantiles de Investigación e Innovación Tecnológica, Facultad de Tecnología y Ciencias Aplicadas, Universidad Nacional de Catamarca, October 2024. Presenting author.

---

## Tech stack

**Languages**
Python · SQL · PL/pgSQL · C · Kotlin

**Data**
PostgreSQL · pandas · NumPy · SciPy · Parquet

**Computer vision & machine learning**
MediaPipe · TensorFlow / TensorFlow Lite · OpenCV · YOLO

**Tools**
Docker · Git · GitHub Actions · Linux · pytest

**Basic knowledge**
Java · C++ · JavaScript · HTML/CSS · Django

---

## Education & certifications

- **Informatics Engineering** — Facultad de Tecnología y Ciencias Aplicadas, Universidad Nacional de Catamarca, 2021 – present (4th year)
- **[Fundamentals of Deep Learning](https://learn.nvidia.com/certificates?id=f-3sTbh5Qu2C0S9FnfFsUg)** — NVIDIA Deep Learning Institute, Certificate of Competency, March 2025
