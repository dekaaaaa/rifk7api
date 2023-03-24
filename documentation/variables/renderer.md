# 🧶 renderer

## Functions:

### draw\_text

`renderer.draw_text(x, y, std::string text, ImFont* font, float red, float green, float blue, float alpha, flags):` <mark style="color:purple;">`void`</mark>

| Name  | Type                                          |
| ----- | --------------------------------------------- |
| x/y   | float                                         |
| flags | [font\_flags](../enumerations/font\_flags.md) |

### draw\_text\_clipped

`renderer.draw_text_clipped(x, y, std::string text, ImFont* font,float_red,float_green,float_blue,float_alpha,flags,clipped_x,clipped_y, clipped_h,clipped_w):` <mark style="color:purple;">`void`</mark>

| Name             | Type  |
| ---------------- | ----- |
| x/y              | float |
| clipped\_x/y/h/w | float |

### get\_font\_range

`renderer.get_font_range(font_range range):` <mark style="color:purple;">`ImWchar*`</mark>

### add\_font

`renderer.add_font(std::string name, std::string font_file, float size, bool bold, ImWchar* range):` <mark style="color:purple;">`ImFont*`</mark>

### add\_merge\_font

`renderer.add_merge_font(std::string font_file, float size, bool bold, ImWchar* range):` <mark style="color:purple;">`void`</mark>

### build\_fonts

`renderer.build_fonts()` <mark style="color:purple;">`void`</mark>

### find\_font

`renderer.find_font(std::string name):` <mark style="color:purple;">`ImFont*`</mark>

### get\_font

`renderer.get_font(fonts font):` <mark style="color:purple;">`ImFont*`</mark>

### get\_text\_size

`renderer.get_text_size(std::string text, ImFont* font):` [<mark style="color:purple;">`c_vector2d`</mark>](../class/c\_vector2d.md)<mark style="color:purple;">``</mark>

### draw\_player\_profile\_picture

`renderer.draw_player_profile_picture(index,x,y,rounding,medium_size):` <mark style="color:purple;">`void`</mark>

| Name         | Type  |
| ------------ | ----- |
| index        | int   |
| x/y          | float |
| rounding     | float |
| medium\_size | bool  |

### get\_world\_to\_screen

`renderer.get_world_to_screen(x,y,z):` <mark style="color:purple;"></mark> <mark style="color:purple;"></mark><mark style="color:purple;">`c_vector2d`</mark>

| Name  | Type  |
| ----- | ----- |
| x/y/z | float |

### draw\_line

`renderer.draw_line(x,y,end_x,end_y,float_red,float_green,float_blue,float_alpha,thickness):` <mark style="color:purple;">`void`</mark>

| Name              | Type  |
| ----------------- | ----- |
| x/y/end\_x/end\_y | float |
| thickness         | float |

### draw\_thickline

`renderer.draw_thickline(x,y,end_x,end_y,float_red,float_green,float_blue,float_alpha):` <mark style="color:purple;">`void`</mark>

| Name              | Type  |
| ----------------- | ----- |
| x/y/end\_x/end\_y | float |

### draw\_line\_multicolored

`renderer.draw_line_multicolored(x,y,end_x,end_y,float_red1,float_green1,float_blue1,float_alpha1,float_red2,float_green2,float_blue2,float_alpha2):` <mark style="color:purple;">`void`</mark>

| Name              | Type  |
| ----------------- | ----- |
| x/y/end\_x/end\_y | float |

### draw\_rectangle

`renderer.draw_rectangle(x,y,size_x,size_y,float_red,float_green,float_blue,float_alpha,rounding):` <mark style="color:purple;">`void`</mark>

| Name                | Type  |
| ------------------- | ----- |
| x/y/size\_x/size\_y | float |
| rounding            | float |

### draw\_rectangle\_filled

`renderer.draw_rectangle_filled(x,y,size_x,size_y,float_red,float_green,float_blue,float_alpha,rounding):` <mark style="color:purple;">`void`</mark>

|                     |       |
| ------------------- | ----- |
| x/y/size\_x/size\_y | float |
| rounding            | float |

### draw\_rectangle\_multicolored

`renderer.draw_rectangle_multicolored(x,y,size_x,size_y,float_red1,float_green1,float_blue1,float_alpha1,float_red2,float_green2,float_blue2,float_alpha2,horizontal):` <mark style="color:purple;">`void`</mark>

| Name                | Type  |
| ------------------- | ----- |
| x/y/size\_x/size\_y | float |
| horizontal          | bool  |

### draw\_rectangle\_multicolored\_4

`renderer.draw_rectangle_multicolored_4(x,y,size_x,size_y,float_red1,float_green1,float_blue1,float_alpha1,float_red2,float_green2,float_blue2,float_alpha2,float_red3,float_green3,float_blue3,float_alpha3,float_red4,float_green4,float_blue4,float_alpha4):` <mark style="color:purple;">`void`</mark>

### draw\_triangle

`renderer.draw_triangle(x1,y1,x2,y2,x3,y3,float_red,float_green,float_blue,float_alpha):` <mark style="color:purple;">`void`</mark>

### draw\_triangle\_filled

`renderer.draw_triangle_filled(x1,y1,x2,y2,x3,y3,float_red,float_green,float_blue,float_alpha):` <mark style="color:purple;">`void`</mark>

