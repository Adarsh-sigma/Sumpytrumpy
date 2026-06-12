# Sumpytrumpy 🚀

Multi-Agent AI System with 3D Visualization, powered by OmniRoute, CrewAI, and LangGraph.

## Features

- **Multi-Agent Orchestration**: CrewAI-based agent swarms with role-based task assignment
- **OmniRoute Integration**: 160+ LLM providers with automatic fallback
- **3D Agent Visualization**: Real-time Three.js visualization of agent swarms
- **Advanced Chat UI**: Claude.ai/ChatGPT-style interface with sidebar, settings, and conversation management
- **Goal-Based Routing**: Intelligent task routing with goal types and skill management
- **Search Integration**: Tavily search for real-world data retrieval
- **MCP Ready**: Model Context Protocol foundation for tool connections
- **Full Persistence**: SQLite database with conversation history, user management
- **WebSocket Support**: Real-time agent status and streaming responses
- **Type-Safe**: Full TypeScript implementation

## Quick Start

```bash
# Install dependencies
npm install

# Setup environment
cp .env.example .env.local

# Start development
npm run dev

# Frontend: http://localhost:3000
# Backend: http://localhost:3001
```

## Architecture

```
Sumpytrumpy/
├── apps/
│   ├── frontend/          # Next.js 15 + React 19 + Three.js
│   └── backend/           # Express + CrewAI + OmniRoute
├── packages/
│   ├── shared-types/      # TypeScript types
│   ├── ui/                # Shared UI components
│   └── config/            # Shared configuration
└── docs/
```

## Tech Stack

- **Frontend**: Next.js 15, React 19, TailwindCSS, Three.js, Socket.io
- **Backend**: Express, TypeScript, CrewAI, LangGraph, Pydantic
- **Database**: SQLite (with migration to PostgreSQL ready)
- **APIs**: OmniRoute, Tavily, OpenAI, Anthropic, Google
- **Monorepo**: Turborepo

## Agent System

- **Role-Based Agents**: Research, Writing, Code, Analysis, Planning
- **Swarm Coordination**: Dynamic task distribution and collaboration
- **Skill Management**: Tool registration and execution
- **Goal Types**: Research, Creation, Analysis, Planning, Automation
- **Memory**: Conversation context and state persistence

## UI/UX

- Sidebar navigation with conversation history
- Real-time chat interface with streaming responses
- 3D agent swarm visualization
- Settings panel (appearance, model selection, API keys)
- Temporary chat mode
- User authentication and profiles
- Goal and task management

## API Reference

See `docs/API.md` for complete API documentation.

## Contributing

Open source and community-driven. Pull requests welcome!

## License

MIT
