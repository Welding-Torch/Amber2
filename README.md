# Amber2
My custom modified theme Amber2 for Windows Terminal.

![Screenshot (3383)](https://github.com/Welding-Torch/Amber2/assets/46340124/036a3811-cee7-45cb-a008-ed06d97343b8)
![Screenshot (3395)](https://github.com/Welding-Torch/Amber2/assets/46340124/919d0ce0-b991-47dd-abe5-518042ba519e)
![image](https://github.com/Welding-Torch/Amber2/assets/46340124/5647f19d-a849-4dd0-9217-8a02905bca6b)

## How to use

- Download `amber2.hlsl`
- In Windows Terminal, Open Settings, then select `Open JSON File`. Open it with VS Code.
- Set the value for `experimental.pixelShaderPath` to `amber2.hlsl`.
- **optional:** Add keybindings for turning the shader on/off and focusmode

### Example Setting

> Please add the lines you need to your own config, this example config only show the values that you need to add.

```jsonc
{
  "profiles": {
    "defaults": {
      // Add Amber2
      "experimental.pixelShaderPath": "C:\\Users\\bhatia\\Downloads\\amber2.hlsl"
    }
  },
  "keybindings": [
    // It's recommended to add those two toggles for ease of use
    {
      "command": "toggleFocusMode",
      "keys": "shift+f11"
    },
    {
      "command": "toggleShaderEffects",
      "keys": "shift+f10"
    }
  ]
}
```
