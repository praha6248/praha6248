<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=24&duration=3000&pause=800&color=FF93A8&center=true&vCenter=true&width=600&lines=%E2%9D%AF+simulation+to+real+robot;%E2%9D%AF+C%2B%2B+%C2%B7+CUDA+%C2%B7+ML;%E2%9D%AF+pixels+that+look+good" alt="typing" />

# Natalia Płocha

<img src="https://img.shields.io/badge/Robotics%20·%20C++%20·%20Python-c9a3e8?style=flat-square" /> <img src="https://img.shields.io/badge/4th--year%20student%20·%20Gdańsk%20Tech-FF93A8?style=flat-square" />

<sub>Robotics, simulation and 3D graphics in the browser: manipulator kinematics, path planning, control, physics engines, interactive visualisations and clean UX/UI.</sub>

<br/><br/>

<a href="https://praha6248.github.io"><img src="https://img.shields.io/badge/Home-222222?style=for-the-badge" /></a>
<a href="#projects"><img src="https://img.shields.io/badge/Projects-FF93A8?style=for-the-badge" /></a>
<a href="https://praha6248.github.io/Natalia_Plocha_CV.pdf"><img src="https://img.shields.io/badge/Resume-222222?style=for-the-badge" /></a>

</div>

<br/>

### about

```python
natalia = {
    "does":     "robotics, simulations, ML and 3D graphics in the browser",
    "loves":    "C++, logic-heavy code, things that look beautiful",
    "ux_ui":    "interfaces that feel obvious, look calm and stay out of the way",
    "now":      "Polish OCR, robot RL in Newton, LQR, path planning",
    "rule":     "measure first, then optimise.",
}
```

<a id="projects"></a>

### Robotics & simulation

