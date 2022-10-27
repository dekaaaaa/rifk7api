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

### get\_smooth\_colors

`menu.get_smooth_colors():` <mark style="color:purple;">`color`</mark>

### override\_visibility

`menu.override_visibility(std::string text, bool):` <mark style="color:purple;">`void`</mark>

Whether the settings menu is visible

### add\_separator

`menu.add_separator(std::string text):` <mark style="color:purple;">`void`</mark>

### add\_text

`menu.add_text(std::string text):` <mark style="color:purple;">`void`</mark>

### set\_text

`menu.set_text(std::string text, text_override):` <mark style="color:purple;">`void`</mark>

### add\_checkbox

`menu.add_checkbox(std::string name, default_value):` <mark style="color:purple;">`void`</mark>

| Name           | Type |
| -------------- | ---- |
| default\_value | bool |

### get\_checkbox

`menu.get_checkbox(std::string name):` <mark style="color:purple;">`bool`</mark>

### set\_checkbox

`menu.set_checkbox(std::string name, bool):` <mark style="color:purple;">`void`</mark>

### add\_slider

`menu.add_slider(std::string name, default_value, min, max):` <mark style="color:purple;">`void`</mark>

| Name           | Type  |
| -------------- | ----- |
| default\_value | float |
| min            | float |
| max            | float |

### get\_slider

`menu.get_slider(std::string name):` <mark style="color:purple;">`float`</mark>

### set\_slider

`menu.set_slider(std::string name, value):` <mark style="color:purple;">`void`</mark>

| Name  | Type  |
| ----- | ----- |
| value | float |

### add\_combo

`menu.add_combo(std::string name, default_value, std::string items):` <mark style="color:purple;">`void`</mark>

| Name           | Type |
| -------------- | ---- |
| default\_value | int  |

{% tabs %}
{% tab title="Example" %}
menu.add\_combo("Example Combo", 0,"First Value\0Second Value\0Third Value\0\0")
{% endtab %}
{% endtabs %}

### get\_combo

`menu.get_combo(std::string name):` <mark style="color:purple;">`int`</mark>

### set\_combo

`menu.set_combo(std::string name, int):` <mark style="color:purple;">`void`</mark>

{% embed url="https://learn.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes" %}
Keybinds key code
{% endembed %}

### add\_keybind

`menu.add_keybind(std::string name, default_button, mode, keybind_options):` <mark style="color:purple;">`void`</mark>

| Name             | Type |
| ---------------- | ---- |
| default\_button  | int  |
| mode             | int  |
| keybind\_options | int  |

### get\_keybind\_button

`menu.get_keybind_button(std::string name):` <mark style="color:purple;">`int`</mark>

### get\_keybind\_mode

`menu.get_keybind_mode(std::string name):` <mark style="color:purple;">`int`</mark>

### get\_keybind

`menu.get_keybind(std::string name):` <mark style="color:purple;">`bool`</mark>

### set\_keybind\_button

`menu.set_keybind_button(std::string name, int):` <mark style="color:purple;">`void`</mark>

### set\_keybind\_mode

`menu.set_keybind_mode(std::string name, int):` <mark style="color:purple;">`void`</mark>

### add\_flex\_checkbox

`menu.add_flex_checkbox(std::string name, default_button, mode):` <mark style="color:purple;">`void`</mark>

### get\_flex\_checkbox\_button

`menu.get_flex_checkbox_button(std::string name):` <mark style="color:purple;">`int`</mark>

### get\_flex\_checkbox\_mode

`menu.get_flex_checkbox_mode(std::string name):` <mark style="color:purple;">`int`</mark>

### get\_flex\_checkbox

`menu.get_flex_checkbox(std::string name):` <mark style="color:purple;">`bool`</mark>

### set\_flex\_checkbox\_button

`menu.set_flex_checkbox_button(std::string name, int):` <mark style="color:purple;">`void`</mark>

### set\_flex\_checkbox\_mode

`menu.set_flex_checkbox_mode(std::string name, int):` <mark style="color:purple;">`void`</mark>

### add\_colorpicker/add\_second\_colorpicker

`menu.add_colorpicker(std::string name,float_red,float_green,float_blue, float_alpha,alpha_slider):` <mark style="color:purple;">`void`</mark>

`menu.add`\_second`_colorpicker(std::string name,float_red,float_green,float_blue, float_alpha,alpha_slider):` <mark style="color:purple;">`void`</mark>

| Name          | Type |
| ------------- | ---- |
| alpha\_slider | bool |

### get\_colorpicker

`menu.get_colorpicker(std::string name):` <mark style="color:purple;">`color`</mark>

### set\_colorpicker

`menu.set_colorpicker(std::string name,float_red,float_green,float_blue, float_alpha):` <mark style="color:purple;">`void`</mark>

### add\_multiselection

`menu.add_multiselection(std::string text, std::string items):` <mark style="color:purple;">`void`</mark>

{% tabs %}
{% tab title="Example" %}
menu.add\_multiselection("Example Multiselection", "First Value\0Second Value\0Third Value\0\0");
{% endtab %}
{% endtabs %}

### get\_multiselection\_item

`menu.add_multiselection(std::string text, slot):` <mark style="color:purple;">`bool`</mark>

| Name | Type |
| ---- | ---- |
| slot | int  |

### set\_multiselection\_item

`menu.set_multiselection(std::string text, slot, bool):` <mark style="color:purple;">`void`</mark>
