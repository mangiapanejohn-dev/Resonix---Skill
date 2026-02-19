# Resonix - Skill - Quick Start Guide

This guide will help you get started with Resonix - Skill in 5 minutes.

## Prerequisites

- OpenClaw framework installed
- Node.js 18+
- Web access (for learning capabilities)
- Memory storage (local filesystem)

## Step 1: Clone the Repository

```bash
git clone https://github.com/mangiapanejohn-dev/Resonix - Skill.git
cd Resonix - Skill
```

## Step 2: Configure Your Agent

Copy the config template and customize:

```bash
cp CONFIG/agent.yaml.example CONFIG/agent.yaml
# Edit CONFIG/agent.yaml with your settings
```

Key settings to configure:

```yaml
agent:
  name: "Your Agent Name"
  timezone: "Asia/Shanghai"

memory:
  storage:
    episodic: "./memory"
    semantic: "~/Desktop/knowledge-base/"

learning:
  enabled: true
```

## Step 3: Set Up Memory Directory

```bash
mkdir -p memory semantic
```

## Step 4: Add Skills (Optional)

```bash
cp -r Skills/* /path/to/your/openclaw/skills/
```

## Step 5: Run Your Agent

```bash
# Start OpenClaw with your agent
openclaw start --config CONFIG/agent.yaml
```

## What's Next?

- Read [ARCHITECTURE.md](ARCHITECTURE.md) to understand the system
- Check [Core/memory.md](Core/memory.md) to customize memory
- Explore [Core/learning.md](Core/learning.md) for learning config
- See [EXAMPLES/](Examples/) for complete setups

## Troubleshooting

**Memory not working?**
- Check file permissions on memory directory
- Verify paths in config are absolute

**Learning not working?**
- Ensure web access is available
- Check API keys if using paid services

**Skills not loading?**
- Verify skill paths in config
- Check skill format matches SKILL.md schema

## Support

- GitHub Issues: Report bugs
- Documentation: See /docs folder
- Updates: Check CHANGELOG.md

---

For more details, see [README.md](README.md)