| Preview | Project | Description | Tech |
|---|---|---|---|
| <img src="https://raw.githubusercontent.com/praha6248/Robot_arm-nl/HEAD/docs/demo.gif" width="180" /> | [Robot_arm-nl](https://github.com/praha6248/Robot_arm-nl) | Robot arm controlled with natural language: a fine-tuned 360M model running locally in llama.cpp turns Polish commands into robot moves, 40/40 on the test set (beats Gemma 3 4B) | Python, llama.cpp, PyTorch, C++ |
| <img src="https://raw.githubusercontent.com/praha6248/praha6248.github.io/HEAD/public/projects/embedded.webp" width="180" /> | [Embedded_Systems_Project_2026](https://github.com/ev3nt-h0riz0n/Embedded_Systems_Project_2026) | Bare-metal firmware for a mobile robot (UniGe, team project): 500 Hz control loop, state machine with obstacle avoidance, 10 kHz PWM, interrupt-driven UART with ring buffers, IMU over SPI | C, dsPIC33, XC16 |
| | [fastcv](https://github.com/praha6248/fastcv) · [adaptiveThreshold](https://github.com/BaTo-n/adaptiveThreshold) | OpenCV filters rewritten in CUDA with PyTorch bindings. Together with [@BaTo-n](https://github.com/BaTo-n) we added an adaptive thresholding kernel (shared/constant memory, Thrust, CUDA Streams, async copies) | CUDA, C++, Thrust, PyTorch |
| <img src="https://raw.githubusercontent.com/praha6248/Robot_arm/HEAD/docs/stacking.png" width="180" /> | [Robot_arm](https://github.com/praha6248/Robot_arm) | Robot arm simulation: inverse kinematics, grabbing and stacking blocks, a text-based robot language | C++, OpenGL |
| | [planar-quadrotor-lqr](https://github.com/praha6248/planar-quadrotor-lqr) | 2D quadrotor simulation controlled by an LQR regulator | C++, Eigen, SDL2 |
| <img src="https://raw.githubusercontent.com/praha6248/praha6248.github.io/HEAD/public/projects/path-planning.webp" width="180" /> | [evolutionary-path-planning](https://github.com/praha6248/evolutionary-path-planning) | Genetic algorithm for mobile robot path planning | C++, pybind11, Python |
| <img src="https://raw.githubusercontent.com/praha6248/praha6248.github.io/HEAD/public/projects/sandbox.webp" width="180" /> | [physics-sandbox-3d](https://github.com/praha6248/physics-sandbox-3d) | Physics engine: collisions, fracturing, variable gravity | React, Three.js |
| | [signal-processing-cpp](https://github.com/praha6248/signal-processing-cpp) | Signal processing in C++ with Python bindings (DFT, noise, WAV) | C++, pybind11, Matplot++ |
|  | [Domestic-Service-Robot…](https://github.com/praha6248/Domestic-Service-Robot-Cooling-and-Quality-Degradation) | Task planning for a barista robot in PDDL / PDDL+ | PDDL, ENHSP |

### Applications

| Preview | Project | Description | Tech |
|---|---|---|---|
|  | [CzytajPDF](https://github.com/praha6248/CzytajPDF) | Library and CLI for Polish and English PDFs and scans: page-by-page text, automatic OCR for pages with missing or garbled text layers, Polish diacritics correction (Morfeusz 2). 0.09% CER on document headers, `readpdf-pl` / `readpdf-en` packages | Python, Tesseract, RapidOCR, pypdf |
|  | [odwolania2Json](https://github.com/praha6248/odwolania2Json) | HackNation 2026, UZP challenge: public procurement appeals (PDFs, scans) converted into structured JSON. CzytajPDF grew out of this project | Python, OCR |
|  | [HackYeah_2026](https://github.com/Lucjuszo/HackYeah_2026) | Focus Map ([thirdplaces.pl](https://thirdplaces.pl)): a map of places to study and work | Flutter, FastAPI, MongoDB |
|  | [praha6248.github.io](https://github.com/praha6248/praha6248.github.io) | Portfolio as an interactive 3D scene | React Three Fiber |
| | [smart-city-gdansk](https://github.com/praha6248/smart-city-gdansk) | Interactive map of Gdańsk: events, issue reports, demographics | Leaflet, FastAPI |
|  | [ambient-assisted-living-app](https://github.com/praha6248/ambient-assisted-living-app) | Monitoring vital signs and location of elderly people | Flutter, Tor |

### Organizations

| Preview | Organization | Description | Tech |
|---|---|---|---|
| <img src="https://raw.githubusercontent.com/praha6248/praha6248.github.io/HEAD/public/projects/diploma-checker.webp" width="180" /> | [PDF Diploma Checker](https://github.com/PDF-Diploma-Checker) | Desktop app that automatically reviews diploma theses in PDF: typography (line spacing, margins, fonts), language, bibliography per PN-ISO 690 and content review with a language model; returns an annotated PDF and a report. Repos: [app](https://github.com/PDF-Diploma-Checker/app), [download page](https://github.com/PDF-Diploma-Checker/diploma-checker-download) (Windows, Linux) | Python, JavaScript |

### Stack

<p align="center">
<img src="https://img.shields.io/badge/C-2b2b2b?style=flat-square&color=2b2b2b&logo=c&logoColor=FF93A8" alt="C" /> <img src="https://img.shields.io/badge/C++-2b2b2b?style=flat-square&color=2b2b2b&logo=cplusplus&logoColor=FF93A8" alt="C++" /> <img src="https://img.shields.io/badge/CUDA-2b2b2b?style=flat-square&color=2b2b2b&logo=nvidia&logoColor=FF93A8" alt="CUDA" /> <img src="https://img.shields.io/badge/Python-2b2b2b?style=flat-square&color=2b2b2b&logo=python&logoColor=FF93A8" alt="Python" /> <img src="https://img.shields.io/badge/JavaScript-2b2b2b?style=flat-square&color=2b2b2b&logo=javascript&logoColor=FF93A8" alt="JavaScript" /> <img src="https://img.shields.io/badge/Dart-2b2b2b?style=flat-square&color=2b2b2b&logo=dart&logoColor=FF93A8" alt="Dart" /> <img src="https://img.shields.io/badge/C%23-2b2b2b?style=flat-square&color=2b2b2b&logo=dotnet&logoColor=FF93A8" alt="C#" /> <img src="https://img.shields.io/badge/React-2b2b2b?style=flat-square&color=2b2b2b&logo=react&logoColor=FF93A8" alt="React" /> <img src="https://img.shields.io/badge/Three.js-2b2b2b?style=flat-square&color=2b2b2b&logo=threedotjs&logoColor=FF93A8" alt="Three.js" /> <img src="https://img.shields.io/badge/Flutter-2b2b2b?style=flat-square&color=2b2b2b&logo=flutter&logoColor=FF93A8" alt="Flutter" /> <img src="https://img.shields.io/badge/PyTorch-2b2b2b?style=flat-square&color=2b2b2b&logo=pytorch&logoColor=FF93A8" alt="PyTorch" /> <img src="https://img.shields.io/badge/FastAPI-2b2b2b?style=flat-square&color=2b2b2b&logo=fastapi&logoColor=FF93A8" alt="FastAPI" /> <img src="https://img.shields.io/badge/CMake-2b2b2b?style=flat-square&color=2b2b2b&logo=cmake&logoColor=FF93A8" alt="CMake" /> <img src="https://img.shields.io/badge/Docker-2b2b2b?style=flat-square&color=2b2b2b&logo=docker&logoColor=FF93A8" alt="Docker" />
</p>

<p align="center"><sub><a href="https://praha6248.github.io">praha6248.github.io</a></sub></p>
