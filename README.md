# 🔌 Sledge API

The **Developer Interface** for SledgeMC.

**Sledge API** provides the events and hooks that modders use to interact with the game and other mods.

## 🏗️ Role
- Provides the core API classes and annotations.
- Defines common hooks used by both the loader and the mods.

## ✨ Features
- **Event Bus**: Simple `@SubscribeEvent` system for handling game events.
- **Lifecycle Hooks**: Interfaces for `onInitialize`, `onInitializeClient`, and `onInitializeServer`.
- **Environment API**: Tools to detect if the mod is running on a client or server.

## 🛠️ Build
To build the API jar:
```bash
./gradlew clean build
```
The artifact will be located in `build/libs/sledge-api-1.0.0-SNAPSHOT.jar`.
