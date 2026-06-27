# mouse_control

21 LLM mouse control tools for Shinsekai. Author: **pipi_**

## Install

### In-app (recommended)

Add to Shinsekai Plugin Registry, then install from Plugin Manager.

### Manual

```bash
git clone https://github.com/Mizushima-Mihane/mouse_control.git plugins/mouse_control
```

Or download zip, rename the extracted folder to `mouse_control`, and place in `plugins/`.

Then add to `data/config/plugins.yaml`:

```yaml
- entry: plugins.mouse_control.plugin:MouseControlPlugin
  enabled: true
```

## Requirements

- `install.bat` — installs pyautogui
- OmniParser: one-click install in plugin settings
- OCR: `pip install rapidocr-onnxruntime`
