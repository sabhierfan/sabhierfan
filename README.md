# Syed Abdul Hadi Sabih

Real-time voice AI engineer. WebRTC, sub-second turn latency, self-hosted STT/TTS pipelines, RAG.

### Projects

**Voxely** [[Live SaaS Product](https://voxely.space/)]
- **Problem**: High-latency, unnatural conversational voice agents degrade customer experience.
- **Stack**: WebRTC, FastAPI, React/TS, custom STT/TTS pipelines.
- **Hard part**: Orchestrating multi-model pipelines over WebRTC while maintaining strict sub-second turn latency.
- **Result**: Live production SaaS successfully handling 100+ concurrent live voice-AI calls.

**Vicibot**
- **Problem**: Scaling browser-based voice automation without physical hardware bottlenecks.
- **Stack**: Python, Docker, Linux audio routing, dual-LLM architecture.
- **Hard part**: Engineering custom Linux OS-level virtual microphone routing for real-time headless audio streaming.
- **Result**: Containerized framework successfully running 100+ autonomous voice bots concurrently.

**Voice Cloning Engine**
- **Problem**: Third-party voice synthesis APIs are expensive and introduce network latency to real-time pipelines.
- **Stack**: PyTorch, RVC v2, HiFi-GAN vocoders, ContentVec.
- **Hard part**: Optimizing feature extraction and vocoder inference for strict real-time execution.
- **Result**: Self-hosted, high-fidelity voice cloning engine trained on just 2 hours of clean audio data.

### Contact

- **Email**: [sabhi@voxely.space](mailto:sabhi@voxely.space)
