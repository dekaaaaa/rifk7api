# 🚜 engine\_game\_trace

## Functions:

### get\_line

`engine_game_trace.get_line(start_x, start_y, start_z, end_x, end_y, end_z, mask, ignore):` <mark style="color:purple;">**`game_trace*`**</mark>

| Name   | Type                                          |
| ------ | --------------------------------------------- |
| x/y/z  | float                                         |
| mask   | [trace\_mask](../enumerations/trace\_mask.md) |
| ignore | c\_client\_entity\*                           |

### get\_hull

`engine_game_trace.get_line(start_x, start_y, start_z, end_x, end_y, end_z, mins_x, mins_y, mins_z, maxs_x, maxs_y, maxs_z, mask, ignore):` <mark style="color:purple;">**`game_trace*`**</mark>

| Name   | Type                                          |
| ------ | --------------------------------------------- |
| x/y/z  | float                                         |
| mask   | [trace\_mask](../enumerations/trace\_mask.md) |
| ignore | c\_client\_entity\*                           |

### autowall\_trace

`engine_game_trace.autowall_trace(enemy, hitpoint_x, hitpoint_y, hitpoint_z, hitbox):` <mark style="color:purple;">**`autowall*`**</mark>

| Name        | Type             |
| ----------- | ---------------- |
| enemy       | c\_cs\_player\*  |
| hitpoint\_x | float            |
| hitpoint\_y | float            |
| hitpoint\_z | float            |
| hitbox      | int              |

### can\_hit\_hitbox

`engine_game_trace.can_hit_hitbox(c_cs_player* shooter, c_cs_player* victim, float end_x, float end_y, float end_z, int hitbox)` <mark style="color:purple;">**`bool`**</mark>

| Name    | Type             |
| ------- | ---------------- |
| shooter | c\_cs\_player\*  |
| victim  | c\_cs\_player\*  |
| end\_x  | float            |
| end\_y  | float            |
| end\_z  | float            |
| hitbox  | int              |
