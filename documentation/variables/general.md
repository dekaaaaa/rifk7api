# ❄ general

## Functions:

### log

`general.log(std::string text)` <mark style="color:purple;">`void`</mark>

### log\_notify

`general.log_notify(std::string text)` <mark style="color:purple;">`void`</mark>

### log\_to\_console

`general.log_to_console(std::string text)` <mark style="color:purple;">`void`</mark>

### log\_to\_console\_colored

`general.log_to_console_colored(std::string text, float_red, float_green, float_blue, float_alpha)` <mark style="color:purple;">`void`</mark>

### ticks\_to\_time

`general.ticks_to_time(int)` <mark style="color:purple;">`float`</mark>

### time\_to\_ticks

`general.time_to_ticks(float)` <mark style="color:purple;">`int`</mark>

### get\_convar

`general.get_convar(std::string var)` <mark style="color:purple;">`convar`</mark>

### get\_smooth\_colors

`general.get_smooth_colors()` <mark style="color:purple;">`color`</mark>

### is\_active\_app

`general.is_active_app()` <mark style="color:purple;">`bool`</mark>

### is\_chat\_open

`general.is_chat_open()` <mark style="color:purple;">`bool`</mark>

### is\_in\_thirdperson

`general.is_in_thirdperson()` <mark style="color:purple;">`bool`</mark>

### get\_lerp

`general.get_lerp()` <mark style="color:purple;">`float`</mark>

### play\_sound

`general.play_sound(`[`sounds`](../enumerations/sounds.md) `sound, volume)` <mark style="color:purple;">`void`</mark>

| Name   | Type  |
| ------ | ----- |
| volume | float |

### play\_custom\_sound

`general.play_custom_sound(std::string sound_file, volume)` <mark style="color:purple;"></mark> <mark style="color:purple;"></mark><mark style="color:purple;">`void`</mark>

### is\_key\_pressed

`general.is_key_pressed(int button)` <mark style="color:purple;"></mark> <mark style="color:purple;"></mark><mark style="color:purple;">`bool`</mark>

### is\_key\_active

`general.is_key_active(int button, int mode)` <mark style="color:purple;"></mark> <mark style="color:purple;"></mark><mark style="color:purple;">`bool`</mark>

### override\_clantag

`general.override_clantag()` <mark style="color:purple;">`void`</mark>

### set\_mouse\_cursor\_visible

`general.set_mouse_cursor_visible(bool visible)` <mark style="color:purple;">`void`</mark>

### get\_mouse\_cursor\_position

`general.get_mouse_cursor_position()` <mark style="color:purple;">`c_vector2d`</mark>

### create\_interface

`general.create_interface(std::string module_name, std::string interace)` <mark style="color:purple;">`void*`</mark>

### force\_mouse\_cursor

`general.force_mouse_cursor(bool force)` <mark style="color:purple;">`void`</mark>

### disable\_keyboard\_inputs

`general.disable_keyboard_inputs(bool disable)` <mark style="color:purple;">`void`</mark>
