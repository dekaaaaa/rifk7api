# 🏎 engine

## Functions:

### is\_ingame

`engine.is_ingame():` <mark style="color:purple;">`bool`</mark>

### is\_connected

`engine.is_connected():` <mark style="color:purple;">`bool`</mark>

### get\_local\_player

`engine.get_local_player():` <mark style="color:purple;">`c_client_entity`</mark>

### get\_view\_target

`engine.get_view_target():` <mark style="color:purple;">`c_client_entity`</mark>

### get\_player\_for\_uid

`engine.get_player_for_uid(index):` <mark style="color:purple;">`int`</mark>

| Name   | Type |
| ------ | ---- |
| userid | int  |

### get\_max\_players

`engine.get_max_players():` <mark style="color:purple;">`int`</mark>

### get\_map\_name

`engine.get_map_name():` <mark style="color:purple;">`std::string`</mark>

### get\_view\_angles

`engine.get_view_angles():` <mark style="color:purple;">`c_vector3d`</mark>

### set\_view\_angles

`engine.set_view_angles(x,y,z):` <mark style="color:purple;">`void`</mark>

### get\_player\_info

`engine.get_player_info(index):` <mark style="color:purple;">`player_info`</mark>

| Name  | Type |
| ----- | ---- |
| index | int  |

### signature

`engine.signature(std::string module_name, std::string sig):` <mark style="color:purple;">`uint8_t*`</mark>

### execute\_console\_command

`engine.execute_console_command(std::string text):` <mark style="color:purple;">`void`</mark>

### send\_share\_packet

`engine.execute_console_command(int packet_id, int value_1, int value_2, int value_3, int value_4):` <mark style="color:purple;">`void`</mark>
