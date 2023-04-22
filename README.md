# COMMUNITY SERVICE SCRIPT FOR PS-MDT QBCORE

https://streamable.com/b89rlz

**Commands**
End Community service with /endcomserv [id]


> **SETUP**
ensure qb-community-service

Change config to liking

GOTO - qbcore/server/player.lua

Find > Line 88 -- Metadata
Under the function - paste below. 
```
 PlayerData.metadata["communityservice"] = PlayerData.metadata["communityservice"] ~= nil and PlayerData.metadata["communityservice"] or 0

```
