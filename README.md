<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=24&duration=3000&pause=800&color=FF93A8&center=true&vCenter=true&width=600&lines=%E2%9D%AF+simulation+to+real+robot;%E2%9D%AF+C%2B%2B+%C2%B7+CUDA+%C2%B7+ML;%E2%9D%AF+pixels+that+look+good" alt="typing" />

# Natalia Płocha

<img src="https://img.shields.io/badge/Robotics%20·%20C++%20·%20Python-c9a3e8?style=flat-square" /> <img src="https://img.shields.io/badge/4th--year%20student%20·%20Gdańsk%20Tech-FF93A8?style=flat-square" />

<sub>Robotyka, symulacje i grafika 3D w przeglądarce: kinematyka manipulatorów, planowanie ścieżek, sterowanie, silniki fizyki i interaktywne wizualizacje.</sub>

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

### Robotyka i symulacje

| Projekt | Opis | Technologie |
|---|---|---|
| [Robot_arm-nl](https://github.com/praha6248/Robot_arm-nl) | Ramię robota sterowane językiem naturalnym: dostrojony model 360M (lokalnie, llama.cpp) tłumaczy polecenia po polsku na ruchy robota, 40/40 w teście (więcej niż Gemma 3 4B) | Python, llama.cpp, PyTorch, C++ |
| [Robot_arm](https://github.com/praha6248/Robot_arm) | Symulacja ramienia robota: kinematyka odwrotna, chwytanie i układanie klocków, tekstowy język robota | C++, OpenGL |
| [evolutionary-path-planning](https://github.com/praha6248/evolutionary-path-planning) | Algorytm genetyczny do planowania ścieżki robota mobilnego | C++, pybind11, Python |
| [planar-quadrotor-lqr](https://github.com/praha6248/planar-quadrotor-lqr) | Symulacja quadrotora 2D sterowanego regulatorem LQR | C++, Eigen, SDL2 |
| [Embedded_Systems_Project_2026](https://github.com/ev3nt-h0riz0n/Embedded_Systems_Project_2026) | Firmware bare-metal robota mobilnego (UniGe, projekt zespołowy): pętla sterowania 500 Hz, automat stanów z omijaniem przeszkód, PWM 10 kHz, UART na przerwaniach z buforami cyklicznymi, odczyt IMU przez SPI | C, dsPIC33, XC16 |
| [Domestic-Service-Robot…](https://github.com/praha6248/Domestic-Service-Robot-Cooling-and-Quality-Degradation) | Planowanie zadań robota-baristy w PDDL / PDDL+ | PDDL, ENHSP |
| [physics-sandbox-3d](https://github.com/praha6248/physics-sandbox-3d) | Silnik fizyki: zderzenia, kruszenie, zmienna grawitacja | React, Three.js |
| [signal-processing-cpp](https://github.com/praha6248/signal-processing-cpp) | Przetwarzanie sygnałów w C++ z bindingami do Pythona (DFT, szum, WAV) | C++, pybind11, Matplot++ |
| [fastcv](https://github.com/praha6248/fastcv) · [adaptiveThreshold](https://github.com/BaTo-n/adaptiveThreshold) | Filtry OpenCV przepisane na CUDA z bindingami PyTorch. Razem z [@BaTo-n](https://github.com/BaTo-n) dodałyśmy jądro progowania adaptacyjnego (pamięć shared/constant, Thrust, CUDA Streams, kopiowanie asynchroniczne) | CUDA, C++, Thrust, PyTorch |

### Aplikacje

| Projekt | Opis | Technologie |
|---|---|---|
| [CzytajPDF](https://github.com/praha6248/CzytajPDF) | Biblioteka i CLI do polskich i angielskich PDF-ów oraz skanów: tekst strona po stronie, automatyczny OCR stron bez warstwy tekstowej lub z „krzakami”, korekta polskich znaków (Morfeusz 2). CER 0,09% na nagłówkach pism, paczki `readpdf-pl` / `readpdf-en` | Python, Tesseract, RapidOCR, pypdf |
| [odwolania2Json](https://github.com/praha6248/odwolania2Json) | HackNation 2026, wyzwanie UZP: odwołania w zamówieniach publicznych (PDF, skany) zamieniane na ustrukturyzowany JSON. Z tego projektu wyrosło CzytajPDF | Python, OCR |
| [HackYeah_2026](https://github.com/Lucjuszo/HackYeah_2026) | Focus Map ([thirdplaces.pl](https://thirdplaces.pl)): mapa miejsc do nauki i pracy | Flutter, FastAPI, MongoDB |
| [ambient-assisted-living-app](https://github.com/praha6248/ambient-assisted-living-app) | Monitorowanie parametrów życiowych i lokalizacji osób starszych | Flutter, Tor |
| [smart-city-gdansk](https://github.com/praha6248/smart-city-gdansk) | Interaktywna mapa Gdańska: wydarzenia, zgłoszenia, demografia | Leaflet, FastAPI |
| [praha6248.github.io](https://github.com/praha6248/praha6248.github.io) | Portfolio w formie sceny 3D | React Three Fiber |
| [budget-app](https://github.com/praha6248/budget-app) | Desktopowa aplikacja do śledzenia wydatków | C#, WinForms, MySQL |

### Organizacje

| Organizacja | Opis | Technologie |
|---|---|---|
| [PDF Diploma Checker](https://github.com/PDF-Diploma-Checker) | Desktopowa aplikacja do automatycznej kontroli prac dyplomowych w PDF: typografia (interlinia, marginesy, czcionki), język, bibliografia wg PN-ISO 690 i ocena merytoryczna modelem językowym; zwraca PDF z komentarzami i raport. Repozytoria: [app](https://github.com/PDF-Diploma-Checker/app), [strona pobierania](https://github.com/PDF-Diploma-Checker/diploma-checker-download) (Windows, Linux) | Python, JavaScript |


### Stack

<p align="center">
<img src="https://img.shields.io/badge/C-2b2b2b?style=flat-square&color=2b2b2b&logo=c&logoColor=FF93A8" alt="C" /> <img src="https://img.shields.io/badge/C++-2b2b2b?style=flat-square&color=2b2b2b&logo=cplusplus&logoColor=FF93A8" alt="C++" /> <img src="https://img.shields.io/badge/CUDA-2b2b2b?style=flat-square&color=2b2b2b&logo=nvidia&logoColor=FF93A8" alt="CUDA" /> <img src="https://img.shields.io/badge/Python-2b2b2b?style=flat-square&color=2b2b2b&logo=python&logoColor=FF93A8" alt="Python" /> <img src="https://img.shields.io/badge/JavaScript-2b2b2b?style=flat-square&color=2b2b2b&logo=javascript&logoColor=FF93A8" alt="JavaScript" /> <img src="https://img.shields.io/badge/Dart-2b2b2b?style=flat-square&color=2b2b2b&logo=dart&logoColor=FF93A8" alt="Dart" /> <img src="https://img.shields.io/badge/C%23-2b2b2b?style=flat-square&color=2b2b2b&logo=dotnet&logoColor=FF93A8" alt="C#" /> <img src="https://img.shields.io/badge/React-2b2b2b?style=flat-square&color=2b2b2b&logo=react&logoColor=FF93A8" alt="React" /> <img src="https://img.shields.io/badge/Three.js-2b2b2b?style=flat-square&color=2b2b2b&logo=threedotjs&logoColor=FF93A8" alt="Three.js" /> <img src="https://img.shields.io/badge/Flutter-2b2b2b?style=flat-square&color=2b2b2b&logo=flutter&logoColor=FF93A8" alt="Flutter" /> <img src="https://img.shields.io/badge/PyTorch-2b2b2b?style=flat-square&color=2b2b2b&logo=pytorch&logoColor=FF93A8" alt="PyTorch" /> <img src="https://img.shields.io/badge/FastAPI-2b2b2b?style=flat-square&color=2b2b2b&logo=fastapi&logoColor=FF93A8" alt="FastAPI" /> <img src="https://img.shields.io/badge/CMake-2b2b2b?style=flat-square&color=2b2b2b&logo=cmake&logoColor=FF93A8" alt="CMake" /> <img src="https://img.shields.io/badge/Docker-2b2b2b?style=flat-square&color=2b2b2b&logo=docker&logoColor=FF93A8" alt="Docker" />
</p>

<p align="center"><sub><a href="https://praha6248.github.io">praha6248.github.io</a></sub></p>
