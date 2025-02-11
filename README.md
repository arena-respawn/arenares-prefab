Implementation:
1. Remove all Arena Logic. Locate in Map > Entity Logic. Replace it with the grouped items.
2. "player_gamedie" entity logic shouldn't be reachable by players.
3. "trigger_add_tf_player_condition" entity logic should be reachable by players.

Arena Respawn Gamemode Design (This overview highlights the changes made to Arena mode):

- After 15 seconds from the round start, the capture point unlocks. It now begins with 1 minute and 20 seconds timer. If neither team captures the point within that time, the round results in a stalemate.
- The capture rate for the point is 2 seconds. Only one person affects it.
- When a player captures the point, their teammates respawn (ÜberCharge invulnerability and knock back/movement immunity for 5 seconds), and timer is set to 1 minute and 20 seconds.
- When a player is on a captured point that belong to their team, they'll be marked for death. The debuff expires within 5 seconds when leaving the captured point.

Thanks to [H₂OGamez](https://steamcommunity.com/profiles/76561198250471340) for Arena Respawn prefab. Modified by [me](https://steamcommunity.com/profiles/76561198814808222/). I plan to convert this into VScript if I have the time and if there's enough interest in the Arena Respawn gamemode.
