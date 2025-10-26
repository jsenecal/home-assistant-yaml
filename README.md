# Home Assistant YAML Repository

Custom scripts and blueprints for Home Assistant automation.

## Structure

```
├── blueprints/
│   └── script/
└── scripts/
```

## Blueprints

### Blinds Temporary Position
Temporarily moves blinds to a specified position, waits, then restores original position.

**Inputs:**
- Blinds entity
- Threshold position (only executes if below this)
- Target position
- Wait time

