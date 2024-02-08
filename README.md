# TPZ-CORE Collectible Herbs

## Requirements

1. TP-Libs: https://github.com/TitansProductions/tp_libs
2. TP-Notify: https://github.com/TitansProductions/tp_notify

## Non Requirements (Suggested)

1. TP-Versions: https://github.com/TitansProductions/tp_versions


# Developers

### The following event is triggered and used client side on game engine herbs.

```lua
-- @param compositeHashId : returns the collected composite hash id (lootable), checkout Config.LootableRewards (CONFIG.LUA) or Composites.LootableList (COMPOSITES_LIST.LUA)

AddEventHandler("tp_collectible_herbs:onLootableHerbCollect", function(compositeHashId)
    -- todo for developers only.
end)
```

### The following event is triggered and used client side on custom herb pickups.

```lua
-- @param objectName : returns the collected custom object name (not hash), checkout Config.CustomLootableRewards (CONFIG.LUA) or Composites.CustomObjectLocations (COMPOSITES_LIST.LUA)

AddEventHandler("tp_collectible_herbs:onLootableCustomHerbCollect", function(objectName)
    -- todo for developers only.
end)

```
