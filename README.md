# For more information and help
Join our Discord
* https://discord.gg/eUDGHx5Kbt
---

# Config
### Framework
* qb or esx
### UseGPS and GPSItem
* Use this if you want players to need a gps to dispatch
* Item name of the gps
### SetWaypoingKey 
* Key for responding a disptach
### WaitTimes
* Cooldown after a dispatch to send another one.
### Enable
* Enable or disable built-in dispatches
### WhitelistedJobs
* Jobs that won't going to give an alert.
### BlipRemoveTime
* Time for blip to remove after a dispatch
### BlipRemoveTime
* Weapons that wont give an alert

### Usage 

### TriggerEvent

* TriggerEvent(“aty_dispatch:SendDispatch”, title, code, blipSprite, jobs)

### Export

* exports[“aty_dispatch”]:SendDispatch(title, code, blipSprite, jobs)

### Examples

* exports[“aty_dispatch”]:SendDispatch(“House Robbery”, “10-26”, 40, {“police”, “sheriff”})

* TriggerEvent(“aty_dispatch:SendDispatch”, “House Robbery”, “10-26”, 40, {“police”, “sheriff”})
