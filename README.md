<div align="center">
  <h1>Omar Younis <img src="https://user-images.githubusercontent.com/1303154/88677602-1635ba80-d120-11ea-84d8-d263ba5fc3c0.gif" width="28" alt="Waving hand"></h1>
</div>

I'm a software engineer with a foundation in mechanical engineering and an M.S. in computer science. I have developed diverse software across the whole tech stack, including:

- ✨ Fine-tuned and deployed a 1.5B parameter LLM that runs entirely on Apple's A16 chip from an iPhone 14 Pro.
- 🎯 Developed the first known CUDA implementation of Brent's root-finding method.
- 📱 Designed, built, and shipped **Nahtadi**, a privacy-first iOS app that computes prayer times and Qibla direction from astronomical algorithms; earned a 5-star average on the App Store.
- 🚁 Created pilot-training software that the US Coast Guard implemented at all of its air stations.
- 🔄 Built several ETL pipelines and cut feature development time by 40% for a Fortune 100 company.
- 🧠 Developed an ML neural network that improved predictive accuracy by 25% for Brazil's largest package delivery company.
- 🤖 Built software for a robotic system at Stanford University.
- 📈 Created software that raised efficiency by 50% at an engineering firm.

---

## 🚀 Featured Project

<div align="center">

<img src="https://www.hendaseh.com/images/nahtadi/icon.png" width="80" alt="Nahtadi App Icon">

### Nahtadi
*Accurate prayer times and Qibla direction, always at hand*

</div>

An iOS app that computes precise Islamic prayer times and Qibla direction using astronomical algorithms. Architected in SwiftUI/SwiftData using MVVM, with 0 data collection and full on-device operation. Supports multiple calculation methods, the Hijri calendar, local notifications, and offline use, and meets WCAG 2.2 AA accessibility with VoiceOver and Dynamic Type support. The astronomical engine behind it is a separate zero-dependency Python library: [Islamic Prayer Time Algorithm Library](https://github.com/osyounis/islamic_prayer_time_app).

<div align="center">

[![Download on App Store](https://tools.applemediaservices.com/api/badges/download-on-the-app-store/black/en-us?size=135x40&releaseDate=1704067200)](https://apps.apple.com/us/app/nahtadi/id6755970888)
&nbsp;&nbsp;
[![Visit Website](assets/website-badge.svg)](https://www.hendaseh.com/nahtadi)

</div>

---

## 🧪 Selected Projects

- ✂️ **[On-Device LLM Summarizer](https://github.com/osyounis/a16-summarizer)**: QLoRA-tuned Qwen2.5-1.5B on DialogSum to achieve a +0.9 ROUGE-L score over the base. Quantized it to 4-bit MLX and deployed it in a SwiftUI app that runs entirely on an iPhone 14 Pro's A16 chip (a chip below Apple Intelligence's hardware line). Built with PyTorch, PEFT/TRL, and MLX Swift.
- 🎯 **[Parallelizing Brent's Method with CUDA](https://github.com/osyounis/brent_cuda)**: First known CUDA implementation of Brent's root-finding method, parallelizing 4M+ independent problems across GPU threads on an NVIDIA RTX 3080. Benchmarked 35x kernel-level and 8.8x end-to-end speedup over a single-threaded C++ baseline. Profiled with Nvidia Nsight Systems to isolate PCIe transfer.
- 🧭 **[Maritime Collision Avoidance](https://collision-avoidance-radar-plotting-app.streamlit.app/)** ([source](https://github.com/osyounis/collision_avoidance_radar_plotting_app)): Live web app in use by the U.S. Coast Guard Auxiliary. Computes the closest point of approach and course/speed maneuver solutions from radar observations, using vector-based relative-motion algorithms. Built in Python and Streamlit with full pytest coverage and type-checked, linted code.
- 🏗️ **[Mini Compiler](https://github.com/osyounis/compiler-project)**: Expanded a 339-line academic project into a 4K+-line modular compiler that translates a Pascal-like language into executable Python, with a table-driven LL(1) predictive parser, semantic analysis, and AST-based code generation.

---

## 💻 Tech Stack

### Languages
![Swift](https://img.shields.io/badge/swift-F54A2A?style=for-the-badge&logo=swift&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge)

### Apple Platforms & On-Device ML
![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=apple&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0066cc?style=for-the-badge&logo=swift&logoColor=white)
![SwiftData](https://img.shields.io/badge/SwiftData-F54A2A?style=for-the-badge&logo=swift&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=for-the-badge&logo=xcode&logoColor=white)
![XCTest](https://img.shields.io/badge/XCTest-147EFB?style=for-the-badge&logo=xcode&logoColor=white)
![MLX](https://img.shields.io/badge/MLX-000000?style=for-the-badge&logo=apple&logoColor=white)

### Machine Learning & GPU Computing
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Nsight](https://img.shields.io/badge/Nsight%20Systems-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)

### Infrastructure & Tooling
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Pytest](https://img.shields.io/badge/pytest-%230A9EDC.svg?style=for-the-badge&logo=pytest&logoColor=white)
![MyPy](https://img.shields.io/badge/MyPy-2A6DB2?style=for-the-badge&logo=python&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=for-the-badge&logo=ruff&logoColor=black)

---

## 📫 Let's Connect

<div align="center">

[![Email](https://img.shields.io/badge/omar%40hendaseh.com-0066cc?style=for-the-badge&logo=minutemailer&logoColor=white)](mailto:omar@hendaseh.com)
&nbsp;&nbsp;&nbsp;&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-omar--younis-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/omar-younis/)
&nbsp;&nbsp;&nbsp;&nbsp;
[![Website](https://img.shields.io/badge/hendaseh.com-0066cc?style=for-the-badge&logo=safari&logoColor=white)](https://hendaseh.com)

</div>
