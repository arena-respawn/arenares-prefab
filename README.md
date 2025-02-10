Type "sv_allow_point_servercommand always" in console command to enable custom configuration provided by the map.

Arena Respawn Gamemode Design (This overview highlights the changes made to Arena mode):

- First Blood crits are disabled.
- After 15 seconds from the round start, the capture point unlocks. It starts with 1 minute and 20 seconds timer. If neither team captures the point within that time, the round results in a stalemate.
- The capture rate for the point is 2 seconds. 
- When a player captures the point, their teammates respawn (ubered for 3 seconds), and timer is set to 1 minute and 20 seconds.
- When a player is on a captured point that belong to their team, they'll be marked for death. The debuff expires within 5 seconds when leaving the captured point.
  
Why Add These Changes (These changes prioritizes toward causal players):
- First Blood crits was too punishing.
- 1 minute and 20 seconds timer for making players move quickly to fight. Players dislike waiting to respawn for long period of time and so, 15 seconds from round start for the capture point to unlock should resolve that.
- Fast capture rate means less risk, high reward to help teammates respawn.
- Letting players respawn on a captured point doesn't make them stare at the spectator screen.
- Marked for death debuff on a captured point that belong to to their team prevents difficulty for the opposing team capper.

Report (Competitive players are not included in this report, 4v4 unaffiliated randoms using [server.cfg](https://github.com/arena-respawn/arenares-cfg/blob/main/cfg/server.cfg)):
- The most favorited arena gamemode Valve map is arena_lumberyard.
- Average match was around 20 minutes.
- Players in Arena mode never waited for the timer to expire.
- Players changing class and using varying type of loadout for fun.
- Stock Engineer were not impactful for sitting at spawn.
- In 3 out of 16 rounds, teammates were respawned by capturing the point.

Thanks to [H₂OGamez](https://steamcommunity.com/id/h20gamez) for Arena Respawn prefab. Modified by me.
