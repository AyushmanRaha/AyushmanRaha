<div align="center">

<a href="https://github.com/AyushmanRaha">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1000&color=00C2FF&center=true&vCenter=true&width=750&lines=Systems+%26+ML+Engineer;Low-Latency+%26+Concurrent+C%2B%2B;Applied+Machine+Learning;Embedded+%26+Real-Time+Systems" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/araha04/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AyushmanRaha)
[![Email](https://img.shields.io/badge/Email-00C2FF?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ayushman.raha.iguide@gmail.com)
[![Open to Opportunities](https://img.shields.io/badge/Open%20to-Systems%20%2F%20ML%20%2F%20Embedded-2ECC71?style=for-the-badge)]()

</div>

<br/>

## About

I work across systems engineering, applied machine learning, and embedded software — building things where correctness and performance both have to hold under real constraints. That means reasoning carefully about concurrency, memory layout, and failure behavior, whether the target is a multi-core process, a model running entirely on-device, or a microcontroller with a few hundred kilobytes of RAM.

---

## Focus Areas

<table>
<tr>
<td width="33%" valign="top">

### ⚡ Low-Latency & Concurrent Systems
Lock-free data structures built on explicit memory ordering, cache-conscious layouts that avoid false sharing, and durable, zero-copy I/O paths — designed to stay correct under concurrent load, not just fast on paper.

</td>
<td width="33%" valign="top">

### 🧠 Applied Machine Learning
End-to-end pipelines that go from messy, real-world data to a trained model to a usable output — local-first inference, model comparison, and evaluation against ground truth, with as much attention on the engineering around the model as on the model itself.

</td>
<td width="33%" valign="top">

### 🔧 Embedded & Real-Time Systems
RTOS-based firmware with clear task separation, control logic kept independent of hardware so it can be unit-tested on a host machine, and fail-safe behavior when sensors or connectivity misbehave.

</td>
</tr>
</table>

---

## Selected Work

### [Aether-Stream](https://github.com/AyushmanRaha/Aether-Stream)
A lock-free, low-latency message broker library in C++20, built around a cache-line-aligned SPSC ring buffer with explicit acquire/release atomics and a memory-mapped write-ahead log for zero-copy durability. CI covers sanitizers (ASan/UBSan/TSan), static analysis, and a Google Benchmark suite — performance is reported only from measured, reproducible runs.

`C++20` `Lock-Free` `SPSC` `mmap` `WAL`

---

### [DepthLens Pro](https://github.com/AyushmanRaha/DepthLensPro)
A local-first desktop application for monocular depth estimation. Runs PyTorch and optional ONNX Runtime models entirely on-device to generate depth maps, compare model architectures side by side, evaluate output against ground truth, and export 3D point clouds — with no cloud calls or external API keys.

`Python` `PyTorch` `ONNX Runtime` `FastAPI` `Electron`

---

### [EdgeGuard-ESP32](https://github.com/AyushmanRaha/EdgeGuard-ESP32)
An RTOS-based ESP32 room-sensing and relay-control node. FreeRTOS task separation across sensing, control, and web layers; a control-logic core kept pure and unit-tested independently of hardware; a local dashboard and HTTP API; and fail-safe relay behavior when sensors go stale or faults occur.

`C/C++` `FreeRTOS` `ESP32` `PlatformIO`

---

## Tech Stack

<div align="center">

**Languages**

![C++](https://img.shields.io/badge/C++17%2F20-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

**Systems & Embedded Tooling**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GoogleTest](https://img.shields.io/badge/GoogleTest-4285F4?style=for-the-badge&logoColor=white)
![PlatformIO](https://img.shields.io/badge/PlatformIO-FF7F00?style=for-the-badge&logo=platformio&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-00979D?style=for-the-badge)

**Machine Learning & Data**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![ONNX Runtime](https://img.shields.io/badge/ONNX%20Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**App & Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

</div>

---

## Currently Exploring

- Lock-free / concurrent data structures in modern C++
- RTOS fundamentals and microcontroller programming (STM32, ESP32)
- ROS 2 basics for robotics and autonomous systems
- Applied ML tooling for real-world, messy data

---

## GitHub Stats

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=AyushmanRaha&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=00C2FF&icon_color=00C2FF&text_color=C9D1D9"/>
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AyushmanRaha&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00C2FF&text_color=C9D1D9"/>

</div>

---

<div align="center">

**Open to systems, applied ML, and embedded engineering conversations — let's connect.**

</div>
