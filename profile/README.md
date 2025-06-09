# PenumbraOS

A developer-friendly resurrection of the Humane Ai Pin.

> [!CAUTION]
> This is extremely experimental and currently is usable by developers only.

PenumbraOS consists of a number of key components:
- [MABL](https://github.com/PenumbraOS/mabl) - The actual user experience for PenumbraOS. Launcher, orchestration, and delegation of "AI assistant" operations
- [PenumbraOS SDK](https://github.com/PenumbraOS/sdk) - A SDK providing privileged access to apps we install on the Ai Pin, along with special permissions
- [`pinitd`](https://github.com/PenumbraOS/pinitd) - Custom rootless init system for the Ai Pin. Allows for persistence (running on boot) and easy developer access to privileged roles
