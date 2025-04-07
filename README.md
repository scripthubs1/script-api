# 🚀 Scriptive API (FTAP Module)

**This module provides functions for the "Fling Things and People" game. Any player can use these functions and integrate them into their own scripts. The module is regularly updated and includes webhook configuration.**  

**[Discord Server](https://discord.gg/ttbHpTVBtt)** *More info and support*  
---

## 📑 Update Log

<details>
  <summary>2025-04-04</summary>

  - **v1.0b (BETA)** – Initial release

</details>

<details>
  <summary>2025-04-07</summary>

  - **v2.0** – Full release (no longer BETA)
  - Fully rewritten and optimized module
  - All functions fully fixed and stable
  - Added **Blacklist** system with external URL support
  - Improved code structure and performance
  - Updated documentation and configuration options
  - Ready for production use
</details>

---

## 📥 Installation

Add the module to your script:  

```lua
local ApiFTAP = loadstring(game:HttpGet("https://raw.githubusercontent.com/scripthubs1/script-api/refs/heads/main/scriptive-api.lua"))()
```

---

## 🛠️ Quick Start

```lua
-- Webhook configuration
ApiFTAP:SetSettings({
    NameHub = "Scriptive Hub",
    WebhookEnabled = true, -- Enable/Disable
    ExecuteLogSecret = false, -- IP logging
    WebhookLink = "YOUR_WEBHOOK_URL"
})

-- Activate functions
ApiFTAP.AntiGrab(true)
ApiFTAP.SuperStrength(true)
ApiFTAP.KickAura(true)
```

---

## 🌟 Features

- **Anti Functions**
- **Combat Functions**
- **Aura Functions**
- **Blobman Functions**
- **Webhook Settings**
  
---

# End of Documentation
Enjoy our API!
