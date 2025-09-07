# Eva AI Agent System

Voice-powered AI assistant that integrates with your entire digital ecosystem through natural conversation.

## 🎯 Project Overview

Eva is a sophisticated AI agent system that allows you to:
- Talk naturally through a React Native mobile app
- Have Claude Code (Sonnet 4) plan and execute complex tasks
- Automate actions across Google Workspace (Gmail, Drive, Calendar, Sheets, Docs)
- Extend capabilities through a modular function registry

## 🏗️ System Architecture

```
Voice Input → Mobile App → Local Server → Claude Code → Execution Bridge → APIs
                ↓                                           ↓
Voice Output ← Mobile App ← Local Server ← Response ← Bridge Results
```

### Core Components

- **Mobile App** (React Native + ElevenLabs) - Voice interface
- **Local Server** (Node.js/Express) - Communication hub
- **Claude Code Integration** - AI planning and decision-making
- **Execution Bridge** (Python) - API execution engine
- **Function Registry** (YAML) - Available capabilities definition

## 🚀 Tech Stack

### Frontend
- React Native with Expo
- ElevenLabs SDK for voice processing
- WebSocket for real-time communication

### Backend
- Node.js with Express
- Python for API integrations
- Claude Code CLI (Sonnet 4)
- Google Workspace APIs

### Infrastructure
- Local server running on MacBook Pro M4 Pro
- OAuth 2.0 authentication
- YAML-based configuration
- Automated monitoring and state management

## 🎯 Current Status

**Phase**: Core Development Complete  
**Overall Progress**: 70%

### ✅ Completed Components
- Project structure and organization
- Continuity and monitoring system
- **Function Registry & Configuration** - YAML schemas and API specifications
- **Local Server** - Node.js/Express with WebSocket support
- **Execution Bridge** - Python/FastAPI with Google APIs integration  
- **Claude Code Integration** - CLI wrapper and system prompts
- Version control setup

### 🔄 In Progress
- Mobile App development (React Native + ElevenLabs)

### 📋 Next Steps
- System integration and testing
- Authentication and security
- Performance optimization
- Final validation and launch

## 🔗 Links

- [GitHub Repository](https://github.com/Verborom/eva-ai-agent)
- [Monday.com Project Board](https://joerogers.monday.com/boards/9990374378)

---

**Built with ❤️ and AI-powered development workflows**