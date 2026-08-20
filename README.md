# Syed Abdul Hadi Sabih

Real-time voice AI engineer. WebRTC, sub-second turn latency, self-hosted STT/TTS pipelines, RAG.

### Projects

**Voice Cloning Engine**
- **Problem**: Third-party voice synthesis APIs are expensive and introduce network latency to real-time pipelines.
- **Stack**: PyTorch, RVC v2, HiFi-GAN vocoders, ContentVec.
- **Hard part**: Optimizing feature extraction and vocoder inference for strict real-time execution.
- **Result**: Self-hosted, high-fidelity voice cloning engine trained on just 2 hours of clean audio data.

**Voxely** [[Live SaaS Product](https://voxely.space/)]
- **Problem**: High-latency, unnatural conversational voice agents degrade customer experience.
- **Stack**: WebRTC, FastAPI, React/TS, custom STT/TTS pipelines.
- **Hard part**: Orchestrating multi-model pipelines over WebRTC while maintaining strict sub-second turn latency.
- **Result**: Live production SaaS successfully handling 100+ concurrent live voice-AI calls.

**Concurrent Voice Session Infrastructure**
- **Problem**: Testing and running real-time voice pipelines at scale requires many simultaneous audio sessions, but browser-based audio assumes one physical microphone per machine.
- **Stack**: Python, Docker, Linux ALSA/PulseAudio virtual devices, dual-LLM pipeline.
- **Hard part**: Building OS-level virtual microphone routing so each headless container streams independent real-time audio, with per-session device isolation and no contention across containers.
- **Result**: Containerized framework orchestrating concurrent headless audio sessions on a single host, with sub-second transcription and intent handling.

### Contact

- **Email**: [sabhi@voxely.space](mailto:sabhi@voxely.space)
