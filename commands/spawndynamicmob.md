# !spawndynamicmob

**Tags:** `mobs`, `dynamic`, `spawn`

Spawns in a dynamic mob with the given parameters at the GM's location.

**Usage**: `!spawndynamicmob <groupId> <zoneId> <look> (name) (drops)`

**Parameters**:
- `groupId`: The ID for the mob group to be associated with. Determines base stats, traits, etc.
- `zoneId`: The ID for the zone the mob group is associated with.
- `look`: The look string or model ID data to be used
  - Options:
    - Model ID: 0 - 65535
    - Look String: `0x00000e0100000000000000000000000000000000`
- `name`: (Optional) The name to give the mob; if none given, then `HorizonXI` is used
- `drops`: (Optional) Triggers whether drops are enabled or not (Default: No Drops)
    - Options: 1 - Drops Enabled, 0 - Drops Disabled
