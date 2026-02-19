# Minimal Example - Basic Agent

This is the simplest possible Resonix - Skill setup.

## Files Needed

```
minimal/
├── CONFIG/agent.yaml    # Only this file needed
└── HEARTBEAT.md         # Empty or with tasks
```

## Configuration

```yaml
agent:
  name: "Minimal Agent"
  timezone: "UTC"

memory:
  enabled: true
  storage:
    episodic: "./memory"
    working: "./HEARTBEAT.md"

learning:
  enabled: false

skills:
  enabled: false

workflows:
  heartbeat:
    enabled: false
```

## Usage

```bash
# Just create the directories
mkdir -p memory

# Your agent is ready!
```

## What's Included

- Basic episodic memory (daily logs)
- Working memory for current tasks
- All core systems initialized

## What's NOT Included

- No learning
- No skills
- No workflows
- No semantic memory

Perfect for: Testing, learning the basics, or as a starting point.
