<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:00C2FF&height=200&section=header&text=Ayushman%20Raha&fontSize=60&fontColor=FFFFFF&animation=fadeIn&fontAlignY=38&desc=Systems%20%26%20Software%20Engineer&descAlignY=58&descSize=20" width="100%"/>

<img src="https://komarev.com/ghpvc/?username=AyushmanRaha&style=flat-square&color=00C2FF&label=PROFILE+VIEWS" alt="Profile Views" />

<a href="https://github.com/AyushmanRaha">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1000&color=00C2FF&center=true&vCenter=true&width=750&lines=Systems+%26+Software+Engineer;C%2B%2B+%7C+Low-Latency+Systems;Applied+Machine+Learning;Exploring+Embedded+Systems+%26+Robotics" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/araha04/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AyushmanRaha)
[![Email](https://img.shields.io/badge/Email-00C2FF?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ayushman.raha.iguide@gmail.com)
[![Open to Work](https://img.shields.io/badge/Open%20to-SDE%20%2F%20Embedded%20Roles-2ECC71?style=for-the-badge)]()

</div>

<br/>

## About

I work across systems and software engineering — from low-level, performance-critical C++ to applied machine learning and the tooling around it. I'm most interested in problems where correctness and performance both matter: concurrency, memory layout, and software that has to behave predictably under real constraints.

Outside of that, I've been spending more time on embedded systems and robotics fundamentals — RTOS concepts, microcontroller programming, and work that sits closer to hardware.

```cpp
class AyushmanRaha {
public:
    std::string languages[] = { "C++17/20", "Python", "C", "Java" };
    std::string focus[]     = { "Low-Latency Systems", "Applied Machine Learning",
                                 "Computer Vision", "Embedded Systems (growing focus)" };
    std::string currently   = "Lock-free C++ · ML pipelines · RTOS & embedded fundamentals";
};
```

---

## What I Work On

<table>
<tr>
<td width="33%" valign="top">

### ⚡ Low-Latency C++ Systems
Lock-free concurrent data structures, cache-conscious memory layouts, and zero-copy I/O — built to avoid the usual overhead of locks and syscalls in throughput-sensitive paths.

</td>
<td width="33%" valign="top">

### 📊 Applied Machine Learning
End-to-end ML pipelines — from messy real-world data to trained models to decision-support output, with an emphasis on the engineering around the model, not just the model itself.

</td>
<td width="33%" valign="top">

### 🖥️ Computer Vision & Desktop Tooling
Vision pipelines and local-first desktop applications — model inference, benchmarking, and evaluation tooling that runs entirely on-device.

</td>
</tr>
</table>

<div align="center">

**Currently building toward:** embedded systems (STM32, ESP32), RTOS fundamentals (FreeRTOS), and robotics (ROS 2).

</div>

---

## Tech Stack

<div align="center">

**Languages**

![C++](https://img.shields.io/badge/C++17%2F20-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

**Systems & Tooling**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GoogleTest](https://img.shields.io/badge/GoogleTest-4285F4?style=for-the-badge&logoColor=white)

**Machine Learning & Data**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![ONNX Runtime](https://img.shields.io/badge/ONNX%20Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**App & Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

</div>

---

## Featured Projects

### [Aether-Stream](https://github.com/AyushmanRaha/Aether-Stream)
**Ultra-low-latency, lock-free messaging engine in C++20**

A messaging engine built around a lock-free single-producer/single-consumer ring buffer using C++20 atomics with explicit acquire/release ordering, instead of `std::mutex`-based queuing. Data structures are cache-line aligned to avoid false sharing, and persistence is handled via a memory-mapped write-ahead log for zero-copy durability. Built with CMake, tested with GoogleTest.

`C++20` `Lock-Free` `SPSC` `mmap`

---

### [BizLens Analytics](https://github.com/AyushmanRaha/BizLens-Analytics)
**ML pipeline for customer churn prediction**

A churn-prediction pipeline with an ETL layer that handles inconsistent real-world CSV schemas, an XGBoost classifier trained with SMOTE to address class imbalance, and a tiered (Low/Medium/High/Critical) risk-scoring output mapped to suggested retention actions. Built with Python and Streamlit.

`Python` `XGBoost` `Streamlit` `ETL`

---

### [DepthLens Pro](https://github.com/AyushmanRaha/DepthLensPro)
**Local-first desktop app for monocular depth estimation**

A desktop application (Electron + FastAPI + PyTorch/ONNX Runtime) for running and comparing monocular depth estimation models, benchmarking ONNX-accelerated inference, evaluating against ground truth, and exporting 3D point clouds — entirely on-device, with no cloud calls.

`Python` `PyTorch` `ONNX Runtime` `Electron`

---

## GitHub Stats

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=AyushmanRaha&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=00C2FF&icon_color=00C2FF&text_color=C9D1D9"/>
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AyushmanRaha&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00C2FF&text_color=C9D1D9"/>

<br/>

[![GitHub Streak](https://streak-stats.demolab.com?user=AyushmanRaha&theme=tokyonight-duo&hide_border=true&background=0D1117&ring=00C2FF&fire=00C2FF&currStreakLabel=00C2FF)](https://git.io/streak-stats)

</div>

---

## Currently Exploring

- Lock-free / concurrent data structures in modern C++
- RTOS fundamentals and microcontroller programming (STM32, ESP32)
- ROS 2 basics for robotics and autonomous systems
- Applied ML tooling for real-world, messy data

---

<div align="center">

**Open to Software / Embedded Engineering opportunities — let's connect.**

</div>
