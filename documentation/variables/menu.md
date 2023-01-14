# 💻 menu

## Functions:

### is\_visible

`menu.is_visible():` <mark style="color:purple;">`bool`</mark>

Detects whether the menu is open (returns true if open)

### get\_menu\_pos

`menu.get_menu_pos():` <mark style="color:purple;">`c_vector2d`</mark>

Detect menu position

### get\_menu\_size

`menu.get_menu_size():` <mark style="color:purple;">`c_vector2d`</mark>

return menu size

### get\_uid

`menu.get_uid():` <mark style="color:purple;">`int`</mark>

### get\_username

`menu.get_username():` <mark style="color:purple;">`string`</mark>

### get

`menu.get(int index):` <mark style="color:purple;">`c_lua_menu_item`</mark>

### add\_separator

`menu.add_separator(std::string text):` <mark style="color:purple;">`int`</mark>

### add\_text

`menu.add_text(std::string text):` <mark style="color:purple;">`int`</mark>

### add\_slider

`menu.add_slider(std::string name, float default_value, float min, float max):` <mark style="color:purple;">`int`</mark>

### add\_combo

`menu.add_combo(std::string name, int default_value, std::string items)` <mark style="color:purple;">`int`</mark>

### add\_keybind

`menu.add_keybind(std::string name, int default_button, int mode, int keybind_options):` <mark style="color:purple;">`int`</mark>

### add\_flex\_checkbox

`menu.add_flex_checkbox(std::string name, int default_button, int mode):` <mark style="color:purple;">`int`</mark>

### add\_colorpicker

`menu.add_colorpicker(std::string name, float default_r, float default_g, float default_b, float default_a, bool alpha_slider):` <mark style="color:purple;">`int`</mark>

### add\_second\_colorpicker

`menu.add_second_colorpicker(std::string name, float default_r, float default_g, float default_b, float default_a, bool alpha_slider):` <mark style="color:purple;">`int`</mark>

### add\_multiselection

`menu.add_multiselection(std::string name, std::string items):` <mark style="color:purple;">`int`</mark>

### add\_text\_input\_box

`menu.add_text_input_box(std::string name, std::string default_text):` <mark style="color:purple;">`int`</mark>

### add\_button\_callback

`menu.add_button_callback(std::string name, protected_function function):` <mark style="color:purple;">`int`</mark>
