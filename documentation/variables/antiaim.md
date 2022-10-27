# 🤯 antiaim

## Functions:

### get\_last\_viewangles

`antiaim.get_last_viewangles():` <mark style="color:purple;">`c_vector3d`</mark>

### get\_last\_desync

`antiaim.get_last_desync():` <mark style="color:purple;">`float`</mark>

### get\_last\_desync\_amount

`antiaim.get_last_desync_amount():` <mark style="color:purple;">`float`</mark>

### get\_manual\_direction

`antiaim.get_manual_direction():` [<mark style="color:purple;">`manual_direction`</mark>](../enumerations/manual\_direction.md)<mark style="color:purple;">``</mark>

### did\_send\_packet\_last\_tick

`antiaim.did_send_packet_last_tick():` <mark style="color:purple;">`bool`</mark>

### override\_fake

`antiaim.override_fake(angle):` <mark style="color:purple;">`void`</mark>

Override fake yaw

If the value is 0, then he will cancel the override

| Name  | Type  |
| ----- | ----- |
| angle | float |

### override\_desync

`antiaim.override_desync(angle):` <mark style="color:purple;">`void`</mark>

Override desync yaw

If the value is 0, then he will cancel the override

| Name  | Type  |
| ----- | ----- |
| angle | float |

### override\_pitch

`antiaim.override_pitch(angle):` <mark style="color:purple;">`void`</mark>

Override pitch

If the value is 0, then he will cancel the override

| Name  | Type  |
| ----- | ----- |
| angle | float |

### override\_roll

`antiaim.override_roll(angle):` <mark style="color:purple;">`void`</mark>

Override roll, Need to enable "enable lean"

If the value is 0, then he will cancel the override

| Name  | Type  |
| ----- | ----- |
| angle | float |

### get\_max\_desync

`antiaim.get_max_desync(index):` <mark style="color:purple;">`float`</mark>

| Name  | Type |
| ----- | ---- |
| index | int  |

###
