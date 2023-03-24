# 🔮 panorama\_engine

### get\_panel

`panorama_engine.get_panel(name)` <mark style="color:purple;">**`c_panorama_panel*`**</mark>

|      | Type        |
| ---- | ----------- |
| name | std::string |

### print\_panels\_to\_console

`panorama_engine.print_panels_to_console()` <mark style="color:purple;">**`void`**</mark>

### is\_valid\_panel

`panorama_engine.is_valid_panel(panel)` <mark style="color:purple;">**`bool`**</mark>

|       | Type                 |
| ----- | -------------------- |
| panel | c\_panorama\_panel\* |

### runscript

`panorama_engine.runscript(panel, js_code, path_to_xml)` <mark style="color:purple;">**`void`**</mark>

|               | Type                 |
| ------------- | -------------------- |
| panel         | c\_panorama\_panel\* |
| js\_code      | std::string          |
| path\_to\_xml | std::string          |
