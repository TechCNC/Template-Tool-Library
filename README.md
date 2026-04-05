# CNC Template & Tool Library

Fusion 360 operation templates and tool libraries for CNC machines.

## Machines

### AP4060
| Date | File | Description |
|------|------|-------------|
| 03/2026 | `Template_AP4060_032026.zip` | Operation templates |
| 12/2025 | `Operation_templates.zip` | Operation templates |

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