### triangle\_multicolored

`renderer.triangle_multicolored(x1,y1,x2,y2,x3,y3,float_red1,float_green1,float_blue1,float_alpha1,float_red2,float_green2,float_blue2,float_alpha2,float_red3,float_green3,float_blue3,float_alpha3):` <mark style="color:purple;">`void`</mark>

### draw\_circle

`renderer.draw_circle(x,y,size,float_red,float_green,float_blue,float_alpha,segments,thickness):` <mark style="color:purple;">`void`</mark>

| Name      | Type  |
| --------- | ----- |
| x/y       | float |
| size      | float |
| segments  | float |
| thickness | float |

### draw\_circle\_filled

`renderer.draw_circle_filled(x,y,size,float_red,float_green,float_blue,float_alpha,segments):` <mark style="color:purple;">`void`</mark>

| Name     | Type  |
| -------- | ----- |
| x/y      | float |
| size     | float |
| segments | float |

### draw\_parallelogram

`renderer.draw_parallelogram(x1,y1,x2,y2,float_red,float_green,float_blue,float_alpha,thickness,side,radius):` <mark style="color:purple;">`void`</mark>

| Name        | Type  |
| ----------- | ----- |
| x1/y1/x2/y2 | float |
| thickness   | float |
| side        | float |
| radius      | float |

### draw\_parallelogram\_filled

`renderer.draw_parallelogram_filled(x1,y1,x2,y2,float_red,float_green,float_blue,float_alpha,side,radius):` <mark style="color:purple;">`void`</mark>

| Name        | Type  |
| ----------- | ----- |
| x1/y1/x2/y2 | float |
| side        | float |
| radius      | float |

### draw\_parallelogram\_multicolored

`renderer.draw_parallelogram_multicolored(x1,y1,x2,y2,float_red1,float_green1,float_blue1,float_alpha1,float_red2,float_green2,float_blue2,float_alpha2,thickness,side,radius):` <mark style="color:purple;">`void`</mark>

| Name        | Type  |
| ----------- | ----- |
| x1/y1/x2/y2 | float |
| thickness   | float |
| side        | float |
| radius      | float |

### draw\_image

`renderer.draw_image(LPDIRECT3DTEXTURE9 texture, float start_x, float start_y, float size_x, float size_y, float red, float green, float blue, float alpha, float rounding):` <mark style="color:purple;">`c_vector2d`</mark>

### create\_texture

`renderer.create_texture(std::string data, int size):` <mark style="color:purple;">`LPDIRECT3DTEXTURE9`</mark>

### get\_texture

`renderer.get_texture(textures texture):` <mark style="color:purple;">`LPDIRECT3DTEXTURE9`</mark>

### get\_center

`renderer.get_center():` <mark style="color:purple;">`c_vector2d`</mark>

### get\_screen\_width

`renderer.get_screen_width():` <mark style="color:purple;">`float`</mark>

### get\_screen\_height

`renderer.get_screen_height():` <mark style="color:purple;">`float`</mark>

### path\_clear

`renderer.path_clear():` <mark style="color:purple;">`void`</mark>

### path\_add\_line

`renderer.path_add_line(x,y):` <mark style="color:purple;">`void`</mark>

### path\_fill

`renderer.path_fill(float_red,float_green,float_blue,float_alpha):` <mark style="color:purple;">`void`</mark>

### path\_stroke

`renderer.path_stroke(float_red,float_green,float_blue,float_alpha,flags,thickness):` <mark style="color:purple;">`void`</mark>

| Name      | Type                                          |
| --------- | --------------------------------------------- |
| flags     | [path\_flags](../enumerations/path\_flags.md) |
| thickness | float                                         |

### path\_arc

`renderer.path_arc(x,y,size,a_min,a_max,num_segments):` <mark style="color:purple;">`void`</mark>

| Name          | Type  |
| ------------- | ----- |
| x/y           | float |
| size          | float |
| a\_min/max    | float |
| num\_segments | int   |

### path\_arc\_fast

`renderer.path_arc_fast(x,y,size,a_min,a_max):` <mark style="color:purple;">`void`</mark>

| Name       | Type  |
| ---------- | ----- |
| x/y        | float |
| size       | float |
| a\_min/max | float |

### path\_bezier\_cubic\_curve

`renderer.path_arc_fast(x1,y1,x2,y2,x3,y3,num_segments):` <mark style="color:purple;">`void`</mark>

| Name          | Type  |
| ------------- | ----- |
| x/y           | float |
| num\_segments | int   |

### path\_bezier\_quadratic\_curve

`renderer.path_bezier_quadratic_curve(x1,y1,x2,y2,num_segments):` <mark style="color:purple;">`void`</mark>

| Name          | Type  |
| ------------- | ----- |
| x/y           | float |
| num\_segments | int   |

### path\_rectangle

`renderer.path_rectangle(x1,y1,x2,y2,rounding,flags):` <mark style="color:purple;">`void`</mark>

| Name     | Type                                          |
| -------- | --------------------------------------------- |
| x/y      | float                                         |
| rounding | float                                         |
| flags    | [path\_flags](../enumerations/path\_flags.md) |

### disable\_scope\_drawing

`renderer.disable_scope_drawing(bool set_value):` <mark style="color:purple;">`void`</mark>
