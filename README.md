# CNC Template & Tool Library

Fusion 360 operation templates and tool libraries for CNC machines.

## Machines

### AP4060
| Date | File | Description |
|------|------|-------------|
| 05/2026 | `Templates_AP4060_05132026.zip` | Operation templates (validated on AP4060, EN/FR/RU descriptions) |
| 03/2026 | `Template_AP4060_032026.zip` | Operation templates |
| 12/2025 | `Operation_templates.zip` | Operation templates |
| 05/2026 | `AP4060_new.tools` | Fusion 360 tool library — 42 tools with cutting data (multiple presets per tool where different cutting modes apply), validated on AP4060 |

### CNC_T800
| Date | File | Description |
|------|------|-------------|
| 03/2026 | `Templates_T800_032026.zip` | Operation templates |
| 05/2025 | `Operation Library_05112025.zip` | Operation templates |
| — | `CNC-T800.tools` | Fusion 360 tool library |
| — | `My tool holder.tools` | Fusion 360 tool holder library |

## Structure

```
CNC Machines/
├── AP4060/
│   └── Fusion 360/
│       ├── Operation Template/
│       │   ├── 05132026/
│       │   ├── 03212026/
│       │   └── 12232025/
│       └── Tool Library/
└── CNC_T800/
    └── Fusion 360/
        ├── Operation Template/
        │   ├── 03212026/
        │   └── 05112025/
        ├── Tool Library/
        └── Tool Holder Library/
```

## How to Import

**Operation Templates (.zip)**
1. Fusion 360 → Manufacture workspace
2. Manage → Templates → Import
3. Select the `.zip` file

**Tool Library (.tools)**
1. Fusion 360 → Manufacture workspace
2. Manage → Tool Library
3. Click the import icon → select `.tools` file
