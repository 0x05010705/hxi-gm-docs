# !setmissionstatus

**Tags:** `player`, `mission`, `status`

Sets the mission status on a player for the given Log ID and Index

**Usage**: `!setmissionstatus <player> <value> <logId> (index)`

**Parameters**:
- `player`: The name of the player to target
- `value`: The value to set the mission status to
- `logId`: The number for the mission log you are setting
  - Options:
    - 0: San D'Oria
    - 1: Bastok
    - 2: Windurst
    - 3: Rise of the Zilart
    - 4: Treasures of Aht Urghan
    - 5: Wings of the Goddess
    - 6: Chains of Promathia
    - 7: Assaults
    - 8: Campaign
    - 9: A Crystalline Prophecy
    - 10: A Moogle Kupo d'Etat
    - 11: A Shantotto Ascension
    - 12: Seekers of Adoulin
    - 13: Rhapsodies of Vana'diel
- `index`: (Optional) The index of the mission to set the value for
    - This value varies based on the index and is used for Sub-Missions in COP (logID 6)
