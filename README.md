# Shinsekai Mouse Control

21 LLM mouse control tools. Author: **pipi_**

## Install

Copy the `mouse_control/` folder into Shinsekai's `plugins/` directory:

```
plugins/
└── mouse_control/    ← copy this entire folder
    ├── plugin.py
    ├── llm_tool.py
    ├── omni_server.py
    └── ...
```

Then add to `data/config/plugins.yaml`:

```yaml
- entry: plugins.mouse_control.plugin:MouseControlPlugin
  enabled: true
```

Restart Shinsekai.

## Requirements

Run `install.bat` to install pyautogui. OmniParser deps can be installed via one-click button in plugin settings.
