---
title: "Version overview"
date: 2022-09-19T11:43:49.783Z
draft: false
tags: ["Meta"]
summary: "Version support overview"
---
# Version support overview

| Mod                   | 1.20 | 1.19.4 | 1.19.2 | 1.18.2 | 1.17.1 | 1.16.5 | 1.15.2 | 1.14.4 | 1.12.2 | 1.8.8/9 |
| --------------------- | ---- | ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------- |
| EntityCulling         | ✅    | ✅      | ⚠️      | ⚠️      | ❌      | ⚠️      |        |        | 🕓🔨     | ⚠️🔨      |
| 3d Skin Layers        | ✅    | ✅      | ⚠️      | ⚠️      | ❌      | ⚠️      |        |        | ⚠️🔨     | ⚠️🔨      |
| Not Enough Animations | ✅    | ✅      | ⚠️      | ⚠️      | ❌      | ❌      |        |        |        |         |
| FirstPerson Mod       | ✅    | ✅      | ⚠️      | ⚠️      | ❌      | ❌      | ❌      | ❌      |        |         |
| WaveyCapes            | ✅    | ✅🪄      | ✅🪄     | ✅🪄     | ✅🪄     | ✅🪄     |        |        | ⚠️🔨     | ⚠️🔨      |
| Paperdoll             | ✅    | ✅      | ⚠️      | ⚠️      | ❌      | ❌      |        |        |        |         |
| MiniMePets            | ✅    | ✅      | ⚠️      | ⚠️      |        |        |        |        |        |         |
| DisguiseHeads         | ✅    | ✅      | ⚠️      | ⚠️      |        |        |        |        |        |         |
| GraphUtil             | ✅    | ✅      | ⚠️      | ⚠️      |        |        |        |        |        |         |
| Exordium              | ✅🧶   | ✅🧶     | ⚠️🧶     | ⚠️🧶     |        |        |        |        |        |         |
| ModelDumper           | ✅🧶   | ✅🧶     | ⚠️🧶     | ⚠️🧶     |        |        |        |        |        |         |
| ItemSwapper           | ✅🧶   | ✅🧶🪄     | ✅🧶🪄     | ✅🧶🪄     |        |        |        |        |        |         |

- ✅ = Supported
- ❌ = Not supported
- 🚧 = Work in progress
- 🕓 = Planned
- ⚠️ = Partially supported(Might get critical updates, but no new features)
- 🧶 = Fabric only
- 🔨 = Forge only
- 🪄 = Direct Fork Backport(Based on the latest MC release version)

## Notes

- ~~1.19-1.19.3 will loose support over time. Consider updating to 1.19.4.~~
- Update: 1.19-1.19.3 are only partially supported. Critical updates(gamecrashes) will be backported, but no new features.

## Priorities

- Fabric is more important than Forge
- Sodium+Iris is more important than Optifine
- Latest version is more important than older versions(1.19>1.18)
- Legacy versions(1.8, 1.12, 1.16) are not a priority and most mods will not be backported to them
- Latest minor version is always more important than older minor versions(1.19.4>1.19.2)
