# 🤺 effects

## Functions:

### draw\_screen\_effect

`effects.draw_screen_effect(c_material* material,x,y,w,h):` <mark style="color:purple;">`void`</mark>

| Name    | Type  |
| ------- | ----- |
| x/y/w/h | float |

### dispatch\_effect

`effects.dispatch_effect(std::string effect, origin):` <mark style="color:purple;">`void`</mark>

| Name   | Type        |
| ------ | ----------- |
| origin | c\_vector3d |

### dispatch\_particle\_effect

`effects.dispatch_particle_effect(std::string particle_effect, origin):` <mark style="color:purple;">`void`</mark>

| Name   | Type        |
| ------ | ----------- |
| origin | c\_vector3d |

### dispatch\_tesla

`effects.dispatch_particle_effect(origin, time, radius, beams, width, std::string sprite_name, float_red, float_green, float_blue):` <mark style="color:purple;">`void`</mark>

| Name   | Type        |
| ------ | ----------- |
| origin | c\_vector3d |
| time   | float       |
| radius | float       |
| beams  | float       |
| width  | float       |

### dispatch\_smoke

`effects.dispatch_smoke(x, y, z, scale, framerate):` <mark style="color:purple;">`void`</mark>

| Name      | Type  |
| --------- | ----- |
| x/y/z     | float |
| scale     | float |
| framerate | float |

### dispatch\_sparks

`effects.dispatch_sparks(x, y, z):` <mark style="color:purple;">`void`</mark>

| Name  | Type  |
| ----- | ----- |
| x/y/z | float |

### dispatch\_dust

`effects.dispatch_dust(x, y, z, size, speed):` <mark style="color:purple;">`void`</mark>

| Name  | Type  |
| ----- | ----- |
| x/y/z | float |
| size  | float |
| speed | float |

### dispatch\_muzzleflash

`effects.dispatch_muzzleflash(x, y, z, scale, type):` <mark style="color:purple;">`void`</mark>

| Name  | Type  |
| ----- | ----- |
| x/y/z | float |
| scale | float |
| type  | int   |

### dispatch\_metalsparks

`effects.dispatch_metalsparks(x, y, z):` <mark style="color:purple;">`void`</mark>

| Name  | Type  |
| ----- | ----- |
| x/y/z | float |

### dispatch\_energysplash

`effects.dispatch_energysplash(x, y, z, explosive):` <mark style="color:purple;">`void`</mark>

| Name      | Type  |
| --------- | ----- |
| x/y/z     | float |
| explosive | bool  |

### dispatch\_ricochet

`effects.dispatch_ricochet(x, y, z):` <mark style="color:purple;">`void`</mark>

| Name  | Type  |
| ----- | ----- |
| x/y/z | float |

### suppress\_effects\_sounds

`effects.suppress_effects_sounds(suppress):` <mark style="color:purple;">`void`</mark>

| Name     | Type |
| -------- | ---- |
| suppress | bool |

### draw\_lights

`effects.draw_lights(c_client_entity* entity, float_red, float_green, float_blue, float_alpha):` <mark style="color:purple;">`void`</mark>

### draw\_beam

`effects.draw_lights(start, end, std::string sprite, time, width, amplitude, speed, segments, float_red, float_green, float_blue, float_alpha):` <mark style="color:purple;">`void`</mark>

| Name      | Type        |
| --------- | ----------- |
| start/end | c\_vector3d |
| time      | float       |
| width     | float       |
| amplitude | float       |
| speed     | float       |
| segments  | int         |
