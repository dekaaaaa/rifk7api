# Events

## List of game events:

{% embed url="https://wiki.alliedmods.net/Counter-Strike:_Global_Offensive_Events" %}
Official CS:GO events
{% endembed %}

```lua
function test(event) 
    if(event ~= nil) then 
        print(event:get_name()); 
    end 
end 
  
hooks.add_hook("on_event", test);
```

## List of events:

### on\_draw

Fired every frame. Most functions from the renderer namespace can only be used here

```lua
function test() 
    if (engine.is_ingame() and engine.is_connected()) then         
        renderer.draw_text(renderer.get_center().x, renderer.get_center().y + 15, "choke me daddy", 255, 255, 255, 255, font_flags.centered_x); 
        renderer.draw_line_multicolored(renderer.get_center().x, renderer.get_center().y + 35, renderer.get_center().x + 40 * clientstate.get_choked_ticks() / 15.0, renderer.get_center().y + 35, 255, 255, 255, 255, 255, 255, 255, 0); 
        renderer.draw_line_multicolored(renderer.get_center().x, renderer.get_center().y + 35, renderer.get_center().x - 40 * clientstate.get_choked_ticks() / 15.0, renderer.get_center().y + 35, 255, 255, 255, 255, 255, 255, 255, 0);         
    end 
end 

hooks.add_hook("on_draw", test)
```

### on\_paint

Fired every frame.&#x20;

### on\_frame\_end

Fired every frame.&#x20;

### on\_level\_clear

on\_level\_init\_pre\_entity

### on\_event

Fired game events

#### 🔗 struct <mark style="color:blue;">`c_game_event`</mark>

|             | Type   | Description                            |
| ----------- | ------ | -------------------------------------- |
| get\_name   | string | Returns the name string of the event.  |
| get\_bool   | bool   | Returns the bool value of the event.   |
| get\_int    | int    | Returns the int value of the event.    |
| get\_float  | float  | Returns the float value of the event.  |
| get\_string | string | Returns the string value of the event. |
| set\_bool   | void   | Set the bool value of the event        |
| set\_int    | void   | Set the int value of the event         |
| set\_float  | void   | Set the float value of the event       |
| set\_string | void   | Set the string value of the event      |

### on\_drawmodel&#x20;

on drawing model&#x20;

#### 🔗 struct <mark style="color:blue;">`lua_dme`</mark>

|   | Type | Description |
| - | ---- | ----------- |
|   |      |             |
|   |      |             |
|   |      |             |

#### 🔗 struct <mark style="color:blue;">`original`</mark>

|   |   |   |
| - | - | - |
|   |   |   |
|   |   |   |
|   |   |   |

### on\_drawmodel

start of createmove

#### 🔗 struct <mark style="color:blue;">`c_user_cmd`</mark>

|   |   |   |
| - | - | - |
|   |   |   |
|   |   |   |
|   |   |   |

### on\_createmove\_pre\_antiaim

before antiaim

#### 🔗 struct <mark style="color:blue;">`lua_createmove`</mark>

|   |   |   |
| - | - | - |
|   |   |   |
|   |   |   |
|   |   |   |

### on\_override\_view

override view - every frame

### on\_render\_view&#x20;

render view - every frame&#x20;

#### 🔗 struct <mark style="color:blue;">`c_view_setup`</mark>

|   |   |   |
| - | - | - |
|   |   |   |
|   |   |   |
|   |   |   |

### on\_shot\_info&#x20;

on ragebot shot

### on\_hitscan&#x20;

on ragebot hitbox selection

### on\_multipoints&#x20;

on ragebot multipoint setup
