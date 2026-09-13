# TargetPortal10

Unofficial Valheim **1.0.12** fork of [Smoothbrain TargetPortal](https://thunderstore.io/c/valheim/p/Smoothbrain/TargetPortal/). Original source: [blaxxun-boop/TargetPortal](https://github.com/blaxxun-boop/TargetPortal).

Walk into a portal to open the map and left-click any portal pin to teleport there. Portal tags still show on the map.

## 1.0.12 changes

- Uses `ZDOMan.GetPortalList`
- Compiles against Valheim 1.0 (`ZRoutedRpc.Everybody` is a const)
- `Humanoid.IsTeleportable(bool)`
- Portal **favorites** use **middle-click** on the map (Valheim 1.0 already uses right-click)

## Portal modes

- Public, Private, Group (needs Groups), Admin, Guild (needs Guilds)

Press **P** on the map to toggle portal icons. Required on the dedicated server too.

Do **not** install this next to Smoothbrain-TargetPortal. Same plugin GUID.

## Install

Thunderstore Mod Manager: Ageous27-TargetPortal10. Disable Smoothbrain-TargetPortal first.