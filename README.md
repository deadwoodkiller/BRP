# Better Roleplay (BRP)

Better Roleplay (BRP) is a lightweight and easy-to-integrate FiveM framework designed for roleplay servers. Developed by a single creator, BRP provides a simple yet powerful core system that seamlessly integrates with existing scripts.

## Features
- **ESX Compatibility Mode** – BRP can mimic ESX, allowing scripts made for ESX to work with minimal modifications.
- **Lightweight & Efficient** – Designed for performance and easy integration.
- **Single-Developer Project** – Focused on quality and simplicity.

## Integration
To use BRP in your scripts, simply call the shared object:
```lua
local BRP = exports['better_core']:getSharedObject()
```
This allows you to access the framework's core functions, similar to ESX.

## Installation
1. Download the latest version of Better Roleplay.
2. Add `better_core` to your FiveM server's resources folder.
3. Ensure `better_core` is started in your `server.cfg`:
   ```
   ensure better_core
   ```
4. Start developing using BRP!

## Support & Contributions
Since BRP is developed by a single creator, contributions and feedback are always welcome. Feel free to reach out for support or feature requests!

---
Enjoy using BRP and take your roleplay server to the next level!

