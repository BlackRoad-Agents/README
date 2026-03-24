# BlackRoad-Agents

Documentation hub for the BlackRoad-Agents GitHub organization. 76 repos, 200 agents, 12 core personas.

## Core Infrastructure

| Repo | Description |
|------|-------------|
| [agent-memory](https://github.com/BlackRoad-Agents/agent-memory) | SQLite + FTS5 persistent agent memory system |
| [ollama-fleet](https://github.com/BlackRoad-Agents/ollama-fleet) | Multi-node Ollama model management across Pi fleet |
| [hailo-vision](https://github.com/BlackRoad-Agents/hailo-vision) | Hailo-8 NPU object detection (YOLOv8s + CPU fallback) |
| [rag-engine](https://github.com/BlackRoad-Agents/rag-engine) | RAG pipeline with Qdrant vectors + Ollama embeddings |
| [voice-engine](https://github.com/BlackRoad-Agents/voice-engine) | Voice I/O — Whisper STT + Piper TTS |
| [roundtrip](https://github.com/BlackRoad-Agents/roundtrip) | Sovereign multi-agent chat system |
| [RoadCode](https://github.com/BlackRoad-Agents/RoadCode) | Monorepo pointer — all agent repos across orgs |

## Agent Personas

| Repo | Agent | Role |
|------|-------|------|
| [road](https://github.com/BlackRoad-Agents/road) | Road | Fleet coordinator, primary agent |
| [echo](https://github.com/BlackRoad-Agents/echo) | Echo | NATS mesh relay, pub/sub |
| [atlas](https://github.com/BlackRoad-Agents/atlas) | Atlas | Infrastructure mapper |
| [cipher](https://github.com/BlackRoad-Agents/cipher) | Cipher | Security and encryption |
| [forge](https://github.com/BlackRoad-Agents/forge) | Forge | Builder and deployer |
| [herald](https://github.com/BlackRoad-Agents/herald) | Herald | Announcements and notifications |
| [nexus](https://github.com/BlackRoad-Agents/nexus) | Nexus | Connection hub |
| [oracle](https://github.com/BlackRoad-Agents/oracle) | Oracle | Knowledge and search |
| [pulse](https://github.com/BlackRoad-Agents/pulse) | Pulse | Health monitoring |
| [sentinel](https://github.com/BlackRoad-Agents/sentinel) | Sentinel | Watchdog and alerts |
| [spark](https://github.com/BlackRoad-Agents/spark) | Spark | Creative and generative |
| [vector](https://github.com/BlackRoad-Agents/vector) | Vector | Embeddings and similarity |

## Fleet Management

| Repo | Description |
|------|-------------|
| [fleet-status](https://github.com/BlackRoad-Agents/fleet-status) | Real-time fleet health dashboard |
| [fleet-deploy](https://github.com/BlackRoad-Agents/fleet-deploy) | Deployment automation across Pi nodes |
| [fleet-monitor](https://github.com/BlackRoad-Agents/fleet-monitor) | Continuous monitoring and alerting |
| [fleet-config](https://github.com/BlackRoad-Agents/fleet-config) | Shared configuration for all agents |

## Vision and Voice

| Repo | Description |
|------|-------------|
| [hailo-vision](https://github.com/BlackRoad-Agents/hailo-vision) | Hailo-8 accelerated object detection |
| [voice-engine](https://github.com/BlackRoad-Agents/voice-engine) | Speech I/O with conversation loop |
| [camera-feed](https://github.com/BlackRoad-Agents/camera-feed) | Camera capture and streaming |

## Monitoring

| Repo | Description |
|------|-------------|
| [agent-dashboard](https://github.com/BlackRoad-Agents/agent-dashboard) | Web dashboard for agent activity |
| [agent-logs](https://github.com/BlackRoad-Agents/agent-logs) | Centralized log aggregation |
| [agent-metrics](https://github.com/BlackRoad-Agents/agent-metrics) | Performance metrics collection |

## Stats

- **76 repos** in BlackRoad-Agents
- **200+ agents** registered in RoundTrip
- **12 core personas** with distinct roles
- **5 Pi nodes** running the fleet (Alice, Cecilia, Octavia, Aria, Lucidia)
- **52 TOPS** AI inference (2x Hailo-8)
- **239 repos** across all Gitea + GitHub orgs

## Architecture

```
User / API
    |
    v
RoundTrip (chat hub) --> Agent Personas
    |                        |
    v                        v
agent-memory (SQLite)   ollama-fleet (inference)
    |                        |
    v                        v
rag-engine (Qdrant)    hailo-vision (NPU)
    |                        |
    v                        v
voice-engine (I/O)     fleet-* (management)
```

## Part of BlackRoad-Agents

Remember the Road. Pave Tomorrow.

BlackRoad OS, Inc. — Incorporated 2025.
