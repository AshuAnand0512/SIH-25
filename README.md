# SIH-25
Acadmix - SIH Project                                                                                10 Sep, 2025 - 15 Oct, 2025
Team Size: 6
                                                                                                      
Key Skills: Web Development Frontend Development

Developed a full-stack, browser-based classroom recording and live streaming platform designed to bridge the urban-rural education gap in India. The system captures teacher screen and audio in real-time using WebRTC and MediaRecorder APIs, processes
recordings via FFmpeg, and serves them through a student dashboard with on-demand playback and AI-based quizzes.

Key highlights:
Built with Go (Gorilla Mux/WebSocket) backend, HTML5/CSS3 frontend, and SQLite for session and media storage
Implemented adaptive Opus codec streaming (8–48 kbps) with dynamic bitrate adjustment for low-bandwidth rural networks (~150
MB/hr)
Designed offline-first architecture with Progressive Web App support for low-spec devices and smartphones
Containerized via Docker Compose for lightweight self-hosted deployment on minimal hardware (2GB RAM, 20GB storage)Leveraged PDF.js and Canvas API for real-time slide rendering and live annotations.
