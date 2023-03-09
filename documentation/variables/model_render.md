# ☃ model\_render

## Functions:

### set\_alpha

`model_render.set_alpha(float):` <mark style="color:purple;">`void`</mark>

### set\_color

`model_render.set_color(float_red, float_green, float_blue):` <mark style="color:purple;">`void`</mark>

### override\_material

`model_render.override_material(material):` <mark style="color:purple;">`void`</mark>

| Name     | Type          |
| -------- | ------------- |
| material | c\_material\* |

### find\_material

`model_render.find_material(std::string name):` <mark style="color:purple;">`c_material*`</mark>

### create\_material

`model_render.create_material(std::string material_name, std::string material_type, std::string material_data):` <mark style="color:purple;">`c_material*`</mark>

### override\_matrix

`model_render.override_matrix(matrix):` <mark style="color:purple;">`void`</mark>

| Name   | Type        |
| ------ | ----------- |
| matrix | matrix3x4\* |

### set\_scroll\_rate

`model_render.set_scroll_rate(material, speed):` <mark style="color:purple;">`void`</mark>

| Name     | Type          |
| -------- | ------------- |
| material | c\_material\* |
| speed    | float         |

### set\_scroll\_angle

`model_render.set_scroll_angle(material, angle):` <mark style="color:purple;">`void`</mark>

| Name     | Type          |
| -------- | ------------- |
| material | c\_material\* |
| angle    | float         |

### smooth\_fade\_alpha

`model_render.smooth_fade_alpha():` <mark style="color:purple;">`float`</mark>

### get\_normal\_material

`model_render.get_normal_material():` <mark style="color:purple;">`table c_material`</mark>

### get\_classic\_material

`model_render.get_classic_material():` <mark style="color:purple;">`table c_material`</mark>

### get\_retro\_material

`model_render.get_retro_material():` <mark style="color:purple;">`table c_material`</mark>

### get\_glass\_material

`model_render.get_glass_material():` <mark style="color:purple;">`table c_material`</mark>

### get\_flat\_material

`model_render.get_flat_material():` <mark style="color:purple;">`table c_material`</mark>

### get\_schleimi\_material

`model_render.get_schleimi_material():` <mark style="color:purple;">`table c_material`</mark>

### get\_holo\_material

`model_render.get_holo_material():` <mark style="color:purple;">`table c_material`</mark>

### get\_granite\_material

`model_render.get_granite_material():` <mark style="color:purple;">`table c_material`</mark>

### get\_oldschool\_material

`model_render.get_oldschool_material():` <mark style="color:purple;">`table c_material`</mark>

### get\_glow\_material

`model_render.get_glow_material():` <mark style="color:purple;">`table c_material`</mark>

### get\_base\_material

`model_render.get_base_material():` <mark style="color:purple;">`table c_material`</mark>

### get\_ultimate\_material

`model_render.get_ultimate_material():` <mark style="color:purple;">`table c_material`</mark>

### get\_animated\_wireframe\_material

`model_render.get_animated_wireframe_material():` <mark style="color:purple;">`table c_material`</mark>

### get\_texture\_1\_material

`model_render.get_texture_1_material():` <mark style="color:purple;">`table c_material`</mark>

### get\_texture\_2\_material

`model_render.get_texture_2_material():` <mark style="color:purple;">`table c_material`</mark>

### get\_texture\_3\_material

`model_render.get_texture_3_material():` <mark style="color:purple;">`table c_material`</mark>

### get\_skybox\_texture\_1\_material

`model_render.get_skybox_texture_1_material():` <mark style="color:purple;">`table c_material`</mark>

### get\_skybox\_texture\_2\_material

`model_render.get_skybox_texture_2_material():` <mark style="color:purple;">`table c_material`</mark>

### get\_skybox\_texture\_3\_material

`model_render.get_skybox_texture_3_material():` <mark style="color:purple;">`table c_material`</mark>

### get\_first\_material

`model_render.get_first_material():` <mark style="color:purple;">`material_handle`</mark>

### get\_next\_material

`model_render.get_next_material(handle):` <mark style="color:purple;">`material_handle`</mark>

| Name   | Type                                                    |
| ------ | ------------------------------------------------------- |
| handle | <mark style="color:purple;">**material\_handle**</mark> |

### is\_invalid\_material

`model_render.is_invalid_material():` <mark style="color:purple;">`material_handle`</mark>

### get\_material

`model_render.get_material(handle):` <mark style="color:purple;">`c_material*`</mark>

| Name   | Type                                                    |
| ------ | ------------------------------------------------------- |
| handle | <mark style="color:purple;">**material\_handle**</mark> |
