# T-BUG OS 🤖

A production-ready AI Agent operating system with memory, learning, skills, and autonomous capabilities.

## What is T-BUG OS?

T-BUG OS is a comprehensive framework for building intelligent AI agents with:

- 🧠 **Multi-layer Memory System** - Episodic, semantic, procedural, and working memory
- 📚 **Autonomous Learning** - Continuous knowledge acquisition and synchronization
- 🔧 **Skill System** - Modular, reusable capabilities
- ⚡ **Workflow Automation** - Reusable automation patterns
- 🎯 **Proactive Behavior** - Self-directed action and decision making

## Quick Start

```bash
# Clone the repository
git clone https://github.com/mangiapanejohn-dev/T-BUG-OS.git
cd T-BUG-OS

# Configure your agent
# Edit CONFIG/agent.yaml with your settings

# Add skills to your agent
cp -r Skills/* /path/to/your/skills/
```

## Architecture

```
T-BUG-OS/
├── Core/                 # Core identity and beliefs
├── Memory/              # Multi-layer memory system
├── Learning/            # Autonomous learning system
├── Workflow/            # Task processing workflows
├── Skills/              # Reusable skill templates
└── CONFIG/              # Configuration templates
```

## Features

### Memory System
- **Episodic Memory**: Event and session records
- **Semantic Memory**: Knowledge and concepts
- **Procedural Memory**: Skills and workflows
- **Working Memory**: Current tasks and context

### Learning System
- Web search and knowledge acquisition
- Automatic knowledge synchronization
- Memory consolidation and refinement

### Skill System
- Modular skill definitions
- Easy integration with OpenClaw
- Reusable across different agents

## Documentation

- [Architecture Overview](Core/system.md)
- [Memory System](Memory/system.md)
- [Learning System](Learning/system.md)
- [Workflow System](Workflow/system.md)
- [Skills](Skills/)

## Requirements

- OpenClaw framework
- Memory storage (file-based or vector DB)
- Web access for learning capabilities

## License

MIT License - Build your own intelligent agent!

---

**Author**: Created with OpenClaw  
**Repository**: https://github.com/mangiapanejohn-dev/T-BUG-OS
