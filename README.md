# Syed Abdul Hadi Sabih

Real-time voice AI engineer — WebRTC, sub-second turn latency, self-hosted STT/TTS pipelines, RAG. Also build full-stack AI applications and automation tools end to end.

### Flagship Projects

**Voxely** [[Live SaaS Product](https://voxely.space/)]
- **Problem**: High-latency, unnatural conversational voice agents degrade customer experience.
- **Stack**: WebRTC, FastAPI, React/TS, custom STT/TTS pipelines.
- **Hard part**: Orchestrating multi-model pipelines over WebRTC while maintaining strict sub-second turn latency.
- **Result**: Live production SaaS answering inbound business calls 24/7, booking appointments, and taking messages.

**Voice Cloning Engine** [[Code](https://github.com/sabhierfan/voice-cloning-engine)]
- **Problem**: Third-party voice synthesis APIs are expensive and introduce network latency to real-time pipelines.
- **Stack**: PyTorch, RVC v2, HiFi-GAN vocoders, ContentVec.
- **Hard part**: Optimizing feature extraction and vocoder inference for strict real-time execution.
- **Result**: Self-hosted, high-fidelity voice cloning engine trained on just 2 hours of clean audio data.

**Concurrent Voice Session Infrastructure**
- **Problem**: Testing and running real-time voice pipelines at scale requires many simultaneous audio sessions, but browser-based audio assumes one physical microphone per machine.
- **Stack**: Python, Docker, Linux ALSA/PulseAudio virtual devices, dual-LLM pipeline.
- **Hard part**: Building OS-level virtual microphone routing so each headless container streams independent real-time audio, with per-session device isolation and no contention across containers.
- **Result**: Containerized framework orchestrating concurrent headless audio sessions on a single host, with sub-second transcription and intent handling.

### Other Projects

- **Medinova** — Healthcare scheduling platform prototype with patient/doctor/admin dashboards and an AI symptom-triage assistant. [[Code](https://github.com/sabhierfan/medinova)] [[Live Demo](https://medinova.21108124ml.workers.dev)]
- **HourHive.ai** — Timetable management system for universities with AI-optimized generation and conflict resolution. [[Code](https://github.com/sabhierfan/HourHive.ai)]
- **Skin Analyze** — Cross-platform React Native app for skin analysis with camera capture and on-device ML inference. [[Code](https://github.com/sabhierfan/Skin_Analyze)]
- **ChronosAI** — Schedule and timetable management web app with Firebase-backed auth. [[Live Demo](https://chronosai-frontend.pages.dev)]
- **Little Story Teller** — AI-powered storytelling app generating stories via NLP. [[Code](https://github.com/sabhierfan/Little-Story-Teller)]
- **Cat vs Dog Classification** — CNN image classifier with data augmentation and evaluation metrics. [[Code](https://github.com/sabhierfan/cat-and-dog-classification)]

### Client Work

- **Earth Engineering Associates** — Website for a geotechnical/geological engineering consulting firm. [[Live Demo](https://earth-engineering-website.pages.dev)]
- **Designer Portfolio** — Portfolio site built for a visual and brand designer client. [[Live Demo](https://saad-portfolio.21108124ml.workers.dev)]

### NDA
- More client & enterprise projects across AI, web, and mobile — under NDA.

### Contact

- **Email**: [sabhi@voxely.space](mailto:sabhi@voxely.space)
- **LinkedIn**: [abdulhadiai](https://www.linkedin.com/in/abdulhadiai/)
- **Upwork**: [Profile](https://www.upwork.com/freelancers/~01eb73aa00b031cb53?mp_source=share)
- **Fiverr**: [Profile](https://www.fiverr.com/s/5rg3apE)
