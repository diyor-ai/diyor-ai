## Hi, I'm Mukhammaddiyor 👋

AI student at **Harbin Engineering University** (China) with **2+ years of full-stack experience on real client projects** (PHP, Laravel, Symfony, Vue.js).
I build AI products end to end, from the architecture to testing on real devices, and I document results honestly: measured, tested, limitations included.

- 🎯 **Open to:** AI / ML engineering and full-stack internships (remote or in China)
- 📫 **Contact:** diyordevwork@gmail.com · [LinkedIn](https://www.linkedin.com/in/muhammaddiyorabdulazimov)

---

### 🔨 Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**CPU Inference Benchmark**](https://github.com/diyor-ai/cpu-inference-bench) | PyTorch vs ONNX Runtime vs OpenVINO on a laptop CPU, FP32 vs INT8 post-training quantization (ResNet-18, DistilBERT). INT8 cut ResNet-18 batch-1 latency 2.3–3.5× with no statistically significant accuracy change on my sample. The first attempt showed up to 48% run-to-run noise, so I built a controlled method: pinned P-cores, fixed clock, thermal cooldown, stability rule. Profiling, paired statistical tests, CI. | PyTorch, ONNX Runtime, OpenVINO, NNCF |
| [**RoadAI**](https://github.com/diyor-ai/roadai-case-study) *(case study, code private)* | Transfer-operations platform I'm building as a product: Claude vision extracts passenger data from paper vouchers, with human review before saving. Flutter background GPS designed to survive kills and reboots (emulator-tested; real-phone re-test pending). I traced an overnight GPS failure to HyperOS switching off the GNSS receiver. 646 automated checks (backend, Flutter, dashboard). MVP; pilot in preparation. | FastAPI, Flutter, React, Claude API |
| [**Gesture Control System**](https://github.com/diyor-ai/gesture-control-system) | Control the computer with hand gestures from a regular webcam: cursor, clicks, joystick scroll, volume, media, screenshots, air drawing. Click lock for reliable double clicks, per-hand stability layer, palm-length–normalised thresholds, privacy blur, Wayland support through a uinput virtual pointer. ~30 FPS on CPU, 228 tests, CI, demo GIF. | Python, MediaPipe, OpenCV |
| [**Ames House Price Prediction**](https://github.com/diyor-ai/house-price-prediction) | Leakage-safe ML pipeline with nested cross-validation and a single test evaluation (MAE $16.4k, R² 0.875), plus error analysis showing that 3% of houses cause 49% of the error. | scikit-learn, pandas |
| [**Pro-Bot**](https://github.com/diyor-ai/pro-bot) | Telegram shop bot in Uzbek, Russian and English with Google Sheets as the database: catalog, fuzzy search, validated orders, admin panel, broadcast. Tested end to end on a real bot; 82 tests and CI. | Python, python-telegram-bot, Google Sheets |
| [**Laravel Blog**](https://github.com/diyor-ai/laravel-blog) | Laravel course project, then reviewed and hardened: found and fixed 11 issues (incl. missing authorization on post updates), upgraded from end-of-life Laravel 11 to 12 with a clean security audit, added 44 feature tests and CI. | PHP, Laravel 12, PHPUnit |

---

### 💼 Experience

- **Kadirov.DEV** — Full-Stack Developer, apprenticeship (Mar 2023 – Aug 2025; remote and part-time from Sep 2024)
  Client web projects: Symfony / Laravel REST APIs, Vue.js front-ends, Docker, GitLab merge requests and CI.
- Before that: non-commercial team projects with fellow developers (2022–2023).

---

### 🧰 Tech stack

- **AI / ML:** Python · LLM APIs (Claude, structured output) · scikit-learn · PyTorch · NumPy · Pandas · OpenCV · MediaPipe
- **Backend:** FastAPI · PHP · Laravel · Symfony · PostgreSQL · MySQL · REST · WebSocket
- **Frontend & mobile:** React · TypeScript · Vue.js · Flutter
- **Engineering:** pytest · GitHub Actions · Docker · Git · Linux · AI coding agents (Claude Code)

🌍 Uzbek · Turkish · English · Russian · Chinese (basic)
