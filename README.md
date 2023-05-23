![](banner.jpg)

# beta-wiki
A wiki documenting Minecraft Beta 1.7.3's technical specification and network protocol.

## Table of Contents
### Packets
1. `0x00` [Keep Alive](networking/packets/000-keep-alive.md)
2. `0x01` [Login](networking/packets/001-login.md)
3. `0x02` [Handshake](networking/packets/002-handshake.md)
4. `0x03` [Chat Message](networking/packets/003-chat-message.md)
5. `0x04` [Time](networking/packets/004-time.md)
6. `0x05` [Entity Equipment](networking/packets/005-entity-equipment.md)
7. `0x06` [Spawn Point](networking/packets/006-spawn-point.md)
8. `0x07` [Click Entity](networking/packets/007-click-entity.md)
9. `0x08` [Health](networking/packets/008-health.md)
10. `0x09` [Respawn](networking/packets/009-respawn.md)
11. `0x0A` [Player On Ground](networking/packets/010-player-on-ground.md)
12. `0x0B` [Player Position](networking/packets/011-player-position.md)
13. `0x0C` [Player Look](networking/packets/012-player-look.md)
14. `0x0D` [Player Position Look](networking/packets/013-player-position-look.md)
15. `0x0E` [Mine](networking/packets/014-mine.md)
16. `0x0F` [Place](networking/packets/015-place.md)
17. `0x10` [Held Item](networking/packets/016-held-item.md)
18. `0x11` [Click Bed](networking/packets/017-click-bed.md)
19. `0x12` [Animation](networking/packets/018-animation.md)
20. `0x13` [Entity Action](networking/packets/019-entity-action.md)
21. `0x14` [Spawn Player](networking/packets/020-spawn-player.md)
22. `0x15` [Spawn Item](networking/packets/021-spawn-item.md)
23. `0x16` [Collect Item](networking/packets/022-collect-item.md)
24. `0x17` [Spawn Object](networking/packets/023-spawn-object.md)
25. `0x18` [Spawn Mob](networking/packets/024-spawn-mob.md)
26. `0x19` [Spawn Painting](networking/packets/025-spawn-painting.md)
27. `0x1A` [Entity Position](networking/packets/026-entity-position.md)
28. `0x1C` [Entity Velocity](networking/packets/027-entity-velocity.md)
29. `0x1D` [Despawn Entity](networking/packets/029-despawn-entity.md)
30. `0x1E` [Entity](networking/packets/030-entity.md)
31. `0x1F` [Entity Relative Position](networking/packets/031-entity-relative-position.md)
32. `0x20` [Entity Look](networking/packets/032-entity-look.md)
33. `0x21` [Entity Relative Position Look](networking/packets/033-entity-relative-position-look.md)
34. `0x22` [Entity Position Look](networking/packets/034-entity-position-look.md)
35. `0x27` [Mount Entity](networking/packets/039-mount-entity.md)
36. `0x28` [Entity Metadata](networking/packets/040-entity-metadata.md)
37. `0x32` [Pre Chunk](networking/packets/050-pre-chunk.md)
38. `0x33` [Chunk](networking/packets/051-chunk.md)
39. `0x34` [Set Multiple Blocks](networking/packets/052-set-multiple-blocks.md)
40. `0x35` [Set Block](networking/packets/053-set-block.md)
41. `0x36` [Note](networking/packets/054-note.md)
42. `0x3C` [Explosion](networking/packets/060-explosion.md)
43. `0x3D` [Effect](networking/packets/061-effect.md)
44. `0x47` [Lightning Bolt](networking/packets/071-lightning-bolt.md)
45. `0x48` [Game State](networking/packets/072-game-state.md)
46. `0x64` [Open Window](networking/packets/100-open-window.md)
47. `0x65` [Close Window](networking/packets/101-close-window.md)
48. `0x66` [Click Inventory Slot](networking/packets/102-click-inventory-slot.md)
49. `0x67` [Set Inventory Slot](networking/packets/103-set-inventory-slot.md)
50. `0x68` [Window Items](networking/packets/104-window-items.md)
51. `0x69` [Furnace](networking/packets/105-furnace.md)
52. `0x6A` [Inventory Transaction](networking/packets/106-inventory-transaction.md)
53. `0x82` [Sign](networking/packets/130-sign.md)
54. `0x83` [Map](networking/packets/131-map.md)
55. `0xC8` [Statistic](networking/packets/200-statistic.md)
56. `0xFF` [Disconnect](networking/packets/255-disconnect.md)
